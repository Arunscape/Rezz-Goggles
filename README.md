# [WIP] An attempt at making my own pair of Rezz Goggles
###### Why? For fun.

###### For now, the readme will be documenting my progress

## Materials list:
###### These are the parts I have on hand and what I think I will use
- 8x [SK6812RGBW LEDs](https://www.adafruit.com/product/2761) (I have 10 just in case)
- 2x [24 LED rings](https://www.adafruit.com/product/2862)
- 2x [16 LED rings](https://www.adafruit.com/product/2862)
- [adafruit trinket m0](https://www.adafruit.com/product/3500) or [gemma m0](https://www.adafruit.com/product/3501) or feather [huzzah](https://www.adafruit.com/product/3046)
  - For now, I will be using the gemma

## Datasheets
- https://cdn-shop.adafruit.com/datasheets/WS2812.pdf
- https://cdn-shop.adafruit.com/product-files/1138/SK6812+LED+datasheet+.pdf
- https://cdn-shop.adafruit.com/product-files/2757/p2757_SK6812RGBW_REV01.pdf

## Documentation
- FastLED Library https://github.com/FastLED/FastLED/wiki/Overview

# Current challenges:
- I have a friend willing to help design the surface mount PCB for the LEDs in the centre
- Powering the LEDs
  - [adafruit guide](https://learn.adafruit.com/adafruit-neopixel-uberguide/powering-neopixels)
  - ~~I'm leaning towards using 4x AA NiMH batteries or 3x AA Alkalines~~
  - ~~using NiMH will have an upfront cost of like $50. Alternatively,~~
  I can just use some Alkaline AAs and just get a battery holder + JST connectors
  - ~~I'll buy a 1000uF capacitor. There's one on digikey with a rating for 10V~~
  - Looks like 3x AA batteries are the way to go. no capacitor needed
  - this looks like a cool battery holder https://www.adafruit.com/product/3287
- 3D printing the glasses frame
  - Probably search for a .stl somewhere
  - figure out which CAD software to use - ask fren for help
  - prototype from that .stl -> need to figure out how to fit over prescription glasses

## Random notes:
- Use a 300-500 ohm resistor to data in of the first neopixel

## Random thoughts
- The feather huzzah would be interesting, since I theoretically could control the system with my phone, but that would result in a huge hit to battery life. I'll stick to using the gemma for now
- I need to find an appropriate battery to use plus the JST connector
- The internet suggests that the [fastLED](http://fastled.io/) library is much better than adafruit's [neopixel library](https://github.com/adafruit/Adafruit_NeoPixel)
- it would be cool if I could get my hands on a microphone to see if I can make an effect that reacts to surrounding frequencies. That would be tacked when I'm nearly finished the project
- maybe I want a multimeter


## Reference images

![](http://trc.daily-beat.com/wp-content/uploads/sites/2/2016/12/hs16a_0251-copy.jpg)

![](https://pbs.twimg.com/media/DZZvvgZUMAAbX_y.jpg)
