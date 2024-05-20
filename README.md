# Gas-Raspberry-MQ-6
Sensor de gás MQ-6 com Raspberry PI 3 B+

Este projeto foi referente a um sistema detector de gás GLP utilizando uma placa Raspberry PI 3+, com alarmes sonoro e visual com uma válvula para interromper o fluxo de gás e envio de mensagem automática em caso de detecção de vazamento, através do aplicativo IFTTT.

Foram utilizados os seguintes componentes para a montagem do projeto:
•	Raspberry PI 3 B+ - 1 unidade;
•	Fonte 5V/1A – 1unidade
•	Monitor para computador – 1 unidade;
•	Teclado de computador padrão ABNT – 1 unidade;
•	Mouse óptico para computador – 1 unidade;
•	Protoboard – 1 unidade;
•	Sensor MQ-6 – 1 unidade;
•	Buzzer ativo – 1 unidade;
•	Pushbutton – 1 unidade;
•	LED vermelho – 1 unidade;
•	LED verde – 1 unidade;
•	Resistor 300 Ohms – 2 unidades;
•	Solenóide 5V 3 vias – 1 unidade;
•	Modulo Relé v2.2 – 1 unidade;

O diagrama ilustra a conexão dos componentes utilizado no protótipo com a Raspberry PI 3 B+. O pino 6 (GND) da placa foi ligado na protoboard para aterramento dos componentes do circuito, o pino 2 (5V power) foi ligado na protoboard para alimentação dos componentes, o LED vermelho foi ligado no pino 37 (GPIO 26), o LED verde foi ligado no pino 16 (GPIO 23) o sensor MQ-6 foi ligado no pino 8 (GPIO 14), a válvula solenóide foi ligada no pino 40 (GPIO 21), o pushbutton foi ligado no pino 38 (GPIO 20) e o buzzer ativo foi ligado no pino 36 (GPIO 16).
