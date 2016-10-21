=======
Funções
=======

Vivemos na era da informação! A todo momento empresas capturam grandes quantidades de dados e buscam formas de processar tais informações e transformá-las em conteúdos relevantes para seus usuários. Por exemplo, os dados sobre tempo de deslocamento de cada veículo, que são obtidos via satélite, aliados ao mapeamento das vias urbanas podem ser processados e devolvidos aos usuários com informações sobre congestionamentos, tempo estimado de viagem, melhores rotas, etc.
A imagem abaixo, que foi retirada do aplicativo Google Maps®, exibe o trânsito de uma região da cidade de Paris em um determinado dia e hora. Perceba a quantidade de informações que podem ser extraídas apenas a partir da observação dos elementos presentes nela: as cores nas vias informam a velocidade média dos veículos que trafegam por elas conforme a legenda na parte inferior, a distância entre dois pontos quaisquer do mapa pode ser estimada usando a escala exibida no canto inferior direto, e tantas outras. Gráficos como este são produzidos a partir do reconhecimento das relações entre as diversas informações coletadas.
        
.. figure:: https://www.umlivroaberto.com/livro/lib/exe/fetch.php?media=maps.png
     :width: 700px
     :align: center

.. note:: As figuras só ficavam visíveis se estivéssemos logados na wiki. Mudei o link para as figuras porque as coloquei na wiki do livro de frações que é aberta a todo mundo para visualização. Agora as figuras devem ser colocadas lá. Por favor, veja a documentação sobre figuras na `sintaxe <https://www.umlivroaberto.com/BookCloud/sintaxe/master/view/index#my-figuras>`_

Neste Capítulo vamos explorar as relações que podem ser estabelecidas entre diferentes tipos de informação. Veremos como conectar grandezas, medidas, conjuntos numéricos e até questões mais subjetivas que muitas vezes não podem ser tão claramente quantificadas. Uma vez definidas as situações que buscamos relacionar, o precisamos definir quais são as causas e quais são os efeitos, e como se dá a dependência entre eles, estabelecendo como a variação das causas provocam as variações nos efeitos.
    

.. admonition:: Atividade 1 

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

   Dizemos que `f:A\to B` é uma *função* de `A` em `B` se a cada elemento `a\in A` está associado um único elemento `b\in B`. O elemento `b` é dito a imagem do elemento `a` e é denotado por `f(a)` (lê-se `f` de `a`). O conjunto `A` é chamado *domínio* da função enquanto o conjunto `B` é o *contradomínio*.

Perceba que na definição está implícito que todo elemento de `a\in A` precisa ter uma imagem `f(a)\in B`, sem haver ambiguidade na determinação da imagem. Por outro lado, nem todo elemento `b\in B`, precisa ser a imagem de algum elemento do domínio. Mas pode ocorrer de um elemento b∈B ser imagem de elementos distintos em `A`, ou seja, `b=f(a_1 )=f(a_2)` com `a_1\neq a_2`.


.. admonition:: Atividade 2

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
    
.. admonition:: Atividade 3

	A sequência `\{1,3,6,10,15,\dots\}` é conhecida como a sequência dos números triangulares. A razão para o nome está ilustrada na figura abaixo.

		.. figure:: https://www.umlivroaberto.com/livro/lib/exe/fetch.php?media=wiki:triangulos.png
			:width: 550px
			:align: center
        
	O n-ésimo número triangular é a quantidade total de pontos, distribuídos como acima, no triângulo equilátero que tem n pontos em um de seus lados. Por exemplo, o quarto número triangular é igual a 10. 

	a) Decida se a relação que associa a cada número natural n, o n-ésimo número triangular é ou não uma função.

	b) Determine, se possível, o 6º, o 7º e o 8º números triangulares. 

	c) É possível obter uma expressão geral que permita encontrar qualquer número triangular? Explique.



.. admonition:: Atividade 4

	Um dado cúbico com as faces numeradas de 1 a 6, é lançado 10 vezes e os 5 primeiros resultados são anotados em uma tabela.

	+---------------+---+---+---+---+---+
	|  Lançamento   | 1 | 2 | 3 | 4 | 5 |
	+---------------+---+---+---+---+---+
	| Resultado     | 3 | 5 | 2 | 2 | 6 |
	+---------------+---+---+---+---+---+

	a) Decida se a relação que associa a cada número natural `n`, o resultado obtido no `n`-ésimo lançamento do dado é ou não uma função. 

	b) Determine, se possível, o 6º, o 7º e o 8º resultados dos lançamentos. 

	c) É possível obter uma expressão geral que permita encontrar o resultado de qualquer lançamento? Explique.
    


