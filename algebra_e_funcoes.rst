=======
Funções
=======



.. admonition:: Objetivos Específicos 

	(EM11MT06) Compreender função como uma relação de dependência entre duas variáveis, as ideias de domínio, contradomínio e imagem, e suas representações algébricas e gráficas e utilizá- las para analisar, interpretar e resolver problemas em contextos diversos, inclusive fenômenos naturais, sociais e de outras áreas.


.. admonition:: Pré-requisitos

	(EF06MT01) Associar pares ordenados a pontos do plano cartesiano, considerando apenas o primeiro quadrante, preferencialmente vinculados a situações com algum significado para o/a estudante, como, por exemplo, para representar pontos de um desenho construído sobre o plano.
    
	(EF09MT16) Reconhecer função como uma relação de dependência entre duas variáveis que pode ser representada nas formas algébrica e gráfica, utilizando essa noção para analisar e compreender situações que envolvem relações funcionais entre duas variáveis.

.. admonition:: Desdobramentos imediatos 

   (EM11CN10) Representar e/ou obter informações de tabelas, esquemas e gráficos de valores de grandezas que caracterizam movimentos ou causas de suas variações; converter tabelas em gráficos e vice-versa; estimar e analisar variações com base nos dados.
   
   Diferenciar relações funcionais e relações não funcionais a partir de fenômenos determinísticos e aleatórios, reconhecendo aqueles que apresentam uma estrutura de causalidade, isto é, aqueles em que é possível estimar resultados; e verificar situações de dependência entre variáveis.
    
    
Vivemos na era da informação! A todo momento empresas capturam grandes quantidades de dados e buscam formas de processar tais informações e transformá-las em conteúdos relevantes para seus usuários. Por exemplo, os dados sobre tempo de deslocamento de cada veículo, que são obtidos via satélite, aliados ao mapeamento das vias urbanas podem ser processados e devolvidos aos usuários com informações sobre congestionamentos, tempo estimado de viagem, melhores rotas, etc.
A imagem abaixo, que foi retirada do aplicativo Google Maps®, exibe o trânsito de uma região da cidade de Paris em um determinado dia e hora. Perceba a quantidade de informações que podem ser extraídas apenas a partir da observação dos elementos presentes nela: as cores nas vias informam a velocidade média dos veículos que trafegam por elas conforme a legenda na parte inferior, a distância entre dois pontos quaisquer do mapa pode ser estimada usando a escala exibida no canto inferior direto, e tantas outras. Gráficos como este são produzidos a partir do reconhecimento das relações entre as diversas informações coletadas.
        
.. figure:: https://www.umlivroaberto.com/livro/lib/exe/fetch.php?media=maps.png
     :width: 700px
     :align: center

.. note:: As figuras só ficavam visíveis se estivéssemos logados na wiki. Mudei o link para as figuras porque as coloquei na wiki do livro de frações que é aberta a todo mundo para visualização. Agora as figuras devem ser colocadas lá. Por favor, veja a documentação sobre figuras na `sintaxe <https://www.umlivroaberto.com/BookCloud/sintaxe/master/view/index#my-figuras>`_

Neste Capítulo vamos explorar as relações que podem ser estabelecidas entre diferentes tipos de informação. Veremos como conectar grandezas, medidas, conjuntos numéricos e até questões mais subjetivas que muitas vezes não podem ser tão claramente quantificadas. Uma vez definidas as situações que buscamos relacionar, o precisamos definir quais são as causas e quais são os efeitos, e como se dá a dependência entre eles, estabelecendo como a variação das causas provocam as variações nos efeitos.
    


Atividade
---------

	A tabela a seguir mostra os dados coletados sobre o tempo gasto pelos veículos (em média) para atravessar uma ponte, ao longo de um dia.

	+------------------+-------------+-------+--------------------------+
	|  Período do Dia  |  Tempo (h)  |  Cor  |  Velocidade Média (km/h) |
	+==================+=============+=======+==========================+
	|    5:00 - 7:00   |     0,11    |       |                          |
	+------------------+-------------+-------+--------------------------+
	|    7:00 - 9:00   |     0,13    |       |                          |
	+------------------+-------------+-------+--------------------------+
	|   9:00 - 11:00   |     0,16    |       |                          |
	+------------------+-------------+-------+--------------------------+
	|   11:00 - 13:00  |     0,12    |       |                          |
	+------------------+-------------+-------+--------------------------+
	|   13:00 - 15:00  |     0,12    |       |                          |
	+------------------+-------------+-------+--------------------------+
	|   15:00 - 17:00  |     0,14    |       |                          |
	+------------------+-------------+-------+--------------------------+
	|   17:00 - 19:00  |     0,27    |       |                          |
	+------------------+-------------+-------+--------------------------+
	|   19:00 - 21:00  |     0,20    |       |                          |
	+------------------+-------------+-------+--------------------------+
	|   21:00 - 23:00  |     0,11    |       |                          |
	+------------------+-------------+-------+--------------------------+  

	a) Utilize a escala de cores abaixo para completar a terceira coluna da tabela acima com a cor que a ponte deveria estar colorida em cada período do dia em um aplicativo que mostra o trânsito como o Google Maps®.

		.. figure:: https://www.umlivroaberto.com/livro/lib/exe/fetch.php?t=1476340957&w=500&h=37&tok=f2c26e&media=escala_cores.jpg
			:width: 250px
			:align: center
         
	b) Você deve ter percebido que precisou associar uma mesma cor para tempos de travessia diferentes. Isso se deu pelo fato de haver somente 4 cores disponíveis e pelo menos 7 tempos diferentes. Descreva os critérios que você utilizou na escolha de cada uma das cores e compare com os critérios dos seus colegas.

	c) Sabendo que a ponte tem 8km de extensão e que a velocidade média é calculada dividindo a distância percorrida pelo tempo gasto no percurso, complete a quarta coluna da tabela acima com a velocidade média aproximada registrada em cada um dos períodos do dia.

	d) É possível que uma mesma velocidade média esteja associada a dois tempos de travessia diferentes? Por quê?

Pode-se perceber, a partir da atividade anterior, que a natureza das relações entre os dados não é sempre a mesma. Para cada tempo de travessia, podemos associar uma única cor e uma única velocidade média. Da mesma maneira, a cada velocidade média está associada uma única cor e um único tempo de travessia. No entanto, a uma mesma cor estão associados diferentes tempos e diferentes velocidades médias. 
De um modo mais geral, dados dois conjuntos quaisquer, `A` e `B` podemos estabelecer diversos tipos de relações entre seus elementos. Dentre elas, uma se destaca e é o tema central deste capítulo, as funções, que definimos a seguir.
   
   

.. admonition:: Definição 

   Dizemos que uma relação `f` é uma *função* de `A` em `B` se a cada elemento `a\in A` está associado um único elemento `b\in B`. O elemento `b` é dito a imagem do elemento `a` e é denotado por `f(a)` (lê-se `f` de `a`). O conjunto `A` é chamado *domínio* da função enquanto o conjunto `B` é o *contradomínio*.
   
  
.. admonition:: Notação 

   Denotamos por `f:A\to B` (lê-se `f` de `A` em `B`) a função cujo domínio é o conjunto `A` e o contradomínio é o conjunto `B`.

Perceba que na definição está implícito que todo elemento de `a\in A` precisa ter uma imagem `f(a)\in B`, sem haver ambiguidade na determinação da imagem. Por outro lado, nem todo elemento `b\in B`, precisa ser a imagem de algum elemento do domínio. Mas pode ocorrer de um elemento b∈B ser imagem de elementos distintos em `A`, ou seja, `b=f(a_1 )=f(a_2)` com `a_1\neq a_2`.



