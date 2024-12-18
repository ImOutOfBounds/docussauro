# Relatório  
A ideia em questão é apresentarmos a linha de desenvolvimento e progresso, além de compartilhar as próximas etapas do projeto.  

## Funcionalidades  
#### 1. Movimentação  
Foi desenvolvida a funcionalidade de movimentação de maneira a qual o jogador, utilizando o gatilho esquerdo do Meta Quest, consegue movimentar a nave para cima, para baixo e para os lados. Atualmente, ele ainda consegue se movimentar por toda a cena do Unity, mas para os próximos passos limitaremos o range de movimento para um túnel delimitado.  

#### 2. Movimento automático da câmera  
Nosso jogo, como um Rail Shooter, depende da funcionalidade da câmera se mover automaticamente para frente na fase. Para isso, desenvolvemos essa feature, que já está operacional, onde a câmera começa de um ponto definido na cena (atualmente 0, 0) e se movimenta em linha reta até um checkpoint, definido por um objeto genérico, que pode estar posicionado à nossa escolha.  

#### 3. Imersão no Cockpit  
O posicionamento de câmera do jogador foi pensado para ser imersivo, de maneira a qual ele vê o espaço em primeira pessoa de dentro da nave, podendo ver elementos que estão presentes naquele espaço, que no caso são a alavanca e o controlador, que devidamente representam os controles do Meta Quest.  

## Próximas Etapas  
#### 1. Mecânica de atirar  
Nossa feature prioritária de desenvolvimento no momento é a mecânica de atirar, onde utilizaremos os assets escolhidos para que o jogador possa realizar um disparo utilizando o gatilho direito do Meta Quest.  

#### 2. Implementar Inimigos  
Para a entrega final, planejamos adicionar inimigos, que serão naves e meteoros que poderão ser destruídos com o disparo. Para isso, já temos os assets definidos; a ideia agora é desenvolver a inteligência deles na cena.  

#### 3. Mecânica de Colisão  
Adicionar pontos e elementos de colisão dentro do jogo, onde, caso a nave do jogador encoste em um desses pontos, seja redirecionado para uma tela de Game Over.  
