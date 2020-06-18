# M031BSP_ADC_IRQ
 M031BSP_ADC_IRQ

update @ 2020/06/18

1. refer Nuvoton sample code , with TestOScope , to monitor ADC value

http://forum.nuvoton.com/viewtopic.php?f=19&t=8564&sid=ed1dc76ec8ff773ccb5820642e5a7f2e

2. 16 bit ADC result , separate to low byte and high byte , transmit by UART0 , refer define : USE_TestOScope

3. below is TestOScope capture screen 

![image](https://github.com/released/M031BSP_ADC_IRQ/blob/master/TestOScope.jpg)


update @ 2020/03/10

Add ADC (PA.0) with interrupt sample code for M031

- Use Modified Moving Average algorithm to calculate smooth ADC data
