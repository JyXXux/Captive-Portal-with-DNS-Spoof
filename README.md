# Captive-Portal-with-DNS-Spoof
will able to extract password, email id


A login page will appear when someone connects to this 
It asks the user for an email and a password for a fake sign in.
The built-in LED will blink 3 times after the login process is completed by someone.

Note: If you want to see the stored credetials go to "http://yourcurrentwebsite.com/creds" or "172.0.0.1/creds"

Installation (Arduino IDE)

Open your Arduino IDE and go to "File -> Preferences -> Boards Manager URLs" and paste the following link: http://arduino.esp8266.com/stable/package_esp8266com_index.json

Go to "Tools -> Board -> Boards Manager", search "esp8266" and install esp8266

Go to "Tools -> Board" and select you board"

Download and open the sketch "captive portal.ino"

You can optionally change some parameters like the SSID name and texts of the page like title, subtitle, text body...

Upload the code into your board.

You are done!
