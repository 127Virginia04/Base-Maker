BaseMaker — Generatore di Basi (PWA)
====================================

Come usare (rapido)
-------------------
1) Apri `index.html` con Chrome o Safari (meglio da computer per la prima volta).
2) Premi **Avvia** per sbloccare l'audio, poi **Genera progressione** o **Sorprendimi**.
3) Imposta BPM, tonalità e genere. Quando ti piace, premi **Esporta WAV** per scaricare la base.

Installazione come App (iPhone/iPad)
------------------------------------
1) Metti l'intera cartella su un server locale o usa un servizio gratuito (es. GitHub Pages). 
2) Apri l'URL con Safari su iPhone.
3) Tocca **Condividi → Aggiungi alla schermata Home**. 
   Dopo l'installazione, BaseMaker funziona anche **offline**.

Installazione come App (Desktop)
-------------------------------
- Chrome/Edge: visita la pagina, poi **Installa** (icona a forma di monitor con freccia) oppure il bottone "Installa come app".

Suggerimenti
------------
- L'esportazione registra in tempo reale la durata selezionata (4/8/16 misure).
- Se l'audio non parte su iOS, tocca prima **Avvia** (richiesto da iOS per sbloccare l'audio web).

Struttura del progetto
----------------------
- index.html — UI principale
- style.css — stile
- app.js — logica generativa con Tone.js
- manifest.webmanifest, sw.js — per la modalità app/offline
- assets/icon-*.png — icone

Nota
----
Questa è una base solida e funziona subito. In futuro si possono aggiungere:
- Esportazione MIDI per batteria/basso/accordi
- Pattern più ricchi (fill, variazioni, bridge)
- Mixer con stems, sidechain, quantizzazione/swing per traccia
- Campioni di batteria dedicati per ciascun genere
