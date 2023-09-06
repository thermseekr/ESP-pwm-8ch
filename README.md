# ESP-PWM-8CH
 
ESP8266/ESP32 based board with 8x PWM output channels.

This board is designed to be driven by an Olimex ESP32-POE, ESP32-POE-ISO or Wemos D1 Mini modules. When using the Wemos D1 Mini the maximum number of outputs is 4, and expect some flickering and frequency oscillation due to the software implementation of the PWMs.

The design considers that the board will be mounted on a PCB DIN rail holder. The dimensions consider the holders offered by the Brazilian manufacturer Metaltex, check [here](https://www.metaltex.com.br/produtos/componentes/suportes/sp7-suporte-para-montagem-de-placa-de-circuito-impresso-em-trilho-din) for details.

![alt text](https://github.com/thermseekr/esp-pwm-8ch/blob/main/V1/esp-pwm-8ch-v1.png "ESP-PWM-8CH")
