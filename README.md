Gara Scarichi - Professional System
Il software Gara Scarichi è una soluzione professionale sviluppata per la gestione completa di gare di scarichi (Sound Pressure Level - SPL). Il sistema permette di automatizzare la registrazione dei partecipanti, monitorare in tempo reale i picchi di decibel (dB) tramite connessione seriale e generare classifiche precise e dinamiche in modo rapido e intuitivo.

🚀 Caratteristiche Principali
Gestione Live Piazzola: Interfaccia dedicata per l'operatore con lettura seriale ultra-rapida dei dB in entrata.

Funzionalità "Annulla Lancio": Possibilità di resettare istantaneamente una misurazione errata o una falsa partenza, garantendo fluidità alla competizione.

Monitoraggio Speaker (Record Assoluto): Box dedicato per monitorare e celebrare in tempo reale il record assoluto del raduno per comunicazioni live coinvolgenti.

Database Categorizzato: Gestione automatica e suddivisa per categorie (Auto Benzina, Auto Diesel e Moto).

Classifiche Professionali: Esportazione automatica dei dati in formato CSV, con backup di sicurezza e generazione di file formattati per la condivisione sui social media.

Tabellone Pubblico Integrato: Schermata per il pubblico con aggiornamento in tempo reale dei record e podio finale automatico.

Correzione Manuale: Funzionalità di rettifica rapida dei punteggi tramite un'interfaccia intuitiva.

Auto-Aggiornamento: Il software verifica autonomamente la presenza di nuove versioni all'avvio sfruttando l'integrazione con le Releases di GitHub.

🛠 Requisiti di Sistema
Sistema operativo: Windows 10 o 11.

Hardware: Porta/Connessione seriale (COM) per il collegamento del sensore fonometro.

Prerequisiti: Nessuna installazione di librerie aggiuntive richiesta (pacchetto "tutto incluso" nell'eseguibile standalone tramite PyInstaller: requests, pyserial, tkinter).

📂 Nota Importante sulla Cartella di Lavoro
Si consiglia vivamente di posizionare l'eseguibile in una cartella dedicata. Il programma genera e gestisce autonomamente il file CSV con i dati dei partecipanti e le relative copie di backup al suo interno: tenerlo in una cartella pulita e isolata evita di disperdere i file di dati della gara.

📥 Installazione e Aggiornamenti
Scarica l'ultima versione dell'eseguibile (.exe o Tabellone-LiveShow.exe) dalla sezione Releases del repository.

Posiziona il file all'interno di una cartella dedicata.

Avvia il programma. Il sistema di controllo integrato ti avviserà automaticamente ogni volta che sarà disponibile una nuova versione migliorata.
---
📝 Changelog & Cronologia Versioni
Versione 1.7
Supporto Multi-Monitor Avanzato: Possibilità di avviare il tabellone sul monitor principale come finestra normale e spostarlo liberamente su qualsiasi schermo o proiettore secondario.

Schermo Intero Intelligente: Toggle rapido tramite il tasto F11 che riconosce automaticamente la posizione della finestra e la espande a schermo intero sul display di destinazione (senza "rimbalzi" indesiderati). Tasto ESC per la chiusura rapida.

UI Dinamica e Scalabile: Ridimensionamento e ricalcolo in tempo reale (tramite evento di resize) di testi, loghi e barra dei decibel in base alla risoluzione dello schermo attivo.

Asset Integrati: Icone e loghi ufficiali inclusi direttamente nell'esecutivo standalone.
---
Versione 1.6
Podio Dinamico sul Tabellone Pubblico: Aggiunto il pulsante interattivo "CHIUDI PODIO" che permette di mostrare/nascondere la cerimonia di premiazione senza chiudere l'intero tabellone pubblico live.
---
Versione 1.5
Salvataggio Dati Avanzato: Perfezionata la gestione della cartella di lavoro e dei file di backup locali dei CSV per evitare qualsiasi perdita di dati durante eventi concitati.
---
Versione 1.4
Flusso Operativo Piazzola: Ridisegnati i controlli rapidi per l'operatore, velocizzando ulteriormente la transizione dei concorrenti durante le prove di scarico.
---
Versione 1.3
Stabilità Comunicazione: Implementati ulteriori filtri e controlli di robustezza sulla porta COM per prevenire disconnessioni del fonometro in ambienti disturbati.
---
Versione 1.2
Reattività UI: Ottimizzati i loop di lettura seriale dei decibel in tempo reale per garantire un aggiornamento fluido e senza lag dell'interfaccia operatore.
---
Versione 1.1
Engine Aggiornamenti: Integrato il sistema di verifica e notifica automatica delle versioni tramite GitHub.
UI Pulita: Rimossa la colonna "Veicolo" nel tabellone pubblico per garantire una lettura immediata e pulita.
Stabilità: Ottimizzazione generale delle dipendenze e della gestione delle comunicazioni seriali.
---
Versione 1.0
Release Iniziale: Rilascio della soluzione professionale per la gestione completa di gare SPL (Sound Pressure Level), registrazione automatica, monitoraggio dB in tempo reale, gestione categorie e generatore di classifiche CSV.
---
Progetto sviluppato per la gestione professionale di eventi motoristici e raduni.
