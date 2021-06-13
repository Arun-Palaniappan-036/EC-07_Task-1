# MiniTask_1
## Project_1
#### Dust Monitor
Monitors the surrounding dust and large particle (>0.5µm) for long time using Blynk IOT and plots the data for further research.
An IOT based Dust density monitor which can measure the surrounding dust and send the data through internet and which can graphically monitor the long term value of the dust density in a place. This helps to make future project like improving the air pollution and many other projects.  
Sensor used : Sharp gp2y1014au0f  
Sharp gp2y1014au0f is a particulate sensor uses an IR LED and when the particle in the air enters into the sensor the light bounce off towards a photo-detector. This technique is called laser scattering. The intensity of the scattered(Bounced) light depends on the dust particles.
And we can read the output voltage and measure the dust density on the air.  
![1](https://user-images.githubusercontent.com/85285913/121808360-ac5dcb00-cc75-11eb-9fe2-6b33b6c32fc3.jpg)  

## Project_2
#### Medi-kit (SPO2 + Heart Rate + ECG)
A small COVID medical kit that measures SPO2, Heart Rate and ECG. ECG readings are analyzed and shared via Matlab on to ThingSpeak.
The following is an Arduino UNO based project that is suppose to calculate SPO2, Heart rate and monitor ECG of a patient. It uses the MAX30100 pulse oximeter and AD8232 ECG sensor module. SPO2 and heart rate is displayed on the 0.91" inch OLED display. And the ECG readings are analyzed and posted on ThingSpeak website.  
Sensors used : MAX30100 pulse oximeter, AD8232 ECG Sensor  
Matlab is used in the following project to demonstrate how an ECG signal can be obtained from the Arduino and further used for any mathematical analysis.  
![2](https://user-images.githubusercontent.com/85285913/121808630-090db580-cc77-11eb-8a85-b598f460bc6f.png)  

## Project_3
#### Capacitive soil moisture sensor
A Smart Irrigation System in which wemos can sense the moisture of the plant soil and watering it accordingly.
To solve under-irrigation its planned to make a device that controls the irrigating system properly. So that there is no over watering and all plants get the "required" amount of water.
Through the listing, wemos is able to control the pump in order to turn it on and off at the most suitable time, referring to the humidity of the soil in which the sensor is positioned.  
Sensor used : Capacitive soil moisture sensor  
It saves some data on the SD card which allow us to obtain charts to study the soil moisture trend.  

https://user-images.githubusercontent.com/85285913/121808968-956ca800-cc78-11eb-9cd7-f7abf2077fd7.mp4
  
## Project_4
#### Glove Controlled Robotic Hand
Controling a servo motor hand with the power of a glove and flex sensors.
Fingers are made out of foam, springs, tape, and string. Each finger consists of three foam bases (two for the thumb) and a spring embedded through the center of it. String is hot glued to the top foam piece and guided down inside the foam piece.
The most important part of the glove controller are the flex sensors. when the fingers wearing the golves are bent, the flex senson gives signal input to arduino pins.In the coding section provided, its important to realize that parameters will be different depending on each flex sensor and servo motor.  

https://user-images.githubusercontent.com/85285913/121810279-d4512c80-cc7d-11eb-868e-c953c7c78b3c.mp4
  
## Project_5
#### Capturing The Water Drops
captures high-speed photos of water drops with an Arduino.
The laser module KY-008 and the LM393-based light sensor module will detect the drop falling.  
Hardware components :  
![5](https://user-images.githubusercontent.com/85285913/121811214-5858e380-cc81-11eb-8df3-94990bbf94e4.png)  
It is possible to arrange these modules in such a way that the falling drop will interrupt the laser beam thus breaking the circuit. The light sensor is capable of adjusting its sensitivity to the laser power by rotating the variable resistor on the module. Additionally, the modules can be positioned at a long distance from each other.
And when the path of laser is broken, the shutter is opened and the picture is taken.  
![55](https://user-images.githubusercontent.com/85285913/121811366-da490c80-cc81-11eb-8264-f7a5e4f3c62e.jpg)  
Photo taken :  
![image](https://user-images.githubusercontent.com/85285913/121811417-006eac80-cc82-11eb-8c9b-c410b012cda5.png)  
  
## Project_6
#### IR TV Remote
This uses the ESP-32 and IR transmitter and receiver to control Ir sensing devices.Due to the versatility of the ESP32, you can control the remote using three different communication protocols (serial, Bluetooth, and http (over Wi-Fi)).
Then the remote is to be created for controlling. I would like to upgrade the circuit to add a higher power transmitter to increase its range.  
![6](https://user-images.githubusercontent.com/85285913/121812157-76741300-cc84-11eb-9520-0cb5da8d32d5.png)  
  
## Project_7
#### 




## Project_12
#### Portable Thermal Imaging
Accurate thermal-measuring using thermo-cameras.
The thermal camera uses a I2C interface, while the LCD uses an SPI interface, both of these can be easily implemented with the MiniZed PS.  
Sensors used : Avnet MiniZed, Pimoroni MLX90640  
![last1](https://user-images.githubusercontent.com/85285913/121811051-b507ce80-cc80-11eb-8282-e037eda481d0.png)
![last2](https://user-images.githubusercontent.com/85285913/121811057-bb964600-cc80-11eb-8bbf-80c5f0e6f345.jpg)
![last3](https://user-images.githubusercontent.com/85285913/121811065-bfc26380-cc80-11eb-818f-c2e76bd40b13.jpg)









