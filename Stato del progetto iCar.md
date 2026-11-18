# Stato del progetto iCar (aggiornato il 18 novembre 2026)

**Versione attuale:** iCar 3.8.1
**Cartella sul computer:** D:\Daniele\Documents\iCar

## File in questa cartella
- `index.html`, `sw.js`, `manifest.json`, `icon.png`, `icon-512.png`: i file dell'app da caricare su GitHub.
- `Guida installazione iCar.md`: come installare, aggiornare, mettere la chiave Google Maps, usare lo schermo diviso.
- `versioni\`: una copia ZIP completa per ogni versione (iCar-3.6.zip, iCar-3.7.zip, iCar-3.7.1.zip, iCar-3.8.zip, iCar-3.8.1.zip…).

## Dove altro è salvato
- Anteprima "iCar" su Claude: https://claude.ai/artifact/TUEnQ4BJR1aVrc35kPAbYg
- Progetto "iCar" su Claude: guida e questa scheda.
- GitHub: repository **dpad85-ai/icar**, sito **https://dpad85-ai.github.io/icar** (la copia che usa l'iPad). Claude carica direttamente gli aggiornamenti su GitHub (permesso dato il 18/11/2026).

## Cosa fa iCar 3.8.1
- Mappa a tutto schermo: Google Maps (normale e satellite) con chiave personale, altrimenti OpenStreetMap. Mappa scura di notte.
- Tre schermate: mappa e riquadri / mappa e app a metà schermo / solo mappa.
- Navigatore interno con voce in italiano, ricalcolo, ora di arrivo; "Apri in Google Maps".
- Tachimetro con avviso di velocità, computer di bordo e storico viaggi, salva parcheggio.
- Comandi vocali (se Safari li permette).
- Telefono: il tasto apre subito l'app Telefono dell'iPad (tramite il Comando rapido "Apri Telefono"), senza schermata propria in iCar. Contatti preferiti e contatti importati (.vcf o scelta dai Contatti) servono ai comandi vocali.
- Catalogo "Aggiungi app" con oltre 50 app + qualsiasi app tramite Comandi rapidi.
- Chiave Google Maps nascosta con spunta ✓ se valida; copia di sicurezza delle impostazioni in un file (iCar-impostazioni.json).
- Icone in stile Apple, icona Home scura con tachimetro verde.

## Scelte fatte
- Google Maps navigatore predefinito per tutto.
- Tolti: collegamento CarPlay/CarCast (beta piena), mappe CARTO.
- iPad solo Wi-Fi: posizione approssimativa; consigliato un ricevitore GPS Bluetooth (Garmin GLO 2, Bad Elf).

## Aggiornare l'iPad
Dopo ogni aggiornamento caricato su GitHub: aspetta 1-2 minuti, chiudi del tutto iCar sull'iPad e riaprilo. In fondo alle Impostazioni compare il numero di versione.

## Per riprendere il lavoro
Apri una chat nel progetto iCar su Claude e chiedi di continuare iCar. Ogni nuova versione verrà salvata in questa cartella, con una copia ZIP in `versioni`.
