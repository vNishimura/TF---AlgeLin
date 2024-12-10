# Trabalho Final - Álgebra Linear e Aplicações - SME0142

# ATENÇÃO
Necessário ter o OpenGL, glfw e demais bibliotecas instaladas corretamente, além dos arquivos descritivos dos objetos, para rodar o código corretamente.

Link para a apresentação: https://www.youtube.com/watch?v=WGXWaJfE1S4

## Alunos:
> Fabricio Sampaio - NUSP: 12547423

> Vitor Nishimura Vian - NUSP: 5255289

## Explicação Geral: 
O presente trabalho explora a área de Álgebra Linear aplicada a Computação Gráfica, mais especificamente a conhecida biblioteca de renderização **Open GL**. 
Conceitos como vetores, matrizes e transformações lineares são essenciais para a manipulação e renderização de objetos em ambientes virtuais, sejam eles 2D ou 3D.

Vetores são utilizados para representar pontos, direções e normais de superfícies, enquanto matrizes são essenciais para aplicar transformações como translações, rotações e escalonamentos, que definem o posicionamento e a orientação de objetos no espaço. Matrizes de projeção, como as projeções perspectiva e ortográfica, convertem coordenadas 3D para 2D, permitindo que cenas tridimensionais sejam renderizadas em telas bidimensionais. 

Assim sendo, a álgebra linear é o núcleo matemático que sustenta a computação gráfica, sendo indispensável para o desenvolvimento de aplicações visuais como jogos, simulações e animações.

## O Trabalho:

O código cria e renderiza em tempo real um ambiente 3D interativo, que se modifica de acordo com os comandos do teclado e do mouse do usuário, como um _**videogame**_. As ferramentes utilizadas para a criar a sensação de movimento na tela do computador, assim como o modelo de iluminação utilizado, são provenientes da Álgebra Linear e serão o foco das explicações teóricas a seguir. Conceitos mais profundos da Ciência da Computação, como a utilização das _GPUs_ e seu processamente paralelo, estruturas de dados e a própria biblioteca Open GL, serão explicados brevemente, mas o foco principal estará na aplicação direta da Álgebra Linear no contexto da computação gráfica.

## Comandos do "_videogame_":
> P: alterna entre visualização padrão e malha poligonal;

### Movimentação da Câmera
> W: Movimenta a câmera para frente;

> A: Movimenta a câmera para esquerda;

> S: Movimenta a câmera para trás;

> D: Movimenta a câmera para direita;

> Mouse: Muda a direção da câmera de acordo com o movimento.

## Controles de Iluminação:
> L: Liga/Desliga a luz da câmera (lanterna);

> 1 e 2: Diminui e aumenta a luz ambiente, respectivamente;

> 3 e 4: Diminui e aumenta a reflexão difusa, respectivamente;

> 5 e 6: Diminui e aumenta a reflexão especular, respectivamente.

## Transformações do Objeto "_Shrek_":
Do lado exterior do mundo 3D criado, existe um objeto representando o famoso personagem animado _Shrek_. Nele, todas as transformações ocorrem:
> Rotação: o objeto está constantemente sendo rotacionado;

> Translação: controlada pelas setas do teclado (→, ←, ↑ e ↓);

> Escala: '>' para aumentar de tamanho de forma uniforme e '<' para diminuir de tamanho de forma uniforme.
