# Pagine regalo — Sogni ed Emozioni e Top Crociere

Web app (PWA) pubblicata su **https://regali.sogniedemozioni.it** con GitHub Pages.

- `?e=CODICE` → pagina regalo da condividere con gli invitati (partecipazione + dati per il bonifico)
- `?p=CODICE` → area riservata del festeggiato (dediche, quote confermate, QR da stampare)

I dati arrivano da TopHub (Apps Script, `doGet ?regalo=1`). Le quote inviate dalla pagina entrano
in TopHub come "In attesa" e l'agenzia le conferma quando arriva il pagamento.
Nessun dato dei clienti è salvato in questo repository.
