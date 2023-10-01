# Jogo da Memória

Este é um jogo de memória simples implementado em JavaScript. O jogo consiste em uma grade de cartas com símbolos de emoji nelas. O objetivo é combinar todos os pares de cartas clicando nelas. Quando duas cartas são clicadas, elas serão reveladas e, se forem iguais, permanecerão abertas; caso contrário, serão viradas novamente.

## Como Jogar

1. Abra o arquivo `index.html` em seu navegador da web.

2. Você verá uma grade de cartas com símbolos de emoji.

3. Clique em duas cartas para revelá-las. Se elas corresponderem, permanecerão abertas; caso contrário, serão viradas novamente.

4. Continue clicando em pares de cartas até combinar todos os pares.

5. Quando você combinar todos os pares, uma mensagem de vitória será exibida.

## Visão Geral do Código

O código para este jogo está escrito em JavaScript e usa HTML e CSS para a interface do usuário. Aqui está uma breve visão geral do código:

- `emojis`: Uma matriz que contém os símbolos de emoji usados no jogo.

- `openCards`: Uma matriz que armazena as cartas atualmente abertas.

- `shuffleEmojis`: Embaralha os símbolos de emoji aleatoriamente para criar um novo layout do jogo.

- O código cria dinamicamente elementos HTML para as cartas e adiciona manipuladores de eventos de clique a elas.

- `handleClick()`: Lida com o evento de clique em uma carta. Ele verifica se duas cartas estão abertas e chama `checkMatch()` quando duas cartas estão abertas.

- `checkMatch()`: Compara os símbolos de emoji nas cartas abertas. Se corresponderem, as cartas permanecem abertas; caso contrário, são viradas novamente. Se todos os pares forem combinados, uma mensagem de vitória é exibida.

## Divirta-se jogando o jogo!
