# tesi_git



### DA FARE:

- Non è possibile fare 'of X T' con X che sia un adt (e non un term)

- Tipaggio LET-IN

- Tipaggio CASE

- È bene avere gli ADT tutti dello stesso tipo ('adt')? Oppure andrebbero differenziati nei vari tipi (nat, list, tree, option) con 'adt' come sovratipo generale?
  (Osservazione: Potrebbe essere meglio differenziarli perché in questo modo si potrebbero differenziare anche i tipi dei rami del case, anziché controllare soltanto che siano tutti adt)



### BOZZE:

idea 1)
 
 type adt tipo.

 of (nat 0) adt.
 of (succ N) adt.
 of (tree T) adt.
 % ...


idea 2)

 type adt term.

 % Quindi è possibile fare 'of X T' con X che sia un adt (perché vale come term)
