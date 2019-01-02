# An attempt at making my own pair of Rezz Goggles
###### Why? For fun.

###### For now, the readme will be documenting my progress

## Materials list:
###### These are the parts I have on hand and what I think I will use
- 8x [SK6812RGBW LEDs](https://www.adafruit.com/product/2761) (I have 10 just in case)
- 2x [24 LED rings](https://www.adafruit.com/product/2862)
- 2x [16 LED rings](https://www.adafruit.com/product/2862)
- [adafruit trinket m0](https://www.adafruit.com/product/3500) or [gemma m0](https://www.adafruit.com/product/3501) or feather [huzzah](https://www.adafruit.com/product/3046)

## Datasheets
- https://cdn-shop.adafruit.com/datasheets/WS2812.pdf
- https://cdn-shop.adafruit.com/product-files/1138/SK6812+LED+datasheet+.pdf
- https://cdn-shop.adafruit.com/product-files/2757/p2757_SK6812RGBW_REV01.pdf

## Documentation
- FastLED Library https://github.com/FastLED/FastLED/wiki/Overview

# Current challenges:
- Choose a board to work with. Shouldn't be too hard to switch later, but may be annoying to switch
- The 8 individual LEDs have to be surface mounted I think, which means I probably have to design a pcb to be in the shape that I want. This would also involve figuring out the proper spacing for the LEDs since it's not already arranged nicely like in the rings
-figure out how to power the LEDs
  - [adafruit guide](https://learn.adafruit.com/adafruit-neopixel-uberguide/powering-neopixels)
  - it seems that the board alone won't be able to power the LEDs properly.
  - probably use a 3.7v li-on battery source
  - I might have to buy a capacitor. I might have enough to wire in parallel, but for the final product it shouldn't be that janky
- 3D printing the glasses frame
  - I'm not even sure where to start with this one
  - Probably search for a .stl somewhere
  - figure out which CAD software to use
  - prototype from that .stl -> need to figure out how to fit over prescription glasses

## Random thoughts
- I'm leaning towards using the Gemma m0 because it already has a JST connector, plus it has a built in on/off switch
- The feather huzzah would be interesting, since I theoretically could control the system with my phone, but that would result in a huge hit to battery life
- I need to find an appropriate battery to use plus the JST connector
- The internet suggests that the [fastLED](http://fastled.io/) library is much better than adafruit's [neopixel library](https://github.com/adafruit/Adafruit_NeoPixel)
- it would be cool if I could get my hands on a microphone to see if I can make an effect that reacts to surrounding frequencies
- maybe I want a multimeter


## Reference images

![](http://trc.daily-beat.com/wp-content/uploads/sites/2/2016/12/hs16a_0251-copy.jpg)

![this one is grey](https://instagram.fyyc3-1.fna.fbcdn.net/vp/f72a607e5014e38cee4a2fc6f5081b17/5CCE0949/t51.2885-15/e35/40803216_2236401669962017_6292816001394278400_n.jpg?_nc_ht=instagram.fyyc3-1.fna.fbcdn.net)
