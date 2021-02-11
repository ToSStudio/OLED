# OLED with U8g2 #

this is a result of experimenting with those small OLED Displays for Arduino (0.96 inch, 128 x 64 pixel) and the like. The most frequently used library is Oliver Karus' U8G8 Lib. All you have to do is select the correct descriptor and off you go with graphics and text to your liking.

Took me a while to figure out that you have to chose **either** one frame or full-frame and code accordingly. You can see the difference in the constructor which is either the F- or the 1-Flavor.

Tested both to see effects in the resulting programme size. Fact is: it hardly makes a difference.

BTW, if you're scouting for a small footprint Graphics lib: check bitbank2/ss:oled -- it will run on a µCPU as small as a ATTINY 85 !
