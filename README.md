# nv5600-6-speed-display
PCB and oled display to show what gear postition for a NV5600 dodge ram diesel manual transmission.
1 x Display Waveshare 1.28inch round display https://www.amazon.com/Waveshare-1-28inch-LCD-Module-Resolution/dp/B08V5538C6
  I suggest this one, because the cheaper ones require more coding changes that can be frustrating. With this and the onboard GC9A01 driver, theirs more documentation and easir to understand the wiring.
    Display to arduino connections
D13 = SCK
D11 = MOSI
D10 = CS
D9 = DC
D8 = RST
BL = VCC (or D6 PWM if you want dimming)

8 x 10k resisters - pullup
8 x ah3503 hall effect sensors 
Arduino Nano 
magnets