Atividade
---------

	Dentre as relações que podem ser feitas entre os conjuntos de dados da atividade anterior, determine quais são funções. Considere os conjuntos nomeados da seguinte maneira, `A=\{0,11;0,12;0,13;0,14;0,16;0,20;0,27\}`, `B=\{` Verde, Amarelo, Vermelho, Vinho `\}` e `C` é o conjunto das velocidades médias:

	+---------------------+-------------------+--------------------+
	| Relação             | É função?         | Se não, por quê?   |
	+=====================+===================+====================+
	| De A em B           |                   |                    |
	+---------------------+-------------------+--------------------+
	| De B em A           |                   |                    |
	+---------------------+-------------------+--------------------+
	| De A em C           |                   |                    |
	+---------------------+-------------------+--------------------+
	| De C em A           |                   |                    |
	+---------------------+-------------------+--------------------+
	| De B em C           |                   |                    |
	+---------------------+-------------------+--------------------+
	| De C em B           |                   |                    |
	+---------------------+-------------------+--------------------+
    

Atividade
---------

.. tikz:: 

	\definecolor{qqwwzz}{rgb}{0.,0.4,0.6}
	\clip(-3.9433675658221032,-5.231822639426822) rectangle (33.786185452043625,7.6600088716920745);
	\draw [color=qqwwzz,fill=qqwwzz,fill opacity=1.0] (-1.,-2.) circle (1.cm);
	\draw [color=qqwwzz,fill=qqwwzz,fill opacity=1.0] (3.,-2.) circle (1.cm);
	\draw [color=qqwwzz,fill=qqwwzz,fill opacity=1.0] (2.,0.) circle (1.cm);
	\draw [color=qqwwzz,fill=qqwwzz,fill opacity=1.0] (4.,0.) circle (1.cm);
	\draw [color=qqwwzz,fill=qqwwzz,fill opacity=1.0] (9.,-2.) circle (1.cm);
	\draw [color=qqwwzz,fill=qqwwzz,fill opacity=1.0] (8.,0.) circle (1.cm);
	\draw [color=qqwwzz,fill=qqwwzz,fill opacity=1.0] (10.,0.) circle (1.cm);
	\draw [color=qqwwzz,fill=qqwwzz,fill opacity=1.0] (7.,2.) circle (1.cm);
	\draw [color=qqwwzz,fill=qqwwzz,fill opacity=1.0] (9.,2.) circle (1.cm);
	\draw [color=qqwwzz,fill=qqwwzz,fill opacity=1.0] (11.,2.) circle (1.cm);
	\draw [color=qqwwzz,fill=qqwwzz,fill opacity=1.0] (17.,-2.) circle (1.cm);
	\draw [color=qqwwzz,fill=qqwwzz,fill opacity=1.0] (16.,0.) circle (1.cm);
	\draw [color=qqwwzz,fill=qqwwzz,fill opacity=1.0] (18.,0.) circle (1.cm);
	\draw [color=qqwwzz,fill=qqwwzz,fill opacity=1.0] (17.,2.) circle (1.cm);
	\draw [color=qqwwzz,fill=qqwwzz,fill opacity=1.0] (19.,2.) circle (1.cm);
	\draw [color=qqwwzz,fill=qqwwzz,fill opacity=1.0] (15.,2.) circle (1.cm);
	\draw [color=qqwwzz,fill=qqwwzz,fill opacity=1.0] (14.,4.) circle (1.cm);
	\draw [color=qqwwzz,fill=qqwwzz,fill opacity=1.0] (16.,4.) circle (1.cm);
	\draw [color=qqwwzz,fill=qqwwzz,fill opacity=1.0] (18.,4.) circle (1.cm);
	\draw [color=qqwwzz,fill=qqwwzz,fill opacity=1.0] (20.,4.) circle (1.cm);
	\draw [color=qqwwzz,fill=qqwwzz,fill opacity=1.0] (24.,6.) circle (1.cm);
	\draw [color=qqwwzz,fill=qqwwzz,fill opacity=1.0] (26.,6.) circle (1.cm);
	\draw [color=qqwwzz,fill=qqwwzz,fill opacity=1.0] (28.,6.) circle (1.cm);
	\draw [color=qqwwzz,fill=qqwwzz,fill opacity=1.0] (30.,6.) circle (1.cm);
	\draw [color=qqwwzz,fill=qqwwzz,fill opacity=1.0] (32.,6.) circle (1.cm);
	\draw [color=qqwwzz,fill=qqwwzz,fill opacity=1.0] (25.,4.) circle (1.cm);
	\draw [color=qqwwzz,fill=qqwwzz,fill opacity=1.0] (27.,4.) circle (1.cm);
	\draw [color=qqwwzz,fill=qqwwzz,fill opacity=1.0] (29.,4.) circle (1.cm);
	\draw [color=qqwwzz,fill=qqwwzz,fill opacity=1.0] (31.,4.) circle (1.cm);
	\draw [color=qqwwzz,fill=qqwwzz,fill opacity=1.0] (26.,2.) circle (1.cm);
	\draw [color=qqwwzz,fill=qqwwzz,fill opacity=1.0] (28.,2.) circle (1.cm);
	\draw [color=qqwwzz,fill=qqwwzz,fill opacity=1.0] (30.,2.) circle (1.cm);
	\draw [color=qqwwzz,fill=qqwwzz,fill opacity=1.0] (27.,0.) circle (1.cm);
	\draw [color=qqwwzz,fill=qqwwzz,fill opacity=1.0] (29.,0.) circle (1.cm);
	\draw [color=qqwwzz,fill=qqwwzz,fill opacity=1.0] (28.,-2.) circle (1.cm);
	\draw (-1.916350032627311,-3.745343115083972) node[anchor=north west] {\Huge{$T_1=1$}};
	\draw (2.083631232877078,-3.745343115083972) node[anchor=north west] {\Huge{$T_2=3$}};
	\draw (8.083603131133662,-3.745343115083972) node[anchor=north west] {\Huge{$T_3=6$}};
	\draw (16.08356566214244,-3.745343115083972) node[anchor=north west] {\Huge{$T_4=10$}};
	\draw (26.867298938738735,-3.745343115083972) node[anchor=north west] {\Huge{$T_5=15$}};
    
	
Considere a sequência de números ilustrada acima. Ela é conhecida como a sequência dos *números triangulares*. O `n`-ésimo número triangular é a quantidade total de pontos, distribuídos como acima, no triângulo equilátero que tem `n` pontos em um de seus lados. Por exemplo, o quarto número triangular é igual a 10. 

	a) Decida se a relação que associa a cada número natural `n`, o `n`-ésimo número triangular é ou não uma função.

	b) Determine, se possível, o 6º, o 7º e o 8º números triangulares. 

	c) É possível obter uma expressão geral que permita encontrar qualquer número triangular? Explique.


Atividade
---------

	Um dado cúbico com as faces numeradas de 1 a 6, é lançado 10 vezes e os 5 primeiros resultados são anotados em uma tabela.

	+---------------+----+----+----+----+----+
	|  Lançamento   | 1º | 2º | 3º | 4º | 5º |
	+---------------+----+----+----+----+----+
	| Resultado     |  3 |  5 |  2 |  2 |  6 |
	+---------------+----+----+----+----+----+

	a) Decida se a relação que associa a cada número natural `n`, o resultado obtido no `n`-ésimo lançamento do dado é ou não uma função. 

	b) Determine, se possível, o 6º, o 7º e o 8º resultados dos lançamentos. 

	c) É possível obter uma expressão geral que permita encontrar o resultado de qualquer lançamento? Explique.
 

.. admonition:: Fenômenos Determinísticos 

	(usar a mesma descrição utilizada no eixo de Estatística e Probabilidade)
    
.. admonition:: Fenômenos Aleatórios

	(usar a mesma descrição utilizada no eixo de Estatística e Probabilidade)
 
 

Atividade
---------
Vimos que para que uma relação seja uma função não pode haver:

	`(1)` Ambiguidade na definição;

	`(2)` Elementos no domínio sem imagem;

Identifique em cada uma das relações abaixo qual(ou quais) dos itens acima fazem com que elas deixem de ser função.

