
## Flashing
Its written in C++, so plan accordingly. It was developed using PlatformIO. Its highly likely that it will also function with the Arduino IDE and .ino extension.

### Info
Simple example of connecting an ESP8266 to OpenRemote, its linked to a presence asset with a custom 'status' attribute which will be updated through the last will message.
Connected to the ESP is just a simple PIR motion sensor which is directly connected to the D1 pin.

### Connection guide
- Ensure you have an OpenRemote manager running and accessible from the ESP
- Update the secrets.h file with the appropriate information
- Update the main.cpp with the appropriate topics, realm, asset ID and the attribute name.



