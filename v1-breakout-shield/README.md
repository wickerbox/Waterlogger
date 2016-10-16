# Waterlogger Project
## Sensor Shield v1.0

This is a simple breakout board to attach the sensors, the Fona 808 2G + GPS breakout board, and a microSD card to the Arduino Uno. 

It's intended to be a platform for prototyping the sensor suite at Portland Science Hackday on October 8th. The big questions to answer at the hackday are:

1. Can we deploy the sensors far below the cell-bearing water bottle? How far below?
1. Can we replicate the 5V-based circuits for turbidity, conductivity, temperature, and depth?
1. How to adapt the sensors to 3.7V of a 2500mAh LiPo battery?
1. How long does it take to charge the final unit?
1. Would a silicone stopper work instead of the bottle cap? How much does air pressure change affect the design? Is there a danger of it popping off? Silicone top would allow for extending the sensors. What about teh Presta valve idea? BlueRobotis Cable Penetrator.
1. How much does temperature change with depth in a river?

### Temperature Sensor Bill of Materials

|Part|Source|Link|
|----|------|----|
|10K Epoxy Thermistor|<a href="https://www.adafruit.com/products/372">Adafruit</a>|$4|
|1% 10K Resistor|Adafruit|Included|

### Conductivity Sensor Bill of Materials

|Part|Source|Link|
|----|------|----|
|Coqui sensor?|
|DIY Conductivity Sensor (Phillip Cook)|
|Nichrome 32AWG|Amazon|<a href="https://www.amazon.com/Pure-Atomist-Nichrome-Gauge-0-20mm/dp/B017E3PWIK/ref=sr_1_3?s=hi&ie=UTF8&qid=1475344249&sr=1-3&keywords=32+awg+nichrome">$6</a>|
|Concerns about 555 Timer under 1V|

### Depth Sensor Bill of Materials

|Part|Source|Link|
|----|------|----|
|555 Timer|
|1K|
|Twisted wires|
|Hot Glue or epoxy|

### Turbidity Sensor Bill of Materials

Try both 90-degree and pointing right at each other.

|Part|Source|Link|
|----|------|----|
|AD820 JFET Op Amp|
|SFH 213 Emitter|
|HIR204 Detector|
|(2) 1K Resistor|
|(1) 1M Resistor|
|(2) 100nF Capacitors|
|Acrylic Window 0.118" thick, 2" diameter|<a href="http://www.tapplastics.com/product/plastics/cake_circles/clear_acrylic_circles/140">Tap Plastics</a>|$1|/W                                                    
|Formazin (Hazardous!) for Calibration|<a href="http://www.hach.com/stablcal-turbidity-standard-100-ntu-100-ml/product?id=7640202637">Hach</a>|$48|

### Breakout Shield v1.0 Bill of Materials

|Part|Source|Link|
|----|------|----|
|Arduino Uno|Adafruit|<a href="https://www.adafruit.com/products/3033">$39.95</a>|
|Fona 808 2G + GPS Breakout Board|Adafruit|<a href="https://www.adafruit.com/products/2542">$49.95</a>|
|MicroSD Card holder|Digikey|<a href="http://www.digikey.com/product-detail/en/molex-llc/0475710001/WM9731CT-ND/4037907">$0.98</a>|
|1x16 0.1" pitch female header|Digikey|<a href="http://www.digikey.com/product-detail/en/sullins-connector-solutions/PPPC161LFBN-RC/S7049-ND/810188">$1.27</a>|

The printed board is a 2 layer board of 2.71x2.11 inches (69x53mm). $28.45 for three. 
