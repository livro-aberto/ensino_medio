****************
Vetores no plano
****************


.. note::

   BNCC(EM11MT01) Compreender o conceito de vetor, tanto do ponto de vista geométrico (coleção de segmentos orientados de mesmo comprimento, direção e sentido) quanto do ponto de vista algébrico, caracterizado por suas coordenadas, aplicando-o em situações da Física.
   
   BNCC(EM13MT02) Estabelecer relações entre as transformações isométricas (reflexão, translação e rotação) e vetores no contexto do plano cartesiano, incluindo o uso de softwares de geometria dinâmica.

   Objetivos adicionais:
   
   1. Despertar para a existência de grandezas vetoriais.
   2. Usar as operações com vetores em situações concretas (cálculo da força resultante, soma de velocidades, deslocamento final, etc.) e suas representações algébricas.
   3. Reconhecer a diferença entre ponto e vetor, embora possam ser representados por mesmas coordenadas.
   4. Reconhecer vetores e suas principais propriedades (quais?) utilizando tanto as coordenadas quanto sua representação visual.
   

Não importa a origem (introdução às coordenadas)
=====


Atividade
---------

Cinco veleiros similares estavam nas posições `A`, `B`, `C`, `D` e `E`, representadas na figura. Após uma tempestade quatro deles conseguiram se comunicar com a guarda costeira e informaram suas novas posições `A'`, `B'`, `C'` e `D'`, respectivamente. A guarda costeira pretende enviar uma equipe de busca para o quinto barco.

