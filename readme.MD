# Tickertape Firmware File

This firmware is replacing the older verison for the Arduino IDE, by moving over to the more advanced PlatformIO framework basically because it has nicer interface for writing code, with the use of true CPP files and intellisense. But also for the advanced library management it provides, as this was causing people a lot of issues with the strictly Arduino IDE approach. 
To learn how to quickly get setup on PlatformIO I recommend this video by Andreas Spiess:
* https://www.youtube.com/watch?v=0poh_2rBq7E&t=924s

### Tickertape Retro Display
This repo is part a wider Tickertape Retro Display project that you can use to create your own Internet of Things LED display with that retro feel.

Check out the website, and my other project for the code library for Arduino and ESP32 for the rest of the project.

* http://tickertape.cc/
* https://github.com/darrendignam/LED_Display_Wrapper

By using PlatformIO the other dependency files are now going to be included for you - the correct versions, and my alternate forked versions of the dependencies where necessary.

# How the project works

Software:

The ArduinoIDE, PlatformIO, and Espressif-tools frameworks are leveraged to allow us to make a desktop retro looking display, and this firmware turns the display into a helpful clock.

This project is dependedn on the work of others:
  AdaFruit GFX and LedBackpack libraries
  WIFIMANAGER-ESP32 by zhouhan0126

Hardware:

In addition to the standard libraries the following Eagle libraries were also used:

    holtek-led-controller-v1
    
    Holtek Semiconductor Inc. Devices
    RAM Mapping 16*8 LED Controller Driver with keyscan
    SOP28, SOP24, SOP20
    www.holtek.com
    Created by S.Hofmann mc_sho@gmx.de
    
* http://eagle.autodesk.com/eagle/download/444

Various SparkFun libraries:
    
    SparkFun-Aesthetics
    SparkFun-Capacitors
    SparkFun-Connectors
    SparkFun-LED
    
* https://github.com/sparkfun/SparkFun-Eagle-Libraries
    
All of these are easy to find either in the library manager, or from the github pages for these projects. The sparkfun link has further great information for using Eagle and custom libraries installing them, everything. So I won't try and replicate that here!


# Hardware License Information
This library is released under the [Creative Commons ShareAlike 4.0 International license](https://creativecommons.org/licenses/by-sa/4.0/). You are welcome to use this library for commercial purposes. For attribution, we ask that when you begin to sell your device, you email us with a link to the product being sold. It would be great to see where this project goes, and will perhaps feature it on the website.

Together we can help the open-source hardware community continue to thrive and grow!

This project uses the 1206 LED footprint and some other helpful parts from the SparkFun projects listed above to help with the project. None of them were modified, they were used as-is.
