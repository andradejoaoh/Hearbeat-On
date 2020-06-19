# Hearbeat On

## Componentes Usados:
- **NodeMCU:** O módulo Wifi ESP8266 NodeMCU é uma placa de desenvolvimento que combina o chip ESP8266, uma interface usb-serial e um regulador de tensão 3.3V.
[NodeMCU (ESP82266)](https://www.filipeflop.com/produto/modulo-wifi-esp8266-nodemcu-esp-12/)
- **Sensor de Frequência Cardíaco:** O sensor de pulso monitor cardíaco efetua a leitura das batidas do coração usando um sensor óptico amplificado, e envia esses dados para o microcontrolador como o Arduino através de um único pino de sinal.
[Sensor de Frequência Cardíaca](https://www.filipeflop.com/produto/sensor-de-frequencia-cardiaca/)
- **Buzzer (campainha):** buzzer ativo que possui um oscilador interno e emite um som contínuo quando alimentado com 3V.
[Buzzer](https://www.baudaeletronica.com.br/buzzer-3v.html)

## Bibliotecas Utilizadas:
- **PubSubClient:** Biblioteca que permite a comunicação através do protocólo MQTT.
[PubSubClient](https://github.com/knolleary/pubsubclient)
- **PulseSensorPlayground:** Biblioteca que trás as funções para utilização do Sensor Cardíaco.
[PulseSensorPlayground](https://github.com/WorldFamousElectronics/PulseSensorPlayground)
