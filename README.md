# ESP-pwm-8ch
 
ESP8266/ESP32 based board with 8x PWM output channels.

This board is designed to be driven by an Olimex ESP32-POE, ESP32-POE-ISO or Wemos D1 Mini modules running Tasmota.

When using the Olimex modules, you will need at least Tasmota V11.0.0 to have access to more than 5 PWM channels. And if you want to use the ethernet interface you will need to compile your own binaries enabling the corresponding features.

When using the Wemos D1 Mini the maximum number of outputs is 4, and expect some flickering and frequency oscillation due to the software implementation of the PWMs.

The design considers that the board will be mounted on a PCB DIN rail holder. The dimensions consider the holders offered by the Brazilian manufacturer Metaltex, check [here](https://www.metaltex.com.br/produtos/componentes/suportes/sp7-suporte-para-montagem-de-placa-de-circuito-impresso-em-trilho-din) for details.

![alt text](https://github.com/thermseekr/ESP-pwm-8ch/blob/main/V1/ESP-pwm_8ch-V1.png "ESP-pwm-8ch")
