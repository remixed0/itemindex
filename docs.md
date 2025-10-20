How does the system work?

A QR code is created with information that genneraly includes:
a unique identifier for the paticular inventory item and is registered to a local database
information refrencing the current position that items are currently stored at

here's an example on information on an item stored in the database:
Name of item: "4684"
Item amount: 50
obtained from: https://www.digikey.com/en/products/detail/adafruit-industries-llc/4684/13170959
Current position x:10, z:50, y:2, drawer#2
Image:https://www.digikey.com/en/products/detail/adafruit-industries-llc/4684/13170959

The formating of information on an item can be changed to the users own prefrences; prefered file format, and necessary info on whats stored

The RFID tag serves as a redundancy to the QR code and is intended to serve the same function, the RFID tag is meant to allow querying and updating the system
but without the need for scanning a QR code

What is used?

https://en.wikipedia.org/wiki/Radio-frequency_identification : RFID tag, redundancy to the QR code and is commonly used to interact with the item DB
https://en.wikipedia.org/wiki/QR_code : Visual QR code scanned for item indexing
https://www.android.com/ : Create the software APK on android platform for use
https://developer.android.com/
https://www.qt.io/ : UI framework
https://www.qt.io/download-open-source?hsCtaTracking=9f6a2170-a938-42df-a8e2-a9f0b1d6cdce%7C6cb0de4f-9bb5-4778-ab02-bfb62735f3e5#consider

The database can be hosted on whatever is used, PC, Embeded system, or Server
Windows/Linux/x86 or ARM

The Interface can be run on Iphone Android RPI ARM

QR codes / RFID / NFC are attached to items that would be indexed to the DB

sqlite
fiducials
http server
AR android app utilizing alignment fiducials

https://developer.android.com/
https://epson.com/For-Work/Wearables/Smart-Glasses/Moverio-BT-40-Smart-Glasses-with-USB-Type-C-Connectivity-/p/V11H969020
https://www.youtube.com/watch?v=7WAhquGQq3o
https://www.youtube.com/watch?v=77hET4FhH_0
