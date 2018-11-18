# c4embed
Embedded systems for RT instrumentation, IoT and experiment

Let us start introducing ourselves with main recepies of this project.

### Teensy 3.2
This is one of my favourite tiny board by Paul who has detail at http://www.pjrc.com . My choice for this over traditional Arduino board is due to compactness, and reasoable better  Cortext processor series. The pins are good to fit on adapter boards, and with resonable size project the whole size should knot go beyond size of a wallet. Please refer to their site for updates on series of this product and many more interesting stuff.


### Teensy Arduino adapter shield
In order to provide some room for additional module, shields are great as they adapt tiny board easily and follow stackable hardware architecture. I had to access only 4 pins - Vcc, GND, Tx and Rx which I could solder on 64 holes, but that would be undermining capability so I left to tag with long male pins. A better usage of this is 2.4 inches TFT touchable shield stacking. This architecture gives plenty room for other hardware module I may attach later on.

### 2.4" TFT Display shield
This shield is really great as it very inexpensive and suits for small area just good to display some instrumented data. The nice display library by MCUFRIEND is quite efficient to fill this display with information. Im ahoping that touch library will grow and offer more features for interaction. For now, displaying is good enough. 
