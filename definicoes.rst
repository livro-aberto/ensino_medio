**********
definicoes
**********

  .. |primario| replace:: verde
  .. |primaria| replace:: verde
  .. |primarios| replace:: verdes
  .. |primarias| replace:: verdes

  .. |secundario| replace:: cinza
  .. |secundaria| replace:: cinza
  .. |secundarios| replace:: cinzas
  .. |secundarias| replace:: cinzas

  .. |terciario| replace:: azul claro
  .. |terciaria| replace:: azul clara
  .. |terciarios| replace:: azuis claros
  .. |terciarias| replace:: azuis claras

  .. |atento| replace:: azul escuro
  .. |atenta| replace:: azul escura
  .. |atentos| replace:: azuis escuros
  .. |atentas| replace:: azuis escuras


  .. |destacado| replace:: vermelho
  .. |destacada| replace:: vermelha
  .. |destacados| replace:: vermelhos
  .. |destacadas| replace:: vermelhas
  
As cores são, |primario|, |secundario|, |terciario|, |atento| e |avisado|. Para inserir as cores no texto devemos usar as expressões segundo sua concordância, veja abaixo.::
   
   Escrevendo, obtém-se
   |primario| = verde
   |primarios| = verdes
   |primaria| = verde
   |primarias| = verdes
   
   |secundario| = cinza
   |secundaria| = cinza
   |secundarios| = cinzas
   |secundarias| = cinzas

   |terciario| = azul claro
   |terciaria| = azul clara
   |terciarios| = azuis claros
   |terciarias| = azuis claras

   |atento| = azul escuro
   |atenta| = azul escura
   |atentos| = azuis escuros
   |atentas| = azuis escuras

   |destacado| = vermelho
   |destacada| = vermelha
   |destacados| = vermelhos
   |destacadas| = vermelhas


.. tikz::

   \foreach \cor/\y in {primario/0, secundario/.4, terciario/.8, atento/1.2, destacado/1.6}{
   \fill[\cor] (0,-\y) circle (.2);
   \node at (1.5,-\y) {\cor};
   };
   
   