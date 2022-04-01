# ESP-pwm-8ch
 
ESP32 based board with 8x PWM output channels.

This board is designed to be driven by an Olimex ESP32-POE or ESP32-POE-ISO module running Tasmota. To have access to more than 5 PWM channels the minimum Tasmota version required is 11.0.0. If you want to use the ethernet interface you will need to compile your own binaries enabling the corresponding features.

The design considers that the board will be mounted on a PCB DIN rail holder. The dimensions consider the holders offered by the Brazilian manufacturer Metaltex, check [here](https://www.metaltex.com.br/produtos/componentes/suportes/sp7-suporte-para-montagem-de-placa-de-circuito-impresso-em-trilho-din) for details.

![alt text](https://github.com/thermseekr/ESP-pwm-8ch/blob/main/V1/ESP-pwm_8ch-V1.png "ESP-pwm-8ch")
