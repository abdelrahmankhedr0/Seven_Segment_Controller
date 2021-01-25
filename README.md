# Seven Segment Controller 
## Abstract :
In this project , we control seven segment display counter through 3 ways : hardware (
push buttons and IR sensors ) ,mobile application and web application . The project based on
ESP32 with micro python firmware and code is written with python . Web application is
connected with program using socket module . Push buttons and IR sensors are connected to
pins with interrupt listener so we can control with buttons although socket blocking . We use IR
sensors to control through hardware without touching . Mobile application is made using MIT
inventor and control counter through accessing the web application in a hidden web browser
included . Web application and mobile application can synchronize with each other and
hardware by clicking refresh button on web and mobile app . 

## Hardware used :
1. Breadboard 840pins * 2
2. ESP32 espressif 30pins * 1
3. Push Buttons * 3
4. IR Sensor Modules * 3
5. 7 Segment comn anode * 1
6. 1/8 watt 220 resistors * 7
7. 1/8 watt 10K resistors * 3
8. 18650 Lithium ion batteries * 2
9. 18650 2cell Battery Holder * 1
10. Jumpers
11. Micro USB cable * 1

## Software used :
1. Thonny IDE
2. Micro python firmware
3. MIT inventor

## Get ready to start coding steps :
1. Download Thonny IDE through [official website](https://thonny.org/) and install it
2. Download USB to UART bridge though [official website](https://www.silabs.com/developers/usb-to-uart-bridge-vcp-drivers) and install it
3. Download Micro python firmware v1.13 through [official website](https://micropython.org/download/esp32/)
4. Burn Micro python firmware to ESP flash though [these steps](https://randomnerdtutorials.com/getting-started-thonny-micropython-python-ide-esp32-esp8266/)
5. Create account on MIT inventor through [This Link](http://ai2.appinventor.mit.edu/)

## Project Photos :
![Hardware](https://github.com/abdelrahmankhedr0/Seven_Segment_Controller/blob/main/Project_photo.jpeg)
![Web app](https://github.com/abdelrahmankhedr0/Seven_Segment_Controller/blob/main/Web_Application_Screenshot.png)
![Mobile app](https://github.com/abdelrahmankhedr0/Seven_Segment_Controller/blob/main/Mobile_Application_Screenshot.png)

## Contact :
[LinkedIn](https://www.linkedin.com/in/abdelrahmankhedr)
</br>
[Facebook](https://www.facebook.com/abdelrahmankhedr0)
</br>
[Youtube channel](https://www.youtube.com/channel/UCSp034JjyGsvDL_g4sSy6rA)
