# https---github.com-Opata-MPU6050_Demo_on_Raspberry-Pi-2-
Simple MPU6050 demo with Raspberry Pi 2 
Simple MPU6050 Demo on Raspberry pi 2 using ITG-MPU breakout board (MPU6050)
This breakout board from aliexpress for $1.50. 40pin old IDE cable used to connect to raspi2
no interrupt, +vcc of the board is connected to +5v of raspi2
only sda, scl connected to raspi2.
MPU data accessed regularly every 10ms (.01sec), sleep time reduced to allow data processing and draw.
By Opata Padmasiri  
codes for reading data from MPU6050 and complementary filter taken from the following blog: 
http://blog.bitify.co.uk/2013/11/reading-data-from-mpu-6050-on-raspberry.html
