# USB2CAN_HW
USB to CAN adapter based on the work done by [Hubert Denkmair](https://github.com/HubertD) and [Ethan Zonca](https://github.com/normaldotcom)

The project was started because of the shortage of STM32 parts available.

The STM32F072xB and STM32F042x6 were both unavailable with no time frame for availability.

The STM32F302C8 was chosen primarily because it was available, and because it included CAN/USB capabilities.

The USB2CAN board does not feature galvanic isolation.

The protocol implemented is SLCAN, although not all functions are complete or included. 

The firmware is a combination of [canable firmware](https://github.com/normaldotcom/canable-fw) and [candleLight firmware](https://github.com/candle-usb/candleLight_fw)

# Renderings
![Top](/Renders/USB2CAN_Top.jpg)

![Bottom](/Renders/USB2CAN_Bottom.jpg)

# Firmware
[USB2CAN firmware](https://github.com/corygrant/USB2CAN_FW)
