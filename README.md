Infinity Solar Jar (Gerber Files)

Thank you for taking the time and interest in this little project.  The Infinity Solar Jar is a circuit for solar sun jar's that uses a solar cell to charge up a supercapacitor instead of a battery to produce light at night.

The circuit takes incoming power from the solar cell, voltage limited by a zener diode in parallel to the solar cell, passes through a schottky blocking diode, and charges the supercapacitor.  The NCP1402 chip is a DC boost converter that takes the lower voltage of the supercapacitor and boosts it up to 3.3vdc to illuminate a white LED.  The NCP1402 is biased off by using the solar cell as a light detector triggering the mosfet attached to the enable pin of the boost chip.  The NCP1402 chip will start operating around 0.9vdc, and once activated will run down to about 0.250vdc before failing to operate.  The 200 ohm resistor in parellel with the LED gives about 24 hours run time on a fully charged 350F supercapacitor.  If you want more light and reduced operational time, try a 150 or 100 OHM resistor instead of the 200 Ohm.

Files included in this repository:

README.md - This file your reading
schematic.jpg - Schematic in pictorial form for reference
Infinity Sun Jar V2.zip - Gerber files

If you would like to order a few of these boards to play with, just upload the Infinity Sun Jar V2.zip file to oshpark.com and order the boards in multiples of 3.  Be advised as most of this circuit is surface mounted components, the only through hole components are the supercapacitor and the LED.

This is my 2nd Open Source Hardware Circuit.  It is free for anyone to use, just please give credit to myself for the circuit and send them here as reference or my youtube page for videos detailing the development of this circuit at www.youtube.com/njsharkracer.   If you feel inclined to give thanks to me, please throw me a few $$ with the button below. All $ is used for my own prototyping of these circuits and every bit helps and is always appreciated!

[![Pledgie](http://www.pledgie.com/campaigns/22214.png)][pledgie]
[pledgie]: http://www.pledgie.com/campaigns/22214

Also follow my other electronics projects on my YouTube channel:  www.youtube.com/njsharkracer
