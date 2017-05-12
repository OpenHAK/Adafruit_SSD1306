# OpenHAK_SSD130
Custom spin of the Adafruit_SSD1306 library for 128x64 and 128x32 OLED displays
Original code can be found [here](https://github.com/adafruit/Adafruit_SSD1306)

## This library specifically targets the Simblee on the OpenHAK Fitness Tracker

Uses the second I2C bus on the Simblee:
`#define SCL_PIN   2  
#define SDA_PIN    3  
Wire2.beginOnPins(SCL_PIN, SDA_PIN);`
