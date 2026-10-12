LA MIA DISPENSA — INSTALLAZIONE

CONTENUTO
- index.html: interfaccia
- app.js: logica e salvataggio locale
- manifest.json, icon.svg: installazione come app web
- sw.js: cache offline (richiede hosting HTTPS)

IMPORTANTE SUL SALVATAGGIO
I dati si salvano automaticamente nel browser/dispositivo dove inserisci gli alimenti.
Non c'è sincronizzazione cloud automatica tra dispositivi in questa versione.
Per trasferire i dati: apri Dati e backup > Scarica backup sul primo dispositivo; trasferisci il file JSON; sul secondo dispositivo apri Dati e backup > Importa un backup.
Non cancellare i dati del browser senza prima esportare un backup.

COME PUBBLICARLA GRATIS CON GITHUB PAGES
1. Sul computer vai su github.com e crea un account, se non ne hai uno.
2. Crea un nuovo repository pubblico chiamato la-mia-dispensa.
3. Carica tutti i file di questa cartella nella radice del repository.
4. Nel repository apri Settings > Pages.
5. In "Build and deployment", scegli "Deploy from a branch", seleziona "main" e "/ (root)", quindi Save.
6. Attendi la pubblicazione. L'indirizzo sarà simile a https://TUO-UTENTE.github.io/la-mia-dispensa/ .
7. Apri quell'indirizzo su ciascun dispositivo.

AGGIUNGERLA ALLA SCHERMATA HOME
iPhone/iPad (Safari): apri l'indirizzo pubblicato > Condividi > Aggiungi alla schermata Home > Aggiungi.
Android (Chrome): apri l'indirizzo > menu ⋮ > Installa app o Aggiungi a schermata Home.
Computer: apri l'indirizzo in Chrome/Edge; usa l'icona Installa se disponibile oppure crea un collegamento.

LIMITI DEL PROTOTIPO
- I dati sono salvati localmente nel browser.
- Per sincronizzazione automatica multi-dispositivo serve un backend/cloud da configurare.
- Le ricette sono dimostrative e controllano la presenza degli ingredienti per nome, non le quantità esatte.
- Le quantità consumate non vengono sottratte automaticamente: dopo aver cucinato, aggiornale manualmente.
- I dati iniziali sono vuoti: inserisci i tuoi alimenti reali.
