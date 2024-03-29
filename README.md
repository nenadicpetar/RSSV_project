# RSSV_project
Lab assignment for course Real-time Computer Systems. Assignment was to create light system for bike in which, depending on leaning direction, turn indicators are turned on. Also, system must have front light which is turned on automatically, depending on day light, and brake light depending on leaning direction. Sensor that are used in this project are:
- [LED's](https://en.wikipedia.org/wiki/Light-emitting_diode)
- [Photoresistor](https://en.wikipedia.org/wiki/Photoresistor)
- [GY-521 accelerometer](https://mschoeffler.com/2017/10/05/tutorial-how-to-use-the-gy-521-module-mpu-6050-breakout-board-with-the-arduino-uno/)
- [Croduino basic module](https://soldered.com/hr/learn/programiranje-croduino-basic2-iz-arduino-ide/)

LED's are used for turn indicators, front and back light. Accelerometer is used for bike's state readings, while photoresistor is used for detection for day light. Code is written in [Arduino software](https://www.arduino.cc/en/software), and libraries that are used in this project are:
- [Adafruit_MPU6050](https://github.com/adafruit/Adafruit_MPU6050)
- [Adafruit_Sensor](https://github.com/adafruit/Adafruit_Sensor)
- [Wire](https://www.arduino.cc/reference/en/language/functions/communication/wire/)

