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
   
   Roteiro do capítulo:
   
   1. Texto com o objetivo de despertar a existência de grandezas vetorias. Utilizar mapas de sites de previsão do tempo contendo a velocidade do vento apresentada por meio da velocidade escalar e da direção (por exemplo, NNE). [Marcos Paulo]
   2. **Escrever para o professor** que quando fixamos um reticulado estamos estabelecendo um par de vetores linearmente independentes no plano sem fixar a origem do sistema de coordenadas porque, na verdade, a descrição dos vetores independe da posição da origem. A origem se faz necessária quando buscamos a posição do objeto. Definir vetor para o professor como um conjunto de segmentos orientados que possuem mesmo módulo direção e sentido, explicar que essa definição será omitida do estudante porque a sua apresentação não trará ganho de compreensão e soa excessivamente abstrata para a maioria dos estudantes na opinião dos autores. Observar que os vetores não dependem de coordenadas.  Que módulo, direção e sentido representam, na verdade, duas informações e não três (porque o módulo e sentido juntos representam uma grandeza escalar quando usamos o sinal do número). [Simas]
   3. Atividade sobre deslocamento para observar que a representação algébrica não depende da origem do sistema de coordenadas (barcos) [Simas]
   4. Atividades análogas com diferentes malhas (diferentes bases do sistema, independente da origem do sistema de coordenadas) (porque é libertador e dá noção de bidimensionalidade). [Marcos Paulo]
   5. **Sistematização:** Afirmação de que um vetor fica caracterizado pelo conhecimento do módulo, direção e sentido (ou que dois vetores são iguais quando possuem essas três características iguais). Sistematização do sistema de coordenadas, observando que a representação dos vetores não dependem da origem, mas apenas da escolha de dois vetores **linearmente independentes** (definição da malha). [Simas]
   6. Atividade ou exemplo com representação polar. [Marcos Paulo]
   7. Observar para o aluno que seja qual for o sistema de coordenadas considerado, serão necessárias duas informações `(x,y)` ou `(r, \theta)`. Isso porque são vetores bidimensionais, são representados no plano. Observar para fins de comparação que existe análogo no espaço, então precisamos de três coordenadas. [Marcos Paulo]
   8. Soma de vetores com representação visual e algébrica. [Wanderley]
   9. Exercícios e exercícios suplementares. [Todos]
   
   
.. admonition:: Para o professor

   Nesta lição supõe-se que o estudante já teve contato com vetores como representação visual das grandezas físicas força e velocidade. Espera-se também que ele consiga marcar pontos no plano cartesiano.

   .. admonition:: Definição
   
      Um vetor é o conjunto de todos os segmentos orientados com mesmo módulo, direção e sentido (ou seja, é uma classe de equivalência de segmentos orientados equipolentes (e.g., \ref{Elon Lima, Coordenadas no Plano}, p. X).

   Este livro não apresenta para o estudante uma definição de vetor.
   
   Ela é abstrata e mesmo sem esta definição,  com uma abordagem mais natural, o estudante pode adquirir uma ideia bastante clara do que é um vetor. 
   
   Para ele fica que um vetor é um segmento orientado que é determinado por seu módulo, direção e sentido, mas que pode ter sua origem em qualquer ponto do plano. 
   
   Embora esta não seja a nossa proposta, caso o professor decida por uma abordagem mais completa do ponto de vista matemático, sugere-se que esta definição venha após a construção do conceito pelo aluno.
   
   Pode-se pedir que eles escrevam uma definição e leiam em voz alta, assim o professor pode encontrar fragilidades e encaminhar para a definição precisa.
   
   O texto introdutório para o estudante busca mostrar que existem grandezas que não ficam claramente representadas por apenas um número. 
   
   É necessário conhecer também outras informações para um entendimento mais completo. 
   Em seguida procura-se observar através do conceito de *deslocamento* que, uma vez fixada uma malha (que equivale a fixar um par de vetores não paralelos, ou seja, uma base para o plano), pode-se representar um vetor do plano através de dois números (as componentes ou coordenadas do vetor nesta base) e que estes números não dependem da escolha da origem do sistema de coordenadas. 
   Assim, dois vetores com mesmo módulo, direção e sentido serão iguais.
   
   São brevemente apresentadas coordenadas oblíquas e polares para que o estudante sinta-se livre para buscar outro sistema de coordenadas caso o cartesiano ortogonal não lhe pareça o mais adequado em alguma situação, embora esta não seja a ênfase .
   Além disso, o conhecimento de outros sistemas de coordenadas deve despertar para a relação entre o número de coordenadas de um vetor e a dimensão do espaço em que ele está inserido.
   
   Neste aspecto, cabe ressaltar que embora um vetor fique determinado por módulo, direção e sentido, não são necessárias três informações para se conhecer um vetor do plano, bastam duas pois o plano é bidimensional. 
   Provavelmente, por isso, alguns livros estrangeiros (e.g., ref e ref), usam apenas comprimento e sentido, endendendo a direção como derivada do sentido.
   
   Também são apresentadas as operações de soma de vetores e multiplicação de vetor por escalar (será melhorado assim que tivermos o texto).
   
------------
Apresentação
------------

As diversas ciências utilizam-se de modelos matemáticos para representar os fenômenos que desejam descrever. As ideias de intensidade, medida e quantidade, além de outros, são agrupados no conceito de *grandeza*.

Chama-se *grandeza escalar*, aquela que se pode representar por um número real. São exemplos de grandezas escalares a temperatura, massa e as variações. Note que podemos nos expressar com exatidão sobre esses conceitos apresentando apenas um número seguido da unidade de medida convencionada.

.. admonition:: Exemplos 

   1) A temperatura máxima atingida em uma cidade foi de `23^\circ C`
   2) A mochila do aluno pesa (no sentido de ter massa igual a) 6,7 Kg.
   3) A temperatura variou em `3^\circ C` *para menos* 

Vale ressaltar que o exemplo da variação de temperatura necessitou da informação do *sentido* dessa variação. Por exemplo, se a tempoeratura anterior era de `23^\circ C` e houve uma variação de `3^\circ C`, não é poss[ivel saber se a temperatura atual é de `20^\circ C` ou de `26^\circ C`. Por outro lado, se informamos que houve uma variação de `-3^\circ C`, não resta dúvidas quanto a teperatura atual, sabendo a anterior.

Neste capítulo, trataremos de grandezas que não podem ser expressas apenas por um número real. Será necessário mais do que um número 
   
   
Não importa a origem (apresentação das componentes de um vetor)
=====


Atividade 1
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

Atividade 2
-------
Nas situações a seguir reproduz as figuras em seu caderno e represente o vetor deslocamento do ponto `A` para o ponto `D`, levando em consideração que o objeto passou por `A`, `B`, `C` e finalmente chegou em `D`, respectivamente.

.. tikz::
       
       \node at (-.5,1.3) {a)};
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
      
      \begin{scope}[shift={(4.5cm,.25)}]
      \node at (-.5,1.05) {b)};
      \fill[blue] (0,0) circle (.08);
      \node[above] at (0,0) {$B$};
      \fill[blue] (1,0) circle (.08);
      \node[above] at (1,0) {$A$};
      \fill[blue] (2,0) circle (.08);
      \node[above] at (2,0) {$C$};
      \fill[blue] (1,-1) circle (.08);
      \node[right] at (1,-1) {$D$};
      
      \begin{scope}[shift={(4.5cm,-.5)}]
      \node at (-.5,1.55) {c)};
      \fill[blue] (0,0) circle (.08);
      \node[below] at (0,0) {$A=D$};
      \fill[blue] (2,0) circle (.08);
      \node[below] at (2,0) {$B$};
      \fill[blue] (1,1.5) circle (.08);
      \node[right] at (1,1.5) {$C$};
      \end{scope}
      \end{scope}
    

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

Atividade 3
-----

Represente o deslocamento de `A` para `D` usando coordenadas. Considere o lado de um quadradinho da malha como sendo uma unidade.




