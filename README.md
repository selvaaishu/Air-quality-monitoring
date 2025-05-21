# Air-quality-monitoring-proceddure
1. Component Assembly:

Collected all required components: NodeMCU ESP8266, MQ135 Gas Sensor, DHT22 Sensor, 16x2 LCD with I2C, and jumper wires.


2. Circuit Design in Wokwi:

Created the full circuit virtually using Wokwi simulator.

Connected MQ135 and DHT22 sensors to NodeMCU.

Interfaced the LCD using I2C to reduce pin usage.

Simulated the setup to verify connections and outputs



3. Coding and Upload:

Wrote the program using Arduino IDE.

Included required libraries for Blynk, LCD, and sensors.

Libraries used : LiquidCrystals I2C,DHT Sensor Library, BlynkESP32_BT_WF,PIR

Added Blynk auth token and Wi-Fi credentials.



4. Blynk App Configuration:

Set up a Blynk project on the mobile app.

Added widgets to display temperature, humidity, and gas levels.


5. Simulation Testing on Wokwi:

Uploaded code in Wokwi and observed sensor data updates.
Verified data flow from sensors to LCD and Blynk app.
