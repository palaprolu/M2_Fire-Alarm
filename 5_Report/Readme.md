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
