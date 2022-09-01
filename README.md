# README

A simple program for downloading BMP images over Wifi on an ESP8266 and displaying them to a Waveshare 7.5" b/w/r E-Ink display. This is a modification of the [wifi example included in GxEPD2](https://github.com/ZinggJM/GxEPD2/blob/master/examples/GxEPD2_WiFi_Example/GxEPD2_WiFi_Example.ino).

**Screen:**

880×528, 7.5inch E-Ink display HAT for Raspberry Pi, red / black / white three-color

SKU: 17960

Part Number: 7.5inch HD e-Paper HAT (B)

Brand: Waveshare

**Controller:**

ESP8266

# Creating BMP images

Note that any BMP images displayed using the bitmap processing included in the GxEPD2 examples must have a color table size that is equal to the square of the bit depth of the image. I used Photoshop to create BMP images that had a bit depth of 4 and a color table size of 16. Given that my E-Ink display only supports 3 colors, I set the first 3 colors as black, red, and white, and then padded the rest of the colors with black until I had 16 colors in total. [More info can be found here](https://forum.arduino.cc/t/waveshare-e-paper-displays-with-spi/467865/3138?u=gtsioni).

# Issue with black image links

[Link to 880x528 bmp](https://drive.google.com/file/d/1MszMWq1h0jqFslfFS5JgHsHkx_4ozQIp/view?usp=sharing)

[Link to code](https://github.com/gavrieltsioni/eink_public/blob/0cfd640e7f3669e2739062de80638194b9881f52/GxEPD2_WiFi_Example_clean.ino)

[Link to diff from example](https://github.com/gavrieltsioni/eink_public/commit/0cfd640e7f3669e2739062de80638194b9881f52)

[Link to picture of screen for 880x528 image](https://i.imgur.com/xooep10.png)

[Link to picture of screen for 200x200 image](https://i.imgur.com/v3by2sS.jpg)

# Issue with transposed image links

[Link to 880x528 bmp](https://drive.google.com/file/d/1MszMWq1h0jqFslfFS5JgHsHkx_4ozQIp/view?usp=sharing)

[Link to code](https://github.com/gavrieltsioni/eink_public/blob/8e6eb24e28f02be56416fa7bb7dc29131545555f/GxEPD2_WiFi_Example_clean.ino)

[Link to diff](https://github.com/gavrieltsioni/eink_public/commit/8e6eb24e28f02be56416fa7bb7dc29131545555f)

[Link to picture of screen for 880x528 image](https://i.imgur.com/clJGeVG.jpg)

[Link to picture of screen for 200x200 image](https://i.imgur.com/hiQejQx.jpg)
