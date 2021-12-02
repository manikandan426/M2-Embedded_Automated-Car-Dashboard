# INTRODUCTION
The presence of dangerous LPG leakage in the cars, service station or in the storage tank environment can be detected using the Ideal Gas Sensor. This LPG gas leakage detector unit can be easily integrated into a unit that can sound an alarm or give a visual suggestion of the LPG concentration. The sensor has both admirable sensitivity and rapid response time. This sensor can also be used to sense other gases like iso-butane, propane, LNG and even cigarette smoke.

The output of the sensor goes LOW as soon as the LPG sensor senses any gas leakage from the storage. This is detected by the microcontroller and the LED & buzzer is turned ON. After the delay of few milliseconds, the exhaust fan is also turned ON for throwing the gas out and it continues sending message as ‘GAS LEAKAGE’ to a mobile number which is pre-defined.

# FEATURES
1. The sensor has both admirable sensitivity and rapid response time.
2. This sensor can also be used to sense other gases like iso-butane, propane, LNG and even cigarette smoke.
3. The output of the sensor goes LOW as soon as the LPG sensor senses any gas leakage from the storage.
4. Easy to use.
# STATE OF ART/RESEARCH
![144088408-5831066c-a48d-4419-8517-bab65da67e2d](https://user-images.githubusercontent.com/71758695/144426071-549b07e0-59c2-46bf-a979-6eabf0115bf5.png)
# SWOT ANALYSIS
## STRENGTH
1. Detection and Prevention of any sort of gas leakage.
2. Cost Efficient and less Complex circuit.
3. No environmental effect or no effect of physical conditions.
4. It is use in vehicles and as well as in houses as LPG leakage detection.

## WAEKNESS
1. It work only when at 5v power supply.
2. It's sensitivity depends on Humidity and temperature.

# OPPORTUNITIES
1. Gas detectors can be used to detect combustible, flammable and toxic gases, and oxygen depletion.
2. This type of device is used widely in industry and can be found in locations, such as on oil rigs, to monitor manufacturing processes and emerging technologies such as
photovoltaic.
3. They may be used in firefighting.
# THREATS
1. Inhaling leaked gas in an indoor space, such as your home can result in a lack of oxygen in the air and lead to hypoxia.
2. That can, in turn, lead to severe headaches, fatigue, decreased vision, short breaths, and even loss of consciousness.
# 4W & 1H
## WHY
   1. The purpose of this system is to detect gas leakage, neutralize it, and prevent the explosion.
## WHEN
   1. Gas detectors can be used to detect combustible, flammable and toxic gases, and oxygen depletion.
## WHERE
   1. They are commonly used to detect toxic or explosive gases and measure gas concentration.- When gas leaks do occur, they pose serious risks of carbon monoxide poisoning in people and animals.
## WHO
   1. Gas sensors are employed in factories and manufacturing facilities to identify gas leaks, and to detect smoke and carbon monoxide in homes and also in vehicles.
## HOW
   1. If it detects a gas leak, the LED will light up, the buzzer will activate, then the system will send a notification message stating that there has been an LPG gas leak.
   2. If no LPG gas leak is detected, the system will continue to detect the gas level through the LPG gas sensor until it detects an LPG gas leak.
# HIGH LEVEL REQUIREMENTS
1. Sensor to detects the gas leakage.
2. GSM module to send a message to a registered mobile number.
3. Buzzer to alert the fire has produced.
# LOW LEVEL REQUIREMENTS
1. LED to display the message.
# UML Diagram
![144085458-2517ac04-787c-4457-915c-46914492302a](https://user-images.githubusercontent.com/71758695/144426210-aba00796-0435-4258-8a63-a54d7d1a87f6.png)

| S.NO |	Components |	Description |	Quantity |	Link |
| ---- | ----------- | -----------  | -------- | ----- |
| 1	| ATmega328	| Microcontroller |	1	| https://www.electronicscomp.com/atmega328p-microcontroller-india?search=atmega328 |
| 2	| ADC	| Analog to Digital Converter	| 1 |	https://www.electronicscomp.com/adc0804-8-bit-analog-to-digital-a-d-converter-ic-dip-20-package?search=analog%20to%20digital%20converter |
| 3	| Exhaust Fan |	Which reduces the concentration of LPG gas |	1 |	https://www.amazon.in/Havells-FHVVEDXOWH08-Ventil-200mm-White/dp/B00KIDSU8S/ref=asc_df_B00KIDSU8S/?tag=googleshopdes-21&linkCode=df0&hvadid=396989272059&hvpos=&hvnetw=g&hvrand=17817879117604266861&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=1007741&hvtargid=pla-404767017039&ext_vrnc=hi&th=1 |
| 4	| Gas Sensor |	MQ-135/MQ7/MQ6/MQ5/MQ2 |	1	| https://amzn.to/2WLIPFL |
| 5 |	LCD Display	| JHD162A 16x2 LCD Display |	1 |	https://amzn.to/2YVEF0W |
| 6	| Transistor |	BC548	| 2 |	https://www.electronicscomp.com/bc548-npn-general-purpose-transistor-30v-100ma-to-92-package?search=BC548 |
| 7	| Resistor |	1k ohm	| 3	| https://www.electronicscomp.com/1k-ohm-half-watt-resistance?search=1k%20ohm%20resistor |
| 8	| GSM Module | SIM800/900 UART GSM Module |	1 |	https://amzn.to/3cqDL06 |
| 9 |	Buzzer | Sound/Alarm |	1 |	https://www.electronicscomp.com/active-buzzer-module-5v-india?search=buzzer |
| 10 |	Bread Board	| -	| 1	| https://www.electronicscomp.com/400-points-half-size-solderless-breadboard?search=bread%20board&limit=50 |
| 11 |	Jumper Wires |	Connecting Wires |	20 |	https://amzn.to/2L8Xc1p |
| 12 |	Arduino Board	| Arduino UNO R3 Development Board	| 1	| https://amzn.to/3bjpPDS |
![144033489-b0d1b180-5273-4bca-8828-fed46b83cd5b](https://user-images.githubusercontent.com/71758695/144426903-d1199308-f0de-40f6-835d-c256f42adaee.png)

# Block Diagram for Connection between Microcontroller and GSM Module
![144033701-be3dccbb-c657-4dfe-ad0d-52dbcb6fb85b](https://user-images.githubusercontent.com/71758695/144426362-c9c4d863-655f-4fda-b76a-efde3d21b75a.png)


# BLOCK DIAGRAM
## Class Diagram
![144086415-aa8fd5c6-10e0-4c22-975d-940475ad6d91](https://user-images.githubusercontent.com/71758695/144426501-c0f8c3c6-c7a7-4285-b6e7-f423d9806e14.png)


## Component Diagram
![143805428-404acfe2-d3b8-46d1-be12-b9cfa04588a9](https://user-images.githubusercontent.com/71758695/144426618-36e94f32-2a87-4e96-8c92-bdbb977cf8a4.png)


# Flow Chart
![143779074-3eb5fa13-50f0-4645-bf46-716d4c8a1183](https://user-images.githubusercontent.com/71758695/144426647-46990c72-7862-4b70-a126-1404dd936902.png)


# HIGH LEVEL TEST PLAN
| Test ID |	Description	| Expected Input |	Actual Output |	Expected Output |
| ------- | ----------- | -------------- | -------------- | --------------- |
| H1	| Monitor gas leakage using gas sensor | MQ5 gas sensor module detects the gas leakage |	Alert the people with buzzer |	Alert the people with buzzer |
| H2	| To send the values to webpage |	GSM module collect the value to web page |	Web page is created	| Web page is created |
# LOW LEVEL TEST PLAN
| Test ID	| Description	| Expected Input	| Actual Output	| Expected Output |
| --------- | ------------ | --------------- | --------------- | --------------- |
| L1 | To print the value in LCD board |	MQ5 gas sensor measures the gas leakage	| Display the message	| Display the message |
| H2 |	To detect the gas leakage	| Buzzer sound	| LED ON/OFF	| LED ON/OFF |
| ![144355117-2de11e18-767a-42bd-b6dd-1a99e51c0f22](https://user-images.githubusercontent.com/71758695/144426731-21217155-c82b-4e7e-8d67-d3a276076b54.png) |

# GAS DETECTION
![144356003-e88a1e07-d3e8-4b55-8fda-1d79018bd135](https://user-images.githubusercontent.com/71758695/144426796-a63a9723-9afb-4599-b77c-d07b77a487ef.png)

