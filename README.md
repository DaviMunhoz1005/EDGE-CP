# EDGE-CP

Checkpoints para a disciplina de Edge Computing and Computer Systems FIAP.

## Esquemática e Montagem

A montagem completa do circuito pode ser visualizada e testada diretamente na simulação do Tinkercad.  
> [Simulação no Tinkercad (Apenas a parte 1 do projeto).](https://www.tinkercad.com/things/j51QYpTMhE4-cp-1-edge?sharecode=ClycW8TVkj-h1uDvxYE7v8UwEznIFJERs4fF8bX5_ok)
>
> [Vídeo rápido explicativo (Apenas a parte 1 do projeto).](https://www.youtube.com/watch?v=CTHkOQF_GoQ)
>  
> [Simulação no Wokwi (Parte 1 e Parte 2).](https://wokwi.com/projects/429966884149495809)
> 


## Sobre o Projeto

Nós elaboramos um sistema utilizando Arduino que tem como propósito capturar as informações de luminosidade, temperatura e umidade do sistema, com o intuito de auxiliar a manter o ambiente com um estado adequado para a preservação de vinhos. 

O sistema funciona da seguinte forma:

- OK (Led Verde):
  - Luminosidade abaixo de 33 (ambiente escuro/baixa iluminação)
  - Temperatura entre 10 °C e 18°C
  - Umidade entre 60% e 70%
  - O LCD mostra os valores em OK
- ALERTA (Led Amarelo):
  - Luminosidade menor que 66 e acima de 33 (ambiente com iluminação considerável)
  - Temperatura entre 8 °C e 10 °C ou 18 °C à 20 °C
  - Umidade entre 50% e 60% ou 70% e 75%
  - ACIONA O PIEZO: buzina por 3 segundos, se persistir, repete a buzina
  - O LCD mostra os valores que estão Moderadamente fora do padrão
- PERIGO (Led Vermelho):
  - Luminosidade maior de 66 (ambiente com alta iluminação)
  - Temperatura menor que 8 °C ou maior que 20 °C
  - Umidade menor que 50% ou maior que 75%
  - ACIONA O PIEZO: buzina de forma constante até que seja corrigida a iluminação
  - O LCD mostra os valores que estão muito fora do padrão

## Tecnologias Utilizadas

Utilizamos as seguintes tecnologias para a simulação e para o HANDS ON:

![Arduino](https://img.shields.io/badge/-Arduino-00979D?style=for-the-badge&logo=Arduino&logoColor=white)
![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)

## Como Reproduzir o Projeto?

Este projeto utiliza os seguintes componentes eletrônicos:

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
| LCD 16x02  | 1  |
| Jumpers  | 43  |

## Observação
Para que o programa funcione é necessário instalar a lib chamada "DHT sensor library", ela permite a obtenção dos valores do sensor, tanto de temperatura quanto de umidade.

# Integrantes do Grupo  

| [<img loading="lazy" src="https://github.com/DaviMunhoz1005.png" width=115><br><sub>Davi Marques</sub>](https://github.com/DaviMunhoz1005) |  [<img loading="lazy" src="https://github.com/catvergueiro.png" width=115><br><sub>Catarina Luiza</sub>](https://github.com/catvergueiro) |  [<img loading="lazy" src="https://github.com/Gabsgc01.png" width=115><br><sub>Gabriel Ciriaco</sub>](https://github.com/Gabsgc01) | [<img loading="lazy" src="https://github.com/Mafraaa.png" width=115><br><sub>Vinicius Mafra</sub>](https://github.com/Mafraaa) | [<img loading="lazy" src="https://github.com/MariFranca.png" width=115><br><sub>Mariana Franca</sub>](https://github.com/MariFranca) | 
| :---: | :---: | :---: | :---: | :---: |
