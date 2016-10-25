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


1. Reproduza a figura no seu caderno e localize a provável posição `E'` do barco que se encontrava inicialmente na posição `E`. Explique cuidadosamente como foi obtida esta posição.
2. Nesta situação o deslocamento de cada um dos barcos é sempre o mesmo e pode ser representado pelas componentes

   x: de oeste para leste e;

   y: do sul para o norte.

Escreva o par `(x,y)` que representa o deslocamento de cada um dos barcos da situação descrita.


Representação algébrica de vetores no plano
---------

.. note::
   Eu sei que já foi discutido, mas eu andei repensando e acho que seria interessante usar uma notação diferente de vetor e de ponto. O Geogebra, por exemplo, usa a notação `\overrightarrow{v}= \binom{x}{y}`. Em princípio isso me pareceu desnecessário, mas pensando melhor, essa notação é usada em muitos livros estrangeiros e usada pelo programa que decidimos associar (mesmo que informalmente) ao livro, que é o Geogebra. A associação `\binom{a}{b}\equiv (a, b)` pode ser feita de forma bastante natural mais tarde. Nem preciso comentar o quanto essa notação ajuda nas transformações que serão vistas posteriormente utilizando matrizes.

Na atividade anterior cada barco foi transladado de 3 km para leste e 4 km para o norte, devido à tempestade. De modo que seu deslocamento resultante pode ser expresso pelo *par ordenado* `(3,4)` uma vez que se estabelece a primeira coordenada como sendo a direção leste-oeste com sentido (para onde cresce) para o leste e segunda coordenada como sendo a direção norte-sul com orientação para o norte.

Do mesmo modo, quando se diz que um avião voa a 700 `Km/h` em direção ao poente. Não se conhece a posição do avião, mas sabe-se que sua velocidade pode ser expressa pelo vetor de coordenadas `\overrightarrow{v} = (-700,0)` com unidade `Km/h`. Sua representação visual é 

.. tikz:: 

   \draw[<-] (0,0) -- (2,0);
   \node at (1,.5) {700 $Km/h$};

e poderá ser usada para representar a velocidade do avião posicionando a origem do vetor na localização atual do avião.

Um vetor fica caracterizado por comprimento, direção e sentido
=====

.. note::
   Nessa subseção deve haver algum espaço para discutir com os alunos o que significa um vetor nulo. Qual sua direção e sentido?

Adição de vetores
=====



Atividade #1
---------

Na malha quadriculada a seguir estão representados os pontos A(1,1), B(4,3) e C(5,7) do plano cartesiano.


.. tikz:: malha quadriculada

   \draw[step=1cm,gray,very thin] (0,0) grid (8.01,8);
   \fill[blue] (1,1) circle (.08);
   \node[right] at (1,1) {$A$};
   \fill[blue] (4,3) circle (.08);
   \node[right] at (4,3) {$B$};
   \fill[blue] (5,7) circle (.08);
   \node[right] at (5,7) {$C$};
 

a) Na mesma malha quadriculada, represente os vetores deslocamentos `\overrightarrow{AB}` e `\overrightarrow{BC}`.
b) Determine as coordenadas dos vetores deslocamentos `\overrightarrow{AB}` e `\overrightarrow{BC}`.
c) Represente agora o vetor deslocamento `\overrightarrow{AC}` e determine as suas coordenadas.
d) Como podemos determinar as cordenadas do vetor `\overrightarrow{AC}` a partir das coordenadas dos vetores `\overrightarrow{AB}` e `\overrightarrow{BC}`? Que relação você observa entre as coordenadas desses três vetores?



.. note::
   Na atividade anterior, dizemos que o vetor `\overrightarrow{AC}` representa o deslocamento final, do ponto A até o onto C, resultante dos deslocamentos parciais e consecutivos `\overrightarrow{AB}`, de A até B, e `\overrightarrow{BC}`, de B até C. Neste caso, dizemos que o vetor `\overrightarrow{AC}` é a adição dos vetores deslocamentos `\overrightarrow{AB}` e `\overrightarrow{BC}`, isto é: `\overrightarrow{AC}` = `\overrightarrow{AB} + \overrightarrow{BC}`.

Atividade #2
---------

Observe agora a representação dos pontos D(2,3), E(7,2) e F(4,7) do plano cartesiano.


.. tikz:: malha quadriculada

   \draw[step=1cm,gray,very thin] (0,0) grid (8.01,8);
   \fill[blue] (2,3) circle (.08);
   \node[right] at (2,3) {$D$};
   \fill[blue] (7,2) circle (.08);
   \node[right] at (7,2) {$E$};
   \fill[blue] (4,7) circle (.08);
   \node[right] at (4,7) {$F$};
 

