# x-nucleo-sensors
Library for STMicroelectronics' Sensors

Note, header files sub-directory `Interfaces` contains all abstract classes which together constitute the common API 
to which all existing and future ST sensor components will adhere to.

The library currently supports the following sensors:
- **hts221**: relative humidity and temperature sensor
- **lis3mdl**: 3-axis magnetometer
- **lps25h**: MEMS pressure sensor (and temperature sensor)
- **lsm6ds0**: 3D accelerometer and 3D gyroscope
- **lsm6ds3**: 3D accelerometer and gyroscope (featuring free-fall detection) 
