# Headphone Preamplifier
This is a follow-on project from https://github.com/bengineer91/Preamp. It features an upgraded DSP (ADAU1450) and discrete AKM ADC and DAK
Headphone amplifier with the following features:

- USBC Power Input
- 5V, 3.3V, 3.3VA, and 1.2V LDOs
- +/-12V split rail switching converter, feeding +/-10V and +/-5V LDOs
- ESP32 Module for control and driving a spectrum visualizer OLED display
- York Pico USB to I2S module
- AK5572EN Analog to Digital Converter
- ADAU1450 DSP
- AK4452VN Digital to Analog Converter
- PGA2311 digital volume controller
- TPA6102A2 Output Amplifier

**To Do:** <br/>

Layout:<br/>
[x] Verify component placement<br/>
[x] Routing!<br/>
[x] Clean up silkscreen<br/>
[X] Adjudicate DRC issues<br/>
[X] Move some of the power pours to second power layer<br/>
[x] Clean up fab layer<br/>

Schematic:<br/>
[X] Clean up placement - make everything fit on the page<br/>
[x] Part selection for capacitors, verify voltages on schematic<br/>
[X] Redo capacitor voltage labels<br/>
[x] Reduce footprint sizes where possible, mainly capacitors<br/>
[x] Pick proper connectors for the front panel stuff<br/>
[ ] Decide on header stack height for the York and ESP32<br/>

ESP32 Code<br/>
[x] Port over spectrum visualizer<br/>
[ ] PGA control<br/>

CAD<br/>
[x] Import board step file<br/>
[x] Figure out rear mounting<br/>
[ ] Layout front/rear panels <br/>

Sigma Studio<br/>
[x] ID reference project<br/>
[ ] Settle on sample rates and clock scalars<br/>
[ ] Port blocks from prior preamp<br/>
