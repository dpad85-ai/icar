# iCar – guida all'installazione su iPad (versione 4.2.1)

File (6): index.html, sw.js, icon.png, icon-512.png, manifest.json, golf7.png

## Novità della 4.2.1: riquadri riordinati e Golf già pronta
- Ordine dei riquadri: meteo, tachimetro con la Golf, computer di bordo e per ultimo **Audio e app**.
- La foto della Golf, con la targa cancellata e scritto **DANY**, è già dentro iCar: non serve più sceglierla. Se avevi messo la foto vecchia, tocca la macchina → **Usa la Golf di iCar (targa DANY)**.

## Novità della 4.2: la tua Golf e il nome del paese
- Nel riquadro del tachimetro c'è la **foto della tua auto** con il nome sotto (**Golf7**).
- Per usare un'altra foto: tocca la macchina nel riquadro → **Scegli la foto** → prendila da Foto o da File. Una foto scelta così resta salvata solo sull'iPad (ed entra nella "Salva copia").
- Toccando la macchina puoi anche **cambiare il nome** o **togliere la foto**; si fa anche da Impostazioni → Guida → "La mia auto".
- L'**avviso di velocità** c'è ancora: tocca il tachimetro per cambiarlo; quando è attivo compare un piccolo cartello rosso sul tachimetro.
- Nel riquadro meteo, sotto la data, c'è il **nome del paese** in cui ti trovi (si aggiorna quando ti sposti).

## Novità della 4.1: meteo animato in cima, tachimetro sottile
- Il riquadro con **ora, data e meteo** è il primo in alto, ed è animato: lo sfondo cambia colore con il tempo; il sole gira, di notte compaiono luna e stelle, con nuvole, pioggia e neve si vedono scorrere o cadere, col temporale ogni tanto un lampo. I due punti dell'ora lampeggiano piano.
- Il **tachimetro** è più piccolo e sottile.
- Le 4 icone del riquadro **Audio e app** hanno sempre la stessa misura; i nomi lunghi si accorciano con i puntini.
- Con l'iPad in verticale il meteo ora si vede (in basso a sinistra, sopra il tachimetro).
- Se nelle impostazioni dell'iPad è attivo "Riduci movimento", le animazioni restano ferme.

## Novità della 4.0: stile più moderno
La barra a sinistra ora galleggia sopra la mappa, che si vede a tutto schermo; con l'iPad in verticale diventa una barra in basso. Riquadri in vetro più scuro e arrotondato, numeri in carattere arrotondato, tasti della mappa rotondi, barra di ricerca a pillola. Le funzioni non cambiano. Dopo l'aggiornamento chiudi del tutto iCar e riaprilo: in fondo alle Impostazioni deve comparire «iCar 4.0».

## Novità della 3.8.2: nomi sotto i tasti di «Audio e app»
Sotto ognuno dei 4 tasti del riquadro compare in piccolo il nome dell'app.

## Novità della 3.8.1: chiave Google Maps nascosta e sempre salvata
- In **Impostazioni → Schermo** la chiave Google Maps è **nascosta** (si vedono solo le ultime 4 cifre). "Mostra" la fa vedere per 8 secondi, "Cambia" ne inserisce una nuova, "Rimuovi" la toglie.
- Accanto compare **✓ Chiave valida** (verde) se Google Maps la accetta, oppure **✗ Chiave non valida** (rossa).
- La chiave resta salvata sull'iPad, anche con "Ripristina".
- **Copia di sicurezza** (Impostazioni, in fondo): "Salva copia" crea il file **iCar-impostazioni.json** con tutte le impostazioni, chiave compresa. Salvalo in File → iCloud Drive. Se perdi i dati, "Carica copia" li rimette in un attimo.
- **Attenzione:** togliere l'icona di iCar dalla schermata Home, o cancellare i dati di Safari, cancella anche le impostazioni di iCar (chiave compresa). Prima fai sempre "Salva copia".

