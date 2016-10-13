********
Teorema de Tales, semelhança e aplicações
********

.. note::
   * Teorema de Tales: fazer a demonstração da parte comensurável, deixar a outra indicada e a ser resolvida pelo estudante em atividade para os alunos interessados. Outra opção é fazer a prova utilizando áreas.

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
    
    Vídeo-aula sobre Teorema de Tales https://www.youtube.com/watch?v=ISt_RsQ2veU

=======
Semelhança
=======

Atividade 1 - Pantógrafo
-----------
Nesta atividade você vai construir e usar um equipamento, chamado *pantógrafo*, com o qual pode-se ampliar ou reduzir figuras desenhadas numa folha de papel e entenderá como ele funciona.

Assista ao vídeo do `Manual do Mundo <https://www.youtube.com/watch?v=Ji7YorM_t_0>`_ e construa o seu pantógrafo. Embora não seja tão divertido quanto construir o seu próprio pantógrafo físico, você também pode utilizar o `pantógrafo virtual <https://www.geogebra.org/m/mrZRVrpf>`_ para ver como ele funciona.

a) Numa folha separada use o pantógrafo para ampliar a seguir.

   .. figure:: https://upload.wikimedia.org/wikipedia/commons/0/0c/Contorno_do_mapa_do_Brasil.svg
     :width: 200px
     :align: center
     
     autor: Giro720 (Wikimedia Commons)

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

Exemplo 1
-------


.. figure:: https://www.umlivroaberto.com/livro/lib/exe/fetch.php?media=semelhanca1.png

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

Projeto Aplicado - Cinema na caixa
---------------

Cinema na caixa - Este é um projeto aplicado sobre homotetias de razão negativa

Apresentar o vídeo: https://www.youtube.com/watch?v=9JBs4T-sd6E (Manual do Mundo) em que é construída uma câmara escura em que o estudante pode sentar dentro e assistir à projeção invertida do que passa atrás dele fora da caixa. O ponto a ser explorado aqui é a homotetia de razão negativa do ponto de vista vetorial pois as imagens ficam reescaladas e invertidas. Aqui o objetivo é apresentar a homotetia de razão negativa do ponto de vista de transformação do plano (no caso do espaço, mas podemos fazer uma simplificação para o plano).

Objetivos: 
a. Descrever este fenômeno do ponto de vista matemático obtendo assim uma transformação do plano. A figura fica deformada? O tamanho modifica? Por que ela fica de cabeça para baixo?
b. Levar o estudante a criar a hipótese sobre a distância que se deve colocar um objeto de altura conhecida para  que caiba na tela (de tamanho também conhecido). Também pode se perguntar qual é o tamanho da folha de papel para que se possa ver um objeto de altura conhecida. Finalmente pode-se calcular a altura de um objeto externo à caixa conhecendo-se a caixa. Devem ser experimentadas nestas aulas e justificados com os casos de semelhança de triângulos. 