.. tikz:: Deslocamento dos barcos devido à tempestade

   \draw[step=1cm,gray,very thin] (0,0) grid (8.01,8);
   \fill[blue] (0,1) circle (.08);
   \node[right] at (0,1) {$A$};
   \fill[blue] (2,0) circle (.08);
   \node[right] at (2,0) {$B$};
   \fill[blue] (3,4) circle (.08);
   \node[right] at (3,4) {$C$};
   \fill[blue] (1,3) circle (.08);
   \node[right] at (1,3) {$D$};
   \fill[blue] (3,5) circle (.08);
   \node[right] at (3,5) {$A'$};
   \fill[blue] (5,4) circle (.08);
   \node[right] at (5,4) {$B'$};
   \fill[blue] (6,8) circle (.08);
   \node[right] at (6,8) {$C'$};
   \fill[blue] (4,7) circle (.08);
   \node[right] at (4,7) {$D'$};
   \draw[->, thick, red] (0,1) -- (3,5);
   \draw[->, thick, red] (2,0) -- (5,4);
   \draw[->, thick, red] (3,4) -- (6,8);
   \draw[->, thick, red] (1,3) -- (4,7);
   \fill[blue] (5,2) circle (.08);
   \node[right] at (5,2) {$E$};
   \draw[|-|] (7,-.5) -- (8,-.5);
   \node at (7.5,-.8) {1 Km};
   \draw[->] (0,-1.1) -- (1,-1.1) node[right] {\small (E) leste};
   \draw[->] (0.5,-1.6) -- (0.5,-.6) node[above] {\small (N) norte};
   .. align:: center

1. Reproduza a figura no seu caderno e localize a provável posição `E'` do barco que se encontrava inicialmente na posição `E`. Explique cuidadosamente como foi obtida esta posição.
2. Na situação descrita o deslocamento dos barcos é o mesmo e pode ser representado pelas componentes

   x: de oeste para leste e;

   y: do sul para o norte.

   Escreva o par ordenado `\binom{x}{y}` que representa o deslocamento de cada um dos barcos.

O conceito de *deslocamento* vem da física e significa a variação da posição de determinado objeto. Este é um exemplo de grandeza vetorial (que possui módulo, direção e sentido). Observe que na situação acima os barcos tiveram mesmo deslocamento apesar de possuirem posições iniciais e finais diferentes.

Atividade
-------
Nas situações a seguir reproduz as figuras em seu caderno e represente o vetor deslocamento do ponto `A` para o ponto `D`, levando em consideração que o objeto passou por `A`, `B`, `C` e finalmente chegou em `D`, respectivamente.

a)

.. tikz::

      \fill[blue] (0,0) circle (.08);
      \node[right] at (0,0) {$A$};
      \fill[blue] (.5,1.5) circle (.08);
      \node[right] at (0.5,1.5) {$B$};
      \fill[blue] (1.5,-1) circle (.08);
      \node[right] at (1.5,-1) {$C$};
      \fill[blue] (2,1) circle (.08);
      \node[right] at (2,1) {$D$};
      \draw[->, thick, red] (0,0) -- (.5,1.5);
      \draw[->, thick, red] (.5,1.5) -- (1.5,-1);
      \draw[->, thick, red] (1.5,-1) -- (2,1);

b) 

.. tikz::

      \fill[blue] (0,0) circle (.08);
      \node[above] at (0,0) {$B$};
      \fill[blue] (1,0) circle (.08);
      \node[above] at (1,0) {$A$};
      \fill[blue] (2,0) circle (.08);
      \node[above] at (2,0) {$C$};
      \fill[blue] (1,-1) circle (.08);
      \node[right] at (1,-1) {$D$};

c)

.. tikz::

      \fill[blue] (0,0) circle (.08);
      \node[below] at (0,0) {$A=D$};
      \fill[blue] (2,0) circle (.08);
      \node[below] at (2,0) {$B$};
      \fill[blue] (1,1.2) circle (.08);
      \node[right] at (1,1.2) {$C$};
    

Representação algébrica de vetores no plano
---------

.. note::
   Eu sei que já foi discutido, mas eu andei repensando e acho que seria interessante usar uma notação diferente de vetor e de ponto. O Geogebra, por exemplo, usa a notação `\overrightarrow{v}= \binom{x}{y}`. Em princípio isso me pareceu desnecessário, mas pensando melhor, essa notação é usada em muitos livros estrangeiros e usada pelo programa que decidimos associar (mesmo que informalmente) ao livro, que é o Geogebra. A associação `\binom{a}{b}\equiv (a, b)` pode ser feita de forma bastante natural mais tarde. Nem preciso comentar o quanto essa notação ajuda nas transformações que serão vistas posteriormente utilizando matrizes.

Na atividade anterior cada barco foi transladado de 3 km para leste e 4 km para o norte, devido à tempestade. De modo que seu deslocamento resultante pode ser expresso pelo *par ordenado* `\binom{3}{4}` uma vez que se estabelece a primeira coordenada como sendo a direção leste-oeste com sentido (para onde cresce) para o leste e segunda coordenada como sendo a direção norte-sul com orientação para o norte.

Do mesmo modo, quando se diz que um avião voa a 700 `Km/h` em direção ao poente. Não se conhece a posição do avião, mas sabe-se que sua velocidade pode ser expressa pelo vetor de coordenadas `\overrightarrow{v} = \binom{-700}{0}` com unidade `Km/h`. Sua representação visual é 

.. tikz:: 

   \draw[<-] (0,0) -- (2,0);
   \node at (1,.5) {700 $Km/h$};

e poderá ser usada para representar a velocidade do avião posicionando a origem do vetor na localização atual do avião.

Atividade
-----

Represente o deslocamento de `A` para `D` usando coordenadas. Considere o lado de um quadradinho da malha como sendo uma unidade.


a)

.. tikz::

       \draw[step=.5cm, color=gray, very thin] (0,-1.01) grid (2.01,1.51);
      \fill[blue] (0,0) circle (.08);
      \node[right] at (0,0) {$A$};
      \fill[blue] (.5,1.5) circle (.08);
      \node[right] at (0.5,1.5) {$B$};
      \fill[blue] (1.5,-1) circle (.08);
      \node[right] at (1.5,-1) {$C$};
      \fill[blue] (2,1) circle (.08);
      \node[right] at (2,1) {$D$};
      \draw[->, thick, red] (0,0) -- (.5,1.5);
      \draw[->, thick, red] (.5,1.5) -- (1.5,-1);
      \draw[->, thick, red] (1.5,-1) -- (2,1);

