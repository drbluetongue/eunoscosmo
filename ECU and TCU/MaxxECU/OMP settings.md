The stock OMP operates in the same way as the S5 RX7. it is a 6 wire unidirectional stepper motor with a position sensor.

You can wire in the stock OMP into the MaxxECU by wiring the 4 stepper motor outputs from the stock ECU - pins 4I, 4J, 4K, 4L - into any spare ground outputs of the Maxx.

Then, wire into a spare Analog Voltage (AIN) pin 3A from the position sensor. This position sensor also recieves 5V from the 5V output of the ECU (shared with sensor output). 

Then, configure as below:

![MOP1](https://github.com/drbluetongue/eunoscosmo/assets/12694883/a084659a-a806-46f2-af51-6811e02eb119)

![MOP2](https://github.com/drbluetongue/eunoscosmo/assets/12694883/bd96d241-ed8c-44c9-90fc-d6368cd0558c)

![MOP3](https://github.com/drbluetongue/eunoscosmo/assets/12694883/fd117381-6458-4d7f-a4df-0b390b9f6fcd)


