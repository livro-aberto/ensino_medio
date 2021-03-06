***************************************
ROTEIRO: MEDIDAS DE POSIÇÃO E DISPERSÃO
***************************************

.. admonition:: Previsão de aulas necessárias 
    
   5 tempos de aula 
       
.. admonition:: Previsão de páginas necessárias 
    
   A ser visto no final da elaboração do capítulo. 
 
.. admonition:: Fase de elaboração 
    
   FASE DE ELABORAÇÃO: 4

.. admonition:: Habilidade

   (EM11MT04) Utilizar a média, a mediana e a amplitude para descrever, comparar e interpretar dois conjuntos de dados numéricos obtidos nas pesquisas realizadas pelos estudantes, em termos de localização (centro) e dispersão (amplitude). 
        
   (EM13MT05) Calcular e interpretar medidas de dispersão (amplitude, desvio médio, variância e desvio padrão) para um conjunto de dados numéricos, agrupados ou não, em pesquisas realizadas pelos estudantes ou usando dados de outras fontes com temas envolvendo os temas integradores.
 
 
.. _sub-objetivogeral:

Objetivo Geral do Capítulo
--------------------------
 
Compreender como algumas medidas, chamadas medidas resumo, podem de alguma forma revelar informações sobre a distribuição dos dados. Para alcançar este objetivo geral, este capítulo inclui:
 
#. definições de medidas de posição (média, mediana, moda e quartis);
#. definições de medidas de dispersão (desvio médio, variância e desvio padrão, amplitude (amostral), amplitude interquartílica, coeficiente de variação);
#. sinalizações para a importância das medidas de dispersão para avaliar a representatividade da média na distribuição;
#. revisão dos conceitos apresentados no capítulo "A Natureza da Estatística": parâmetro e estatística, definindo média populacional e média amostral, variância populacional e variância amostral.
#. definição de representação gráfica para variáveis quantitativas, conhecida como desenho-esquemático ou diagrama de caixa (boxplot).

Observação: Embora muitos textos denominem as medidas de posição (média, mediana e moda) como medidas de tendência central, interpretando "tendência central" como "valor representativo" na distribuição", preferimos denominá-las medidas de posição, pois, por exemplo, dependendo da forma da distribuição, a média pode não ser um "valor representativo" da distribuição.

.. admonition:: Por que estudar o assunto? 

   As medidas resumo (posição e dispersão) correspondem a uma síntese do conjunto de dados observados e ao passo preliminar para fazer uma inferência estatística, ou seja, a partir das informações obtidas na amostra, expandir nossas conclusões para a população. Como as distribuições podem apresentar formas variadas é importante conhecer diferentes tipos de medidas resumo, tanto de posição como de dispersão, para usar medidas apropriadas em cada caso.

.. admonition:: Desafios do Capítulo

   #. Entender as especificidades das variadas medidas resumo e reconhecer suas limitações em cada contexto.
   #. A partir de algumas medidas resumo, ser capaz de ter uma noção quanto à forma da distribuição dos dados.

 
.. admonition:: Conteúdos abordados 

   #. Medidas de posição: média, mediana, moda e quartis.
   #. Medidas de dispersão: amplitude, amplitude interquartílica, desvio médio, variância, desvio padrão e coeficiente de variação.
   #. Parâmetro versus Estatística (Média populacional versus média amostral, Variância populacional versus variância amostral, etc.).
   #. Construção do "boxplot".
 
 
.. admonition:: Pré-requisitos

   (EF07MA29) Compreender, em contextos significativos, o significado de média estatística como indicador da tendência de uma pesquisa, calcular seu valor e relacioná-lo, intuitivamente, com a amplitude do conjunto de dados.
 
   (EF08MA22) Obter os valores de medidas de tendência central de uma pesquisa estatística (média, moda e mediana) com a compreensão de seus significados e relacioná-los com a dispersão de dados, indicada pela amplitude.
 
   (EM11MT03) Realizar pesquisas, considerando: o planejamento, a discussão (se será censitária ou por amostra), a seleção de amostras, a elaboração e aplicação de instrumentos de coleta, a organização e representação dos dados (incluindo agrupamentos de dados em classe), a construção de gráficos apropriados (incluindo o histograma), a interpretação e a análise crítica apresentadas em relatórios descritivos.

.. admonition:: Desdobramentos imediatos

   (EM15MT06) Analisar criticamente os métodos de amostragem em relatórios de pesquisas divulgadas pela mídia e as afirmativas feitas para toda a população baseadas em uma amostra.
   
   
