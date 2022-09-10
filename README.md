# Stm32F469 Evaluation Board Example Projects

Projects :

- LEDs_GPIO: Initialize LEDs and blink them using defaults HAL functions

- Push_Button: Initialize the on-board push button, get it state and blink the LEDs using defaults HAL functions

- ADC_Potentiometer: Initialize the on-board Potentiometer, get its value, for debugging use ST-link Trace 

- ADC_Continuous_Conversion: Initialize the ADC1 with Continuous Conversion settings, and get the values, for debugging use ST-link Trace 

- ADC_Timer_Trigger: Initialize the ADC1 and Timer2 to trigger the conversion, and get the values, for debugging use ST-link Trace 

- ADC_Multi_Channels: Initialize the ADC1 With 2 Channels , first channel is PA4 and the second for PC0, Enable the DMA circular Continuous request and Number of conversion, after that get the values for the DMA buffer, note use th on board jumper to switch between PA4 and PC0 since both are connected to the same Potentiometer.

- DAC_Output: Initialize the DAC, and output single voltage value

- DAC_Sine_Wave: Initialize the DAC Channel 2 , and outputing a Sine wave signal, with the help of DMA and Timer2

- UART_DMA: Setup USART1 in STM32CubeMX and use DMA to transmit any received messages

