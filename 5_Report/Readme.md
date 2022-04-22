# Introduction:-
Nowadays, fire incidents have become a critical issue , which must be dealt with on time without any unnecessary delay to avoid the loss in lives and belongings . It is considered a fire situation when the monitored temperature exceeds 50o C. In critical places such as hospitals, schools, and banks, personnel's arrival time to come for help in fire hazards is around 15 minutes .
## Circuit:-

![image](https://user-images.githubusercontent.com/101261412/164719626-aef39f74-535b-4527-ac55-d93f3a82a739.png)

#Requirements:-

## High LEvel Requirements:-

|HLR(ID)|Description|

|HLR01|Senses the time to time temperature in the building|

|HLR02|Compares with the regular room temperature|

|HLR03|Rings the buzzer if the temperature is High then room temperature|

|HLR04|Rings the buzzer if temperature is High or Smoke is detected in the building|

|HLR05|Shows the status on the LED screen|


## Low Level Requirements:-
|LLR(ID)|Description|

|LLR01HLR_01|Smokesensor send the high if fire/smoke is detected|

|LLR02_HLR_02|Temperature sensor compares the room temperature with average room temperature|

|LLR03_HLR_02|The sensor send high if temperature is High else sends low|

|LLR04_HLR_02|The process takes the input|

|LLR05_HLR_02|Processor sends high signal to buzzer|

|LLR06_HLR_04|The buzzer rings if the fire/somke is detected|

# Flowchart

![image](https://user-images.githubusercontent.com/101261412/164721761-704081e1-cb01-429b-a300-0677c56b3369.png)

# SWOT Analysis 
![image](https://user-images.githubusercontent.com/101261412/164721887-9494cf55-bc74-4dc8-9652-437592f9a944.png)

# 4W's And 1H

## What
It is a fire alarm system which is used in helping or alerting the people when fire broke out

## Where
In the offices, schools, buildings, public places, Theatres etc

## When
useful when the fire broke out

## Why
To alert people as fast as possible and save a lot of injuries

## How
By ringing the buzzer and displaying on Lcd screen

# Testcases

## High-Level Requirements:-

|Test ID|HLR|Description|Inputs|Expected Output|Actual Output|

|TD01|HLR01|when fire is not present               |buzzer dosen't ring|output on screen "SAFE"                |Sucess|

|TD02|HLR02|when fire is introduced near the buzzer|buzzer should ring |output on the screen is "FIRE DETECTED"|Success|

|TD01|HLR03|when smoke is not present|buzzer shuldn't ring|output on the screen is "SAFE"|Sucess|

|TD04|HLR04|when smoke is present|buzzer should ring|output on the screen is"FIRE DETECTED"|Sucess|

## Low-Level Requirements:-

|Test ID|LLR|Input|Expected Output|Message on screen|Output|

|TD01|LLR01_HLR01|if no fire detected by flame sensor|no sound generated|"SAFE"|no sound|

|TD02|LLR02_HLR01|if no smoke deted by smoke sensor|no sound generated|"SAFE"|no sound|

|TD03|LLR03_HLR01|if temperature of room<45'c|no sound generated|"SAFE"|no sound|

|TD04|LLR04_HLR01|if fire is detectedby flame sensor|sound generated|"FIRE DETECTED"|sound generated|

|TD05|LLR05_HLR02|if smoke detected by smoke sensor|sound genertaed|"FIRE DETECTED"|sound generated|

|TD06|LLR06_HLR02|if temperature > 45'c|sound generated|"FIRE DETECTED"|sound generated|

# Block Diagram
![image](https://user-images.githubusercontent.com/101261412/164723208-ffd93039-1828-4fdf-bac8-e693f784b60d.png)

# Components Used
Micro controller ATMega 328
Temperature sensor(which is used to check the temperature) But instead of the temperature sensor which is not available in the simullIde We are using the Potentiometer. Which Acts as a thermistor, Resists the flow of signal at low temperature and allows the flow at the particular and higher than that temperature.
Buzzer(for cautioning the people)
Smoke or fire sensor (which is used to detect Smoke or Fire)
Led (Used as an indicator when the fire or smoke broke out)ss

# Conclusion
The fire detection systems proposed in the literature served fire stopping with no care of the responsiveness. Thus, this study considers the existing issues and build an efficient and effective fire detection system based on IoT technology, gas, temperature, and smoke sensors to collect the data accurately and rapidly And alert all and help them from escape.


