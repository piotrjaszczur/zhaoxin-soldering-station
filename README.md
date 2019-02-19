# zhaoxin-soldering-station
Project for microcontrollers course at AGH. Soldering station control unit for the Zhaoxin 936 soldering iron


The schematic and the board created for the project for the microcontrollers course at AGH. 
It was based around the "Blue Pill" STM32 Development Board with STM32f103c8t6 MCU. It provided the temperature reading based on the ADC measuring of the voltage on the soldering iron termistor. IRF4905 PMOS transistor was driven by the PWM signal with the duty cycle depending on the current temperature reading. The rotary encoder allowed to change the desired temperature and the 4 microswitches allowed to choose one of the preset 4 different temperatures.

It is planned to be used with a 24V switching power supply.

![stacja schem](https://user-images.githubusercontent.com/47760713/53008008-b4f0be80-3438-11e9-8bb2-147e5deb2065.png)

![stacja board](https://user-images.githubusercontent.com/47760713/53008007-b4582800-3438-11e9-8ad9-ceec06772020.png)
