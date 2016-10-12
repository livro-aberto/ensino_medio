*****************
algebra_e_funcoes
*****************

********
Funções
********

Vivemos na era da informação! A todo momento empresas capturam grandes quantidades de dados e buscam formas de processar tais informações e transformá-las em conteúdos relevantes para seus usuários. Por exemplo, os dados sobre tempo de deslocamento de cada veículo, que são obtidos via satélite, aliados ao mapeamento das vias urbanas podem ser processados e devolvidos aos usuários com informações sobre congestionamentos, tempo estimado de viagem, melhores rotas, etc.
A imagem abaixo, que foi retirada do aplicativo Google Maps®, exibe o trânsito de uma região da cidade de Paris em um determinado dia e hora. Perceba a quantidade de informações que podem ser extraídas apenas a partir da observação dos elementos presentes nela: as cores nas vias informam a velocidade média dos veículos que trafegam por elas conforme a legenda na parte inferior, a distância entre dois pontos quaisquer do mapa pode ser estimada usando a escala exibida no canto inferior direto, e tantas outras. Gráficos como este são produzidos a partir do reconhecimento das relações entre as diversas informações coletadas.
        
.. figure:: https://www.umlivroaberto.com/wiki/lib/exe/fetch.php?media=maps.png
     :width: 700px
     :align: center

Neste Capítulo vamos explorar as relações que podem ser estabelecidas entre diferentes tipos de informação. Veremos como conectar grandezas, medidas, conjuntos numéricos e até questões mais subjetivas que muitas vezes não podem ser tão claramente quantificadas. Uma vez definidas as situações que buscamos relacionar, o precisamos definir quais são as causas e quais são os efeitos, e como se dá a dependência entre eles, estabelecendo como a variação das causas provocam as variações nos efeitos.
    
Atividade 1
-----------

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
    

.. note:: Não conseguimos centralizar os elementos da tabela

(a)	Utilize a escala de cores abaixo para completar a terceira coluna da tabela acima com a cor que a ponte deveria estar colorida em cada período do dia em um aplicativo que mostra o trânsito como o Google Maps®.

	.. figure:: https://www.umlivroaberto.com/wiki/lib/exe/fetch.php?t=1476218022&w=500&h=37&tok=f2c26e&media=escala_cores.jpg

(b)	Você deve ter percebido que precisou associar uma mesma cor para tempos de travessia diferentes. Isso se deu pelo fato de haver somente 4 cores disponíveis e pelo menos 7 tempos diferentes. Descreva os critérios que você utilizou na escolha de cada uma das cores e compare com os critérios dos seus colegas.

(c)	Sabendo que a ponte tem 8km de extensão e que a velocidade média é calculada dividindo a distância percorrida pelo tempo gasto no percurso, complete a quarta coluna da tabela acima com a velocidade média aproximada registrada em cada um dos períodos do dia.

(d)	É possível que uma mesma velocidade média esteja associada a dois tempos de travessia diferentes? Por quê?

Pode-se perceber, a partir da atividade anterior, que a natureza das relações entre os dados não é sempre a mesma. Para cada tempo de travessia, podemos associar uma única cor e uma única velocidade média. Da mesma maneira, a cada velocidade média está associada uma única cor e um único tempo de travessia. No entanto, a uma mesma cor estão associados diferentes tempos e diferentes velocidades médias. 
De um modo mais geral, dados dois conjuntos quaisquer, `A` e `B` podemos estabelecer diversos tipos de relações entre seus elementos. Dentre elas, uma se destaca e é o tema central deste capítulo, as funções, que definimos a seguir.

.. note:: Dizemos que `f:A\to B` é uma *função* de `A` em `B` se a cada elemento `a\in A` está associado um único elemento `b\in B`. O elemento `b` é dito a imagem do elemento `a` e é denotado por `f(a)` (lê-se `f` de `a`). O conjunto `A` é chamado *domínio* da função enquanto o conjunto `B` é o *contradomínio*.

Perceba que na definição está implícito que todo elemento de `a\in A` precisa ter uma imagem `f(a)\in B`, sem haver ambiguidade na determinação da imagem. Por outro lado, nem todo elemento `b\in B`, precisa ser a imagem de algum elemento do domínio. Mas pode ocorrer de um elemento b∈B ser imagem de elementos distintos em `A`, ou seja, `b=f(a_1 )=f(a_2)` com `a_1\neq a_2`.

Atividade 2
-----------
Dentre as relações que podem ser feitas entre os conjuntos de dados da atividade anterior, determine quais são funções.

.. math::

	A=\{0,11;0,12;0,13;0,14;0,16;0,20;0,27\}.
    
	B=\{Verde,Amarelo,Vermelho, Vinho\}.
    
	C \mathrm{\ é\ o\ conjunto\ das\ velocidades\ médias}.