## Novità della 3.8: il tasto Telefono apre subito l'app Telefono
- Il tasto **Telefono** di iCar ora apre direttamente l'**app Telefono dell'iPad** (come Messaggi apre l'app Messaggi). iCar non ha più una sua schermata per le chiamate: chiamate recenti, rubrica, preferiti e tastierino sono nell'app Telefono.
- **Una volta sola**: al primo tocco iCar ti chiede di creare il Comando rapido **Apri Telefono** (Comandi rapidi → Aggiungi azione → Apri app → Telefono → rinomina in "Apri Telefono" → Fine). Poi tocca "Fatto". Da quel momento il tasto apre subito l'app. (L'iPad non permette ad una pagina web di aprire l'app Telefono senza questo passaggio.)
- I **contatti per i comandi vocali** ("chiama Marco", "scrivi a Giulia") si importano da iCar → Impostazioni → Telefono → **Importa**.

## Novità della 3.7: Telefono con contatti e chiamate (sostituita dalla 3.8)
- In alto nella sezione **Telefono** c'è il tasto **Apri l'app Telefono dell'iPad**: apre l'app Telefono di iPadOS 26, con tutte le chiamate recenti (anche ricevute e perse), contatti e segreteria del tuo iPhone.
- **Da fare una volta (versione 3.7.1):** l'iPad non permette a iCar di aprire direttamente l'app Telefono (prima compariva "Safari non può aprire la pagina perché l'indirizzo non è valido"). Al primo tocco iCar ti guida: apri Comandi rapidi → "Aggiungi azione" → cerca **Apri app** → scegli **Telefono** → rinomina il comando in **Apri Telefono** → Fine. Torna in iCar e tocca "Fatto".
- Nuove schede: **Preferiti**, **Contatti**, **Recenti**, **Tastierino**.
- **Contatti**: importa i contatti dell'iPad, cercali, chiamali o scrivi un messaggio; la stella li mette nei Preferiti. Se un contatto ha più numeri, iCar chiede quale usare.
- **Recenti**: le chiamate fatte da iCar, con giorno e ora.
- I comandi vocali "chiama…" e "scrivi a…" cercano anche tra i contatti importati.

**Come importare i contatti (iCar non può leggere da solo la rubrica):**
- *Modo 1 – Scegli dai Contatti*: Telefono → Contatti → "Scegli dai Contatti" e tocca i contatti da portare. Se iCar dice che non è disponibile, attivalo una volta: Impostazioni dell'iPad → App → Safari → Avanzate → Feature Flags → **Contact Picker API**.
- *Modo 2 – File .vcf*: nell'app Contatti dell'iPad tieni premuto un elenco (es. "Tutti i contatti") → **Esporta** → Salva su File. Poi in iCar → Telefono → Contatti → "Importa file dei contatti (.vcf)" e scegli il file.

I contatti restano salvati solo sull'iPad. Se hai dato al comando un nome diverso da "Apri Telefono", scrivilo in iCar → Impostazioni → Telefono.

## Novità della 3.5: mappa Google Maps (normale e satellite)
Con una tua chiave Google la mappa principale di iCar diventa **Google Maps**. Il nuovo tasto sotto + e − passa da **mappa normale** a **satellite** (con i nomi delle strade). Di notte la mappa normale diventa scura. Senza chiave iCar continua a usare OpenStreetMap.

**Costo:** Google dà gratis 10.000 aperture della mappa al mese (ogni volta che apri iCar è un'apertura). Chiede però una carta per attivare l'account.

**Come avere la chiave (una volta, circa 10 minuti):**
1. Apri **console.cloud.google.com** e accedi con il tuo account Google. Crea un progetto chiamato "iCar".
2. Menu ☰ → **Fatturazione**: crea l'account di fatturazione e aggiungi la carta, poi collegalo al progetto "iCar".
3. Menu ☰ → **API e servizi** → **Libreria** → cerca **Maps JavaScript API** → **Abilita**.
4. **API e servizi** → **Credenziali** → **Crea credenziali** → **Chiave API**. Copia la chiave.
5. **Proteggi la chiave** (importante): apri la chiave appena creata →
   - Restrizioni delle applicazioni: **Siti web** → aggiungi `https://TUONOME.github.io/*` (il tuo indirizzo GitHub).
   - Restrizioni API: **Limita chiave** → scegli solo **Maps JavaScript API** → Salva.
6. Consigliato: **Fatturazione → Budget e avvisi** → crea un budget di 1 € con avviso via email, così sai subito se qualcosa non va.
7. In iCar → **Impostazioni → Schermo → "Chiave Google Maps"**: incolla la chiave. iCar si riapre con Google Maps.

La chiave resta salvata solo sul tuo iPad, non nei file su GitHub. Se compare "Chiave Google Maps non valida", controlla di aver abilitato Maps JavaScript API, di aver collegato la fatturazione e di aver scritto bene l'indirizzo nelle restrizioni (le modifiche possono richiedere qualche minuto).

## Novità della 3.4
- **iCar a tutto schermo**: niente più bordi, la mappa arriva fino ai lati dello schermo.
- **Tre schermate della mappa** (tasto sotto + e −, oppure Impostazioni → Guida → "Schermata della mappa"):
  1. **Mappa e riquadri**: tachimetro, ora e meteo, audio, computer di bordo.
  2. **Mappa e app a metà schermo**: a destra la griglia con tutte le tue app (tocchi e si aprono), con ora e velocità.
  3. **Solo mappa a tutto schermo**: resta solo un piccolo tachimetro tondo.
- **Nuova icona** scura con tachimetro verde e freccia (in stile auto, disegnata da zero).
- iCar si adatta anche quando è affiancato a un'altra app.

**Cosa non si può fare (limiti di Apple):** una pagina web come iCar non può leggere l'elenco delle app installate e non può mostrare un'altra app dentro di sé. Le alternative:
- **Tutte le app**: "Aggiungi app" ha il catalogo pronto; per qualsiasi altra app usa un Comando rapido con "Apri app" e poi "+ Comando" in iCar.
- **App accanto alla mappa, a metà schermo**: usa la divisione dello schermo dell'iPad. Impostazioni dell'iPad → Multitasking e gesti → **App in finestre**. Poi apri iCar, tieni premuti i pulsanti colorati in alto a sinistra della finestra → affianca a sinistra → scegli l'app da mettere a destra. Trascina la linea in mezzo per cambiare le dimensioni.
- **Tutto schermo vero**: apri sempre iCar dalla sua icona sulla schermata Home (non da Safari). Con "App in finestre" attivo, tocca il pulsante verde in alto per metterlo a tutto schermo.

**Nuova icona sulla schermata Home:** carica su GitHub index.html, icon.png e icon-512.png, poi togli iCar dalla schermata Home (tieni premuto → Rimuovi app → Rimuovi dalla schermata Home) e aggiungilo di nuovo da Safari.

## Novità della 3.2
- **Icone in stile Apple**: simboli pieni, colori sfumati e riflesso lucido, in tutta l'app e nel catalogo "Aggiungi app".
- Tolto il collegamento **CarPlay** (CarCast): la beta per iPhone è al completo e non si può usare.

**Per vedere la nuova icona sulla schermata Home:** su GitHub carica **index.html**, **icon.png** e **icon-512.png** (sostituiscono i vecchi). Poi sull'iPad (dopo aver fatto "Salva copia" nelle Impostazioni) tieni premuta la vecchia icona di iCar → Rimuovi app → Rimuovi dalla schermata Home, e aggiungila di nuovo da Safari (Condividi → "Aggiungi alla schermata Home"). L'iPad non aggiorna da solo l'icona di un sito già aggiunto. Togliendo l'icona si cancellano le impostazioni di iCar: dopo averla rimessa, vai in Impostazioni → "Carica copia" e scegli il file iCar-impostazioni.json.

## Novità della 3.0
- **Grafica nuova** in stile vetro, con la mappa a tutto schermo e i riquadri sopra, come il CarPlay più recente.
- **Mappa vera e fluida**: scorre insieme a te, si trascina col dito, ha i tasti + e −, doppio tocco per avvicinare, si allarga quando vai più veloce. Di notte diventa scura.
- **Navigatore dentro iCar**: scrivi dove vuoi andare (con suggerimenti), vedi percorso, durata, km e ora di arrivo, poi "Avvia". Istruzioni grandi in alto e **voce in italiano** ("Tra 300 metri svolta a destra"). Se sbagli strada ricalcola da solo. Il tasto "Apri in Google Maps" passa il percorso a Google Maps.
- **Computer di bordo**: km, tempo in viaggio, velocità media e massima. Il viaggio si salva da solo dopo 10 minuti da fermo; gli ultimi viaggi sono in Impostazioni.
- **Tachimetro** con cartello del limite: toccalo per cambiare l'avviso di velocità.
- **Comandi vocali** (tasto microfono colorato): "portami a casa", "vai in via Roma 10 Milano", "chiama Marco", "scrivi a Giulia", "benzina", "apri Spotify", "dove ho parcheggiato", "che tempo fa", "termina navigazione". Funzionano solo se Safari dell'iPad lo permette; altrimenti usa "Ehi Siri".
- **Google Maps navigatore predefinito** per tutto (benzina, parcheggi, "Apri in…", percorso a piedi verso l'auto). Si cambia in Impostazioni.
- **Aggiungi app**: catalogo con oltre 50 app (Netflix, YouTube, Telegram, Deezer, Waze, Uber…) da aggiungere con un tocco. Per **qualsiasi altra app** dell'iPad: Comandi rapidi → "+" → azione "Apri app" → scegli l'app → dai un nome; poi in iCar → Aggiungi app → "+ Comando" e scrivi quel nome.
- Riquadro "Audio e app" sulla mappa con 4 tasti a scelta (Impostazioni).

**Servizi gratuiti usati** (serve internet dall'hotspot): mappe OpenStreetMap, ricerca indirizzi Photon, percorsi OSRM, meteo Open-Meteo. Sono servizi pubblici gratuiti: ogni tanto possono essere lenti.

**Mappe:** senza chiave Google iCar usa OpenStreetMap, che non chiede nessuna chiave.

**iPad solo Wi-Fi e GPS**: senza GPS la posizione arriva dal Wi-Fi ed è approssimativa (anche centinaia di metri), quindi navigatore, tachimetro e computer di bordo funzionano male in movimento. Soluzione: un **ricevitore GPS Bluetooth** compatibile con iPad (es. Garmin GLO 2 o Bad Elf). Si abbina dalle impostazioni Bluetooth e dà la posizione GPS a tutte le app, iCar compreso.

## Novità della 2.0
- Dashboard con **mappa dal vivo** che segue la tua posizione (tocca la mappa per aprire il navigatore). Sopra c'è la ricerca, sotto i tasti Casa, Lavoro, luoghi preferiti, Benzina, Ricarica, Parcheggi, Mangiare.
- **Torna all'auto**: salva dove hai parcheggiato e poi ti ci porta a piedi.
- **Avviso di velocità**: il numero diventa rosso e suona un bip oltre il limite scelto.
- **Modalità notte**: dopo il tramonto la mappa diventa scura e lo schermo si abbassa.
- **Comandi rapidi**: tasti che avviano i tuoi Comandi rapidi (es. "Auto ON").
- Preferiti del Telefono con tasto **Messaggio**.
- Si apre direttamente sulla Dashboard (si può cambiare) e funziona anche senza internet (file sw.js).

## 1. Metti iCar online (gratis, con GitHub Pages)
1. Su github.com crea un account gratuito.
2. Tocca "+" → New repository → nome `icar` → Public → Create.
3. Tocca "uploading an existing file" e carica i 5 file (dall'app File) → Commit changes.
4. Settings → Pages → Branch: `main` → Save. Dopo 1-2 minuti l'indirizzo è `https://TUONOME.github.io/icar`.

**Per aggiornare iCar a una nuova versione:** nel repository `icar` tocca "Add file" → "Upload files", scegli il nuovo **index.html** → Commit changes. Il file con lo stesso nome viene sostituito. Dopo 2 minuti chiudi e riapri iCar sull'iPad.

**Se sw.js non si scarica:** nel repository tocca "Add file" → "Create new file", scrivi il nome `sw.js`, incolla il testo del file (te lo dà Claude) → Commit changes. Senza sw.js iCar funziona lo stesso, solo non si apre quando manca internet.

## 2. Mettila sulla schermata Home
Apri l'indirizzo in Safari → tasto Condividi → "Aggiungi alla schermata Home". Da lì si apre a schermo intero, come un'app.

## 3. Impostazioni da fare una volta
- iPhone: Impostazioni → Cellulare → Hotspot personale attivo; l'iPad si collega a quella rete.
- iPhone: Impostazioni → App → Telefono → "Chiamate su altri dispositivi" → attiva l'iPad (stesso Apple ID).
- In iCar → Impostazioni: Casa, Lavoro, contatti preferiti, avviso di velocità (il navigatore esterno è già Google Maps).
- Al primo avvio tocca "Consenti" per la posizione (mappa, velocità e meteo) e, se usi i comandi vocali, per il microfono.

## 4. (Facoltativo) Modalità Auto automatica con Full immersione e Comandi rapidi
Idea presa dai migliori setup "iPad come CarPlay" trovati online: una Full immersione dedicata all'auto che mostra solo iCar e prepara l'iPad da sola.

1. **Pagina solo per l'auto:** sulla schermata Home dell'iPad crea una pagina vuota e mettici solo l'icona di iCar (e se vuoi i widget Meteo e Musica).
2. **Full immersione "Auto":** Impostazioni → Full immersione → "+" → Personalizzata → nome "Auto". In "Personalizza schermate" → Schermata Home scegli solo la pagina del punto 1. Silenzia le notifiche non importanti.
3. **Comando "Auto ON"** (app Comandi rapidi → "+"): aggiungi Imposta luminosità 80%, Imposta volume 70%, Imposta Bluetooth Attivo, Imposta aspetto Scuro.
4. **Comando "Auto OFF":** Imposta luminosità 50%, Imposta aspetto Automatico.
5. **Automazioni** (Comandi rapidi → Automazione → "+" → Full immersione → Auto): "Quando si attiva" → Esegui subito → Auto ON; un'altra "Quando si disattiva" → Auto OFF.
6. In auto: apri Centro di Controllo, attiva la Full immersione "Auto" e tocca iCar.

Puoi anche mettere un tasto per questi comandi dentro iCar: Aggiungi app → "+ Comando" e scrivi il nome esatto (es. Auto ON).

## Note
- Gli iPad solo Wi-Fi non hanno GPS: mappa, navigazione e velocità sono imprecise. Rimedio: un ricevitore GPS Bluetooth (Garmin GLO 2, Bad Elf).
- I tasti aprono le app vere (Mappe, Spotify, ecc.): devono essere installate sull'iPad.
- La musica esce dall'iPad: collegalo all'auto via Bluetooth o cavo AUX.
- Mappa e navigatore usano un po' di dati dell'hotspot.
- Con il sole diretto l'iPad si scalda: meglio un supporto vicino alla bocchetta dell'aria.
- Per sicurezza imposta tutto da fermo e usa Siri ("Ehi Siri…") mentre guidi.
