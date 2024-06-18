# PHP Hotel

## Descrizione

- Partiamo da questo array di hotel. https://www.codepile.net/pile/OEWY7Q1G
- Stampare tutti i nostri hotel con tutti i dati disponibili.

```txt
Iniziate in modo graduale.
Prima stampate in pagina i dati, senza preoccuparvi dello stile.
```

- Aggiungete Bootstrap e mostrate le informazioni con una tabella.

## Bonus:

1. Aggiungere un form ad inizio pagina che tramite una richiesta GET permetta di filtrare gli hotel che hanno un parcheggio.
2. Aggiungere un secondo campo al form che permetta di filtrare gli hotel per voto (es. inserisco 3 ed ottengo tutti gli hotel che hanno un voto di tre stelle o superiore)
   #### NOTA:
   - Deve essere possibile utilizzare entrambi i filtri contemporaneamente (es. ottenere una lista con hotel che dispongono di parcheggio e che hanno un voto di tre stelle o superiore)
   - Se non viene specificato nessun filtro, visualizzare come in precedenza tutti gli hotel.

## Svolgimento:

- Copio l' array degli hotel su index.php
- Creo un primo foreach per avere a disposizione tutti gli hotel
- Creo un secondo foreach all'interno del primo per la stampa delle info di ogni hotel modificando la visualizzazione del valore booleano
- Importo Bootstrap tramite CDN
- Creo una tabella usando le classi di bootstrap e cicli e variabili create precedentemente
