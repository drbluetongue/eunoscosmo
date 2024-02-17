**Wiring in a piggyback ECU to work with the automatic gearbox**

Wiring in a patch harness to an aftermarket ECU (such as a Link, Haltech, MaxxECU, Microtech) is fairly simple. 

You will need to run both the stock ECU, and the stock TCU. Currently I am working on emulating the remaining stock ECU pins in order to remove it, and run it with just the TCU. 

**For 13B cars, unless your new ECU supports S5 RX7 confirmation mode ignitors (like Adaptronic) you will need to convert your ignitor to be direct trailing fire - see the Using FD ignitor pinout file in this directory**

The stock ECU requires the following to be remain pinned at a bare minimum (or shared with stock ECU and aftermarket ECU) to keep it from throwing limp mode. If in doubt, leave everything still going to stock ECU except stuff you want to run on your other ECU e.g. injector, ignition, CAS, coolant & IAT etc. The stock ECU will happily work without these connected - for example if it has no coolant temp connected it defaults to 80c.

Torque down 

Torque down confirmation signal

TPS wide range

TPS narrow range

Turbo and Emissions solenoids, 20b airpump relay (if you are running stock turbos or emissions otherwise not needed)

Brake switchs

12v

Grounds

For A/C, you can wire pin 1O (Gry/Blue) into your aftermarket ECU to act as a A/C on switch. Then, use a spare ignition output on your aftermarket ECU to send a 5v signal on Pin 1L (Gry/Red) based on load - 5v for compressor on, 0v for WOT or high load/RPM.
