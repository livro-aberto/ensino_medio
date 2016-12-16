
****************
Teorema de Tales
****************

.. admonition:: Objetivos específicos

   BNCC (MTMT1MOA003) Compreender e aplicar o teorema de Tales na resolução de problemas, incluindo a divisão de segmentos em partes proporcionais.
   
.. admonition:: Pré requisito
   
   buscar no Ensino Fundamental
	
    
.. admonition:: Desdobramentos Imediatos

	BNCC (MTMT1MOA005) Compreender e aplicar as razões trigonométricas no triângulo retângulo e as relações trigonométricas em triângulos quaisquer.


.. note::
   * Teorema de Tales: fazer a demonstração da parte comensurável, deixar a outra indicada e a ser resolvida pelo estudante em atividade para os alunos interessados. Outra opção é fazer a prova utilizando áreas.

    
    Vídeo-aula sobre Teorema de Tales https://www.youtube.com/watch?v=ISt_RsQ2veU


.. admonition:: Roteiro da aula de Teorema de Tales
   
   Motivação - sugiro se inspirar naquela do livro do Harold Jacobs para o uso do teorema no contexto da barragem de Fundão. Enunciar e usar o teorema para calcular o comprimento da parte da barragem em contato com os dejetos. 
   
   .. _fig-barrage_a_mao:

   .. figure:: https://dl.dropboxusercontent.com/u/2371346/barragem.jpg
      :width: 400px
      :align: center

      A ser subsituída
   
   
   #. Atividades em que o estudante experimente medições dos segmentos formados por diversas transversais em um feixe de retas paralelas para que visualize e experimente de maneira livre [Visualização].   
   
   #. Na mesma ou em outra atividade levar o estudante a buscar padrões nestes experimentos [Analise]. O ideal é que ao final da atividade ele mesmo consiga enunciar que seja qual for a transversal traçada, as razões entre os segmentos serão as mesmas. Espera-se com isso que ele retenha o fato de que a transversal não importa, aquela razão é uma propriedade das paralelas.  
      
   #. Fechamento das atividades acima com um texto breve e objetivo deixando claro que temos uma hipótese a ser justificada e com o teorema enunciado claramente com todas as letras. Não chamar de teorema, podemos chamar de "afirmação" por enquanto. 
   
   # Apresentar mais atividades que coloquem à prova o resultado enunciado pelos estudantes. Apresentar exemplos em que as paralelas não estão na "horizontal", com os segmentos formados nas transversais não consecutivos, com muitas paralelas e com as transversais intersectando-se entre as paralelas. Talvez o ideal é que o estudante estabeleça a igualdade dada no teorema para cada uma das figuras apresentadas.
   
   .. _fig-variedade_tales

   .. figure:: https://dl.dropboxusercontent.com/u/2371346/IMG_20161216_191600865.jpg
      :width: 400px
      :align: center

      refazer em tikz
   
   #. Atividades (ou observação) que levem o estudante a entender que se dois triângulos possuem mesma altura (respectivamente, mesma base), então a razão entre as áreas é a razão entre as bases (respectivamente, razão entre as alturas). Como este não é um objetivo da lição, o resultado pode ser apresentado aos estudantes, mas é fundamental que para eles esteja claro a validade do resultado ao final da atividade (ou observação).   
   
   #. Provar o Teorema de Tales no caso usado na motivação (ver figura) usando áreas.[melhorar]   
   
   #. Atividade que leve o estudante a generalizar o Teorema de Tales acima para a versão usual.
   
   #. Observação aritmética (`\frac{a}{b}=\frac{c}{d} \Rightarrow \frac{a + b}{b}=\frac{c + d}{d}`).
   
   #. Atividade com régua e compasso ou com o Geogebra para fazer a construção com régua e compasso da divisão de segmentos em partes iguais.
   
   #. Atividades contextualizadas (ruas paralelas e ....).
   
   
Motivação do Teorema de Tales

.. note:: Inserir imagem característica do desastre abaixo relatado.

No dia 5 de novembro de 2015, a barragem de Fundão, na cidade mineira de Mariana, se rompeu deixando centenas de pessoas desabrigadas e enchendo o Rio Doce e de rejeitos de mineração causando o maior desastre sócioambiental da história brasileira. A figura a seguir apresenta um esquema de uma barragem (melhorar e citar fonte desta história). 


A seguir apresentamos um esquema simplificado de uma barragem. A força que o material represado faz sobre a barragem depende da área de contato deste material com a barragem, representado pelo segmento `PB`. Como se trata de uma região submersa, esta medição pode ser de difícil obtenção. 

Mostraremos que se `BC \parallel PQ`, então 