a) Represente os vetores deslocamentos `\overrightarrow{DE}` e `\overrightarrow{EF}` na mesma malha quadriculada e determine as suas coordenadas.
b) Represente agora o vetor deslocamento `\overrightarrow{DF}` e determine as suas coordenadas.
c) Como podemos determinar as cordenadas do vetor `\overrightarrow{DF}` a partir das coordenadas dos vetores `\overrightarrow{DE}` e `\overrightarrow{EF}`? A relação que você observou entre as coordenadas do **vetor** **deslocamento final** e as coordenadas dos **vetores deslocamentos parciais** se manteve?

Atividade #3
---------
Com o objetivo de ver mais exemplos similares aos das atividades  1 e 2, faça agora a atividade digital no link a seguir. Antes porém, cabe adotar uma notação mais simplificada para os vetores. Representaremos os vetores  `\overrightarrow{AB}`, `\overrightarrow{BC}` e `\overrightarrow{AC}`, respectivamente, por `\overrightarrow{u}`, `\overrightarrow{v}` e `\overrightarrow{w}`, sendo:

* `x_{u}` e `y_{u}` as coordenadas do vetor `\overrightarrow{u}`;
* `x_{v}` e `y_{v}` as coordenadas do vetor `\overrightarrow{v}`;
* `x_{w}` e `y_{w}` as coordenadas do vetor `\overrightarrow{w}`.



https://www.geogebra.org/m/mwBjY5xN



Atividade #4 (Regra do paralelogramo)
---------
Um bloco está sendo puxado ao longo de uma mesa lisa em duas direções distintas, conforme ilustrado na figura a seguir.

# colocar figura #

A força resultante, `\overrightarrow{R}`, é a adição dos vetores `\overrightarrow{F_{1}}` e `\overrightarrow{F_{2}}`, isto é, `\overrightarrow{R} = \overrightarrow{F_{1}}+\overrightarrow{F_{2}}`.

Na figura a seguir temos representados os dois vetores `\overrightarrow{F_{1}}` e `\overrightarrow{F_{2}}`. Considere como unidade de comprimento a medida do lado de cada quadradinho da malha. 

# colocar figura #

.. tikz:: malha quadriculada 

   \draw[step=1cm,gray,very thin] (0,0) grid (8.01,6);
   \node[right] at (1,3) {$\overrightarrow{F_{2}}$};
   \node[right] at (3,1) {$\overrightarrow{F_{1}}$};
   \draw[->, thick, red] (1,1) -- (3,4);
   \draw[->, thick, blue] (1,1) -- (5,2);
   

a) Determine as coordenadas dos vetores `\overrightarrow{F_{1}}` e `\overrightarrow{F_{2}}`.
b) Construa, na mesma malha da figura anterior, o vetor `\overrightarrow{F_{2}}` tendo como origem a extremidade do vetor `\overrightarrow{F_{1}}`.
c) Represente o vetor `\overrightarrow{F_{1}}+\overrightarrow{F_{2}}` e determine suas coordenadas.
d) Agora, construa, ainda na mesma malha, o vetor `\overrightarrow{F_{1}}` tendo como origem a extremidade do vetor `\overrightarrow{F_{2}}`.
e) Represente o vetor `\overrightarrow{F_{2}}+\overrightarrow{F_{1}}` e determine suas coordenadas.
f) O que pode ser afirmado sobre os vetores obtidos nos itens (c) e (e)? Eles são iguais? Justifique sua resposta.

.. note::
   Na atividade anterior, dizemos que o vetor `\overrightarrow{R} = \overrightarrow{F_{1}}+\overrightarrow{F_{2}} = \overrightarrow{F_{2}}+\overrightarrow{F_{1}}` é a soma dos dos vetores  `\overrightarrow{F_{1}}` e `\overrightarrow{F_{2}}`. Observe que o vetor `\overrightarrow{R}` é dado pela diagonal do paralegramo cujos lados não paralelos são formados pelos vetores `\overrightarrow{F_{1}}` e `\overrightarrow{F_{2}}`. 
   
   De modo geral, dados dois vetores `\overrightarrow{u}` e `\overrightarrow{v}` que não possuem a mesma direção, a soma dos dois vetores é dado pela diagonal do paralegramo cujos lados não paralelos são formados pelos vetores `\overrightarrow{u}` e `\overrightarrow{v}`. Este resultado é conhecido como a *Regra do Paralelogramo*.
   
  


