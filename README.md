# PCS3539-GustavoHonda-PedroChazanas

Jogo de Terror inspirado na POLI-Elétrica

Gustavo Ken Honda - 8992687
Pedro Lui Nigro Chazanas - 8992496

A ideia consiste em um jogo de terror em primeira pessoa com o cenário sendo um modelo simplificado, porém reconhecível do prédio de engenharia elétrica da POLI.

Cenário: Prédio da engenharia elétrica da POLI inicialmente sem salas (somente portas fechadas) podendo-se percorrer os espaços abertos e corredores, caso houver tempo, tentaremos modelar as salas. Como é um jogo de terror pensamos em iluminação noturna com poucas fontes de luz.

Jogador: Primeira pessoa, movimentando-se com o teclado (WASD) e movendo a câmera com o mouse, para interagir com o ambiente pensamos em usar o botão direito e esquerdo do mouse e caso necessite de mais ações, a tecla E poderá ser usada. O jogador se movimenta em velocidade de caminhada, precisando segurar a tecla shift para correr, no entanto uma barra de energia é consumida ao correr e se regenera com o tempo.

Contexto: O jogador está na POLI-Elétrica na madrugada, ele terá uma prova no dia seguinte e precisa encontrar 5 “colinhas” geradas aleatoriamente no cenário para conseguir tirar 5 na prova.

Colinha: As 5 “colinhas” serão representadas por pedaços de papel espalhadas pelo cenário, cada colinha terá uma equação importante.

Obstáculos: Além de precisar procurar as “colinhas” pelo cenário, existem inimigos inicialmente invisíveis que perseguirão o jogador e, ao conseguirem alcançá-lo o jogo precisará ser reiniciado do começo. O inimigo invisível produzirá um som distinto que fica cada vez mais alto ao se aproximar do jogador, um mecanismo parecido com o jogo Slender. Ainda estamos pensando no mecanismo de perseguição, mas uma ideia inicial é que um inimigo é gerado em um lugar aleatório do cenário, persegue o jogador durante 2 minutos com velocidade 90% do jogador e depois “desiste” da busca, sumindo do jogo e deixando que outro inimigo entre no lugar dele. Podemos ter 1 a 10 inimigos ao mesmo tempo, somente testando para definir um valor melhor.

Poder: O jogador consegue visualizar e combater os inimigos se conseguir encontrar o “Óculos de Fourier”, objeto mágico que permite que o jogador consiga ver no domínio da frequência. O artefato será gerado aleatoriamente no cenário. A ideia é o jogador, ao achar o “Óculos de Fourier” utilize o óculos sinalizado por uma mudança de cor na visão (como um efeito de visão noturna em jogos). Os inimigos poderão ser visualizados pelo jogador e será revelado que os inimigos são equações da transformada de Fourier flutuantes. O jogador poderá com o clique do mouse atirar “raios Fourier” para eliminar um inimigo.

Tela de Derrota: Se o jogador for pego por um dos inimigos a tela ficará escura e um texto escrito: “Você zerou a prova e pegou DP da matéria!” com a opção de reiniciar ou sair do jogo.

Tela de Vitória: Se o jogador conseguir achar as 5 “colinhas” a tela ficará escura e um texto escrito “Você tirou 5 na prova e conseguiu passar na matéria!” com a opção de reiniciar ou sair do jogo.