.. math::

   \dfrac{AP}{PB} = \dfrac{AQ}{QC}.

Desse modo, o comprimento `PB` pode ser calculado a partir das distâncias `AP`, `AQ` e `QC`, que podem ser medidas mais facilmente.


.. _ativ-descobrindo_tales:

Atividade: Visualização e análise de padrões
------------------------------

Copie as figuras (I), (II) e (III) em seu caderno e resolva cada um dos itens a), b), c) e d) para cada uma das figuras.

.. _fig-tales_tres_paralelas:

.. figure:: https://dl.dropboxusercontent.com/u/2371346/tres_paralelas.jpg
   :width: 450px
   :align: center

   Refazer em tikz

#. Trace uma reta $u$ transversal a `r`, `s` e `t` e marque os pontos `\{A\} = r \cap u`, `\{B\} = s \cap u` e `\{C\} = t \cap u`.

#. Calcule as distâncias `\overline{AB}` e `\overline{BC}` na reta traçada por você. Use as retas traçadas por 3 de seus colegas para preencher a tabela a seguir.

   .. table:: 
      :widths: 1 1 1 1
      :column-alignment: center

      +-----------------+-----------+-----------+-----------+
      |  Figura ____    | medição 1 | medição 2 | medição 3 |
      +=================+===========+===========+===========+
      | `\overline{AB}` |           |           |           |
      +-----------------+-----------+-----------+-----------+
      | `\overline{BC}` |           |           |           |
      +-----------------+-----------+-----------+-----------+

#. Analisando cada uma das tabelas preenchidas obtenha uma relação entre `\overline{AB}` e `\overline{BC}` para cada um dos cenários (I), (II) e (III), que sirva para todas as medições. 

#. Complete a sentença a seguir a seguir de modo a resumir uma conclusão dos itens anteriores.

"Quando três retas paralelas são fixadas, a ___________ entre os segmentos formados por uma reta ___________________ às três retas é ______________________ da reta tomada." (melhorar ou repensar)

Teorema de Tales
------------

.. note:: Enunciado e prova da versão acima do Teorema de Tales. A prova será por área? Incluir também exemplos característicos.




********
Semelhança
********

.. admonition:: Objetivos específicos

   BNCC (MTMT1MOA004) Utilizar a semelhança de triângulos e o teorema de Pitágoras (exemplo: diagonais de prismas e da altura de pirâmides) para resolver e elaborar problemas.

.. admonition:: Pré requisito

	BNCC (MTMT9FOA002) Reconhecer as condições necessárias e suficientes para obter triângulos semelhantes e utilizar a semelhança de triângulos para estabelecer as relações métricas no triângulo retângulo e as razões trigonométricas.
  
.. admonition:: Desdobramentos Imediatos

	BNCC (MTMT1MOA005) Compreender e aplicar as razões trigonométricas no triângulo retângulo e as relações trigonométricas em triângulos quaisquer.

.. note::

   * Semelhança. Definimos para polígonos. Fazemos uma prova de caso de semelhança para que haja uma conexão entre o Teorema de Tales e as semelhanças de triângulos. Deixamos um caso como atividade para os interessados e outro para todos os estudantes.

   * Importante lembrar que na base está "uso de semelhança"...

    Neste vídeo o professor realiza o experimento de medir a altura do mastro da bandeira da escola com os estudantes e surgem diversas oportunidades de aprendizado sobre outros temas em que os estudantes tinham dificuldades no uso da matemática. Ele mostra toda a dinâmica da atividade. Esta pode ser uma atividade de aplicação do conteúdo de semelhanças.

    https://www.teachingchannel.org/videos/similar-triangles-geometry-lesson-nea

    * Acho que aqui vale a pena usar exemplos diferentes de polígonos e também tridimensionais.

    * Este site possui diversos exemplos de atividades eletrônicas com semelhanças de triângulos.

    https://education.ti.com/en/timathnspired/us/geometry/similarity-and-proportion

    * Podemos retomar as coordenadas de vetores em atividades em que são dadas as coordenadas de um triângulo no plano e aplica-se uma homotetia (talvez seja melhor não falar esse nome) para obter uma figura semelhante. Podem ser feitos casos simples no papel e casos interessantes no Geogebra com uma barra em que o estudante pode escolher a razão da homotetia (inclusive com sinal negativo) para ver a figura se transformando em outra semelhante. 

    "É preciso ficar claro para o aluno como e em que circunstâncias são produzidas figuras semelhantes. Para tanto, é preciso compreender a ideia de razão de semelhança (a razão k que existe entre dois de seus lados homólogos.), por meio de ampliações e reduções que podem ser feitas numa figura pela transformação conhecida como homotetia". (PCN, 1998, p. 195)

   "O conceito de semelhança está presente no estudo de escalas, plantas, mapas, ampliações de fotos, fotocópias como também quando se verifica, por exemplo, se as medidas das partes do corpo humano se mantêm proporcionais entre um representante jovem e um representante adulto. (PCN 1998 p.125)."

   * Em atividades pode-se explorar o fato de que a razão entre os perímetros de polígonos semelhantes é a razão de semelhança e que a razão entre as áreas de figuras semelhantes é a razão de semelhança ao quadrado.
    
