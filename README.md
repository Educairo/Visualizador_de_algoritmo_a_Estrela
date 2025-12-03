# Visualizador_de_algoritmo_a_Estrela
Esta é uma implementação visual do algoritmo A* (A-estrela) para busca de caminhos, desenvolvida em Python com PyGame. O algoritmo encontra o caminho mais curto entre dois pontos em um grid, evitando obstáculos.

Funcionalidades
Interface visual interativa para criar e visualizar o algoritmo

Colocação de elementos:
Ponto de início (laranja)
Ponto de destino (turquesa)
Barreiras/obstáculos (pretos)
Algoritmo A* com heurística de distância de Manhattan
Visualização em tempo real do processo de busca
Reinicialização completa do grid

🎮 Controles
Ação	Tecla/Mouse
Colocar ponto de início	Botão esquerdo do mouse
Colocar ponto de destino	Botão esquerdo do mouse
Colocar barreiras	Botão esquerdo do mouse
Remover elementos	Botão direito do mouse
Executar algoritmo A*	Barra de espaço
Limpar toda a tela	Tecla 'C'
Fechar aplicação	Botão 'X' da janela

📊 Detalhes Técnicos
Grid: 50x50 células

Resolução da janela: 800x800 pixels

Movimentação: Apenas ortogonal (cima, baixo, esquerda, direita)

Heurística: Distância de Manhattan |x1-x2| + |y1-y2|

🛠️ Pré-requisitos
pip install pygame
