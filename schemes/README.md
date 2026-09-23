# Schemes Documentation

This folder contains the complete electrical schematics, and power management documentation for Team SJVL67 WRO 2026 Future Engineers robot. All the electronics were assambled in a custom PCB designed by us to achieve optimal performance and organization in our robot.

## - Why we choosed a PCB?

We choosed a pcb due to the organization management that it provides to the electronics. We used a web based EDA in order to design this PCB, the program used was EasyEDA. We wanted to use a custom pertinax board but it was too bulky, but in the end we selected the PCB for the the previous mentioned reasons, even if it presented the problem of slow manufacturing and modification produced by the need of get them machined in China, we are from Ecuador. With us making a custom design we developed the essential engineering skills to manufacture it int the best way.

## Complete Bill of Materials (BOM)


| Component | Image | Quantity | Type | Description |
|-----------|-------|----------|------|-------------|
| ARDUINO NANO ESP32 | <img src="../other/Arduino_nano_esp32.jpg" alt="Sensor Microcontroller" width="200"> | 1 | Sensor Microcontroller | Dual-core 240MHz microcontroller with 512KB SRAM and 3.3V logic. Used for sensor managing, controlling the motors, and processing data. |
| ESP32-S3-CAM | <img src="../other/esp32s3-cam.jpg" alt="Camera Microcontroller" width="200"> | 1 | Camera Microcontroller | Dual-core 240MHz processor with vector instructions and 3.3V logic. Used for computer vision. |
| OV2640 | <img src="../other/ov2640_image.jpg" alt="Camera" width="200"> | 1 | 2MP camera | A 2-Megapixel CMOS sensor with a 68° view angle and 3.6mm focal length. |
| TOF400C | <img src="../other/TOF400C.jpg" alt="ToF Sensor" width="200"> | 4 | ToF sensor | 400cm range, 27° FOV - used for front, back, and sides detection. |
| BMI160 | <img src="../other/BMI160_image.jpg" alt="IMU" width="200"> | 1 | 6-axis IMU |  A 6-axis motion sensor combining a 3-axis accelerometer and a 3-axis gyroscope for navigation. |
| TB6612FNG DRIVER | <img src="../other/tb6612fng_image.jpg" alt="Motor Driver" width="200"> | 1 | Motor Driver |  A PWM motor driver for DC motor control |
| VOLTAGE REGULATOR | <img src="../other/Buck_converter_image.jpg" alt="Voltage Regulator" width="200"> | 1 | Voltage Regulator |  A step-down 5v voltage regulator to power the microcontrollers and the sensors. |
| SG90 SERVO | <img src="../other/SG90_IMAGE.jpg" alt="Servo" width="200"> | 1 | Servo Motor | Micro servo motor for the steering mechanism. |
| 1000rpm N20 motor | <img src="../other/1000rpm_N20_dc_motor_encoder.jpg" alt="DC Motor + Encoder" width="200"> | 1 | DC Motor + Encoder | Brushed DC motor with Hall effect encoder. |
| GNB 3s 380mAh lipo | <img src="../other/Battery_image.jpg" alt="Battery" width="200"> | 1 | Battery | 11.4V 380mAh lipo battery. |
| Start Button | <img src="../other/BUTTON_image.jpg" alt="Start Button" width="200"> | 1 | Start Button | Start action initiation button. |
| Custom Tire | <img src="../other/Custom_Tire_image.jpeg" alt="Tire" width="200"> | 1 | Tire | 41mm diameter, 5mm silicon tire. |

---

## Complete Wiring System

<center>
  
  ### PCB Schematic
  
  <img src="../schemes/SCH_WRO_1-Sheet_1.png" width="900">
  
</center>

<center>
  
### Wiring to PCB

  <img src="../schemes/Wiring_Diagram.png" width="900">
  
</center>
