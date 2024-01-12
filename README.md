# Scary-RF Tool

## Descrição
O Scary-RF Tool é um projeto raiz de Arduino, usando um ESP32, um módulo CC1101 e alguns componentes para criar uma ferramenta versátil de comunicação por rádio (RF). Com ela, você pode capturar e reproduzir sinais RF (o famoso Replay Attack) nas frequências de 315MHz ou 433.92MHz, enviar um código aleatório em 315-433Mhz e analisar qual frequêcia esta recebendo 300-928Mhz. Ainda vou adicionar mais funções usando os 4 botões de navegação, criando um menu com mais possibilidades usando radiofrequência. (O plano é esse, projeto tá em pré-alpha, né!)

## Hardware Usado
- **ESP32:** O mais brabo.
- **Módulo CC1101:** O rei da comunicação RF. (ele e um transceiver então recebe e envia no mesmo módulo, sem contar que pega uma faixa grande de SubGhz).
- **Switches:** Um pra ligar e outro pra escolher a frequência.
- **Botões de Pressão:** Pro futuro menu.
- **Bateria:** 1300mAh, arrancada de um pod. (MrFreeze 2200Puffs).
- **Placa Reguladora de Carga:** Também veio do pod. (Elfbar TE6000, a placa dele é muito boa).
- **Placa de Cobre:** Feita na forma old school, usando estampagem e corroída no percloreto de ferro.
- **Tela OLED:** 128x32.

## Recursos Principais
- Pegar sinais RF com o módulo CC1101.
- Mostrar dados em um display OLED.
- Mandar de volta sinais RF na mesma frequência ou em outra.
- Futuras funções com os 4 botões.
- Analisar frequência do sinal (300-928Mhz).
- Enviar um sinal aleatório (315-433Mhz).

<img src="Placa.jpg" alt="Placa" width="300"><img src="Placa1.jpg" alt="Placa1" width="338">

