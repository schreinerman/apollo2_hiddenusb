# apollo2 hiddenusb

Apollo2 hidden USB is not a hidden hardware feature, but software bit-banging using Apollo2s flexible GPIOs including the capability to drive 1.5k pullup resistors on special pins used with I2C. At least low-speed USB is working for realizing HID USB transfers. Idea is to add an USB HID based bootloader.

The demo emulates an USB keyboard and is starting the start menu and typing "April Joke" and return (opens Internet Explorer searching for April Joke):

Download apollo2_hiddenusb.bin to Apollo2 MCU

Do the USB Cable connection:
- Connect D- to AMAPHEVB GPIO8
- Connect D+ to AMAPHEVB GPIO9
- Connect GND to AMAPHEVB GND
- Connect VBUS (5V) to AMAPHEVB 5V (!!not to VCC!!)

Last Step:
- Connect USB to PC.

Wait 15 seconds and see the result on a Windows PC

See also http://shop.feeu.com/Shops/es966226/Products/AMAPHEVB to order a board

Stay tuned for the full sources...
