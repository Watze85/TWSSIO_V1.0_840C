# TWSSIO_V1.0_840C   &   TWSSIO_V1.1_840C

Adapter Platine um eine Maschinensteuertafel Siemens Sinumerik 840 C  (6FC5103-0AD03-0AA0) über Mesa SmartSerial zu betreiben.  
Die Platine hat 64 Eingänge, die von den Tastern und Potis verwendet werden  
und 64 Ausgänge, wovon 48 für die LEDs des Panels verwendet werden.  
Die übrigen 16 Ausgänge sind über Schraubklemmen nach Außen geführt und können frei verwendet werden.  
Des weiteren sind 2 Analog Eingänge und 1 Encoder Eingang verbaut.  
Über 2 Flachband Kabel wird die Platine mit dem Siemens Panel verbunden (Pfostenbuchse, 64-polig)  




Achtung: Der Microchip ist ein PIC und lässt sich nur mit dem entsprechenden Programmiergerät beschreiben.  
Da der DSPIC33FJ64GS606-I/PT nur schwer zu bekommen ist gibt es eine Alternative DSPIC33FJ64GS406-I/PT  
Ab V1.1 kann auch der DSPIC33EP32MC204-I/PT verwendet werden (ist auch leichter zu Löten)
  
Firmware beachten!!  
[DSPIC33FJ64GS606-I/PT](/Firmware/SmartSerial_IO_GS606.hex)  
[DSPIC33FJ64GS406-I/PT](/Firmware/SmartSerial_IO_GS406.hex)  
[DSPIC33EP32MC204-I/PT](/Firmware/SmartSerial_IO_MC204.hex)  
  
Mit einem PICkit 3 lässt sich das HEX-File auf den Microchip schreiben.

![This is an image](/Bilder/Sie_1.png)
![This is an image](/Bilder/V1.1_3.jpg)
