Library only works for Arduino Uno and others based on the ATmega328.
The pins are hard coded into the library for better performance, only port D and the SPI Pins are used.

**LAT** / **STB** / **LT**<tab> --</tab> Digital Pin **2**<br>
**OE** / **EN**<tab> ---------</tab> Digital Pin **3**<br>
**LA** / **A**<tab> -----------</tab> Digital Pin **4**<br>
**LB** / **B**<tab> -----------</tab> Digital Pin **5**<br>
**LC** / **C**<tab> -----------</tab> Digital Pin **6**<br>
**LD** / **D**<tab> -----------</tab> Digital Pin **7**<br>
**R1** / **R1**<tab> -----------</tab> Digital Pin **11**<br>
**CLK** / **SK**<tab> ---------</tab> Digital Pin **13**<br>
  
  
The library increases the Timer2 frequency so that the PWM runs on 32 kHz.
Affected are only the pins 3 and 11, both occupied by the interface.  <br>
Χρησιμοποιούμε Timer2 έτσι ώστε το PWM να λειτουργεί στα 32 kHz. Timer2 οι ακίδες 3 και 11.
