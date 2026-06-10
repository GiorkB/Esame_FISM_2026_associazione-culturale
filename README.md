# Esame FISM 2026 Associazione Culturale

Questa repository serve per verificare la comprensione dei concetti sulla creazione di siti multipagina statici con utilizzo di API e JSON locali.
In questo caso, il tema è Associazione Culturale.
Il sito è disponibile su [GitHub Pages](https://giorkb.github.io/Esame_FISM_2026_associazione-culturale/).

## Funzionalità
Il progetto espone queste funzionalità:

- sito statico con multipaging
- homepage che riassume il sito
- pagina eventi che mostra gli eventi dell'associazione presi dalle API
- pagina chi siamo che mostra tabella dei membri del team dell'associazione
- integra un design responsive anche per dispositivi mobili

## Tecnologie
- HTML
- CSS & Bootstrap
- Javascript
- API locali

## Istruzioni per aprire il sito
Questo tema usa `fetch("data.json")` per leggere i dati locali. Per questo motivo il sito deve essere aperto tramite un server locale.  
Per maggiori dettagli, visualizzare [Guida all'installazione](docs/installazione.md).

## Requisiti
- Un browser moderno
- Connessione internet (per Bootstrap e per fetchare i dati delle API)
- API per i dati
- Git installato

## Struttura
Il progetto è organizzato in questo modo:

```text
nome-progetto/
├── README.md
├── index.html
├── eventi.html
├── chi-siamo.html
├── style.css
├── script.js
├── data.json
├── docs/
│   ├── installazione.md
│   ├── faq.md
│   └── api.md
└── assets/
    └── immagini/
```

## Documentazione
- [Guida all'installazione](docs/installazione.md)
- [Domande frequenti](docs/faq.md)
- [Dettagli sulle API](docs/api.md)

## Autore
L'autore di questa repository è Gianmarco Bonanomi.