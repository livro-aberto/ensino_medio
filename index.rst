********
Volume 1 - Coleção do Ensino Médio - Livro Aberto de Matemática
********

Contents:

.. toctree::
   :maxdepth: 1
   :glob:

   *

********
Vetores no plano
********




Subseção
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
.. note::

   BNCC(EM11MT01) Compreender o conceito de vetor, tanto do ponto de vista geométrico (coleção de segmentos orientados de mesmo comprimento, direção e sentido) quanto do ponto de vista algébrico, caracterizado por suas coordenadas, aplicando-o em situações da Física.
   
   BNCC(EM13MT02) Estabelecer relações entre as transformações isométricas (reflexão, translação e rotação) e vetores no contexto do plano cartesiano, incluindo o uso de softwares de geometria dinâmica.

   Objetivos adicionais:
   
   1. Despertar para a existência de grandezas vetoriais.
   2. Usar as operações com vetores em situações concretas (cálculo da força resultante, soma de velocidades, deslocamento final, etc.) e suas representações algébricas.
   3. Reconhecer a diferença entre ponto e vetor, embora possam ser representados por mesmas coordenadas.
   4. Conhecer bem o plano cartesiano.
   


Não importa a origem (introdução às coordenadas)
=====


Atividade
---------

Devido à força do vento os barcos `A`, `B`, `C` e `D` do mapa sofrem um deslocamento que é representado na figura. 

.. tikz:: Barcos ao vento

   \draw[step=1cm,gray,very thin] (0,-0) grid (8,8);
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

a) Supondo que o barco  

b) 


Adição de vetores
=====




   
Roteiro da lição:

Atividade motivadora: 
 1.  despertar para a existência de grandezas vetoriais através do contato com uma situação-problema.
 2. despertar para a necessidade uso de coordenadas para representar vetores.
   
Introdução: Esta parte está intimamente ligada à parte do livro que trata de grandezas e medidas. Há que se estabelecer tipos de grandezas:

Escalares: massa, volume, área, comprimento, deslocamento escalar, velocidade escalar, etc. 

Vetoriais: Variação de posição, Velocidade, Força, etc.

Exemplo 1:
Velocidade como grandeza escalar: Se dizemos que dois objetos se deslocam 15 metros em 3 minutos, as velocidades dos dois objetos são iguais e valem 5 metros por minuto. 

Velocidade como grandeza vetorial: Se dizemos que dois objetos que ocupam a mesma posição inicial partem com velocidade de 5 metros por minuto, não é possível dizer, após 10 minutos, a posição relativa entre eles, pois falta uma informação crucial que é a direção que eles tomam.

Em geral, grandezas escalares podem ser representadas por segmentos de reta e medidos com uma régua. Grandezas vetoriais, por outro lado, não podem ser representados por segmentos de reta e necessitamos introduzir o conceito de segmento orientado.

Enquanto segmentos de reta são bem caracterizados por um conjunto de dois pontos `S = \{A, B\}` cujos elementos são ditos extremos do segmento, os segmentos orientados são caracterizados por um conjunto do tipo `V = \{A, B, \{A\}\}`, indicando que `A` e `B` são os extremos e que `A` é o ponto de partida. Essa notação, no entanto, não é muito apropriada e pode ser substituída por um par ordenado de pontos `V = (A, B)`.
Para descrever o segmento orientado `V=(A, B)`, ou simplesmente , sem desenhar o segmento propriamente dito, precisamos fornecer três informações:

1. O comprimento do segmento `AB`
2. A direção (que é dada pela reta `AB`)
3. O sentido, que pode ser de `A` para `B` ou de `B` para `A`

Aqui, observamos que na descrição informal, quando falamos no segmento orientado de A para B, o sentido confunde-se com a direção (a direção parece um dado supérfluo pois ela vem junto com o sentido). Por outro lado, o elemento da geometria que encerra a ideia de direção é a reta. Acontece que as retas AB e BA são a mesma reta e, portanto, os segmentos V=(A, B) e V=(B, A) devem ter a mesma direção. A diferença entre esses segmentos orientados está no sentido e não na direção.
Passagem dos segmentos orientados para vetores: Nessa parte, faz-se necessária a apresentação do plano cartesiano e de representação de pontos nele. O grupo que está escrevendo a parte de funções considera que essa apresentação é um pré-requisito. No meu entendimento, o plano cartesiano deve ser apresentado, assim como seus 7 subconjuntos mais importantes: os 4 quadrantes, os 2 eixos e a origem. É imprescindível que se saiba localizar um ponto pelas suas coordenadas (principalmente fazer uma transição para que o aluno não dependa eternamente de observar a figura desenhada no plano para poder trabalhar com suas coordenadas).
Algumas operações são fundamentais para a introdução do conceito de vetor no plano. Dentre elas eu considero que determinar as coordenadas do ponto médio de um segmento é a mais importante, pois permite que se decida se dois segmentos orientados estão ou não na mesma classe de equivalência.

Exemplo 2:
Determinar se os segmentos orientados  e   estão ou não na mesma classe


Uma saída geométrica razoável, seria a decomposição dos segmentos orientados em “direita” e “cima”. Muito facilmente, o aluno perceberá que para sair de A e chegar a B, ele precisa deslocar-se 2 unidades para a direita e 4 unidades para cima e o mesmo acontece quando pretende sair de C para D. Essa saída é particularmente interessante porque, no fim, desejamos que esses segmentos orientados sejam representados pelo mesmo vetor e (2, 4) é exatamente o vetor que os representa.
No mesmo exemplo, no entanto, há uma conexão com o conteúdo do ensino fundamental que consiste em 2 maneiras diferentes de definir um paralelogramo:
Definição1:
Um paralelogramo é o quadrilátero que tem 2 lados paralelos e congruentes.

Definição 2:
Um paralelogramo é o quadrilátero em que as diagonais se cruzam em seus pontos médios.


Aqui, lembramos que os segmentos orientados estão na mesma classe se têm mesma direção, mesmo sentido e mesmo comprimento. Todas essas condições são atendidas se ABDC formar um paralelogramo.
Exemplo 2:
Determinar se os segmentos orientados  e   estão ou não na mesma classe, dados A(2, 4); B(4, 8); C(4, -1) e D(6, 3).
Trata-se, obviamente do mesmo exercício, mas sem o auxílio da figura. Para resolvê-lo, uma maneira interessante seria lembrar que ABCD deve ser um paralelogramo, e, usando a definição 2, as diagonais AC e BD devem ter o mesmo ponto médio:
	 

Logo a primeira parte da equivalência mostrada acima já seria um critério bom para decidir se os segmentos orientados estão ou não na mesma classe, mas o desenvolvimento nos leva a  , que será bastante usado ao longo do estudo de vetores.

********
Teorema de Tales, semelhança e aplicações
********


********
Funções
********


********
Probabilidade e Estatística
********