# filtro-commenti-tossici
Usando `tensorflow`, costruire un modello in grado di filtrare i commenti degli utenti in base al grado di dannosità del linguaggio

## Descrizione
Viene fornito un dataset di commenti classificati in base a sei distinte categorie di tossicità:

![Primi 10 commenti](first10.png)

Svolgimento:
* Analisi esplorativa
* Preprocessing testo
* Modello naive
* Rete neurale ricorrente con strato LSTM bidirezionale
* Affrontare overfitting con dropout e regolarizzazione L2

![Categorie di commenti](categorie.png)
