# TinyBasicPlus_OLED_support
SSD1306 compatible OLED/LCD (128x64 dots) support is added, using Adafruit_GFX lib. 
Frame buffer for 21x8 characters is added for text display.
//      SSD1306 compatible OLED/LCD (128x64 dots) support is added, using Adafruit_GFX lib. 
//      Frame buffer for 21x8 characters is added.
//      Along this support, TVout and PS2 keyboard support is subtracted, assuming
//      re-programmed Xbox360 or serial console usage for input device.
//      (you can add PS/2, if you need) I refered the source code by Ben Heck's
//      Retro Basic Computer. 
//      GRAPHIC related BASIC commands (currently supporting only direct command): 
//      CLS, LINE x0,y0,x1,y1 CIRCLE x,y,radius FILLCIRCLE x,y,radius ROUNDRECT x,y,w,h,r
//      FILLROUNDRECT x,y,w,h,r are added just for graphic test..
