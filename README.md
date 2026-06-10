# Selezione video Tuttobatterie

Pagina statica HTML per mostrare al cliente i video generati con AI e raccogliere una scelta per ogni video: `OK` oppure `Non OK`.

## Cosa contiene

- `index.html`: pagina principale con player video, sezioni prodotto e pulsanti di invio.
- Cartelle video:
  - `motobat`
  - `nba-ermetica`
  - `nba-piana`
  - `vesna`

## Funzionamento

Le scelte vengono salvate nel browser del cliente tramite `localStorage`.

I pulsanti finali permettono di inviare il riepilogo direttamente a Pietro:

- via WhatsApp
- via email

Il riepilogo include solo i video selezionati, quindi i video senza scelta non vengono inviati.

## Pubblicazione

Il progetto e' statico e puo' essere pubblicato direttamente su Vercel collegando questo repository GitHub.

Non richiede build step, backend o dipendenze esterne.
