A ESP32 based fingerprint sensor.
This code is for making an esp32 based fingerprint sensor which has the following parameters:
1. The fingerprint sensor (AS608) will be communicating with the ESP32 through I2C protocol.
2. First you have to store the fingerprints of the people you need to check. To do this you have to upload the enroll code first and store all the finger prints you want to check.
3. After the configuration is done, upload the biometric code to run the main program.
4. This code is programmed to send the data to a Thingspeak DataBase through API protocol where you can see the raw data as well as you can see the data in graphical and other types of representations. You can either check the Fingerprint ID in Thingspeak or you can add a LCD screen to see the data.
5. 
