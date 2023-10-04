# README - Jogo Papel, Pedra e Tesoura

Este código em Python implementa o jogo clássico "Papel, Pedra e Tesoura" para ser jogado contra o computador. O objetivo do jogo é escolher um dos três movimentos (papel, pedra ou tesoura) e competir com o computador para ver quem ganha.

## Funcionalidades do Código

- Função `main_print()`: imprime o placar atual e as opções disponíveis para o jogador.
- Função `select_move()`: escolhe um movimento aleatório para o computador.
- Função `get_player_move()`: solicita ao jogador que escolha um movimento válido.
- Função `select_winner(p_move, c_move)`: determina o vencedor com base nos movimentos escolhidos pelo jogador e pelo computador.
- Laço `while again == 1`: executa o jogo repetidamente até que o jogador decida parar.
- Limpeza do console: utiliza a função `os.system('clear')` para limpar a tela do console entre cada jogada.

## Execução do Código

Para executar o código, basta copiá-lo para um ambiente Python e rodar. O jogo será iniciado e as instruções serão exibidas no console.

Durante o jogo, o jogador deve escolher um número correspondente à opção desejada (0 para papel, 1 para pedra e 2 para tesoura). O computador fará sua escolha de forma aleatória. O resultado de cada rodada será exibido, indicando se o jogador ganhou, perdeu ou empatou. O placar atual será atualizado a cada rodada.

Ao final de cada rodada, o jogador terá a opção de jogar novamente ou sair do jogo.

## Nota

Este código é uma implementação básica do jogo "Papel, Pedra e Tesoura" e tem fins didáticos. É possível expandir e aprimorar o código de acordo com suas necessidades e requisitos específicos, incluindo recursos como validação de entrada, interface gráfica, regras adicionais, etc.