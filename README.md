# Projeto "Dungeon Crawler"

Este projeto foi desenvolvido por alunos do curso de Ciência da Computação do CESUPA (Centro Universitário do Pará)
O mesmo fez parte do nosso primeiro semestre como conteúdo avaliativo para desenvolvimento de habilidades de programação

# O Projeto

Jogo em linguagem C chamado "Castle Conquer" onde o jogador deve conquistar o Castelo que possui 3 níveis. Para isso
o jogador deverá encontrar a chave que abrirá as portas para os próximos níveis. CUIDADO! O castelo esconde perigos
mortais e fica mais perigoso à medida que o jogador avança de nível.

Cada elemento no mapa é representado por um caractere especial:

- '&': Símbolo que representa o jogador.
- 'P': Símbolo que representa um NPC.
- '*': Símbolo que representa uma parede, o jogador ao se movimentar não pode
passar pela parede.
- '@': Simbolo que representa a chave para abrir a porta para finalizar a fase, a
porta abre no momento que o jogador interage com a chave.
- 'D': Símbolo que representa a porta fechada.  
- '=': Simbolo que representa a porta aberta quando o jogador interage com a
chave.
- 'O': Símbolo que representa um botão que o usuário pode interagir, o botão
fica no chão e o jogador deve ficar em cima dele para poder interagir.
- '#': Símbolo que representa um espinho. A fase é reiniciada quando o jogador
toca no espinho, caso a fase seja reiniciada três vezes, o jogo volta para o
menu principal.
- '>': Símbolo que representa um teletransporte. Quando o jogador toca em um, ele
é transportado para o outro e vice-versa.
- 'X': Símbolo que representa o monstro nível 1. Esse monstro tem um
movimento aleatório para cima, para esquerda, para baixo e para direita. Caso
o monstro toque no jogador, o jogador morre.
- 'V': Símbolo que representa o monstro nível 2. Esse monstro tem uma
inteligência para seguir o jogador. Caso o monstro toque no jogador, a fase é reiniciada.

# A História

Você joga na pele de um guerreiro que escuta uma voz que o atrai para uma Vila. Lá, um aldeão
conta que o que o atraiu foi um castelo com poderes sobrenaturais capaz de se alimentar do medo
e da força vital de todos na Vila e dos aventureiros que adentram. Ele pede sua ajuda para derrotar
o castelo, chegando ao nível mais profundo e conquistando o mesmo, retirando a coroa do pedestal mágico. 
No caminho, pode-se ver os outros aventureiros que tentaram conquistar o castelo e falharam, sendo condenados
a vagar eternamente pelo castelo como mortos-vivos. Na última câmara está preso aquele que tem o poder de 
atrair e dominar a mente daqueles que se julgam fortes o suficiente para enfrentar o castelo.

# Equipe

- Arthur Vicente Ono
- Caio Augusto Freitas Barbosa de Souza
- Luan Queiroz Fonseca de Menezes
