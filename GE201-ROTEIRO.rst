.. _rot-tales:

*************************
ROTEIRO: TEOREMA DE TALES
*************************

.. admonition:: Roteiro

 .. admonition:: Previsão de aulas necessárias
 
    Entre 4 e 6 aulas de 50 minutos cada, a ser avaliado no final do desenvolvimento.

 .. admonition:: Previsão de páginas necessárias
 
    A ser visto no final da elaboração do capítulo

 .. admonition:: Habilidade
    
    **(EM12MT01)** Compreender o teorema de Tales e aplicá-lo em demonstrações e na resolução de problemas, incluindo a divisão de segmentos em partes proporcionais.

 .. admonition:: Objetivos gerais
    
    Levar o estudante a perceber a proporcionalidade de segmentos. Ele deverá compreender o enunciado do teorema sua demonstração no caso de segmentos comensuráveis.
    
    O aluno deverá ainda aprender a aplicar o teorema em problemas práticos do mundo da geometria e do mundo real.


 .. admonition:: Conteúdos abordados
    
    #. Razão entre segmentos
    #. Retas paralelas equidistantes
    #. Enunciado e demonstração (parcial) do teorema de Tales
    #. Aplicações
    #. Primeiras técnicas de demonstração


 .. admonition:: Pré-requisitos

   **(EF08MA12)** Demonstrar propriedades de quadriláteros por meio da identificação da congruência de triângulos.
   
   **(EF09MA10)** Demonstrar relações simples entre os ângulos formados por retas paralelas cortadas por uma transversal.

 .. admonition:: Desdobramentos imediatos
   
   **(EM12MT02)** Resolver e elaborar problemas utilizando a semelhança de triângulos e o teorema de Pitágoras, incluindo aqueles que envolvem o cálculo das medidas de diagonais de prismas, de altura de pirâmides, e aplicar esse conhecimento em situações relacionadas ao mundo do trabalho.
   
   **(EM12MT03)** Utilizar a noção de semelhança para compreender as razões trigonométricas no triângulo retângulo, suas relações em triângulos quaisquer e aplicá-las em situações como o cálculo de medidas inacessíveis, entre outras.


 .. admonition:: Abordagem 
 
   * Usaremos inicialmente duas atividades que possuem o objetivo de recordar os temas abordados no 9º ano e que são pré-requisitos básicos para a compreensão deste capítulo. Após essas atividades aparecerá um texto com as ideias organizadas que será de grande importância para o aluno que estiver estudando sozinho.
   
   * A seguir, o capítulo se inicia com uma atividade motivadora onde, em alguma situação contextualizada, retas paralelas e razões serão os ingredientes para a resposta de alguma pergunta. 
   
   * As atividades de desenvolvimento do capítulo serão feitas de forma a encaminhar o aluno para uma demonstração (parcial) do Teorema de Tales.
   
   * O aluno então realizará a demonstração do teorema no caso de segentos comensuráveis. Consideramos essa abordagem perfeitamente adequada, pois nas aplicações, todas as medidas dos segmentos serão expressas por números racionais.
   
   * Após essas atividades aparecerá um texto com as ideias organizadas e com comentários sobre a demonstração geral, e sobre a recíproca do teorema.
   
   * Duas atividades seguintes mostrarão aplicações e os Exercícios mostrarão diversas outras.

 .. admonition:: Distratores
 
  As dificuldades típicas dos alunos referem-se principalmente às figuras. Eles compreendem bem o teorema na sua figura básica, mas em outras situações têm dificuldade em reconhecer, nelas, a aplicação do teorema de Tales. 
   
  Digamos que a figura básica tenha sido a abaixo.
   
   .. tikz:: figuras amigáveis
     \draw [line width=1.pt] (0.,1.)-- (7.,1.);
     \draw [line width=1.pt] (3.45,1.12) -- (3.45,0.88);
     \draw [line width=1.pt] (3.55,1.12) -- (3.55,0.88);
     \draw [line width=1.pt] (0.,0.)-- (7.,0.);
     \draw [line width=1.pt] (3.45,0.12) -- (3.45,-0.12);
     \draw [line width=1.pt] (3.55,0.12) -- (3.55,-0.12);
     \draw [line width=1.pt] (0.,-2.)-- (7.,-2.);
     \draw [line width=1.pt] (3.45,-1.88) -- (3.45,-2.12);
     \draw [line width=1.pt] (3.55,-1.88) -- (3.55,-2.12);
     \draw [line width=1.pt] (4.,1.52)-- (6.,-3.);
     \draw [line width=1.pt] (2.98,1.54)-- (0.,-3.);
     \draw [fill=black] (2.63,1.) circle (2.0pt);
     \draw [fill=black] (1.97,0.) circle (2.0pt);
     \draw [fill=black] (0.66,-2.) circle (2.0pt);
     \draw [fill=black] (4.23,1.) circle (2.0pt);
     \draw [fill=black] (4.67,0.) circle (2.0pt);
     \draw [fill=black] (5.56,-2.) circle (2.0pt);

  Os alunos resolverão muito bem situações que se pareçam com essa, mas alguns terão natural dificuldade em identificar que, nas figuras seguintes, o mesmo teorema se aplica.
   
  
  .. tikz:: testando
    \draw [line width=1.pt] (-2.,-3.)-- (3.,0.);
    \draw [line width=1.pt] (3.,0.)-- (2.,-3.);
    \draw [line width=1.pt] (2.6296533840669043,-1.4905131670194958) -- (2.40196939253478,-1.4146185031754537);
    \draw [line width=1.pt] (2.5980306074652195,-1.585381496824547) -- (2.3703466159330957,-1.5094868329805051);
    \draw [line width=1.pt] (2.,-3.)-- (-2.,-3.);
    \draw [line width=1.pt] (1.3323529411764703,-1.0005882352941178)-- (0.6658823529411763,-3.);
    \draw [line width=1.pt] (1.1287710311257282,-1.990807284666554) -- (0.9010870395936043,-1.914912620822512);
    \draw [line width=1.pt] (1.0971482545240436,-2.0856756144716053) -- (0.8694642629919197,-2.0097809506275635);
    \draw [line width=1.pt] (4.,0.)-- (6.,-1.);
    \draw [line width=1.pt] (5.00894427191,-0.37030805730501226) -- (4.90161300899001,-0.584970583144993);
    \draw [line width=1.pt] (5.098386991009991,-0.41502941685500877) -- (4.991055728090001,-0.6296919426949895);
    \draw [line width=1.pt] (6.,-1.)-- (3.,-3.);
    \draw [line width=1.pt] (4.,0.)-- (7.,-5.);
    \draw [line width=1.pt] (7.,-5.)-- (3.,-3.);
    \draw [line width=1.pt] (4.991055728090001,-4.129691942694989) -- (5.098386991009991,-3.9150294168550084);
    \draw [line width=1.pt] (4.90161300899001,-4.084970583144995) -- (5.00894427191,-3.8703080573050137);
    \draw [line width=1.pt] (8.,0.)-- (9.,-1.);
    \draw [line width=1.pt] (8.549497474683061,-0.379791847198288) -- (8.37979184719829,-0.5494974746830584);
    \draw [line width=1.pt] (8.620208152801714,-0.45050252531694335) -- (8.450502525316942,-0.6202081528017137);
    \draw [line width=1.pt] (8.,0.)-- (8.,-3.);
    \draw [line width=1.pt] (9.,-1.)-- (9.528,-4.528);
    \draw [line width=1.pt] (9.84,-0.16)-- (12.874256872973351,-1.1817431270266496);
    \draw [line width=1.pt] (8.,-0.7)-- (9.1232,-1.8232);
    \draw [line width=1.pt] (8.61109747468306,-1.1413918471982862) -- (8.441391847198288,-1.3110974746830566);
    \draw [line width=1.pt] (8.681808152801713,-1.2121025253169415) -- (8.51210252531694,-1.3818081528017119);
    \draw [line width=1.pt] (9.,-1.)-- (9.84,-0.16);
    \draw [line width=1.pt] (9.26443650813896,-0.565857864376271) -- (9.434142135623732,-0.7355634918610413);
    \draw [line width=1.pt] (9.335147186257615,-0.4951471862576156) -- (9.504852813742389,-0.664852813742386);
    \draw [line width=1.pt] (9.405857864376271,-0.42443650813896033) -- (9.575563491861043,-0.5941421356237307);
    \draw [line width=1.pt] (9.1232,-1.8232)-- (10.54799327036045,-0.3984067296395521);
    \draw [line width=1.pt] (9.680033143319182,-1.0966612291960456) -- (9.849738770803956,-1.266366856680816);
    \draw [line width=1.pt] (9.750743821437839,-1.0259505510773914) -- (9.92044944892261,-1.195656178562162);
    \draw [line width=1.pt] (9.821454499556493,-0.9552398729587374) -- (9.991160127041267,-1.1249455004435078);
    \draw [line width=1.pt] (9.528,-4.528)-- (12.874256872973351,-1.1817431270266496);
    \draw [line width=1.pt] (11.045564944625635,-2.8407294278895945) -- (11.215270572110407,-3.0104350553743653);
    \draw [line width=1.pt] (11.11627562274429,-2.7700187497709394) -- (11.285981250229062,-2.93972437725571);
    \draw [line width=1.pt] (11.186986300862946,-2.699308071652284) -- (11.356691928347718,-2.8690136991370543);
    \draw [line width=1.pt] (8.,-3.)-- (9.528,-4.528);
    \draw [line width=1.pt] (8.813497474683063,-3.6437918471982873) -- (8.64379184719829,-3.81349747468306);
    \draw [line width=1.pt] (8.884208152801715,-3.71450252531694) -- (8.714502525316943,-3.884208152801713);
    \draw [fill=black] (2.,-3.) circle (2.0pt);
    \draw [fill=black] (3.,0.) circle (2.0pt);
    \draw [fill=black] (1.3323529411764703,-1.0005882352941178) circle (2.0pt);
    \draw [fill=black] (4.,0.) circle (2.0pt);
    \draw [fill=black] (6.,-1.) circle (2.0pt);
    \draw [fill=black] (5.,-1.6666666666666667) circle (2.0pt);
    \draw [fill=black] (3.,-3.) circle (2.0pt);
    \draw [fill=black] (7.,-5.) circle (2.0pt);
    \draw [fill=black] (-2.,-3.) circle (2.0pt);
    \draw [fill=black] (0.6658823529411763,-3.) circle (2.0pt);
    \draw [fill=black] (9.1232,-1.8232) circle (2.0pt);
    \draw [fill=black] (10.54799327036045,-0.3984067296395521) circle (2.0pt);
    \draw [fill=black] (8.,0.) circle (2.0pt);
    \draw [fill=black] (8.,-0.7) circle (2.0pt);
    \draw [fill=black] (8.,-3.) circle (2.0pt);
    \draw [fill=black] (9.528,-4.528) circle (2.0pt);
    \draw [fill=black] (12.874256872973351,-1.1817431270266499) circle (2.0pt);
    \draw [fill=black] (9.84,-0.16) circle (2.0pt);
    \draw [fill=black] (9.,-1.) circle (2.0pt);

 .. admonition:: Exemplos 

   Serão apresentados exemplos diversos, uns contextualizados no mundo real, outros no mundo da matemática abordando algum conceito novo.

   
   .. admonition:: Exemplo 1: A projeção paralela conserva as razões
   
    Esta é uma oportunidade para abordar um conceito novo como o de projeção. 
    A figura a seguir mostra a projeção sobre a reta `r` paralelamente à reta `s`.
      
      .. tikz:: projeção
        \draw [line width=2.pt] (0.,-5.)-- (10.,-5.);
        \draw (9.78,-4.9) node[anchor=north west] {$r$};
        \draw [line width=2.pt] (-0.04,-1.74)-- (1.56,1.5);
        \draw (1.58,1.8) node[anchor=north west] {$s$};
        \draw [line width=2.pt] (3.28,-0.62)-- (9.,1.);
        \draw [line width=2.pt] (3.28,-0.62)-- (1.1170370370370366,-5.);
        \draw [line width=2.pt] (2.132101471650325,-2.944494519908092) -- (2.037125094628808,-2.7302995437581674);
        \draw [line width=2.pt] (2.132101471650325,-2.944494519908092) -- (2.359911942408229,-2.889700456241832);
        \draw [line width=2.pt] (5.214741107099608,-0.07204884728997098)-- (2.781184982304532,-5.);
        \draw [line width=2.pt] (3.9315459978338776,-2.6705189435530774) -- (3.836569620812361,-2.456323967403153);
        \draw [line width=2.pt] (3.9315459978338776,-2.6705189435530774) -- (4.159356468591782,-2.6157248798868173);
        \draw [line width=2.pt] (9.,1.)-- (6.037037037037036,-5.);
        \draw [line width=2.pt] (7.452101471650324,-2.134494519908091) -- (7.357125094628807,-1.9202995437581665);
        \draw [line width=2.pt] (7.452101471650324,-2.134494519908091) -- (7.679911942408228,-2.079700456241831);
        \draw (2.82,0.22) node[anchor=north west] {$A$};
        \draw (4.88,0.7) node[anchor=north west] {$P$};
        \draw (8.54,1.74) node[anchor=north west] {$B$};
        \draw (0.76,-4.96) node[anchor=north west] {$A'$};
        \draw (2.52,-4.96) node[anchor=north west] {$P'$};
        \draw (5.78,-4.92) node[anchor=north west] {$B'$};
        \draw [fill=black] (1.1170370370370366,-5.) circle (2.0pt);
        \draw [fill=black] (2.781184982304532,-5.) circle (2.0pt);
        \draw [fill=black] (6.037037037037036,-5.) circle (2.0pt);
        \draw [fill=black] (3.28,-0.62) circle (2.0pt);
        \draw [fill=black] (5.214741107099608,-0.07204884728997098) circle (2.0pt);
        \draw [fill=black] (9.,1.) circle (2.0pt);
     
    O que é relevante nessa situação é que `\frac{PA}{PB}=\frac{P'A'}{P'B'}`
     
    A projeção mantém as razões.
  
  
   .. admonition:: Exemplo 2: Cidades Planejadas
   
    A figura a seguir mostra a maquete de uma cidade que está sendo planejada.
    
    .. _fig-maquete:
    .. figure:: _resources/maquete.jpg
    
     :width: 200px
     :align: center
   
    Há diversas possibilidades para explorar o Teorema de Tales nessa maquete.
   
    Com as medidas do terreno da frente, podemos, por exemplo, calcular as medidas dos fundos


.. admonition:: Estrutura

 .. admonition:: Para o professor do Capítulo
 
  Comunicar claramente a habilidade que será desenvolvida no capítulo.
 
  Apresentar um destaque (janela com uma tag) mencionando os pré-requisitos necessários.
 
  Apresentar um destaque (janela com uma tag) trazendo algumas imagens sobre o tema.
 
 .. admonition:: Textos para o aluno
 
  Iniciar com texto destacando o papel fundamental que o tópico desempenha na matemática.
 
  Elaborar os textos para o aluno permeando as atividades de forma que a reunião dos textos tenha coerência e completude de forma que o leitor solitário possa compreender o assunto de forma autônoma.

 .. admonition:: Explorando o assunto: o que é um teorema? 
 
  Apresentar a implicação lógica e mostrar seu significado.
 
  Mostrar a estrutura de um teorema e em particular, o enunciado do teorema de Tales.
 
  Pesquisar se os alunos conhecem outros teoremas.
 
  Dizer o que segnifica a recíproca de um teorema, dar exemplos e, em particular, enunciar a recíproca do teorema de Tales.

 .. admonition:: Organizando as ideias: o que é uma demonstração?
 
  Explicar o que é uma demonstração no sentido de partir da hipótese, reunir argumentos, conectar fatos e concluir a tese.
  
  Elaborar uma atividade com a demonstração de um teorema simples de geometria relacionado a conhecimento anterior. Por exemplo, o fato de que a soma dos ângulos internos de qualquer triângulo é `180^\circ`.
  
  Explicar o que significa uma definição.

 .. admonition:: Praticando o assunto: aplicações 
 
  Elaborar atividade conduzindo o aluno a compreender e demonstrar o teorema das paralelas equidistantes cortadas por duas transversais.
  
  Elaborar atividade conduzindo o aluno a compreender e demonstrar o teorema de Tales no caso dos segmentos comensuráveis.
  Mostrar aplicações em situações diversas, contextualizadas ou não.

 .. admonition:: Aprofundando
 
  Comentar que dois segmentos nem sempre são comensuráveis e explicar o significado desse conceito.
  
  Mostrar a demonstração do teorema de Tales usando áreas. Essa demonstração desloca, naturalmente, a questão da continuidade para mais adiante.

 .. admonition:: Primeiras técnicas de demonstração 
 
  Mostrar o significado da demonstração por absurdo.
 
  Explicar o que significa que “algo é único” e de que forma se pode demonstrar uma proposição desse tipo. Por exemplo, “Por um ponto dado é possível traçar uma única perpendicular a uma reta dada”.
 
  Exemplificar uma demonstração por absurdo com a recíproca do teorema de Tales.

 .. admonition:: Exercícios do capítulo
 
  Serão elaborados 10 exercícios envolvendo situações variadas, algumas contextualizadas, e outras solicitando alguma demonstração. Nesses casos, serão dadas sugestões para que o aluno possa iniciar sua tentativa.


           
    






 
 





