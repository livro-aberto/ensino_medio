.. _sec-vetores-aprofund:

***************
Aprofundamentos
***************

O que se quer dizer precisamente com *sentido* de um segmento orientado?

Toda reta tem dois *sentidos*: fixando os pontos `A` e `B` na reta, temos o sentido `AB` (de `A` para `B`) e sentido `BA` (de `B` para `A`). Considere dois segmentos orientados `AB` e `CD` de mesma direção. Se ambos estão sobre a mesma reta dizemos que possuem *mesmo sentido* quando ambos determinam o mesmo sentido da reta. Se os segmentos orientados `AB` e `CD` estão em retas paralelas, dizemos que possuem mesmo sentido quando os pontos `B` e `D` pertencem à mesma região determinada pela reta `AC` (veja a figura).  

.. tikz:: 

   \draw (0,0)--(3,3);
   \node at (-.3,0) {$r$};
   \fill[blue] (1,1) circle (.08);
   \node[below] at (1,1) {$A$};
   \fill[blue] (2,2) circle (.08);
   \node[below] at (2,2) {$B$};
   \draw[very thick, red, -latex] (1,1)--(2,2);
   \draw[green, very thick] (0,1)--(4,1);
   \node at (1.5,-.6) {Mesmo sentido};
      
   \begin{scope}[xshift=1.5cm]
   \draw (0,0)--(3,3);
   \node at (-.3,0) {$s$};
   \fill[blue] (1,1) circle (.08);
   \node[below] at (1,1) {$C$};
   \fill[blue] (2,2) circle (.08);
   \node[below] at (2,2) {$D$};
   \draw[very thick, red, -latex] (1,1)--(2,2);
   \end{scope}
   
   \begin{scope}[xshift=5cm]
   \draw (0,0)--(3,3);
   \node at (-.3,0) {$r$};
   \fill[blue] (1,1) circle (.08);
   \node[below] at (1,1) {$A$};
   \fill[blue] (2,2) circle (.08);
   \node[below] at (2,2) {$B$};
   \draw[very thick, red, -latex] (1,1)--(2,2);
   \draw[green, very thick, domain=0:4.6] plot (\x, {0.4*\x+.6});
   \node at (1.5,-.6) {Sentidos contrários};
      
   \begin{scope}[xshift=1.5cm]
   \draw (0,0)--(3,3);
   \node at (-.3,0) {$s$};
   \fill[blue] (1,1) circle (.08);
   \node[below] at (1,1) {$D$};
   \fill[blue] (2,2) circle (.08);
   \node[below] at (2,2) {$C$};
   \draw[very thick, red, latex-] (1,1)--(2,2);
   \end{scope}
   \end{scope}

.. _sec-vetores-aprofund-operacoes:

Propriedades da operação de adição de vetores
=============================================

Enunciaremos a seguir algumas propriedades da operação de vetores no plano. Cabe destacar, entretanto, que essas propriedades também são válidas para vetores no espaço.

**a) Comutativa**

Dados dois vetores `\overrightarrow{u}` e `\overrightarrow{v}` no plano, `\overrightarrow{u} + \overrightarrow{v} = \overrightarrow{v}+\overrightarrow{u}`

.. note:: 
   .. math::
   
      \overrightarrow{u}+\overrightarrow{v}=\binom{x_{u}}{y_{u}}+\binom{x_{v}}{y_{v}}=\binom{x_{u}+x_{v}}{y_{u}+y_{v}}=\binom{x_{v}+x_{u}}{y_{v}+y_{u}}=\binom{x_{v}}{y_{v}}+\binom{x_{u}}{y_{u}}=\overrightarrow{v}+\overrightarrow{u}

Em verdade, essa propriedade já havia sido verificada quando a Regra do Paralelogramo foi apresentada na Atividade (4).

**b) Associativa**

