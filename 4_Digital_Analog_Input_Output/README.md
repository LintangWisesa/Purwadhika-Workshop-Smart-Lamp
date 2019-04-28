# **Workshop How to Create a Simple Smart Lamp**

![Lintang_Purwadhika](https://static.wixstatic.com/media/2e6af2_f69a4271c3534ae1869a7ed63e278b2b~mv2.png/v1/fill/w_246,h_39,al_c,usm_0.66_1.00_0.01/2e6af2_f69a4271c3534ae1869a7ed63e278b2b~mv2.png)

# *__4. Digital & Analog Input/Output__*

## **4a. Digital Input/Output :heavy_check_mark:**

  1. **Schematics :wrench: :hammer:**
      
      Assemble your parts as the schematics below.
      
      ![Digital_IO](https://raw.githubusercontent.com/LintangWisesa/LSTP-Workshop-IoT-ESP8266/master/4_Digital_Analog_Input_Output/4_Digital_InOut.png)

  2. **Sketch :clipboard:**
      
      Open Arduino IDE, type & upload the sketch below.

      - Control LED ON/OFF using push button

        ```c++
        void setup(){
          pinMode(D3, INPUT);
          pinMode(D5, OUTPUT);
        }

        void loop(){
          digitalWrite(D5, digitalRead(D3));  
        }
        ```

  - __Done!__ :ballot_box_with_check:

#

## **4b. Analog Input/Output :heavy_check_mark:**

  1. **Schematics :wrench: :hammer:**

      Assemble your parts as the schematics below.

      ![Analog_IO](https://raw.githubusercontent.com/LintangWisesa/LSTP-Workshop-IoT-ESP8266/master/4_Digital_Analog_Input_Output/4_Analog_InOut.png)

  2. **Sketch :clipboard:**
      
      Open Arduino IDE, type & upload the sketch below.

      - Control LED lightness using potentiometer

        ```c++
        void setup(){
          pinMode(D5, OUTPUT);
        }

        void loop(){
          analogWrite(D5, analogRead(A0)/4);
        }
        ```
      
  - __Done!__ :ballot_box_with_check:

  - __Next material: :fast_forward: *[ESP8266 & LDR Sensor](https://github.com/LintangWisesa/LSTP-Workshop-IoT-ESP8266/tree/master/5_ESP8266_LDR)*__ 

#

## **Table of Contents :memo:**

  No.|Material|Tutorial
  -----|-----|-----
  0.|Setup _**(please do this before the workshop)**_ :point_right:|*__[click here](https://github.com/LintangWisesa/Purwadhika-Workshop-Smart-Lamp/tree/master/0_Setup)__*
  1.|Hello World!|*__[click here](https://github.com/LintangWisesa/Purwadhika-Workshop-Smart-Lamp/tree/master/1_Hello_World)__*
  2.|Digital & Analog Output|_**[click here](https://github.com/LintangWisesa/Purwadhika-Workshop-Smart-Lamp/tree/master/2_Digital_Analog_Output)**_
  3.|Digital & Analog Input|_**[click here](https://github.com/LintangWisesa/Purwadhika-Workshop-Smart-Lamp/tree/master/3_Digital_Analog_Input)**_
  4.|Analog & Digital I/O|_**[click here](https://github.com/LintangWisesa/Purwadhika-Workshop-Smart-Lamp/tree/master/4_Digital_Analog_Input_Output)**_
  5.|ESP8266 & LDR Sensor|_**[click here](https://github.com/LintangWisesa/Purwadhika-Workshop-Smart-Lamp/tree/master/5_ESP8266_LDR)**_
  6.|ESP8266 WiFi Scanner|_**[click here](https://github.com/LintangWisesa/Purwadhika-Workshop-Smart-Lamp/tree/master/6_ESP8266_WiFi_Scanner)**_
  7.|Connecting ESP8266 to A WiFi Network|_**[click here](https://github.com/LintangWisesa/Purwadhika-Workshop-Smart-Lamp/tree/master/7_Connect_to_A_WiFi)**_
  8.|ESP8266 & Blynk|_**[click here](https://github.com/LintangWisesa/Purwadhika-Workshop-Smart-Lamp/tree/master/8_ESP8266_Blynk)**_
  9.|ESP8266 & Thinger.io|_**[click here](https://github.com/LintangWisesa/Purwadhika-Workshop-Smart-Lamp/tree/master/9_ESP8266_Thinger)**_

#

#### Lintang Wisesa :love_letter: _lintangwisesa@ymail.com_

[Facebook](https://www.facebook.com/lintangbagus) | 
[Twitter](https://twitter.com/Lintang_Wisesa) |
[Google+](https://plus.google.com/u/0/+LintangWisesa1) |
[Youtube](https://www.youtube.com/user/lintangbagus) | 
:octocat: [GitHub](https://github.com/LintangWisesa) |
[Hackster](https://www.hackster.io/lintangwisesa)
