# DIY Retro USB Controller (AKA a "fight stick")

In this project, I created a box which utilizes old school arcade buttons to act as a working game controller.
The device can connect to a computer with a micro USB cable and outputs keyboard inputs to the computer.
This allows the controller to be used for any game as long as it allows you to rebind the controls.
Everything runs off of an Arduino Leonardo which allows for USB device emulation due to its ATmega32U4 microcontroller.

![The completed controller](https://i.imgur.com/KjPFICD.png)

The outer box was made using some wood found in the street which was cut with power tools and put together with hot glue.
The top piece is the most intricate part of the build in terms of wood working as it features the holes that the button and joystick will be put into.
This part was planned out using AutoCad 2020, and the basic design for the layout was based off of one of the designs showed on [SlagCoin.com](https://www.slagcoin.com/joystick/layout.html).
The top piece was attached to the rest of the box by a pair of hinges rather than simply being glued on. This allows the controller to be opened for easy access to the inside.


![Top piece design](https://i.imgur.com/hokwO5i.png)

The interior of the controller houses all of the wiring. I wanted to refrain from soldering things together to keep everything as modular as possible.
A small breadboard was stuck to the bottom piece of the box to help organize wires.
In the picture below you can see the Arduino which has been screwed into the bottom next to the bread board. I used a short male-to-female micro USB cable to transfer the port access to the back of the box.
The buttons are attached to wires using 0.110" 'Quick Disconnect' cables. I cut the ends off of the opposing ends and used solder to turn the wire into a pin which would nicely stick into the breadboard holes.

![Controller interior](https://i.imgur.com/nuaqRsC.png)

Despite not being the neatest wiring job, everything has managed to remain fully functional since I made it.
I use it quite often for playing older arcade games and it's definitely been a project which I've gotten some use out of.
If you would like to take a look, the code that was uploaded to the Arduino should be included in this Github repository.
