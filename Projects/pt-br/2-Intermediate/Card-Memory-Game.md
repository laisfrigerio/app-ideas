# Jogo-da-Memória

**Tier:** 2-Intermediário

Jogo da memória é um jogo onde você deve clicar em um cartão para ver a imagem que está embaixo e tentar encontrar seu par idêntico embaixo das outras cartas.

## Histórias do Usuário

- [ ] Usuário pode observar uma grade com n x n cartas (sendo `n` um inteiro). Todos os cartões são virados para baixo inicialmente (estado `escondido`)
- [ ] Usuário pode apertar um botão para iniciar o jogo. Quando este for pressionado um temporizador irá iniciar.
- [ ] Usuário pode clicar em qualquer carta para revelar a imagem que está abaixo (mude o estado para `visivel`). A imagem estará visível até que o Usuário clique num segundo card.

Quando o Usuário clica na segunda carta:

- [ ] Se for um par, as duas cartas serão eliminadas do jogo (Pode esconder/remover ou deixar em estado `visivel`)
- [ ] Se não for um par, as duas cartas devem ser viradas ao seus estados originais (estado `escondido`)
- [ ] Quando todos os pares forem encontrados, o Usuário pode ver uma caixa de diálogo com uma mensagem de Parabéns, junto com um contador informando o tempo que levou para terminar o jogo.

## Características Bonus

- [ ] Usuário pode escolher entre múltiplos níveis de dificuldade (Fácil, Médio, Difícil). Aumentar a dificuldade significa: reduzir o tempo disponível para finalizar o game e/ou aumentar o número de cartas
- [ ] Usuário pode ver as estatísticas do jogo (Nr. de vezes vencido/perdido, melhor tempo por nível)

## Links e recursos úteis

- [Wikipedia](<https://en.wikipedia.org/wiki/Concentration_(game)>)

## Exemplo de projetos

-   [Flip - card memory game](https://codepen.io/zerospree/full/bNWbvW)
-   [Memory Game](https://jdmedlock.github.io/memorygame/)
-   [SMB3 Memory Card Game](https://codepen.io/hexagoncircle/full/OXBJxV)
-   [BHMBS - Memory Game](https://barhouum7.github.io/JS-MemoryGame.github.io/)