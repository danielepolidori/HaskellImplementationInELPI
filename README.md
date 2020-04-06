# HaskellImplementationInELPI

Implementazione in ELPI, un linguaggio logico con vincoli di ordine superiore, dell'algoritmo di type inference di Haskell.
ELPI è un'estensione con vincoli di lambda Prolog. Utilizzando lambda Prolog risulta impossibile implementare la type inference di Haskell. Si è reso dunque necessario l'utilizzo di ELPI, più espressivo (non nel senso di Turing completezza) di lambda Prolog.

La presente trattazione ha una duplice finalità.
La prima consiste nel dimostrare che le estensioni a lambda Prolog presenti in ELPI permettono di risolvere problemi non risolvibili in lambda Prolog.
La seconda, non ancora implementata ma lasciata agli sviluppi futuri, prevede di fare del mio lavoro uno strumento di prova per testare, implementare e studiare nuove estensioni al meccanismo delle type class di Haskell. Infatti, essendo ELPI un linguaggio di più alto livello e più semplice (grazie alle features del linguaggio) rispetto ad Haskell, aggiungere estensioni al meccanismo base delle type class dovrebbe risultare banale (in confronto alla complessità di eseguire tale operazione in Haskell).


--
Tesi.
Corso di laurea triennale in informatica.
Alma Mater Studiorum - Università di Bologna.