.. admonition:: Roteiro da aula de semelhanças
   
   a ser construído.


Atividade 1 - Pantógrafo
-----------
Nesta atividade você vai construir e usar um equipamento, chamado *pantógrafo*, com o qual pode-se ampliar ou reduzir figuras desenhadas numa folha de papel e entenderá como ele funciona.

Assista ao vídeo do `Manual do Mundo <https://www.youtube.com/watch?v=Ji7YorM_t_0>`_ e construa o seu pantógrafo. Embora não seja tão divertido quanto construir o seu próprio pantógrafo físico, você também pode utilizar o `pantógrafo virtual <https://www.geogebra.org/m/mrZRVrpf>`_ para ver como ele funciona.

a) Numa folha separada use o pantógrafo para ampliar a seguir.

.. figure:: https://upload.wikimedia.org/wikipedia/commons/e/ec/Necker_cube_and_impossible_cube.PNG
     :width: 300px
     :align: center
     
     autor: Maksim (`Wikimedia Commons <https://commons.wikimedia.org/wiki/Category:Impossible_cubes?uselang=pt-br>`_)

b) Que adaptações devem ser feitas para transformar o seu pantógrafo num pantógrafo de redução?

c) Tente entender por que ele funciona. Tudo bem se você não conseguir justificar tudo com cuidado, este é o tema desta seção.

Em matemática quando uma figura é uma ampliação ou uma redução de outra dizemos que são figuras *semelhantes*. Embora a palavra *semelhante* seja um sinônimo de *parecido* na linguagem corrente, em matemática isso não é verdade. As figuras a seguir não são semelhantes.

.. tikz:: Parecidas na linguagem corrente, mas não semelhantes do ponto de vista da matemática (adaptação da figura de Alain Matthes)

        \draw[ball color=red,shading=ball, scale=.25] (4,1) ..controls +(120:2cm)
        and +(90:2cm) .. (0,0) .. controls  +(-90:2cm) and +(90:3cm) ..
        (4,-8) .. controls +(90:3cm) and +(-90:2cm) ..(8,0)  .. controls
        +(90:2cm) and  +(60:2cm) .. (4,1);
        
        \begin{scope}[xshift=3cm]
        \draw[ball color=red,shading=ball, scale=.25] (4,1) ..controls +(120:2.5cm)
        and +(90:1.5cm) .. (0,0) .. controls  +(-90:1cm) and +(90:2cm) ..
        (4,-8) .. controls +(90:3cm) and +(-90:1cm) ..(8,0)  .. controls
        +(90:2cm) and  +(60:2cm) .. (4,1);
        \end{scope}

Os conceitos matemáticos precisam ser definidos por meio de outros conceitos matemáticos para que seja possível justificar fatos matemáticos precisamente. Para fazer uma definição de figuras semelhantes nos restringiremos, por ora, aos polígonos planos.

.. note:: Dois polígonos planos são *semelhantes* quando existir uma correspondência entre os vértices de um e de outro de modo que os lados correspondentes são proporcionais e os ângulos em vértices correspondentes são iguais. 
         
         Usa-se o símbolo `\sim` para representar a semelhança. Assim, a notação `ABC \sim XYZ` significa *"os triângulos* `ABC` *e* `XYZ` *são semelhantes"*.

Exemplo 1
-------


.. figure:: https://www.umlivroaberto.com/livro/lib/exe/fetch.php?media=semelhanca1.png
   :width: 600px

    autor: Arquivo próprio

Os triângulos `ABC` e `XYZ` da figura são semelhantes com a correspondência `A \to X`, `B \to Y` e `C \to Z` se valem as seguintes igualdades:

.. math::

   \dfrac{AB}{XY} = \dfrac{BC}{YZ} = \dfrac{CA}{ZX} \quad \quad
   \widehat{A} = \widehat{X},\quad \widehat{B} = \widehat{Y} \quad \text{e} \quad \widehat{C} = \widehat{Z}.


Atividade 2
-----------
Exemplo numérico para ambientação do estudante com o conceito.


Atividade 3
-----------
Decida se cada uma das afirmações a seguir são verdadeiras ou falsas e em seguida justifique as verdadeiras e apresente um exemplo que sirva de explicação para a falsidade de cada uma das demais afirmações.

