# zeroairfeeder
ZeroAirFeeder turns the CardputerZero into an ADS-B feeder for Flightradar24, Plane Finder and AirNav RadarBox. Plug an RTL-SDR dongle with a 1090 MHz antenna into the USB-A port, fit the Cap LoRa-1262 with GPS, connect to Wi-Fi and start feeding.
The app can also be used without an internet connection, the feeder firmware will work and send data to a local network(like the Cardputer hotspot or any network at which the device is connected to).

Download the latest release from [here](https://github.com/wirpool/zeroairfeeder/releases/latest)


Following an explanation of what the pages of the app do:


PAGE FEED

<img width="320" height="170" alt="feed" src="https://github.com/user-attachments/assets/3216f68c-c67b-4ec3-85da-5b63921f1f46" />

Here you can see the status of every feeder you are running, receiver data and GPS data.
In the lower part of the screen you see key 4 to change page, key 5 to start the feeder firmware, key 6 is the log access, key 7 is day/night mode and key 8 is for exit the app.


PAGE KEYS

<img width="320" height="170" alt="keys" src="https://github.com/user-attachments/assets/a9a06353-ab18-4829-9c6a-61a1da3c4786" />

Here you can manage your keys as well as request a new one directly in app:
- Flightradar24 and AirNav Radarbox: if you don't have a key the request is automatic in the app.
- PlaneFinder: you have to submit the request via planefinder website, find the qrcode and instruction in app.


PAGE SETUP

This is where you can manage all about the services in the app. 

<img width="320" height="170" alt="setup 1" src="https://github.com/user-attachments/assets/5405d21c-e33a-4e45-88b1-d994d5b506af" />

First of all you can choose which service is active and which is not, like if you are on a plane and want to track the route keep active only Plane Finder and connect to the remote page instead of waste energy for Flightradar24 and AirNav Radarbox services which are useless for this purpose. 

<img width="320" height="170" alt="setup 2" src="https://github.com/user-attachments/assets/e6005416-80ec-43b6-bab7-61b634e38a70" />

Then if you scroll down you'll see the setup for the receiver(gain, ppm correction) and the GPS data if you want or need you can insert them manually from here pushing enter on the row position or altitude depending on what you want to add.

<img width="320" height="170" alt="setup 3" src="https://github.com/user-attachments/assets/69482862-4309-441b-bb6c-cdbfc92d4585" />

Last but not least you have this zone where you can do multiple things. 
If you enter in "Local pages(QR)" you'll find multiple pages with different qrcodes, every qrcode redirect to a selfhosted page that you can see with your mobile: radar page, page of the FlightRadar24 service, page of the PlaneFinder service, page of the AirNav Radarbox service(this is not selfhosted, need internet connection to work).
Pushing enter in the second row you'll check for update of all the clients installed.
Selection theme and Language of the app.
See the log and the About pages.

Thankyou all for downloading my app, hope you enjoy it.

Wirpool
