# IoT-Projects

A place to keep track of my projects utilizing Raspberry Pi, Jetson Nano, etc.

## Pi-Projects

#### Pi Zero W + PiTFT:
1. Pi-Hole Ad-Blocker
  - Stats.py - PiTFT script from AdaFruit ([found here](https://learn.adafruit.com/pi-hole-ad-blocker-with-pi-zero-w/install-mini-pitft "Pi-Hole Ad-Blocker: Install Mini PiTFT")), adjusted to my liking
    - changed `HOST` to display "Pi-Hole", moved to first line
    - changed font colors
    - removed `IP` & `DNS Queries` from screen2
    - added `CPU Temp` to screen2
    - changed `Mem:` to `Memory:` and moved values to new line to fix off screen text
    - set backlight off, screen black when no buttons are pressed
    - set top button to display screen1, bottom button to display screen2
    - calculations don't run until a button is pressed
  - Unbound Recursive DNS Resolver


## Jetson-Projects


#### Jetson Nano + Waveshare IMX219-160IR Camera
1. DLInano
