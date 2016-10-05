********
Volume 1 - Coleção do Ensino Médio - Livro Aberto de Matemática - Geometria
********

Contents:

.. toctree::
   :maxdepth: 1
   :glob:

   *

********
Vetores no plano
********


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


1. Reproduza a figura no seu caderno e localize a provável posição `E'` do barco que se encontrava na posição `E` inicialmente. Explique cuidadosamente como foi obtida esta posição.
2. Nesta situação o deslocamento de cada um dos barcos é sempre o mesmo e pode ser representado pelas componentes

   x: de oeste para leste e;

   y: do sul para o norte.

   Escreva o par `(x,y)` que representa o deslocamento de cada um dos barcos da situação descrita.


Representação algébrica de vetores no plano
---------

Na atividade anterior cada barco foi transladado de 3 km para oeste e 4 km para o norte, devido à tempestade. De modo que seu deslocamento resultante pode ser expresso pelo *par ordenado* `(3,4)`.

Do mesmo modo, quando se diz que um avião voa a 700 `Km/h` em direção ao poente. Não se sabe a posição do avião, mas sabe-se que sua velocidade pode ser expressa pelo vetor de coordenadas `\overrightarrow{v} = (-700,0)` com unidade `Km/h`. Sua representação visual é 

.. tikz:: 

   \draw[<-] (0,0) -- (2,0);
   \node at (1,.5) {700 $Km/h$};

e poderá ser usada para representar a velocidade do avião posicionando a origem do vetor na localização atual do avião.

Um vetor fica caracterizado por comprimento, direção e sentido
=====



Adição de vetores
=====



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


********
Transformações isométricas no plano
********

********
Teorema de Tales, semelhança e aplicações
********
