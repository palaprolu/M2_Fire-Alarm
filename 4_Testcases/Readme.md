# Testcases:

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
