# dados-atleta
# Sistema de Informações de Atletas

Aplicação desenvolvida em JavaScript orientada a objetos para gerenciar e calcular os dados de competidores.

## Funcionalidades
A classe `Atleta` recebe informações básicas (nome, idade, peso, altura e notas) e fornece métodos para:
- Calcular a categoria de competição baseada na idade.
- Calcular o Índice de Massa Corporal (IMC) usando a fórmula: peso / (altura x altura).
- Calcular a média válida das notas recebidas (descartando a maior e a menor pontuação).

## Tecnologias Utilizadas
- JavaScript (ES6) - Classes, Métodos de Array (`sort`, `slice`, `reduce`, `join`).

## Como Executar o Projeto
1. Tenha o [Node.js](https://nodejs.org/) instalado em sua máquina.
2. Clone o repositório ou baixe o arquivo `dados-atletas.js`.
3. Abra o terminal no diretório do arquivo.
4. Execute o comando:
   ```bash
   node dados-atletas.js