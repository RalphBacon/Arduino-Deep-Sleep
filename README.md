# Arduino Deep Sleep & Bare Bones Arduino
How to put your Arduino to sleep to save power (and wake up again)

# See the accompanying videos #115 & #116 at https://www.youtube.com/ralphbacon  
(Direct link to part 1 video: https://youtu.be/jqFl8ydUzZM)  
(Direct link to part 2 video: https://youtu.be/8fiYvnBDsDE)

There are two ways to put your Arduino ATMEGA328P (UNO or Nano, for example) to sleep - or more accurately, two ways to wake it up after it has been put to sleep in order to save (battery) power.

So we have TWO sketches here: one to wake up using a switch (which triggers an INTERRUPT), and another to wake up every few seconds (8 seconds max) using an inbuilt TIMER.

They are very similar and I suggest you start with the interrupt driven one first (using two switches) as it's easier to get your head round what's actually going on!

It's all very well saving power by putting your ATMEGA328P board to sleep, but what are we going to do about the supporting circuitry? We cover that in part two by putting together a bare-bones Arduino using a handful of components. Easy to do and cheap.

# Kickstarter campaign (not mine)  
Also, have a look at Thijs Ruiter's Kickstarter campaign - if he reaches his goal I'll do a proper review of his sound module:  
http://kck.st/2M2KeRr

---

The 18650 Battery Charge Shield:  
https://www.aliexpress.com/item/ESP32-ESP32S-For-Wemos-For-Raspberry-Pi-18650-Battery-Charge-Shield-Board-V3-Micro-USB-Port/32870411748.html

The official ATmega28P data sheet:  
http://ww1.microchip.com/downloads/en/DeviceDoc/ATmega328_P%20AVR%20MCU%20with%20picoPower%20Technology%20Data%20Sheet%2040001984A.pdf

The FP6298 PWM converter datasheet:  
http://www.feeling-tech.com.tw/km-master/ezcatfiles/cust/img/img/24/fp6298v063.pdf

Arduino pin mapping (GPIO numbers vs Chip numbers):  
https://www.arduino.cc/en/Hacking/PinMapping168


If you like this video please give it a thumbs up, share it and if you're not already subscribed please consider doing so :)

My channel and blog are here:  
------------------------------------------------------------------  
https://www.youtube.com/RalphBacon  
https://ralphbacon.blog  
------------------------------------------------------------------  
