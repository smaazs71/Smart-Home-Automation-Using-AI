# Smart-Home-Automation-using-AI
Home Automation system using Android App with some AI and NodeMCU (Wifi module).  
There are a bunch of home automation apps in the market.
So it was very much difficult to find an advancement in the domain.
We have tried to make some changes and built the whole system along with the app from scratch.

Features of the application include : 

1)Voice access :- The program is designed to access through voice commands. It uses basic NLP for achieving its goal.

2)Command Store :- Since we have the Voice access we have introduced a command store feature where we can store predefined commands to control appliance. This feature is very helpfull. For eg. Assume command "Night Mode" can be used to turn off all lights and turn on specific lights as defined.

3)GUI : A Good GUI was our primary goal but we were unable to achieve it properly. Still the app provides drag and drop, sizing of appliance objects. Also the background can also be set to design and place objects at correct position.

4)Floating Widget Service: This service helps you to access the app or the appliance while using other apps or in home. Its helps the user to access the app wihtout even opening the app.

5)Auto Scheduling: This feature enables the program to schedule the user automatically after confirming with the user on the basis of usage. To be honest, It is an incomplete feature the server and hardware side programming is done just the programming in app is remaining. 


   On the Hardware end NodeMCU wifi module is used and programmed to be accessed from remote locations too. The connection is made through http protocol. The response is in String format in json structured. Then the response is analysed to control the appliance or signal the relay. 

   To link the hardware and the app a server is created using a website which can be accessed through Http protocol.
The server is manipulated by application and manipulates the hardware.
