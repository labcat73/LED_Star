# LED Star / Christmas Star

This is the recreation of a small SMD project that was published in the german
EAM "Electronic Actuell Magazin" some time in the 90ies.

It features a simple HEF4060 counter IC that drives 24 LEDs in a repeating pattern.

Everything has a microcontroller and firmware these days, so it was quite fun to go back
to something old-school that just works when powered up.

I built this project as a teenager as a christmas present for my dad and yes it was
working, but oh boy did the self-etched PCB look terrible.
You could also buy this thing as a kit from Conrad Electronic if i remember correctly and
it was using 24 red low-current 1mA leds in SOT-23 package.

I redrew the schematic and PCB with "DesignSpark PCB Explorer 11.0" and send it off to
JLCPCB for manufacturing. The Gerber_Files.zip contains the generated files that were
used to order working PCBs.

More information e.g. the BOM can be found in the 'doc' folder.

When assembling make sure to use the correct polarity for D1, C1 and all LEDs.
All diodes have the cathode marked on the silkscreen. C1 has the anode (+) marked. This
is where the brown stripe is on KEMET Tantalum capacitors. The SMD LEDs i got had a green
arrow at the bottom pointing to the cathode. On top the green end was the cathode. The
silkscreen has a small arrow marking the cathode. Always three LEDs from the center
outwards have the same orientation, make sure to assemble with correct orientation. If
you get it wrong the thing will still work, but your blink pattern might not be as nice
/ pseudo random as it could be. Try to get LEDs with <=20mA rating.

I used the cheapest 0805 SMD LEDs i could find on eBay. I populated:

4 x Blue, 4 x Red, 4 x White, 4 x Yellow, 4 x Green, 4 x Pink/Violet

You can be creative here. The thing seems to be pretty robust and forgiving in respect to
which LEDs to use knowing that the original design used 1mA LEDs. My build started
working around 3.6V. 5V via USB was just perfect, but i guess also higher voltages are
fine, as the outputs are current limited. Look at the rating of the HEF4060 for maximum
allowed voltage. If you replace R1 and D1 with a 0R resistor, it might even work with a
single 3V coin cell. I have not tried that myself though.

YouTube videos:

Happy New Year 2024! | #leds #electronics #shorts https://youtube.com/shorts/Sz0-PjsIPsk

Building the LED Christmas Star - LiveStream | Electronics https://www.youtube.com/watch?v=KstYk-73qtE&t=3s

Finishing the LED Christmas Star - Timelapse | Electronics https://www.youtube.com/watch?v=y3fU2dq_Xd4


Hope this brings you some joy!

Tobias - @labcat73
