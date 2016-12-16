***********
A Representação algébrica de vetores no plano
***********

Nos exemplos e atividades anteriores você deve ter observado que quando fixamos uma malha em um plano, um vetor fica representado por dois números, `x` e `y`, que são chamados as *coordenadas do vetor* naquela malha.
Assim, na situação acima os vetores `\overrightarrow{AB}` e `\overrightarrow{XY}` têm coordenadas `x=2` e `y=3`. Isto significa que este vetor é do tipo 2 para a direita e 3 para cima seguindo as linhas da malha.

.. admonition:: Notação 
   
   Usaremos a notação 
   
   .. math::

      \overrightarrow{v} = \binom{x}{y} 
   
   para representar o vetor do tipo `x` para a direita e `y` para cima.
   
Por exemplo, o vetor `\overrightarrow{AB} = \binom{2}{3}` e os vetores da :ref:`my-ativ-barcos` são todos iguais a `\overrightarrow{AA'} = \binom{3}{4}`.

Atividade
-----------

Determine as coordenadas dos vetores na malha abaixo.

.. tikz:: Aumentar a malha e incluir diversos vetores.

	\draw[step=1cm,gray,very thin] (-3,-1) grid (1,2);
	\draw[-latex, thick, red] (0,0) -- (-2,1);
    \fill[blue] (0,0) circle (.08);
    \node[right] at (0,0) {$A$};
    \fill[blue] (-2,1) circle (.08);
    \node[left] at (-2,1) {$B$};
    
Atividade
----------

Dadas as coordenadas, determinar uma representação do vetor.


Atividade
-----

Represente o vetor deslocamento usando coordenadas sabendo que em cada uma das situações o movimento saiu de `A`, passou em `B`, depois em `C` e terminou em `D`.
Considere o lado de um quadradinho da malha como sendo uma unidade.

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
      \draw[-latex, thick, red] (0,0) -- (.5,1.5);
      \draw[-latex, thick, red] (.5,1.5) -- (1.5,-1);
      \draw[-latex, thick, red] (1.5,-1) -- (2,1);
      
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
    
      
Atividade
------
Outro uso importante dos vetores na Física é a representação de forças. Alguns exemplos são ilustrados nos itens a seguir:
   
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
      
#. A escaladora da figura usa um grampo simples para sua segurança. Para maior segurança costuma-se prender dois grampos próximo ao topo da rocha. Em qual das situações a seguir a corda fica mais tensionada próximo aos grampos?   
#. Faça um esquema de forças similar ao apresentado para a corda que auxilie a justificativa da sua escolha no item a).
#. Justifique a sua escolha do item a) utilizando vetores.

.. Fim edição Fabio e início de Wanderley
