# Bresenham's Line Algorithm
Discente: Maria Raquel Alves da Silva

O seguinte texto tem como objetivo apresentar um memorial descritivo das atividades relacionadas à criação de uma forma triangular através da implementação e rasterização de pontos e linhas. Para auxiliar esse procedimento será feito uso do algoritmo de Bresenham, que utiliza-se ................
O código foi escrito em C++ baseando-se no framework disponibilizado pelo docente da disciplina de Introdução à Computação Gráfica.

Como funciona o algoritmo de Bresenham?
Iniciamos o processo fazendo a definição das variáveis. Para simplificar, utilizaremos uma estrutura para definir as coordenadas e outra para as cores RGBA.
________________________________________
Vantagens: 
O algoritmo de Brsenham tem como uma de suas vantagens a sua "economia" em relação à seus predecessores, pelo fato de não fazer uso de operações de maior custo, como multiplicações e divisões, além de não fazer uso de variáveis de ponto flutuante. O algoritmo parte do princípio de que a inclinação da reta sempre está entre 0 e 1.

________________________________________

Funções determinantes para a criação dos pontos linhas e triângulos:

Foram realizadas as seguintes funções:
PutPixel(int x, int y) - 
DrawLine(int x0, int y0, int x1, int y1) - 
DrawTriangle() - 

Dificuldades: não foi obtido sucesso em fazer linhas inclinadas fora da origem, optando por permanecê-las iniciando na origem.

Resultado:
![Screenshot](https://i.imgur.com/Y86Mv0og.png)


