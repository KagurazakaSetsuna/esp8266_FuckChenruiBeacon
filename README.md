# ESP8266 FuckChenruiBeacon

## About
This project is based on the esp8266_beaconSpam [esp8266_beaconSpam](https://github.com/spacehuhn/esp8266_beaconSpam)

The Arduino sketch comes with 50 SSIDs, but you can edit that list easily in the source code :).  
By constantly broadcasting the so-called beacon frames, your standard WiFi scanner will think there are active networks nearby and adds them to the list.  
In reality though, it is just advertising Fuckchenrui without actually creating them. So there is no way you could connect to one of the "created" networks.  

It is using the `wifi_send_pkt_freedom` function in the ESP8266 Arduino Core SDK. This function allows packet injection for specific Wi-Fi frames.  

## License

This project is licensed under the MIT License - see the [license file](LICENSE) file for details