a) Quaisquer dois triângulos equiláteros são semelhantes.
b) Quaisquer dois triângulos retângulos são semelhantes.
c) Se dois triângulos são congruentes, então eles são semelhantes.
d) Quaisquer dois quadrados são semelhantes.
e) Quaisquer dois retângulos são semelhantes.
f) Quaisquer dois losangos são semelhantes.

O teorema a seguir ensina uma maneira de se construir triângulos semelhantes a um triângulo dado. 

Teorema Fundamental das Semelhanças de Triângulos
----------------
Se uma reta `r` é paralela a um dos lados de um triângulo `ABC` forma um triângulo com as retas suportes dos outros dois lados de `ABC`, então este novo triângulo é semelhante a `ABC`.

.. tikz::
   
   \draw (0,0) -- (4,0);
   \draw (0,0) -- (1,5);
   \draw (1,5) -- (4,0);
   \node[left] at (0,0) {$B$};
   \node[above] at (1,5) {$A$};
   \node[right] at (4,0) {$C$};
   \draw (-.8,2)--(4,2);
   \node[above] at (4,2) {$r$};
   \node[left] at (0.4,2.2) {$P$};
   \node[right] at (2.8,2.2) {$Q$};
   \fill[black] (0,0) circle (.08);
   \fill[black] (1,5) circle (.08);
   \fill[black] (4,0) circle (.08);
   \fill[black] (.4,2) circle (.08);
   \fill[black] (2.8,2) circle (.08);
   
.. note:: Exemplo, provar ao menos 1 casos de semelhança, enunciar todos três e incluir exercícios, nos exercícios provar os casos que faltaram.

O retângulo dourado (para os estudantes que gostam de matemática)
-------------------
Você deve ter percebido que dois retângulos `R_1` e `R_2` são semelhantes se a razão 

.. math:: \dfrac{\text{lado maior de } R_1}{\text{lado menor de } R_1} = \dfrac{\text{lado maior de } R_2}{\text{lado menor de } R_2}.

Pergunta 1: Existe um retângulo de lados `a` e `a+b` com `b \neq 0` que quando dele se retira um quadrado de lado `a` como na figura, o retângulo restante seja um retângulo semelhante ao inicial?

Pergunta 2: Qual é a razão entre o maior e o menor lado deste retângulo? Este número é chamado de *número de ouro* e é representado pela letra `\phi`.

Pergunta 3: Quantos retângulos existem com essa propriedade?

.. figure:: https://upload.wikimedia.org/wikipedia/commons/f/f8/Rectangle_GoldenRatio.svg
   :width: 200px
   :align: center

   Refazer esta figura (autor: Kaneiderdaniel - Wikimedia)

Problema: Use uma calculadora para obter todas as casas decimais de `\phi` que você puder e faça o mesmo com o número `\phi^{-1}`. Conclua que `\phi^{-1} = \phi - 1`.

.. note:: Construção para o estudante obter os retângulos de ouro encaixados como na figura.

   .. figure:: https://upload.wikimedia.org/wikipedia/commons/2/23/Golden_spiral_in_rectangles.png
      :align: center
      :width: 300px

   retângulos dourados encaixados (substituir figura por outra própria e mais bonita, esta é da wikimedia).


Projeto Aplicado - Cinema na caixa
---------------

Cinema na caixa - Este é um projeto aplicado sobre homotetias de razão negativa

Apresentar o vídeo: https://www.youtube.com/watch?v=9JBs4T-sd6E (Manual do Mundo) em que é construída uma câmara escura em que o estudante pode sentar dentro e assistir à projeção invertida do que passa atrás dele fora da caixa. O ponto a ser explorado aqui é a homotetia de razão negativa do ponto de vista vetorial pois as imagens ficam reescaladas e invertidas. Aqui o objetivo é apresentar a homotetia de razão negativa do ponto de vista de transformação do plano (no caso do espaço, mas podemos fazer uma simplificação para o plano).

Objetivos: 
a. Descrever este fenômeno do ponto de vista matemático obtendo assim uma transformação do plano. A figura fica deformada? O tamanho modifica? Por que ela fica de cabeça para baixo?
b. Levar o estudante a criar a hipótese sobre a distância que se deve colocar um objeto de altura conhecida para  que caiba na tela (de tamanho também conhecido). Também pode se perguntar qual é o tamanho da folha de papel para que se possa ver um objeto de altura conhecida. Finalmente pode-se calcular a altura de um objeto externo à caixa conhecendo-se a caixa. Devem ser experimentadas nestas aulas e justificados com os casos de semelhança de triângulos. 

