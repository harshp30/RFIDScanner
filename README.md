# RFID_Arduino

December 2019

Youtube Demonstration: https://youtu.be/T_e9xgo-yPg

Pictures Link: https://drive.google.com/drive/folders/1-TAw9pxDyWZWpBgNZ-vt6mStMALKgFxF?usp=sharing

The entire system is based around a RFID sensor (RFID - RC522) and a solenoid Valve Lock. 
All attached to the arduino the RFID sensor scans for any cards/tags near by. 
Each tag has its own unique ID which can then be inputted into the code as a approached tag. 
In the demostraction I have approved the white card, but not the blue tag. 
The sensor then reads for the values and if the ID is approved a green light will flash, if not a red light will flash.
I then attached the system to a relay module (TE213) whihc acts as a switch.
That relay is attached to the solenoid loack with a battery pack attached for external power.
Togther the RFID looks for a approved ID, if the ID is aprroved a green LED will turn on, the relay switched on, and the solenoid lock opens for a set period of time.
If the ID is not approved a red LED turns on simply indicating a invalid ID has been used.

Lessons:

I was always curious about how RFID sensors worked and visualizing it live helped my undertsanding.
It was intresting to see the lock and RFID scanner interact with the simple tap of a card or tag.
