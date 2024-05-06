# USB2CAN_HW
USB to CAN adapter based on the work done by [Hubert Denkmair](https://github.com/HubertD) and [Ethan Zonca](https://github.com/normaldotcom)

The project was started because of the shortage of STM32 parts available.

The STM32F072xB and STM32F042x6 were both unavailable with no time frame for availability.

The STM32F302C8 was chosen primarily because it was available, and because it included CAN/USB capabilities.

The USB2CAN board does not feature galvanic isolation.

The protocol implemented is SLCAN, although not all functions are complete or included. 

The firmware is a combination of [canable firmware](https://github.com/normaldotcom/canable-fw) and [candleLight firmware](https://github.com/candle-usb/candleLight_fw)

# [Store](https://dingo-electronics.square.site/product/usb2can/2)

# Photos
![Top](/Images/Top1.jpg)

![Top2](/Images/Top2.jpg)

![Bottom](/Images/Bottom.jpg)

# Firmware
[USB2CAN firmware](https://github.com/corygrant/USB2CAN_FW)

# Disclaimer
Please note that this product has been designed by a hobbyist, not a professional. It is intended for off-road and testing use only. Users should operate the product at their own discretion and risk. The designer explicitly disclaims any responsibility for damage or injury that may result from the use of this product.
