# TradeScience
Trade project based on multi strategies optimized by machine learning.

No universo de criptomoedas podemos fazer operações de compra e venda nos mais variados tipos de moedas como por exemplo Bitcoin, Eterium, Cardana, entre outras e com essas operações podemos obter lucro.
Podemos fazer essas operações de maneira simples ou de maneira profissional usando indicadores. E esses indicadores são a base desse projeto, eles serão 
utilizados para podermos encontrar momentos de compra e venda das moedas, momentos esses baseados em dados históricos e otimizados pela IA.

# Indice
* [Objetivo](#objetivo)
* [Resources](#resources)
* [Language](#language)
* [Libs](#libs)
* [Steps](#steps)

# Objetivo
Encontrar um melhor indicador que resulte em um melhor retorno financeiro utilizando algoritmos inteligentes.

# Resources
## Broker
* FTX

# Language
* Python
* SQL

# Libs
## API
* [vectorBT](https://vectorbt.dev/)
Nesse projeto iremos usar como base a biblioteca chamada vectorBT que tem como objetivo de otimizar os parametros dos indicadores

## ML
* Pandas

## VectorBT
https://www.youtube.com/watch?v=knOPLwyc5u0
https://www.youtube.com/watch?v=OiQRD2BcHhA&t=4s
https://www.youtube.com/watch?v=OiQRD2BcHhA&t=4s

# Steps
## Part 1
- [ ] Ler a documentação do VectorBT 
- [ ] Configurar um docker como base
- [ ] Fazer a implementação de uma classe para adquiridir os dados históricos de uma corretora usando o vectorBT ([Referencia])(https://www.youtube.com/watch?v=knOPLwyc5u0)
  - Devemos adquirir esses dados usando uma quantidade variavel de estratégias
  - Devemos salvar todos os resultados de cada estratégia
- [ ] Fazer uma classe para analisar os dados adquiridos e retornar um ranking de estratégias sendo a primeira a com maior lucro/score.
  - Escolher uma forma de score para as estratégias

## Part 2
- [ ] Desenvolver o algoritmo para execução em paralelo
  - Usar AWS? Azure? Google?
- [ ] Interface
