# MinMaxJogoDaVelha

O Jogo da Velha funciona com uma técnica de IA, mostrada na função minmax.
A função funciona pegando o tabuleiro como já está e testando todas as jogadas possíveis, levando em conta que o usuário tentará minimizar as chances de vitória do computador, usando da recursividade para simular a mudança de jogadas, e se utilizando de dois loops "for" para interagir com todos os possíveis movimentosde se jogar.
A função decide qual jogada seria ideal comparando com os pontos que seriam feitos em um jogo simulado, comparando uma jogada com a outra, e com a próxima, e com todas as possíveis, para se encontrar uma que maximize seus pontos. Ela leva em conta que o jogador faria a mesma coisa, mas ao invés de maximizar os pontos, ele iria tentar minimizar os pontos do computador, portanto, pegando sempre a menor pontuação entre as duas.
