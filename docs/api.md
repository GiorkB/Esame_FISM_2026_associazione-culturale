# API

In questa repository l'API è simulata tramite il file locale data.json.  
Il file data.json contiene eventi culturali con date, luoghi, tipo e pubblico.  
Tutti i campi del file sono utilizzati e vengono mostrati nella pagina degli eventi con una visualizzazione a card.
Il file script.js carica i dati con:
```bash
fetch("data.json")
```
Quindi il progetto deve essere aperto tramite un piccolo server locale.