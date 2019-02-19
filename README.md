# zhaoxin-soldering-station
Project for microcontrollers course at AGH. Soldering station control unit for the Zhaoxin 936 soldering iron


The schematic and the board created for the project for the microcontrollers course at AGH. 
It was based around the "Blue Pill" STM32 Development Board with STM32f103c8t6 MCU. It provided the temperature reading based on the ADC measuring of the voltage on the soldering iron termistor. IRF4905 PMOS transistor was driven by the PWM signal with the duty cycle depending on the current temperature reading. The rotary encoder allowed to change the desired temperature and the 4 microswitches allowed to choose one of the preset 4 different temperatures.
