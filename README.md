# STM32F446_Nucleo-64
STM32CubeMX &amp; STM32Workbench Projects

   Application uses PWM Mode of General Timer Output Compare to control the voltage from 0 to 100 (0V -> 3.3V) of Duty cycle
   and then from 100 back to 0 (3.3V -> 0V) on 2 GPIO Pins: PA_0 and PA_1 of STM32F446RET6 Nucleo-64 board.
   PWM Mode is used to obtain a glowing effect of LED lights connected to pins.
   These 2 LEDs glow 1 after the other. Every time any of them is off, on-board LED is Toggled.
   Program also outputs frequencies of SYSCLK, HCLK, PCLK1 and PCLK2 on the display connected through UART2 GPIO_PIN_2 (I used Tera Term VT)
   
   Using STM32 Workbech (Eclipse)
