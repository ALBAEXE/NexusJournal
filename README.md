<div align="center">

<img src="icon-512.png" width="128" height="128" style="border-radius:28px" alt="NexusJournal">

# NexusJournal

**Il tuo diario di trading personale, nero, fluido e tutto sul tuo iPhone.**

<img src="https://img.shields.io/badge/Versione-v1.3.1-22c55e?style=for-the-badge&labelColor=1c1c1e" alt="Versione v1.3.1"><br>
<img src="https://img.shields.io/badge/iPhone%20%7C%20Android%20%7C%20Desktop-Web%20App-3b82f6?style=for-the-badge&labelColor=1c1c1e&logo=safari&logoColor=white" alt="iPhone | Android | Desktop Web App"><br>
<img src="https://img.shields.io/badge/Lingua-Italiano-8b5cf6?style=for-the-badge&labelColor=1c1c1e" alt="Lingua Italiano"><br>
<img src="https://img.shields.io/badge/Dati-Solo%20sul%20dispositivo-0d0d0f?style=for-the-badge&labelColor=1c1c1e&logo=icloud&logoColor=white" alt="Dati Solo sul dispositivo"><br>
<a href="https://albaexe.github.io/NexusJournal/"><img src="https://img.shields.io/badge/Installa-Gratis-000000?style=for-the-badge&labelColor=1c1c1e&logo=apple&logoColor=white" alt="Installa Gratis"></a>

<br><br>

<a href="https://albaexe.github.io/NexusJournal/"><b>Apri NexusJournal →</b></a>

</div>

---

## Screenshot

<div align="center">
<table>
<tr><td align="center"><img src="docs/screenshots/1-introduzione.png" width="240"><br><sub><b>Introduzione</b></sub></td><td align="center"><img src="docs/screenshots/2-panoramica.png" width="240"><br><sub><b>Panoramica</b></sub></td><td align="center"><img src="docs/screenshots/3-operazioni.png" width="240"><br><sub><b>Operazioni</b></sub></td></tr>
<tr><td align="center"><img src="docs/screenshots/4-nuova-operazione.png" width="240"><br><sub><b>Nuova operazione</b></sub></td><td align="center"><img src="docs/screenshots/5-statistiche.png" width="240"><br><sub><b>Statistiche</b></sub></td><td align="center"><img src="docs/screenshots/6-impostazioni.png" width="240"><br><sub><b>Impostazioni</b></sub></td></tr>
</table>
</div>

## Cos'è

NexusJournal è una web app installabile (PWA) per registrare e analizzare ogni operazione di trading. Pensata per un solo utente, funziona offline e salva tutto in locale sul dispositivo: nessun account, nessun server.

## Funzioni

### Panoramica
- P&L netto con contatore animato e frase di sintesi
- Win rate, profit factor, operazioni chiuse e aperte
- Curva del capitale interattiva
- Ultime operazioni

### Operazioni
- Elenco completo con ricerca per simbolo, setup, tag e note
- Filtri per esito, direzione e periodo
- Modifica ed eliminazione di ogni operazione

### Nuova operazione
- Data e ora, simbolo, direzione Long/Short
- Quantità, prezzo di ingresso e uscita (vuoto = posizione aperta), stop loss, commissioni
- P&L e R-multiplo calcolati in automatico
- Setup, tag, emozione, voto esecuzione, note e screenshot del grafico

### Statistiche
- Vincita e perdita media, aspettativa, R medio
- Migliore e peggiore operazione, max drawdown
- Serie di vincite e perdite consecutive

### Impostazioni
- Valuta e capitale iniziale
- Vibrazione (feedback aptico) on/off
- Rivedi introduzione, controlla aggiornamenti
- Backup JSON, esportazione CSV, importazione, dati di esempio

### Esperienza
- Tema nero OLED, icone animate, transizioni fluide
- Feedback aptico al tocco su iPhone
- Schermate introduttive alla prima apertura
- Nessuna selezione blu con pressione prolungata, come un'app nativa
- **Aggiornamento automatico**: all'apertura l'app controlla `version.json` e si ricarica da sola quando esce una nuova versione

## Installazione su iPhone

1. Apri **https://albaexe.github.io/NexusJournal/** in Safari
2. Tocca **Condividi** → **Aggiungi alla schermata Home**
3. Lascia attivo **Apri come app web** e conferma

Su Android: Chrome → menu ⋮ → **Installa app**. Su desktop si apre direttamente nel browser.

## Dati e privacy

Tutte le operazioni restano nella memoria locale del dispositivo (`localStorage`). Se elimini l'app dalla schermata Home i dati vengono cancellati: usa **Impostazioni → Esporta backup** e salva il file su File o iCloud.

## Struttura del repository

| File | Contenuto |
|---|---|
| `index.html` | L'intera app (HTML, CSS, JS) |
| `hark*.css`, `hark*.js`, `chart.js`, `datalabels.js` | Stili e grafici |
| `apple-touch-icon.png`, `icon-192.png`, `icon-512.png` | Icone |
| `version.json` | Versione pubblicata, letta dall'aggiornamento automatico |
| `docs/screenshots/` | Screenshot aggiornati a ogni versione |

## Versione

**v1.3.1** · aggiornato il 19/11/2026

<div align="center"><sub>Uso personale · © ALBAEXE</sub></div>
