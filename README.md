# RFID_Arduino

December 2019
 
Tutorial by: https://create.arduino.cc/projecthub/diyprojectslab/diy-rfid-door-lock-system-074173
 
Youtube Demonstration: https://youtu.be/T_e9xgo-yPg
 
Pictures Link: https://drive.google.com/drive/folders/1-TAw9pxDyWZWpBgNZ-vt6mStMALKgFxF?usp=sharing
 
The entire system is based around an RFID sensor (RFID - RC522) and a solenoid Valve Lock. 
All attached to the Arduino the RFID sensor scans for any cards/tags nearby. 
Each tag has its own unique ID which can then be inputted into the code as an approached tag. 
In the demonstration I have approved the white card, but not the blue tag. 
The sensor then reads for the values and if the ID is approved a green light will flash, if not a red light will flash.
I then attached the system to a relay module (TE213) which acts as a switch.
That relay is attached to the solenoid lock with a battery pack attached for external power.
Together the RFID looks for an approved ID; if the ID is approved a green LED will turn on, the relay switched on, and the solenoid lock opens for a set period of time.
If the ID is not approved, a red LED turns on simply indicating an invalid ID has been used.
 
Lessons:
 
I was always curious about how RFID sensors worked and visualizing it live helped my understanding.
It was interesting to see the lock and RFID scanner interact with the simple tap of a card or tag.
