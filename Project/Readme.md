# ABSTRACT

Water tank overflow is a common problem which leads to the wastage of water. This circuit will detect the water level and will turn the lever on or off depending on the level. 
Water level indicator is a modern way of measuring the water level using latest technologies like sensors, Arduino. The main aim of the project is to observe the water level at 
any instant of time using Arduino, Servo Motor and Ultrasonic sensor to make it possible. As the servo motor used as an actuator will turn off when the tank fulls with water so 
that the water will not overflow. This may be useful in saving water from getting waste.

# Requirements

## HIGH LEVEL REQUIREMENTS

|ID |Description |
|--|-------------|
|01|Servo motor should ON/OFF|
|02|Ultrasonic Sensor should sense the level of water|
|03|LED should glow|
|04|Voltmeter should measure the voltage|

## LOW LEVEL REQUIREMENTS

|ID |Description |
|--|-------------|
|01|Servo motor valve should be open when the water is less.|
|02|Servo motor valve should close when water is full.|
|03|LED should glow when valve is open/close|
|04|Potentiometer should regulate the voltage properly.|

# TEST PLAN AND OUTPUT

## HIGH LEVEL TEST PLAN

|Test |Description |Input |Output |Requirement Met|
|--|-------------|------|------|---|
|01|Arduino UNO Board|Input from Microcontroller|Expected 5V output|Yes|
|02|Ultrasonic Senor|Data from Arduino board|Detect Object|Yes|
|03|LED|Show the level of tank|Glow when water reaches the level|Yes|
|04|Resistor|Restrict the flow|Restrict the flow of current|Yes|
|05|Potentiometer|Vary the resistance and regulates the flow|Flow of circuit|Yes|
|06|Servo Motor|ON to suply water and OFF to stop overflow|Water above 50% and below 100%|Yes|

## LOW LEVEL TEST PLAN
|Test |Description |Input |Output |Requirement Met|
|--|-------------|------|------|---|
|01|Servo motor valve should be open when the water is less.|Less Water|Servo ON|Yes|
|02|Servo motor valve should close when water is full.|Full Water (Near to 100%)|Servo OFF|Yes|
|03|LED ON|ON when level is below threshold|Water below 50%|Yes|
|04|LED OFF|FF when level is above max limit|Water above 100%|Yes|
|05|Potentiometer Regulation|Regulate when water is above or below the required limit|Water should be between 50% and 100%|Yes|

## Badges

|Badges |Status |
|--------|-------------|
|CI|[![CI](https://github.com/tanmaypadhi08/M2-EmbSys/actions/workflows/blank.yml/badge.svg)](https://github.com/tanmaypadhi08/M2-EmbSys/actions/workflows/blank.yml)|
|CPP|[![Cpp-Check](https://github.com/tanmaypadhi08/M2-EmbSys/actions/workflows/c-cpp.yml/badge.svg)](https://github.com/tanmaypadhi08/M2-EmbSys/actions/workflows/c-cpp.yml)|
|Build Linux|[![Build-Linux](https://github.com/tanmaypadhi08/M2-EmbSys/actions/workflows/Build.yml/badge.svg)](https://github.com/tanmaypadhi08/M2-EmbSys/actions/workflows/Build.yml)|
|Valgrind|[![Valgrind](https://github.com/tanmaypadhi08/M2-EmbSys/actions/workflows/Val.yml/badge.svg)](https://github.com/tanmaypadhi08/M2-EmbSys/actions/workflows/Val.yml)|
|Unit Testing|[![Unit Testing](https://github.com/tanmaypadhi08/M2-EmbSys/actions/workflows/Unit.yml/badge.svg)](https://github.com/tanmaypadhi08/M2-EmbSys/actions/workflows/Unit.yml)|
|Codiga|https://api.codiga.io/project/31650/score/svg|