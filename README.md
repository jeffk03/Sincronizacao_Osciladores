# Sincronização de Osciladores

Este projeto tem como objetivo principal **estudar diferentes fenômenos de sincronização em sistemas oscilatórios**. Exploramos a interação entre osciladores, observando como eles se comportam e sincronizam sob diversas condições.

## Estrutura do Projeto

A pasta principal do projeto é a **`acoplamento`**, que contém subpastas dedicadas a cada tipo de oscilador e fenômeno de sincronização estudado:

### 1. Osciladores Regulares
Esta pasta contém os estudos de **sincronização em osciladores regulares**, que servem como base para a compreensão dos fenômenos mais complexos.

### 2. Oscilador de Lorenz
Aqui, o foco é a **sincronização completa** de um **oscilador caótico de Lorenz**. Investigamos as condições sob as quais dois osciladores caóticos idênticos podem operar em perfeita sincronia.

### 3. Oscilador de Rössler
Esta seção é dedicada ao estudo da **sincronização de fase** em um **oscilador de Rössler**. Analisamos como a fase dos osciladores se alinha, mesmo que suas amplitudes não estejam perfeitamente sincronizadas.

### 4. Double Scroll
Nesta pasta, exploramos a **sincronização completa com intermitência on-off** em um oscilador **Double Scroll**. Este tipo de sincronização é caracterizado por períodos de sincronia completa alternados com breves períodos de dessincronia.

## Conteúdo de Cada Pasta

Cada subpasta (ex: `lorenz`, `rossler`) segue um padrão de organização para manter a consistência do projeto:

* **`acoplamento.jl`**: Contém o código-fonte em linguagem Julia para simular o acoplamento dos osciladores e gerar os resultados.
* **`fig/`**: Uma pasta dedicada a armazenar todas as figuras e gráficos gerados pelo código, facilitando a visualização dos resultados.