a) Seja P o conjunto de todas as pessoas e considere a relação de P em P, que a cada pessoa associa o seu irmão.
b) Seja `\mathbb{R}`  o conjunto dos números reais e considere a relação de `\mathbb{R}` em `\mathbb{R}`, que a cada número real associa sua raiz quadrada.
c) Sejam `\mathbb{R}^+` o conjunto dos números reais positivos e `\mathcal{T}` o conjunto de todos os triângulos. Considere a relação de `\mathbb{R}^+` em `\mathcal{T}` que a cada número real positivo `x` associa o triângulo de área `x`.

Quando nos deparamos com uma função é fundamental identificarmos os conjuntos domínio e contradomínio, e a maneira como os elementos desses conjuntos estão relacionados. Muitas vezes a forma de associação entre os elementos pode ser descrita por palavras, no entanto, principalmente quando os conjuntos envolvidos são numéricos, a lei de associação entre os elementos é dada por uma expressão algébrica. Vejamos alguns exemplos.

`1.` A função de `\mathbb{N}` em `\mathbb{N}` que associa cada número natural `n` à soma de todos os números naturais de `1` até `n`.

.. math::

	f: \mathbb{N} \to \mathbb{N} \quad;\quad f(n)=1+2+...+n=\frac{n(n+1)}{2}.
    

`2.` A função de `\mathbb{Z}` em `\mathbb{Z}` que associa cada número inteiro ao seu dobro pode ser representada por


.. math::

	f: \mathbb{Z} \to \mathbb{Z} \quad;\quad f(x)=2x.

`3.` A função de `\mathbb{R}^+` em `\mathbb{R}` que associa cada número real positivo à sua raíz quadrada.
 
.. math::

	f: \mathbb{R}^+ \to \mathbb{R} \quad;\quad f(x)=\sqrt{x}.
 
`4.` Seja `\mathbb{R}^2=\{ (x,y)\, ;\,x\in\mathbb{R}, y\in\mathbb{R}\}` o conjunto dos pares ordenados de números reais e a função `f` de `\mathbb{R}^+` em `\mathbb{R}` que associa cada par ordenado `(x,y)` a média aritmética de `x` e `y`.

.. math::

	f: \mathbb{R}^2 \to \mathbb{R} \quad;\quad f(x,y)=\frac{x+y}{2}.
 
 
Atividade
---------

Navegando pela internet, um estudante encontrou a seguinte lista de expressões algébricas. 

a) `f(x)=\sqrt{x}`
b) `f(x)=\frac{1}{x}`
c) `f(x)=\frac{1}{\sqrt{x}}`
d) `f(x)=\frac{1}{x+8}`
e) `f(x)=mdc(30,x)` ,  em que `mdc` = maior divisor comum.
f) `f(x)=x^2+5x+1`
g) `f(x)=\sqrt{x-5}`
h) `f(x)=\frac{\sqrt{3x-1}}{2x+9}`

Como estava estudando funções ele resolveu determinar para cada expressão um *domínio*, `A`, e um *contradomínio*, `B`, que a tornasse a lei de associação de uma função `f:A \to B`. Para isso, ele produziu a seguinte tabela:

.. table:: 
   :widths: 3 3 3
   :column-alignment: center center center
   
	+-------------+-----------------------------+---------------------+
	| Expressão   |              A              |          B          |
	+=============+=============================+=====================+
	|     (a)     |        `\mathbb{R}^+`       |     `\mathbb{R}`    |
	+-------------+-----------------------------+---------------------+
	|     (b)     |                             |     `\mathbb{R}`    |
	+-------------+-----------------------------+---------------------+
	|     (c)     |                             |                     |
	+-------------+-----------------------------+---------------------+
	|     (d)     | `\mathbb{R}\setminus \{8\}` |                     |
	+-------------+-----------------------------+---------------------+
	|     (e)     |                             |     `\mathbb{Z}`    |
	+-------------+-----------------------------+---------------------+
	|     (f)     |                             |                     |
	+-------------+-----------------------------+---------------------+
	|     (g)     |                             |    `\mathbb{R}^+`   |
	+-------------+-----------------------------+---------------------+
	|     (h)     |                             |                     |
	+-------------+-----------------------------+---------------------+


