# Hearbeat On
O projeto tem como principal objetivo o monitoramento cardíaco através de um pequeno sensor conectado à internet. Este sensor pode atuar de diversas maneiras, em casos hospitalares, por exemplo, os dados são enviados diretamente para uma plataforma online, e isso permite que médicos que estejam de plantão não necessariamente precisem ir até a sala do paciente ser verificado o estado do paciente, já que os dados captados são disponibilizados em uma plataforma online. A solução também permite um rastreamento de dados, isso faz com que possa haver uma revisão dos dados captados da pessoa de uma maneira rápida e fácil.
## Componentes Usados
- **NodeMCU:** O módulo Wifi ESP8266 NodeMCU é uma placa de desenvolvimento que combina o chip ESP8266, uma interface usb-serial e um regulador de tensão 3.3V.
[NodeMCU (ESP82266)](https://www.filipeflop.com/produto/modulo-wifi-esp8266-nodemcu-esp-12/)
- **Sensor de Frequência Cardíaco:** O sensor de pulso monitor cardíaco efetua a leitura das batidas do coração usando um sensor óptico amplificado, e envia esses dados para o microcontrolador como o Arduino através de um único pino de sinal.
[Sensor de Frequência Cardíaca](https://www.filipeflop.com/produto/sensor-de-frequencia-cardiaca/)
- **Buzzer (campainha):** buzzer ativo que possui um oscilador interno e emite um som contínuo quando alimentado com 3V.
[Buzzer](https://www.baudaeletronica.com.br/buzzer-3v.html)

## Bibliotecas Utilizadas
- **PubSubClient:** Biblioteca que permite a comunicação através do protocolo MQTT.
[PubSubClient](https://github.com/knolleary/pubsubclient)
- **PulseSensorPlayground:** Biblioteca que trás as funções para utilização do Sensor Cardíaco.
[PulseSensorPlayground](https://github.com/WorldFamousElectronics/PulseSensorPlayground)
- **ESP8266Wifi:** Biblioteca utilizada para poder conectar a placa de desenvolvimento (NodeMCU) à rede wifi.
[ESP8266Wifi](https://github.com/esp8266/Arduino)

## Interface de Desenvolvimento
Para o desenvolvimento do projeto foi utilizada a ferramenta **Arduino IDE**, que é uma interface de desenvolvimento que permite a programação e escrita de código de maneira fácil em placas como Arduino e NodeMCU. [Arduino IDE](https://www.arduino.cc/en/main/software)
