# Alexa-Iot
Welcome to my Alexa IOT project. This started as a class project for a certificate program I'm taking in IOT design. My final project to date is a mini-weather station using a Raspberry Pi 3 with the Pi SenseHat. I’ve also Alexa-enabled my Raspberry Pi using the Alexa Voice Service sample project and I’ve connected the Pi to AWS IOT enabling me to create an Alexa Voice Skill to access the sensor data and even write messages to the LED display on the Pi SenseHat. 

I’m documenting this from a beginner perspective and I hope this will help others trying to learn how to build IOT devices and integrate with Alexa. This project will guide you through creating a simple IOT prototype using the Raspberry Pi 3.

# What You'll Need
- Raspberry Pi 3: https://www.amazon.com/Raspberry-Pi-RASPBERRYPI3-MODB-1GB-Model-Motherboard/dp/B01CD5VC92
- SD Card with Raspbian Jessie: https://www.amazon.com/Raspberry-Pi-Preloaded-NOOBS-Card/dp/B00ENPQ1GK
- Pie SenseHat: https://www.adafruit.com/products/2738
- AWS Free Tier Account: https://aws.amazon.com/free/
- Alexa Developer Account: https://developer.amazon.com/alexa
- TFT 5 inch Monitor (or other HDMI monitor): https://www.adafruit.com/products/2232
- HDMI Cable: https://www.adafruit.com/products/2197
- Keyboard and Mouse
- Micro-USB Power Cable
- (Optional) USB 2.0 Mic: http://amzn.com/B00IR8R7WQ 
- (Optional) External Speaker: http://amzn.com/B007OYAVLI

# Setting up the Raspberry Pi

## Downloading and Burning a New Image 
My RPI3 is running Raspbien Jessie with PIXEL but you could also just use NOOBS that comes with the SD card. If you want to update:
1. Download the image: https://www.raspberrypi.org/downloads/raspbian/
2. Follow the instructions to install the OS image. 