b) 

.. tikz::
      
      \draw[step=.5cm, color=gray, very thin] (0,-1.01) grid (2.01,1);
      \fill[blue] (0,0) circle (.08);
      \node[above] at (0,0) {$B$};
      \fill[blue] (1,0) circle (.08);
      \node[above] at (1,0) {$A$};
      \fill[blue] (2,0) circle (.08);
      \node[above] at (2,0) {$C$};
      \fill[blue] (1,-1) circle (.08);
      \node[right] at (1,-1) {$D$};

c)

.. tikz::

      \draw[step=.5cm, color=gray, very thin] (0,-0.51) grid (2.01,1.51);
      \fill[blue] (0,0) circle (.08);
      \node[below] at (0,0) {$A=D$};
      \fill[blue] (2,0) circle (.08);
      \node[below] at (2,0) {$B$};
      \fill[blue] (1,1.5) circle (.08);
      \node[right] at (1,1.5) {$C$};
      
Atividade
------
Outro uso importante dos vetores na Física é a representação de forças. Alguns exemplos são ilustrados nos itens a seguir:

1. A escaladora da figura usa um grampo simples para sua segurança. Para maior segurança costuma-se prender dois grampos próximo ao topo da rocha. Em qual das situações a seguir a corda fica mais tensionada próximo aos grampos?

.. figure:: https://upload.wikimedia.org/wikipedia/commons/d/d8/Free_climbing_20060701.jpg
            :align: center
            :width: 200px
   
.. tikz::

      \node at (0,-.5) {$a)$};
      \fill[blue] (0,0) circle (.08);
      \node[above] at (0,0) {\small Grampo 1};
      \fill[blue] (2,0) circle (.08);
      \node[above] at (2,0) {\small Grampo 2};
      \fill[blue] (1,-1) circle (.08);
      \draw[very thick, red] (0,0) -- (1,-1);
      \draw[very thick, red] (2,0) -- (1,-1);
      \draw[very thick, red] (1,-1) -- (1,-2);
      \fill[blue] (1,-2) circle (.08);
      \node[below] at (1,-2) {\small Escalador};
      
      \begin{scope}[xshift=4cm]
      \node at (0,-.5) {$b)$};
      \fill[blue] (0,0) circle (.08);
      \node[above] at (0,0) {\small Grampo 1};
      \fill[blue] (2,0) circle (.08);
      \node[above] at (2,0) {\small Grampo 2};
      \fill[blue] (1,-1) circle (.08);
      \draw[very thick, red] (0,0) -- (1,-1);
      \draw[very thick, red] (2,0) -- (1,-1);
      \draw[very thick, red] (1,-1) -- (1,-2);
      \fill[blue] (1,-2) circle (.08);
      \node[below] at (1,-2) {\small Escalador};
      \end{scope}

Um vetor fica caracterizado por comprimento, direção e sentido
=====

.. note::
   Nessa subseção deve haver algum espaço para discutir com os alunos o que significa um vetor nulo. Qual sua direção e sentido?

Adição de vetores
=====

a

Atividade
---------

Atividade #

Na malha quadriculada a seguir estão representados os pontos A(1,1), B(4,3) e C(5,7) do plano cartesiano.


## desenho da malha ##

a) Na mesma malha quadriculada, represente os vetores deslocamentos `\overrightarrow{AB}` e `\overrightarrow{BC}`.
b) Determine as coordenadas dos vetores deslocamentos `\overrightarrow{AB}` e `\overrightarrow{BC}`.
c) Represente agora o vetor deslocamento `\overrightarrow{AC}` e determine as suas coordenadas.
d) Como podemos determinar as cordenadas do vetor `\overrightarrow{AC}` a partir das coordenadas dos vetores `\overrightarrow{AB}` e `\overrightarrow{BC}`? Que relação você observa entre as coordenadas desses três vetores?

.. note::

  Definir AC por AB + BC

