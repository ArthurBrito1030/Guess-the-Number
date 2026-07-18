# 🎮 Jogo do Número Secreto

Um jogo web interativo e acessível onde o jogador precisa adivinhar um número secreto gerado aleatoriamente pelo sistema.
O projeto foi desenvolvido para colocar em prática conceitos fundamentais de **Lógica de Programação** e **Manipulação do DOM** com JavaScript.

## 📝 Sobre o Projeto

O "Jogo do Número Secreto" desafia o usuário a descobrir um número oculto (por padrão, entre 1 e 10).
A cada tentativa, o jogo fornece dicas visuais e sonoras, informando se o número secreto é maior ou menor do que o chute atual. Ao acertar, o jogo exibe a quantidade de tentativas utilizadas.

Um dos grandes diferenciais deste projeto é a implementação de **acessibilidade em áudio**, utilizando a biblioteca `responsiveVoice` para ler os textos da tela em voz alta (Português do Brasil).

## ✨ Funcionalidades

- **Sorteio Inteligente:** O sistema gera números aleatórios e armazena os números já sorteados em uma lista, garantindo que o mesmo número não se repita até que todas as possibilidades sejam esgotadas.
- **Feedback Interativo:** Dicas em tempo real informando se o número secreto é maior ou menor.
- **Contador de Tentativas:** Cálculo de quantas jogadas foram necessárias para vencer, ajustando o texto (singular/plural) dinamicamente.
- **Acessibilidade (Text-to-Speech):** O jogo "fala" as instruções e os resultados, melhorando a experiência de uso.
- **Design Responsivo:** Layout adaptável para diferentes tamanhos de tela (Mobile e Desktop) utilizando CSS Flexbox e Media Queries.

## 🚀 Tecnologias Utilizadas

O projeto foi construído utilizando as tecnologias base do desenvolvimento web:

- **HTML5:** Estruturação semântica da página.
- **CSS3:** Estilização, background em gradiente, layout com Flexbox e responsividade.
- **JavaScript (Vanilla):** 
  - Variáveis e Tipos de Dados.
  - Funções com e sem retorno.
  - Estruturas condicionais (`if/else`, operadores ternários).
  - Recursividade (na geração de números).
  - Manipulação do DOM (`querySelector`, `innerHTML`, `removeAttribute`).
- **APIs e Bibliotecas Externas:**
  - Google Fonts (Chakra Petch e Inter).
  - [ResponsiveVoice.js](https://responsivevoice.org/) para síntese de voz.

## 🛠️ Como executar o projeto

Como o projeto é feito puramente em Front-end (HTML, CSS e JS), não é necessário instalar nenhum ambiente complexo.

1. Faça o clone deste repositório ou baixe o arquivo `.zip`.
2. Extraia os arquivos no seu computador.
3. Certifique-se de estar conectado à internet (necessário para carregar as fontes e a API de voz).
4. Dê um duplo clique no arquivo `index.html` para abri-lo no seu navegador de preferência.
5. Divirta-se jogando!

## 🧠 Aprendizados e Lógica

Este projeto foi fundamental para consolidar conceitos de **Software Engineering** voltados ao front-end, especialmente a lógica por trás de arrays. 
A função de gerar números aleatórios verifica se a lista de sorteados já atingiu o limite máximo, limpando-a automaticamente para que o jogo possa continuar indefinidamente sem quebrar ou entrar em loops infinitos.
