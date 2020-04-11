# Phone---PC
Use Adb to create a bridge between phone and pc


This project is under construction. 
When I have free time I'll improve my source code with new functionalities..


Even if, I written everything about the problems to connect phone to pc in my source code, I would like to add the tasks to do in order to get the connection.
//*********************************************************************************************************
So when you connected by USB follow these commands:

stay connect via USB

connect to your WIFI network (computer and mobile device both)

ping DeviceIP (must be have ping to your device)

adb kill-server

adb usb

adb tcpip 5555

unplug usb cable (as per @captain_majid 's comment)
adb connect yourDeviceIP

adb devices (must be see two device names , one of them is by deviceIP)

unplug USB cable
//*************************************************************************************************