.. tikz::
       
       \node at (-.5,1.3) {a)};
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
      
      \begin{scope}[shift={(4.5cm,.25)}]
      \node at (-.5,1.05) {b)};
      \draw[step=.5cm, color=gray, very thin] (0,-1.01) grid (2.01,1);
      \fill[blue] (0,0) circle (.08);
      \node[above] at (0,0) {$B$};
      \fill[blue] (1,0) circle (.08);
      \node[above] at (1,0) {$A$};
      \fill[blue] (2,0) circle (.08);
      \node[above] at (2,0) {$C$};
      \fill[blue] (1,-1) circle (.08);
      \node[right] at (1,-1) {$D$};
      
      \begin{scope}[shift={(4.5cm,-.5)}]
      \node at (-.5,1.55) {c)};
      \draw[step=.5cm, color=gray, very thin] (0,-0.51) grid (2.01,1.51);
      \fill[blue] (0,0) circle (.08);
      \node[below] at (0,0) {$A=D$};
      \fill[blue] (2,0) circle (.08);
      \node[below] at (2,0) {$B$};
      \fill[blue] (1,1.5) circle (.08);
      \node[right] at (1,1.5) {$C$};
      \end{scope}
      \end{scope}
    
      
Atividade 4
------
Outro uso importante dos vetores na Física é a representação de forças. Alguns exemplos são ilustrados nos itens a seguir:

a) A escaladora da figura usa um grampo simples para sua segurança. Para maior segurança costuma-se prender dois grampos próximo ao topo da rocha. Em qual das situações a seguir a corda fica mais tensionada próximo aos grampos?

   .. figure:: https://upload.wikimedia.org/wikipedia/commons/d/d8/Free_climbing_20060701.jpg
            :align: center
            :width: 200px
            
            foto: Elke Wetzig
   
   .. tikz::

      \node at (-1.5,-.3) {(I)};
      \fill[blue] (0,0) circle (.08);
      \fill[blue] (160:1.5) circle (.08);
      \node[above] at (160:1.5) {\small Grampo 1};
      \fill[blue] (20:1.5) circle (.08);
      \node[above] at (20:1.5) {\small Grampo 2};
      \fill[blue] (270:1.5) circle (.08);
      \node[below] at (270:1.5) {\small Escalador};
      \draw[very thick, red] (0,0) -- (160:1.5);
      \draw[very thick, red] (0,0) -- (20:1.5);
      \draw[very thick, red] (0,0) -- (270:1.5);
      
      
      \begin{scope}[xshift=5cm]
      \node at (-1.5,-.3) {(II)};
      \fill[blue] (0,0) circle (.08);
      \fill[blue] (135:1.5) circle (.08);
      \node[above] at (135:1.5) {\small Grampo 1};
      \fill[blue] (45:1.5) circle (.08);
      \node[above] at (45:1.5) {\small Grampo 2};
      \fill[blue] (270:1.5) circle (.08);
      \node[below] at (270:1.5) {\small Escalador};
      \draw[very thick, red] (0,0) -- (135:1.5);
      \draw[very thick, red] (0,0) -- (45:1.5);
      \draw[very thick, red] (0,0) -- (270:1.5);
      
      
      \begin{scope}[xshift=5cm]
      \node at (-1.5,-.3) {(III)};
      \fill[blue] (0,0) circle (.08);
      \fill[blue] (120:1.5) circle (.08);
      \node[above] at (130:1.7) {\small Grampo 1};
      \fill[blue] (60:1.5) circle (.08);
      \node[above] at (50:1.7) {\small Grampo 2};
      \fill[blue] (270:1.5) circle (.08);
      \node[below] at (270:1.5) {\small Escalador};
      \draw[very thick, red] (0,0) -- (120:1.5);
      \draw[very thick, red] (0,0) -- (60:1.5);
      \draw[very thick, red] (0,0) -- (270:1.5);
      \end{scope}
      \end{scope}

b) Faça um esquema de forças similar ao apresentado para a corda que auxilie a justificativa da sua escolha no item a).

c) Justifique a sua escolha do item a) utilizando vetores.


Um vetor fica caracterizado por comprimento, direção e sentido
=====

.. note::
   Nessa subseção deve haver algum espaço para discutir com os alunos o que significa um vetor nulo. Qual sua direção e sentido?

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