Dados três vetores `\overrightarrow{u}`, `\overrightarrow{v}` e `\overrightarrow{w}` no plano, `(\overrightarrow{u} + \overrightarrow{v})+ \overrightarrow{w}= \overrightarrow{u}+(\overrightarrow{v}+\overrightarrow{w})`

.. note:: 
   .. math::
   
      (\overrightarrow{u} + \overrightarrow{v}) + \overrightarrow{w} = \binom{x_{u}+x_{v}}{y_{u}+y_{v}}   + \binom{x_{w}}{y_{w}} = \binom{(x_{u}+x_{v})+x_{w}}{(y_{u}+y_{v})+y_{w}} = \binom{x_{u}+(x_{v}+x_{w})}{y_{u}+(y_{v}+y_{w})} = \binom{x_{u}}{y_{u}} + \binom{x_{v}+x_{w}}{y_{v}+y_{w}}= \overrightarrow{u} + (\overrightarrow{v}+\overrightarrow{w})

   
   
.. figure:: https://www.umlivroaberto.com/livro/lib/exe/fetch.php?media=associativa_1.png 
   :width: 400px
   :align: center

   figura 1

.. figure:: https://www.umlivroaberto.com/livro/lib/exe/fetch.php?media=associativa_2.png
   :width: 400px
   :align: center
   
   figura 2


A figura 1 ilusta a primeira situação: primeiro realiza-se a adição `(\overrightarrow{u} + \overrightarrow{v})` para depois realizar a adição deste vetor soma com o vetor  `\overrightarrow{w}`. 

Já a figura 2 ilustra a segunda situação: primeiro realiza-se a adição `(\overrightarrow{v} + \overrightarrow{w})` para depois realizar a adição o vetor  `\overrightarrow{u}` com este vetor soma. 

Em ambas as situações, o resultado é o mesmo vetor.

**c) Elemento neutro (vetor nulo)**

Considere o vetor `\overrightarrow{o}=(0,0)`. Portanto, para qualquer vetor `\overrightarrow{u}` no plano, `\overrightarrow{u} + \overrightarrow{o}= \overrightarrow{o}+ \overrightarrow{u} = \overrightarrow{u}`

.. note:: 
   .. math::
   
      \overrightarrow{u} + \overrightarrow{o} = \binom{x_{u}+0}{y_{u}+0} = \binom{x_{u}}{y_{u}} = \overrightarrow{u} 

   .. math::
   
      \overrightarrow{o}+\overrightarrow{u} = \binom{0+x_{u}}{0+y_{u}} = \binom{x_{u}}{y_{u}} = \overrightarrow{u} 


**d) Elemento simétrico (vetor simétrico)**

Para cada vetor `\overrightarrow{u}=\binom{x_{u}}{y_{u}}` existe um vetor `(-\overrightarrow{u})` definido por `\binom{-x_{u}}{-y_{u}}` tal que `\overrightarrow{u} + (-\overrightarrow{u}) = (-\overrightarrow{u})+\overrightarrow{u}=\overrightarrow{o}`. 


.. note:: 
   .. math::
   
      \overrightarrow{u} + (-\overrightarrow{u}) = \binom{x_{u}-x_{u}}{y_{u}-y_{u}}   =\overrightarrow{o}

   .. math::
   
      (-\overrightarrow{u}) + \overrightarrow{u} = \binom{-x_{u}+x_{u}}{-y_{u}+y_{u}}   =\overrightarrow{o}


.. note:: 
   
   Você deve ter percebido que o vetor nulo `\overrightarrow{o}` contraria a definição original de vetor. Qual seria a direção de um vetor nulo? Qual seria  o sentido de um vetor nulo? Entretanto, ele surge, por exemplo, quando realizamos a adição `\overrightarrow{u}+ (-\overrightarrow{u})`. Sua definição, do ponto de vista formal, se faz então necessária. Podemos interpretar o vetor nulo como sendo o deslocamento resultante de dois deslocamentos consecutivos, de mesma direção e mesmo módulo, mas em sentidos contrários: primeiro desloca-se de um ponto A até um ponto B, e depois, do ponto B, retorna-se para o ponto A. 


   .. figure:: https://www.umlivroaberto.com/livro/lib/exe/fetch.php?media=vetornulo3.png
	:width: 300px
	:align: center
   

