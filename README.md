# expressDAC

W. I. P.

Proof of concept for a ExpressCard DAC

Using a TI part that does all the hard work (USB bridge, DAC) just to prove feasibility. It should be USB AUdio class and need no driver whatsoever

Had to change the amplifier chip twice because of the shortage and it's pretty much the least interesting part. The LM4917 is very underwhelming compared to recent TI integrated, 3V3 headphone amplifier

The PCM datasheet is very short and power supply rules are not clear. That's why there so many solder bridge. This is pretty much a dk at this point...

Also had to go with awkward footprints for the LDO and EEPROM because it's 2021

The main goal is to go noise free even with sensitive IEM. Might one day go for a proper DAC + USB bridge
