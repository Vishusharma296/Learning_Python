# Exploratory Data Analysis code for collected temperature pressure data

## Sensor Data EXP1 -Test 03
   
- Experiment duration: 01.05.2024 - 01.06.2024
- Total samples: 81,456
- Sampling Period: 10 seconds
- Microcontroller: rpi picoW
- Sensor: Bosch BMP280 temperature pressure sensor
- Sensor data transfer from sensor to MCU via I2C
- Sensor data transfer to server via MQTT Wirelessly
- Data logging using InfluxDB then extracted using python scripts
- Recorded Variables: Message counter, Timestamp, Temperature, Pressure
