# hoverboard-firmware-hack-FOC

This Fork is for storing the modifications of the original firmware to support SSD1306 OLED panels for some debug info, and for other changes I make. If this becomes useful enough, I may try to do a pull request on the main repo, but for now I am still learning github.

Added function: in config.h there is one argument added called OLED_DISPLAY under I2C debug display. In main.c there is a simple function that brings the serial debug features to this display.

Visit here for the original firmware: [hoverboard-firmware-hack-FOC](https://github.com/EFeru/hoverboard-firmware-hack-FOC)
