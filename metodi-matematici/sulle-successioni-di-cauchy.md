## Successioni di Cauchy
Le successioni sono studiate estensivamente in quanto alla base di nozioni di analisi matematica come la continuita' e l'esistenza.
L'idea delle successioni di Cauchy e' che da un certo elemento della successione $X_n$  in poi, tutti gli elementi tendono a stare in una sfera di raggio $\epsilon$.

### teorema
Una successione di Cauchy e' LIMITATA
Estendendo $\epsilon$ dalla distanza dal centro scelto per la definizione di successione di Cauchy alla *distanza dall'elemento di partenza*. Facendo cosi' e' immediato notare che tutti gli elementi della successione sono in tale sfera (garantito dal fatto che nonostante la successione sia di infiniti termini, dal termine $X_0$ a $X_n$ ci sono finiti elementi).

### nota bene
Le successioni di Cauchy **non sono sempre convergenti**. Tuttavia sono le uniche successioni in grado di convergere!
Ad esempio una successione a valori in $\mathbb{Q}$ potrebbe convergere ad un valore in $\mathbb{R}$: tale successione potrebbe essere di Cauchy in $\mathbb{Q}$ perche' di Cauchy in $\mathbb{R}$, senza pero' convergere in $\mathbb{Q}$.
- **Una successione convergente sicuramente e' di Cauchy**
- **Se una successione non e' di Cauchy _sicuramente non converge_**


## Spazi completi
Uno spazio _metrico_ in cui tutte le successioni di Cauchy convergono si dice **completo**, in particolare contiene tutti i punti di accumulazione.
Quindi $\mathbb{Q}$ non e' uno spazio completo, ed il suo completamento e' proprio l'insieme $\mathbb{R}$.
