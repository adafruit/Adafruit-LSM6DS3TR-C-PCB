## Adafruit LSM6DS3TR-C 6-DoF Accel + Gyro IMU - STEMMA QT / Qwiic PCB

<a href="http://www.adafruit.com/products/4503"><img src="assets/4503.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit LSM6DS3TR-C 6-DoF Accel + Gyro IMU - STEMMA QT / Qwiic. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/4503

### Description

Add motion and orientation sensing to your Arduino project with this affordable 6 Degree of Freedom (6-DoF) sensor with sensors from ST. The board includes an ST LSM6DS3TR-C, a great entry-level 6-DoF IMU accelerometer + gyro. The 3-axis accelerometer can tell you which direction is down towards the Earth (by measuring gravity) or how fast the board is accelerating in 3D space. The 3-axis gyroscope can measure spin and twist.

This chip is very similar to the now-discontinued LSM6DS33, a great entry-level IMU. As part of the illustrious LSM6DS family, its well-established, well-supported and this chip even has better performance! Note it is not firmware-compatible with the 'DS33, so you will need to recompile code (e.g our Arduino and Python libraries support the whole family but you do have to indicate which exact chip you're using)

To make getting started fast and easy, we placed the sensors on a compact breakout board with voltage regulation and level-shifted inputs. That way you can use them with 3V or 5V power/logic devices without worry. Both I2C and SPI interfaces are available, so you'll be able to use them with any hardware setup. The breakout comes fully assembled and tested, with some extra header so you can use it on a breadboard. Four mounting holes make for a secure connection.

This breakout does not include a magnetometer, often required for accurate orientation. We recommend the LIS3MDL 3-axis magnetometer to match up with this IMU.

Additionally, since it speaks I2C you can easily connect it up with two wires (plus power and ground!).  We've even included SparkFun qwiic compatible STEMMA QT connectors for the I2C bus so you don't even need to solder! Just wire up to your favorite micro like the STM32F405 Feather with a plug-and-play cable to get 6 DoF data ASAP. You can change the I2C address on the back using the solder jumper, to have two of these sensor boards on one bus.

We also wrote libraries to help you get these sensors integrated with your Arduino/C++. This library contains an Arduino driver for the accel/gyro. For advanced Arduino usage, ST has their own fully-featured library that includes extras such as FIFO management and tap detection for the LSM6DS3TR-C. We also have a Python/CircuitPython library that will work on microcontroller or single board linux computers.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
