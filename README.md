# EDGE-CP1

Checkpoint 1 para a disciplina de Edge Computing and Computer Systems FIAP.

## Esquemática e Montagem

A montagem completa do circuito pode ser visualizada e testada diretamente na simulação do Tinkercad.  
> [Clique aqui para acessar a simulação.](https://www.tinkercad.com/things/j51QYpTMhE4-cp-1-edge)

## Sobre o Projeto

Nós elaboramos um sistema utilizando Arduino que tem como propósito capturar as informações de luminosidade do sistema, com o intuito de auxiliar a manter o ambiente com uma iluminação adequada para a preservação de vinhos. 

O sistema funciona da seguinte forma:

- OK (Led Verde):
  - Luminosidade acima de 800 (ambiente escuro/baixa iluminação)
- ALERTA (Led Amarelo):
  - Luminosidade menor que 800 e acima de 500 (ambiente com iluminação considerável)
  - ACIONA O PIEZO: buzina por 3 segundos, se persistir, repete a buzina
- PERIGO (Led Vermelho):
  - Luminosidade abaixo de 500 (ambiente com alta iluminação)
  - ACIONA O PIEZO: buzina de forma constante até que seja corrigida a iluminação

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
| Resistor 220 Ω  | 3 |
| Resistor 1 kΩ  | 1  |
| Fotorresistor  | 1  |
| Piezo  | 1  |
| Jumpers  | 14  |

# Integrantes do Grupo  

| [<img loading="lazy" src="https://github.com/DaviMunhoz1005.png" width=115><br><sub>Davi Marques</sub>](https://github.com/DaviMunhoz1005) |  [<img loading="lazy" src="https://github.com/catvergueiro.png" width=115><br><sub>Catarina Luiza</sub>](https://github.com/catvergueiro) |  [<img loading="lazy" src="https://github.com/Gabsgc01.png" width=115><br><sub>Gabriel Ciriaco</sub>](https://github.com/Gabsgc01) | [<img loading="lazy" src="https://github.com/Mafraaa.png" width=115><br><sub>Vinicius Mafra</sub>](https://github.com/Mafraaa) | [<img loading="lazy" src="https://github.com/MariFranca.png" width=115><br><sub>Mariana Franca</sub>](https://github.com/MariFranca) | 
| :---: | :---: | :---: | :---: | :---: |