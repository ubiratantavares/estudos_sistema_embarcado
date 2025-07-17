# Curso ESP32


## Aula 01 - Apresentação

### Ementa

* Conhecendo o ESP32

* Instalação e configuração do VSCode

* DHT11

	- Introdução Teórica
	- Programando o ESP32

* $I^{2}C$

	- Fundamentos do $I^{2}C$
	- Biblioteca Wire
	- BH1750

* WiFi

	- Modos de Operação
	- Estados e Eventos

* MQTT

	- Introdução
	- Configuração de Broker e Cliente
	- Programação

* FreeRTOS

	- Introdução
	- Tarefas
	- Semáforos
	- Filas
	- Grupos de Eventos

### Materiais utilizados no curso

* ESP32

* Cabos Jumper

* Protoboard

* Resistores

* Push-Button

* Cabo USB-Micro

* DHT11

* BH1750

## Aula 02 - Conhecendo o ESP32

### Introdução

O ESP32 é uma série de SoC (System on Chip) de baixo custo, desenvolvido pela Espressif Systems para atender a demanda de dispositivos para aplicações de Internet das Coisas.

INSERIR IMAGEM "ESP32.png"

### Características do ESP32

* Processadores

	- Microprocessador Xtensa dual-core 32-bit LX6 (clock ajustável de 80 MHz até 240 MHz)
	- Co-processador Ultralow power (ULP)

* Memória

	- 520 KiB SRAM
	4 MB Flash

* Conectividade Wireless

	- Wi-Fi 802.11 b/g/n
	- Bluetooth v4.2 BR/EDR e BLE

* Segurança

	- IEEE 802.11 standard security features all supported, including WFA, WPA/WPA2 and WAPI
	- Secure boot
	- Flash encryption
	- 1024-bit OTP, up to 768-bit for customers
	- Cryptographic hardware acceleration: AES, SHA-2, RSA, elliptic curve cryptography (ECC), random number generator (RNG)

* Interfaces Periféricas

	- Até 18 canais ADC de 12 bits
	- 2 canais DAC de 8 bits
	- 16 canais PWM
	- 2 canais $I^{2}C$
	- 2 canais $I^{2}S$
	- 3 canais UART
	- 4 canais SPI (Serial Peripheral Interface)
	- 10 GPIOs com sensor de toque capacitivo

INSERIR IMAGEM "ESP32_PINOS.png"



### Conclusão


