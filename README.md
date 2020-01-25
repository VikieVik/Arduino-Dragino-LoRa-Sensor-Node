# Arduino-Dragino-LoRa-Sensor-Node

This project simplifies LoRawan sensor node development using Dragino LoRa shield for Ardunino

## Hardware Requirements 

### Arduino

Arduino platform is preferd as Host MCU
Arduino [UNO](https://store.arduino.cc/usa/arduino-uno-rev3),[Leonardo](https://www.arduino.cc/en/Main/Arduino_BoardLeonardo), [Mega](https://store.arduino.cc/usa/mega-2560-r3) and other boards with same pin layout are compatible
You do not need to buy from official store amazon ones also peroforms the same
*Buy from arduino.cc if you want to support them !*







Note : While Ordering LoRa devices for Arduino/RaspberryPi select the freqency as per you region as
LoRa operates on different freqncy for different region use below table for reference.

|   Region   |    Frequency  |
| ---------- | ------------- |
| INDIA/EUR  |    868 MHz    |
|   US/AUS   |    915 MHz    |
|   CHINA    |    433 MHz    |

[Detailed Country-Frequency Guide](https://www.thethingsnetwork.org/docs/lorawan/frequencies-by-country.html)




### Dragino Arduino LoRa shield 

[Dragino LoRa shield for Arduno](https://www.amazon.com/Dragino-Compatible-Arduino-Leonardo-Consumption/dp/B07HD1MH3J/ref=sr_1_2?keywords=dragino+Arduino+LoRa+shield&qid=1579113922&sr=8-2) is a plug and play shield for adding LoRa connectivity to your arduino
Just Place it on the arduino and push like resular shield and follow the software guide. You can find
more on [Offical Dragino site](https://wiki.dragino.com/index.php?title=Lora_Shield)

[Dragino's Official Hardwar guide and manual](https://wiki.dragino.com/index.php?title=Lora_Shield)


### LoRa Gateway

LoRa devices send data to internet like regular cellphone devices
They also need an intermediate device that accepts their sensor data and relay it to a cloud(also known as network server eg: [TheThingsNetwork](https://www.thethingsnetwork.org/))

**This guide assumes you either have TheThingsNetwork LoRa gateway coverage in your area that you can 
check the live coverage map provided on [TheThingsNetwork](https://www.thethingsnetwork.org/)**

or 

**You have a Local DIY LoRa gateway running that can route data transmitted by arduino LoRa node to cloud**

You will need [Raspberry Pi 3](https://www.amazon.com/Raspberry-Pi-RASPBERRYPI3-MODB-1GB-Model-Motherboard/dp/B01N13X8V1/ref=sxbs_sxwds-stvp?cv_ct_cx=prime+raspberry+pi&keywords=prime+raspberry+pi&pd_rd_i=B01N13X8V1&pd_rd_r=6e87624d-3249-44b0-930a-193955cbce0b&pd_rd_w=Q31Fs&pd_rd_wg=Y8Rzi&pf_rd_p=a6d018ad-f20b-46c9-8920-433972c7d9b7&pf_rd_r=YGWB89HDQDD4655XVVWQ&psc=1&qid=1579114780&s=specialty-aps) and [Dragino LoRa Raspberry Pi Hat](https://www.amazon.com/Dragino-Raspberry-Temperature-Support-Command/dp/B07HCZMHKZ/ref=sr_1_1_sspa?keywords=raspberry+pi+LoRa+hat&qid=1579114833&s=electronics&sr=1-1-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUE5OUtFNkdYT1NLTVEmZW5jcnlwdGVkSWQ9QTA0NzU1OTkxQUM3OVNDUlVKUU1IJmVuY3J5cHRlZEFkSWQ9QTAzMTYzODkxMEVEUEwzOFgxUlBEJndpZGdldE5hbWU9c3BfYXRmJmFjdGlvbj1jbGlja1JlZGlyZWN0JmRvTm90TG9nQ2xpY2s9dHJ1ZQ==) to build one.
YouTuber **Andreas Spiess** Has provided Very good [video](https://www.youtube.com/watch?v=Ya-QlEaonLU&list=PL3XBzmAj53Rkkogh-lti58h_GkhzU1n7U&index=6) on building such gateways.



# Contributions

[Arduino-LMIC](https://github.com/matthijskooijman/arduino-lmic)

# See Also

[Semtech core LMIC implementation](https://github.com/Lora-net/LoRaMac-node)