.. admonition:: Abordagem do Capítulo

   Pretende-se ao longo do capítulo, além de apresentar as definições das variadas medidas, enfatizar suas propriedades. Por exemplo, no caso da média, pretende-se explorar as seguintes propriedades:

   #. a média de um conjunto de números é um valor entre os valores extremos deste conjunto;
   #. a soma dos desvios da média é sempre zero para qualquer conjunto de números;
   #. a média é influenciada por todos os valores no conjunto;
   #. a média pode ser um valor que não pertence ao conjunto analisado;
   #. a média é um valor representativo do conjunto analisado.

   Após definir a média e explorar algumas de suas propriedades, pretende-se apresentar situações em que ela pode ser inadequada como valor representativo de uma distribuição (distribuições com forte assimetria), motivando assim a definição da mediana, uma medida que é pouco afetada por valores extremos.

   Uma vez definidas média e mediana, pretende-se apresentar uma situação em que ambas podem ser consideradas inadequadas como valores representativos de uma distribuição (distribuições bimodais simétricas), motivando assim a definição da moda.

   Em adição às medidas de posição, medidas de dispersão complementam a descrição de uma distribuição. A motivação para a necessidade de definir medidas de dispersão será realizada com base num exemplo com dados reais em que todos os conjuntos apresentam média, mediana e moda coincidentes, mas apresentam distribuições empíricas diferentes (traduzidas no diagrama de pontos). 

   Finalmente, após a definição das medidas de dispersão, será proposta uma atividade na qual variados conjuntos de dados apresentam a mesma variância. A finalidade dessa atividade será avaliar a magnitude da variância em relação ao conjunto e definir o coeficiente de variação amostral, usado para avaliar essa magnitude. 
 
   Na seção **Aprofundando o assunto** pretende-se definir o esquema dos cinco números - mínimo, quartis e máximo - usado na construção do boxplot. Os boxplots são gráficos simples e muito usados na comparação de diferentes conjuntos de dados. Na construção do boxplot, será apresentado o critério adotado para considerar um valor do conjunto como valor destoante em relação aos demais valores do conjunto de dados. 

 
.. admonition:: Diferencial do Capítulo 

   De acordo com Russel e Mokros (1991), citados em Batanero e Borovnik (2016), a compreensão da ideia de "valor representativo" implica em três competências diferentes:

   #. selecionar o melhor valor representativo para um dado conjunto de dados;
   #. construir um conjunto de dados tendo um determinado valor representativo, por exemplo, a moda;
   #. compreender o efeito que uma mudança em parte dos dados tem sobre os possíveis valores representativos.

   Pretende-se explorar estas três competências nas atividades e exercícios do capítulo.

   Embora a fórmula de cálculo da variância seja necessária, evitaremos seu uso direto, isto é, exploraremos o uso da tecnologia para obter variância, desvio padrão e demais medidas trabalhadas no capítulo.
 
   A definição de quartis e a construção do boxplot são propostas inovadoras em relação ao conteúdo usual de Estatística nos livros didáticos do Ensino Médio. Os conceitos relativamente simples de quartis aliados  à grande utilidade do boxplot na comparação de grupos diferentes, reforçam a pertinência em tratá-los no Ensino Médio.
   
.. admonition:: Dificuldades típicas dos estudantes (distratores)

   Com base no texto de Batanero e Borovnik (2016), apesar da maior parte dos métodos de análise exploratória de dados envolverem apenas cáculos e interpretações de medidas estatísticas simples, bem como, construções de gráficos e suas respectivas leituras, pesquisadores sugerem que os estudantes apresentam problemas na compreensão de conceitos, e em relacionar estes conceitos ao contexto de forma significativa. Uma razão para isso é que, em geral, os professores focam sobre a aplicação de métodos em vez da interpretação de resultados em um dado contexto. Neste texto, um resumo de resultados de pesquisas realizadas neste tema é apresentado. A seguir, algumas das dificuldades são destacadas.

   #. Cálculo de médias combinadas (quando pede-se para combinar médias de diferentes grupos, muitos estudantes não levam em conta os tamanhos dos diferentes grupos,  calculando uma média simples das médias dos grupos.
   #. Cálculo de média para dados agrupados: ignora-se a frequência, considerando apenas os pontos médios dos intervalos, somando-os e dividindo pelo número de intervalos, ou simplesmente, considerando apenas o valor da variável, quando a variável é quantitativa discreta.
   #. Compreensão das medidas de posição: média, mediana e moda.
   #. Interpretação dos valores obtidos no contexto considerado.
 
   Observação: os dois primeiros estendem-se para o cálculo da variância e do desvio padrão.
 
   Os distratores serão explorados nas atividades e nos exercícios.
     
.. admonition:: Exemplos
   
   Princípios norteadores dos exemplos selecionados: 
  
   #. propor problemas cuja solução requer dados a serem coletados pelos alunos ou que de alguma forma estão disponíveis para consulta.
   #. contextualizar sempre os problemas propostos, pois o contexto é fundamental nas investigações e interpretações.
    
.. admonition:: Estratégia pedagógica 

   Usar um processo reflexivo baseado no pensamento estatístico. 
    
   #. Fórmulas e algoritmos para obter as medidas resumo, embora importantes neste capítulo, não serão valorizados. 
   #. Dar importância à compreensão dos conceitos e à interpretação dos resultados. 
   #. As atividades deverão estar sempre bem caraterizadas a um problema a ser resolvido em um contexto específico.
   #. 	Neste capítulo, o uso de recursos tecnológicos para a realização dos cálculos de medidas resumo é fundamental. Recomenda-se o GeoGebra e planilhas de cálculo. 
 
