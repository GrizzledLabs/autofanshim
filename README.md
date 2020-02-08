# autofanshim
Custom script utilizes a pimoroni fanshim for cooling raspberry pi

Uses fanshim for cooling raspberry pi from Pimoroni.

When  the pi reaches 70 F, cools for 60 seconds and LED on fanshim lights up a muted white while fan runs. When 60 second fan runtime ends, fan and LED turn off. Temp is checked every 5 seconds when fan not running.

Make file executable, and schedule to run at boot. 