.. note:: 

   No código tem uma tabela que não compila de jeito nenhum =[

Ajude o estudante a completar a tabela:


Atividade
---------

Uma placa metálica quadrada é posicionada num sistema de coordenadas cartesiano de acordo com a figura abaixo.


.. tikz::

   \definecolor{cqcqcq}{rgb}{0.7529411764705882,0.7529411764705882,0.7529411764705882}
	\draw [color=cqcqcq,, xstep=1.0cm,ystep=1.0cm] (0,0) grid (11.979044374511444,9.496648594153639);
	\draw[->,color=black] (-0.5881726245274497,0.) -- (11.979044374511444,0.);
	\foreach \x in {,1,2,3,4,5,6,7,8,9,10,11}
	\draw[shift={(\x,0)},color=black] (0pt,2pt) -- (0pt,-2pt) node[below] {\footnotesize $\x$};
	\draw[->,color=black] (0.,-0.42159619430354267) -- (0.,9.496648594153639);
	\foreach \y in {,1,2,3,4,5,6,7,8,9}
	\draw[shift={(0,\y)},color=black] (2pt,0pt) -- (-2pt,0pt) node[left] {\footnotesize $\y$};
	\draw[color=black] (0pt,-10pt) node[right] {\footnotesize $0$};
	\clip(-0.5881726245274497,-0.42159619430354267) rectangle (11.979044374511444,9.496648594153639);
	\fill[color=cqcqcq,fill=cqcqcq,fill opacity=0.8] (2.,0.) -- (10.,0.) -- (10.,8.) -- (2.,8.) -- cycle;
	\draw [color=cqcqcq] (2.,0.)-- (10.,0.);
	\draw [color=cqcqcq] (10.,0.)-- (10.,8.);
	\draw [color=cqcqcq] (10.,8.)-- (2.,8.);
	\draw [color=cqcqcq] (2.,8.)-- (2.,0.);
	\draw (4.438714175088108,7.784057258010101) node[anchor=north west] {$D$};
	\draw (10.04467862073781,8.757400535386644) node[anchor=north west] {$C$};
	\draw (10.056999421717261,0.8474463065797986) node[anchor=north west] {$B$};
	\draw (3.108067669307519,1.8700727878741414) node[anchor=north west] {$A$};
	\draw [fill=black] (10.,8.) circle (3.0pt);
	\draw [fill=black] (5.,7.) circle (3.0pt);
	\draw [fill=black] (10.,0.) circle (3.0pt);
	\draw [fill=black] (3.,1.) circle (3.0pt);


Sabe-se que a temperatura em graus Celsius em cada ponto `(x,y)` da placa é dada pela seguinte função


.. math::

	T:\mathbb{R}^2\setminus\{(0,0)\} \to \mathbb{R} \quad ; \quad T(x,y)=\frac{100}{\sqrt{x^2+y^2}}

a) Determine a temperatura nos pontos `A`, `B`, `C` e `D` indicados na figura.

b) Caminhando ao longo da borda inferior, afastando-se da origem, o que se pode afirmar sobre a temperatura?

Atividade
---------

Temperatura no fio. itens
 
 
 
 
 
 
 
 
 
 


===========
Função Afim
===========

.. admonition:: Pré-requisitos 

	(EF07MT21) Resolver e elaborar problemas que possam ser representados por equações polinomiais de 1º grau, redutíveis à forma `ax+b=0` , iniciando a compreensão da linguagem algébrica.

	(EF09MT17) Resolver e elaborar problemas que envolvam relações de proporcionalidade direta e inversa entre duas ou mais grandezas, inclusive escalas, divisão em partes proporcionais e taxa de variação, em contextos socioculturais, ambientais e de outras áreas.

=================
Função Quadrática
=================

.. admonition:: Pré-requisitos 

	(EF08MT15) Resolver e elaborar problemas que possam ser representados por equações polinomiais de 2º grau do tipo `ax^2=b`.

	(EF09MT18) Compreender os processos de fatoração de expressões algébricas, a partir de suas relações com os produtos notáveis, para resolver e elaborar problemas que possam ser representados por equações polinomiais de 2º grau.
