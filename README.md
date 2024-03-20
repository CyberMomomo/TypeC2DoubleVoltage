# TypeC2DoubleVoltage
>
> ## Introduction
>
> This device is used for converting voltage from 5V input by USB Type-C Plug to any positive and negetive voltages from 1.25V to 30V.

> ## How to use
>
> Use the gerber files and bom from releases you could get a demo board which can produce +12V 40mA and -12V 40mA output. By changing R7, R8, R11, R14 you could get any other voltages you want. But you should use proper capacitors when you use the device to get other voltages in order to avoid the overvoltage. And any sigle volatge output should not load over 500mW or the output ripple will surge and the MC34063 may overheat.

> ## Performance
>
> For the demo board, the output ripple is lower than 1mVpp in unloaded test, and it is lower than 2mVpp when loading a 40mA output.

> ## Images
>
> ![image](images/DSC09725.jpg)
> ![image](images/DSC09719.jpg)
> ![image](images/DSC09720.jpg)
> ![image](images/DSC09727.jpg)