.. admonition:: Estrutura
  
   **Explorando 1** Nesta seção serão trabalhadas duas atividades. A primeira servirá como motivação para compreender a necessidade mínima de duas medidas para caracterizar uma distribuição e, a segunda, focará especificamente no cálculo de medidas de posição tais como média, mediana e moda, que já devem ser conhecidas do Ensino Fundamental. Também proporemos a divisão do conjunto de dados em quatro intervalos de classes de frequências iguais a 1/4 para definir os três quartis de uma distribuição.
 
   #. Atividade: Distribuição de notas para perceber o efeito de transformações simples (multiplicação e/ou adição de um valor) no dado na posição e escala(forma) da distribuição, comparando histogramas. 
 
   #. Atividade: Apresentação de diferentes conjuntos de dados sobre tempos para completar uma “maratona” que apresentam diferentes formas de distribuição (assimétricas e simétricas).
            
   **Organizando as ideias. 1** 
 
   Definições de:
 
   #. Média; 
   #. Mediana;
   #. Moda e 
   #. Quartis
 
   de um conjunto de valores.
 
   Inclusão de uma caixa para descrição do tratamento de dados agrupados. 
 
   **Praticando 1** Atividades explorando os conceitos  e propriedades apresentados no organizando 1, incluindo atividades com dados agrupados.
       
   **Explorando -2 .** Proposição de uma atividade envolvendo alguns conjuntos de dados reais, todos com medidas de posição iguais, mas apresentando diferenças em suas distribuições caracterizando a necessidade da medida de dispersão.
 
   **Organizando as ideias 2** 
 
   Definições de 
 
   #. amplitude; 
   #. amplitude interquartílica;
   #. desvio-médio;
   #. variância e 
   #. desvio-padrão
 
   de um conjunto de valores.
 
   Inclusão de uma caixa para descrição do tratamento de dados agrupados. 
 
   Inclusão de uma caixa para reforçar a diferença entre estatística e parâmetro, tratadas no capítulo "A Natureza da Estatística" apresentando a definição de variância populacional e amostral, idem para desvio-padrão populacional e amostral.
 
     
   **Praticando 2** 
 
   Atividades que usarão os conceitos e propriedades apresentados no organizando 2.

   **Explorando 3**
 
   Atividade: Apresentar conjuntos de dados, todos com a mesma variância, mas com medidas de posição diferentes.
 
   **Organizando 3**
 
   Definição de coeficiente de variação amostral.
 
   **Praticando 3**
 
   Atividades usando a noção de coeficiente de variação 
 
 
   **Aprofundando o assunto**
 
   #. Definição do desenho esquemático (boxplot) outro tipo de representação gráfica para variáveis quantitativas.
 
   #. Descrição do critério de classificação de um valor como valor destoante do conjunto de dados.
  
   #. Construção do boxplot, usando tecnologia.
 
   **Material Suplementar**
 
   #. Statlet: são dois *applets* para treinar uma compreensão intuitiva da média, mediana, desvio padrão a partir de um gráfico de barras para variáveis discretas.
      
   #. `média e mediana <http://www.math.usu.edu/~schneit/Statlets/center/center.html.html>`_
   #.  `média e desvio padrão <http://www.math.usu.edu/~schneit/Statlets/StandardDeviation/sd.html>`_
    
   #. Rossman/Chance `link <http://www.rossmanchance.com/applets/Dotplot.html>`_: *Applet* mostrando um histograma e um boxplot simultaneamente para aprender como estas representações revelam a distribuição. 

   **Exercícios** 
 
   Serão propostos exercícios do ENEM, Vestibulares entre outros abordando os conteúdos desse capítulo, a saber, medidas de posição e dispersão e suas interpretações. Nos exercícios serão tratados os distratores.

 

.. admonition:: Referências bibliográficas

   ABE (2015) ABE: Reflexões a respeito dos conteúdos de probabilidade e estatística na escola no Brasil - uma proposta. Disponível em: <https://goo.gl/OBtwpv>. Acesso em: 18 ago. 2017. 

   Batanero, C., Burrill, G., & Reading, C. (Eds.). (2011). Teaching statistics in school mathematics-challenges for teaching and teacher education: A joint ICMI/IASE study: the 18th ICMI study (Vol. 14). Springer Science & Business Media.
      
   Batanero, C., & Borovcnik, M. (2016). Statistics and probability in high school. Springer.
  
   Bussab, W. O. & Morettin, P. A. (2017). Estatística Básica.  Saraiva. Nona edição.
  
   Rossman, Allan J., and Beth L. Chance. Workshop Statistics:: Discovery With Data and Minitab. Springer Science & Business Media, 1998.  
  



 
  
  

       



