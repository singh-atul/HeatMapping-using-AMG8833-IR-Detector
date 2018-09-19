# HeatMapping-using-AMG8833-IR-Detector
Heat Mapping with a 64-Pixel Infrared Detector (AMG8833), Arduino, and Python

# Download the Arduino Software (IDE)
Download the software from [here](https://www.arduino.cc/en/Guide/Linux) for your respective OS

# Download AMG88xx
Goto Tools->ManageLibrary
Search for AMG88 and install Adafruit AMG88XX library by adafruit v1.0.2

# Connect your Arduino with PC and get the port number
Tools->Port
It will show the port connected to your arduino , Select it and make sure you have a check infron of it.
Note down the port name as you have to update it in the python file.

Select the board you are using from Tools->Boards

# Check Connection of Arduino
Upload a basic code to the arduino from example if it get uploaded without any error then everything is working properly.
Inorder to upload the basic code follow the steps
File->Example->Basics->Bare Minimum and upload it.
If you get any error try running the following command in terminal and retry.

sudo chmod a+rw /dev/ttyACM1

# Make sure you have the following python packages
 Pyserial python -m pip install pyserial
 Matplotlib pip install --user matplotlib
 
 run the python file using the following command
 
 python HeatMapGeneration.py


