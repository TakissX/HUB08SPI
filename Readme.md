Library only works for Arduino Uno and others based on the ATmega328.
The pins are hard coded into the library for better performance, only port D and the SPI Pins are used.

  - LAT / STB / LT  -> Digital Pin 2<br>  
  OE / EN         -> Digital Pin 3<br>  
  LA / A          -> Digital Pin 4<br>  
  LB / B          -> Digital Pin 5<br>  
  LC / C          -> Digital Pin 6<br>  
  LD / D          -> Digital Pin 7<br>  
  R1 / R1         -> Digital Pin 11<br>  
  CLK / SK        -> Digital Pin 13<br>
  
The library increases the Timer2 frequency so that the PWM runs on 32 kHz.
Affected are only the pins 3 and 11, both occupied by the interface.
