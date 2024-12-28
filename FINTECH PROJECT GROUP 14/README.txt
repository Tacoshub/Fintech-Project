Il codice è intereamente scritto su python, abbiamo usato jupyter notebook come editor per poter inserire commenti.
Consigliamo di aprire i notebook nel seguente ordine:

1)Lasso Regression Validation. Qui alleniamo il modello di regressione lineare con lasso penalty sia nel caso di weekly rebalancing che nel caso di monthly rebalancing

2)Lasso Regression Test. Qui osserviamo la performance del nostro modello sul test set.

3)Feature selection. Qui discutiamo brevemente il raziocinio utilizzato per la selezione delle feature da inserire nel kalman filter

4)Kalman Filter. Qui implementiamo il kalman filter e vediamo come si comporta nel validation set senza nessuna ottimizzazione di parametri.
Lo scopo è confrontare l'andamento base con quello della lasso regression

5)Neural Network Anomaly Detection. Qui implementiamo e ottimizziamo una rete neurale per riuscire future anomalie di mercato. Alla fine del codice dovrebbe essere creato un nuovo file excel, VALORI_PREDETTI. Lo inseriamo già dentro la cartella sperando che non si creino problemi con la gestione dei file durante la creazione.

6)Kalman Filter Validation. Qui cerchiamo l'iperparametro ottimale per il treshold del classificatore allo scopo di ottimizzare il nostro modello.

7)Kalman Filter Test. Proviamo la performance del nuovo modello al variare del parametro alfa di esposizione.

Presentazione: nella cartella puó trovare una presentazione pdf del nostro progetto, nel caso Le interessasse al seguente link potrà trovare una presentazionee esteticamente piú bella

https://www.canva.com/design/DAGGOhPhAbo/7hebG9Wt6jVbkB2kBKlU5w/edit?utm_content=DAGGOhPhAbo&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton