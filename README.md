# EPSO AD5 PWA

## Pubblicazione su Vercel
1. Carica questa cartella in un repository GitHub (index.html deve essere nella root).
2. Su Vercel scegli **Add New → Project**, importa il repository.
3. Framework preset: **Other**; nessun build command; output directory lasciata vuota.
4. Premi Deploy e apri l’URL HTTPS generato.

## Installazione
- iPhone: Safari → Condividi → Aggiungi alla schermata Home.
- Android: Chrome → menu → Installa app / Aggiungi a schermata Home.

## Note
I progressi restano nel browser del dispositivo; non si sincronizzano tra dispositivi. Non cancellare i dati del sito senza esportare i progressi. Il funzionamento offline è disponibile dopo il primo caricamento online. Per forzare il rinnovo della cache in future release, incrementa la costante CACHE in sw.js.
