# ESP8266-with-BME280
Sample Code of ESP8266 with BME280

# Wiring BME280 Sensor to ESP8266 NodeMCU
Connections are fairly simple. Start by connecting VIN pin to the 3.3V output on the ESP8266 NodeMCU and connect GND to ground.
Next, Connect the SCL pin to the I2C clock D1 pin on your ESP8266 and connect the SDA pin to the I2C data D2 pin on your ESP8266.

# Installing Library For BME280
To install the library navigate to the Arduino IDE > Sketch > Include Library > Manage Libraries… Wait for Library Manager to download libraries index and update list of installed libraries.

Filter your search by typing ‘bme280’. There should be a couple entries. Look for Adafruit BME280 Library by Adafruit. Click on that entry, and then select Install.

The BME280 sensor library uses the Adafruit Sensor support backend. So, search the library manager for Adafruit Unified Sensor and install that too (you may have to scroll a bit)

# 
