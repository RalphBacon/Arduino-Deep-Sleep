# Arduino Deep Sleep & Bare Bones Arduino
How to put your Arduino to sleep to save power (and wake up again)

# See the accompanying videos #115 & #116 at https://www.youtube.com/ralphbacon  
(Direct link to part 1 video: https://youtu.be/jqFl8ydUzZM)  
(Direct link to part 2 video: https://youtu.be/8fiYvnBDsDE)

There are two ways to put your Arduino ATMEGA328P (UNO or Nano, for example) to sleep - or more accurately, two ways to wake it up after it has been put to sleep in order to save (battery) power.

So we have TWO sketches here: one to wake up using a switch (which triggers an INTERRUPT), and another to wake up every few seconds (8 seconds max) using an inbuilt TIMER.

They are very similar and I suggest you start with the interrupt driven one first (using two switches) as it's easier to get your head round what's actually going on!

It's all very well saving power by putting your ATMEGA328P board to sleep, but what are we going to do about the supporting circuitry? We cover that in part two by putting together a bare-bones Arduino using a handful of components. Easy to do and cheap.
