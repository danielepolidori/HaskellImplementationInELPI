# tesi_git



### DA FARE:

- ADT (i vari singoli adt li cancello o li uso come ipotesi dei test?)

- Tipaggio CASE (sistemare secondo le nuove modifiche)

- Test CASE

- Tipaggio LET-IN

- IF-THEN-ELSE come pattern matching



### DOMANDE:

- Come si fa l'if-then-else in elpi?
  
  (Risposta: ite è pattern matching sui booleani, ite è solo zucchero sintattico; posso anche introdurla come sintassi a sé stante)

  % Però così sto introducendo una nuova sintassi, e soprattutto non sto facendo pattern matching
  Idea:
       type if_then_else bool -> term -> term -> term.
       if_then_else tt X Y :- X.
       if_then_else ff X Y :- Y.
