# EDGE-CP

Repositório com os checkpoints desenvolvidos para a disciplina de Edge Computing and Computer Systems da FIAP.

## 🔧 Visão Geral do Projeto

Este projeto propõe um sistema de monitoramento ambiental utilizando Arduino, com o objetivo de preservar a qualidade do ambiente para armazenar vinhos. Através de sensores de luminosidade, temperatura e umidade, o sistema indica o estado do ambiente (OK, ALERTA ou PERIGO) por meio de LEDs, sons e exibição em um display LCD.

O comportamento do sistema varia de acordo com as medições, acionando dispositivos visuais e sonoros conforme os parâmetros ambientais. 

## 🧠 Lógica de Funcionamento

### ✅ Estado OK
- Luminosidade: abaixo de 33
- Temperatura: entre 10 °C e 18 °C
- Umidade: entre 60% e 70%
- Ações:
  - LED verde aceso
  - LCD exibe os valores com indicação de ambiente ideal

### ⚠️ Estado de Alerta
- Luminosidade: entre 33 e 66
- Temperatura: entre 8 °C e 10 °C ou entre 18 °C e 20 °C
- Umidade: entre 50% e 60% ou entre 70% e 75%
- Ações:
  - LED amarelo aceso
  - Piezo toca por 3 segundos. Se o problema persistir, repete o som.
  - LCD destaca os valores fora do ideal

### 🚨 Estado de Perigo
- Luminosidade: acima de 66
- Temperatura: abaixo de 8 °C ou acima de 20 °C
- Umidade: abaixo de 50% ou acima de 75%
- Ações:
  - LED vermelho aceso
  - Piezo toca continuamente enquanto houver condição de risco
  - LCD alerta com valores em vermelho ou destaque
 
## 🔬 Simulações e Demonstrações
> [🔗 Simulação no Tinkercad (Parte 1)](https://www.tinkercad.com/things/j51QYpTMhE4-cp-1-edge?sharecode=ClycW8TVkj-h1uDvxYE7v8UwEznIFJERs4fF8bX5_ok)
>
> [🎥 Vídeo explicativo (Parte 1)](https://www.youtube.com/watch?v=CTHkOQF_GoQ)
>
> [🔗 Simulação no Wokwi (Partes 1 e 2)](https://wokwi.com/projects/430521461111936001)
>
> [🎥 Vídeo explicativo (Partes 1 e 2)](https://www.youtube.com/watch?v=D1xrjWwjxWU)

## 🧰 Componentes Utilizados

| Componente  | Quantidade |
| ------------- | ------------- |
| Arduino Uno R3  | 1  |
| LED Vermelho  | 1  |
| LED Amarelo  | 1  |
| LED Verde  | 1  |
| Resistor 220 Ω  | 4 |
| Resistor 4,7 kΩ  | 1 |
| Fotorresistor  | 1  |
| Piezo  | 1  |
| DHT11 ou DHT22  | 1  |
| LCD 16x02 (I2C)  | 1  |
| Jumpers  | 39  |

## 💻 Bibliotecas Necessárias

Para compilar e executar corretamente o projeto, é necessário instalar:
- [DHT sensor library](https://github.com/adafruit/DHT-sensor-library) – Para leitura de temperatura e umidade.
- [LiquidCrystal_I2C](https://github.com/johnrickman/LiquidCrystal_I2C) – Para controle do LCD via interface I2C.

## 🛠️ Tecnologias

![Arduino](https://img.shields.io/badge/-Arduino-00979D?style=for-the-badge&logo=Arduino&logoColor=white)
![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)

# 👥 Integrantes do Grupo  

| [<img loading="lazy" src="https://github.com/DaviMunhoz1005.png" width=115><br><sub>Davi Marques</sub>](https://github.com/DaviMunhoz1005) |  [<img loading="lazy" src="https://github.com/Gabsgc01.png" width=115><br><sub>Gabriel Ciriaco</sub>](https://github.com/Gabsgc01) | [<img loading="lazy" src="https://github.com/Mafraaa.png" width=115><br><sub>Vinicius Mafra</sub>](https://github.com/Mafraaa) | [<img loading="lazy" src="https://github.com/MariFranca.png" width=115><br><sub>Mariana Franca</sub>](https://github.com/MariFranca) | 
| :---: | :---: | :---: | :---: |
