# Bresenham's Line Algorithm
Discente: 11409513

O seguinte texto tem como objetivo apresentar um memorial descritivo das atividades relacionadas à criação de uma forma triangular através da implementação e rasterização de pontos e linhas. Para auxiliar esse procedimento será feito uso do algoritmo de Bresenham.
O código foi escrito em C++ baseando-se no framework disponibilizado pelo docente da disciplina de Introdução à Computação Gráfica.

Como funciona o algoritmo de Bresenham?
Iniciamos o processo fazendo a definição das variáveis. Para os parâmetros de entrada recebidos (x0,y0, x1, y1) calculamos dois valores inteiros que serão chamados de dx e dy, que serão:
dx = x1-x0;
dy = y1-y0;

Teremos, também, as variáveis auxiliares aux1 e aux2, que receberão os seguintes valores:
aux1 = 2*dy;
aux2 = 2*dy-2dx;


________________________________________

Vantagens: 
O algoritmo de Brsenham tem como uma de suas vantagens a sua "economia" em relação à seus predecessores, pelo fato de não fazer uso de operações de maior custo, como multiplicações e divisões, além de não fazer uso de variáveis de ponto flutuante. O algoritmo parte do princípio de que a inclinação da reta sempre está entre 0 e 1.
________________________________________

Foram realizadas as seguintes funções:

PutPixel(int x, int y)

DrawLine(int x0, int y0, int x1, int y1)

DrawTriangle()

Dificuldades: não foi obtido sucesso em fazer linhas inclinadas fora da origem, optando por permanecê-las iniciando na origem.
As cores ficaram por padrão as mesmas, independente da linha. A escolha foi feita devido ao fato de não ter sido bem sucedida a tentativa de fazer as linhas com o parâmetro de escolha de cor habilitado.

Resultado:


![Screenshot](https://i.imgur.com/Y86Mv0og.png)