.. _sec-vetores-aprofund-mult-escalar:

Propriedades da operação de multiplicação de um vetor por um escalar
==========================================================================


Enunciaremos as propriedades considerando vetores no plano. Entretanto, cabe destacar que essas propriedades também são válidas para vetores no espaço. 

Sejam `\overrightarrow{u}` e `\overrightarrow{v}` vetores do plano e `\lambda` e `\mu` números reais.

**a) Associativa**

`\lambda.(\mu.\overrightarrow{u})=(\lambda.\mu).\overrightarrow{u}` 


.. note:: 
   .. math::
   
      \lambda.(\mu.\overrightarrow{u})=\lambda.\binom{\mu.x_{u}}{\mu.y_{u}}=\binom{\lambda.\mu.x_{u}}{\lambda.\mu.y_{u}}=\binom{(\lambda\mu).x_{u}}{(\lambda\mu).y_{u}}=(\lambda\mu).\binom{x_{u}}{y_{u}}=(\lambda.\mu).\overrightarrow{u}
      

**b) Distributiva em relação à adição de escalares**

`(\lambda+\mu)\overrightarrow{u}=\lambda\overrightarrow{u}+\mu\overrightarrow{u}` 


.. note:: 
   .. math::
   
      (\lambda+\mu).\overrightarrow{u}=\binom{(\lambda+\mu)x_{u}}{(\lambda+\mu)y_{u}}=\binom{\lambda.x_{u}+\mu.x_{u}}{\lambda.y_{u}+\mu.y_{u}}=\binom{\lambda.x_{u}}{\lambda.y_{u}}+\binom{\mu.x_{u}}{\mu.y_{u}}=\lambda.\overrightarrow{u}+\mu.\overrightarrow{u}.

**c) Distributiva em realação à  adição de vetores**

`\lambda.(\overrightarrow{u}+\overrightarrow{v})=\lambda\overrightarrow{u}+\lambda\overrightarrow{v}` 


.. note:: 
   .. math::
   
      \lambda.(\overrightarrow{u}+\overrightarrow{v})=\lambda\binom{x_{u}+x_{v}}{y_{u}+y_{v}}=\binom{\lambda.x_{u}+\lambda.x_{v}}{\lambda.y_{u}+\lambda.y_{v}}=\binom{\lambda.x_{u}}{\lambda.y_{u}}+\binom{\lambda.x_{v}}{\lambda.y_{v}}=\lambda.\binom{x_{u}}{y_{u}}+\lambda.\binom{x_{v}}{y_{v}}=\lambda\overrightarrow{u}+\lambda\overrightarrow{v}
      

**d) Identidade**

`1.(\overrightarrow{u})=\overrightarrow{u}` 


.. note:: 
   .. math::
   
      1.(\overrightarrow{u})=\binom{1.x_{u}}{1.y_{u}}=\binom{x_{u}}{x_{u}}=\overrightarrow{u}


.. admonition:: Observação 

   `\lambda.\overrightarrow{u}=\overrightarrow{o}\Leftrightarrow\lambda=0` ou `\overrightarrow{u}=\overrightarrow{o}`.
   
   De fato.

   Se `\lambda=0` ou `\overrightarrow{u}=\overrightarrow{o}`, tem-se que `\lambda.\overrightarrow{u}=\overrightarrow{o}`.

   Por outro lado se `\lambda.\overrightarrow{u}=\overrightarrow{o}` e `\lambda\neq0`, tem-se que 
   `\overrightarrow{u}=1.\overrightarrow{u}=(\lambda^{-1}.\lambda).\overrightarrow{u}=(\lambda^{-1}).(\lambda.\overrightarrow{u})=(\lambda^{-1}).\overrightarrow{o}=\overrightarrow{o}.`