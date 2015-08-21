# Unmanned Ground Vehicle

This project aims to develop a low cost unmanned ground vehicle which can be modular to provide video feed and process the feed to target the enemy. Various sensors such as camera, Global Positioning System (GPS), digital Flash are installed on UGV for the operator to sense the environment. Camera is used to provide live feed of the field. It also serves as an input device to track the enemy[person]. The image processing on the video feed is done on the Base station computer side which then sends the 2d frame coordinates of detected motion or detected face to the Arduino on the UGV side. This Arduino controls the gun control mechanism (GCM) with two preloaded preses, manually or autonomously. The data from the sensors and camera is presented on Graphical User Interface (GUI) on Base Station computer for the operator . XBEE modules are used to implement the wireless communication between the base station computer and UGV. The platform is suitable for several military and rescue operations. 

# Handbook for UGV
Contains structural dimensions of UGV, tools, Literature survey, Details, References, Setups and more...

[Handbook Link](https://drive.google.com/open?id=0B8AvA4pSX6fcbGpYTXYxTVRtUTQ)

# Final Product
* Hardware prototype

 ![image](https://github.com/gauresh10/Unmanned_Ground_Vehicle/blob/master/Images/final.jpg)
* GUI
 ![image](https://github.com/gauresh10/Unmanned_Ground_Vehicle/blob/master/Images/guifinal.jpg)



# System Block

* Block diagram of BS

![image](https://github.com/gauresh10/Unmanned_Ground_Vehicle/blob/master/Images/bs.jpg)

* Block diagram of UGV

![image](https://github.com/gauresh10/Unmanned_Ground_Vehicle/blob/master/Images/ugvside.jpg)

# Technologies used
* Java
* OpenCV
* Arduino Java

# Software tools
* Processing IDE v 2.xx
* Arduino IDE v 1.5 or later
* Zigbee XCTU with drivers

# Electronic components
* 1. Arduino UNO or MEGA 2560
* 2. Zigbee S2 or S2 Pro 
* 1. Wireless HD camera
* 1. Digital flash lights















