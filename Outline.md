# Waterlogger

Based on the Riffle. Twenty-five water quality sensor bottles placed in the Willamette River to monitor sewage outfall in the Portland Harbor Superfund site in Oregon.

#### Floating Antenna Bottle $5 for case

- Adafruit Mini GSM/Cell Quad-Band Antenna with Male SMA $4.46
- 12-oz or 20-oz Gatorade bottle $1

#### Tether

- SMA cable $7.29

#### ABS Enclosure

1.5"x6" ABS Pipe $1
1.5" ABS End Cap $2.37

- Microcontroller
  - Atmega328 $2.74
- Battery Status 
- Cell Chip $10
- Thermistor Sensor $2
  - TMP36 Sensor 
- Conductivity Sensor $2
  - (2) Screws
  - (2) Washers
  - (2) Gaskets
  - 555 Timer $.33
  - 0.1uF Capacitor
- Turbidity Sensor $2 
  - TL082 JFET Input Amplifier $0.70
  - (2) 1K Resistor
  - 1M Resistor
  - (2) 0.1uF Capacitor
  - 1N4001 Diode $0.11
  - Emitter $0.59
  - Detector $0.36
- Depth Sensor $2
  - 1K Res
  - 555 Timer $.33
  - Pair of twisted wires

#### Total Per Unit Cost

$17 Mechanical Cost
$6 Board Cost
$30 Parts Cost

Possibly get it below $50 for cell/atmega32u4

##### Drill Hole ABS End Cap Jig

3D-printed turbidity sensor piece

#### Things I removed

- Removed USB so you have to buy a one-time FTDI cable for $17
- RTC (we get time from cell chip)
- Batteyr backup for RTC
- Battery charging 
- SD card (just send it, save ten measurements and send)
