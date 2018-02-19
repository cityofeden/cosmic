## IMU MPU9250

Enable your I2C Communication

Make the wiring 
```
mpu9250	Raspberry Pi
SDA -> 		SDA
SCL->		SCL
VCC->		3volt
Gnd -> 		GND
```

## How to install.
Go to Terminal
Write following commands
Go to the directory

```python
cd mpu9250

```

After Reaching in the Directory
Write the commands mention below

```python
sudo pip install FaBo9Axis_MPU9250
```

After the installation of library just run the python script by typing the command

```python
sudo python program.py
```

So it will show the 
9-Axis sensor data on the screen with the speed of 0.1sec
