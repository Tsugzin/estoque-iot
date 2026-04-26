# estoque-iot
Sistema de monitoramento de estoque em tempo real com ESP32 e MQTT
Este projeto propõe a implementação de um sistema IoT para monitoramento
contínuo de estoque em estabelecimentos comerciais (restaurantes, mini mercados, almoxarifados).
Células de carga conectadas a microcontroladores ESP32 capturam o peso dos produtos em tempo
real, transmitindo os dados via protocolo MQTT para um servidor local. Um dashboard web exibe o
estado atual do estoque e dispara alertas automáticos quando itens atingem o nível mínimo
configurado.
