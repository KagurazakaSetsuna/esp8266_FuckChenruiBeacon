

# ESP8266 FuckChenruiBeacon

## About
This project is based on the  [esp8266_beaconSpam](https://github.com/spacehuhn/esp8266_beaconSpam)  
  
Connect ESP01 or ESP07's VCC and EN to 3.3Vdc or an AMS1117-3.3 regulator (5v will fry the module), GND to ground, Tx to the programmer's Rx and Rx to the programmer's Tx. Make sure your programmer has a 3.3v output mode or you will need to use a voltage divider to convert 5v to 3.3v.  
    
To flash the .ino file, open the file in Arduino IDE, import the board url http://arduino.esp8266.com/stable/package_esp8266com_index.json and add the ESP8266 in the Boards Manager, choose the  board and flash size according to the board you have. Choose flash mode DIO, reset method NO DTR(CK) and upload speed 921600 for faster upload(try 115200 if upload failed). Pull GPIO0 low BEFORE powering up the module and plug in the module when the IDE says connecting...... Release GPIO0 after uploading the code BEFORE powering up the board again.  

The ESP module could run very hot for some reasons I don't know, so I recommend adding a heat sink to prevent damaging the module.

I made two versions of the beacon with ESP01s and ESP07. The images could be found in the Images folder and the schematics will be uploaded later.
## License

This project is licensed under the MIT License - see the [license file](LICENSE) file for details


> Written with [StackEdit](https://stackedit.io/).
