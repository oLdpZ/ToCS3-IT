# The Legend of Heroes: Trails of Cold Steel III — Traduzione italiana

Traduzione amatoriale e non ufficiale in italiano di *Trails of Cold Steel III*
per PC, fatta da fan, senza legami con Nihon Falcom o NIS America.
**Serve una copia originale del gioco.**

**[Scarica l'ultima versione](../../releases/latest)** — `ToCS3-IT-2026.10.19.zip`, 30,8 MB.

## Prima di tutto: come è stata fatta

Questa traduzione è stata realizzata con l'aiuto di un'intelligenza artificiale
(Claude, di Anthropic), guidata e controllata dall'autore.

Cosa è stato controllato:

- **in modo automatico, su tutte le righe**: i codici di controllo del gioco
  (colori, a capo, nomi, pause), la lunghezza rispetto alle finestre, e un
  glossario di oltre mille termini (nomi, luoghi, oggetti, arti), perché la
  stessa cosa si chiami sempre allo stesso modo;
- **giocando**: menu, schermate e parti della storia.

Cosa **non** è stato fatto: una rilettura umana completa di tutti i dialoghi.
Troverete errori, frasi innaturali e, qua e là, sfumature sbagliate. Le
segnalazioni sono benvenute (vedi in fondo).

## Cosa è tradotto

- tutti i testi del gioco: dialoghi, storia, missioni, menu, oggetti, abilità,
  libri e giornali, tutorial;
- le scritte ridisegnate nelle immagini: menu, cartelli dei capitoli, mappe,
  didascalie di apertura delle scene;
- la frase d'apertura del prologo e la scena dopo i titoli di coda, impresse
  nei filmati.

Restano in inglese per scelta, come nei menu originali, alcuni termini: *Arts*,
*Quartz*, *Master Quartz*, *Sepith*, *CHANGE LINK* e pochi altri. I titoli di
coda e i nomi restano come sono.

## Requisiti

- *Trails of Cold Steel III* per PC, **versione GOG** (build 1189175006) o **Steam**;
- Windows 10 o 11.

Versione Steam: i file del testo sono gli stessi di GOG, l'eseguibile
(`bind\ed8_3_PC.exe`) no. L'installazione lo lascia com'è e installa tutto
il resto; l'unica differenza è che nel menu dell'equipaggiamento le sigle sotto
l'arma restano in francese (PUI, POR…).

L'installazione controlla ogni file prima di toccarlo: se il gioco non è la
versione attesa, si ferma senza modificare niente e dice quali file non
corrispondono.

## Installazione

1. Estrai lo zip **dentro** la cartella del gioco, cioè quella che contiene le
   cartelle `bin` e `data` (per GOG di solito `C:\GOG Games\ToCS3`). Deve
   risultare `C:\GOG Games\ToCS3\ToCS3-IT\INSTALLA.bat`. Se lo metti altrove,
   l'installazione ti chiederà dov'è il gioco.
2. Fai doppio clic su `ToCS3-IT\INSTALLA.bat`: si apre una finestra con la
   sigla del gioco (presa dalla tua copia del gioco). Premi **Installa** e
   aspetta la fine (un paio di minuti). Se la finestra non si apre,
   l'installazione continua nella finestra nera, come prima.
3. Avvia il gioco. Dal titolo: **System › Text Language › Italiano** (con la
   traduzione installata, la voce che si chiamava *French* si chiama
   *Italiano*). Le voci possono restare in inglese o in giapponese.

Prima di sostituire un file, l'installazione ne salva l'originale in
`ToCS3-IT\backup`: non cancellare quella cartella se vuoi poter tornare
indietro. Chiudi il gioco prima di installare o rimuovere.

La traduzione occupa lo spazio della lingua francese: con la traduzione
installata il francese non è disponibile.

## Rimozione

Premi **Rimuovi** nella finestra, oppure fai doppio clic su
`ToCS3-IT\DISINSTALLA.bat`: rimette gli originali dal backup. In alternativa,
«Verifica / Ripara» da GOG Galaxy.

Se il gioco riceve un aggiornamento, conviene rimuovere la traduzione prima di
aggiornare e riprovare l'installazione dopo: se i file non sono più quelli
attesi, si fermerà senza fare danni.

## Come è fatto il pacchetto

Il pacchetto **non contiene file del gioco**, ma solo le differenze (patch in
formato VCDIFF) fra i file originali e quelli tradotti. Vengono applicate con
[xdelta3](https://github.com/jmacd/xdelta) 3.2.0 di Joshua MacDonald,
distribuito secondo la licenza Apache 2.0 (`file\LICENSE-xdelta3.txt`).
Anche la sigla che si vede durante l'installazione viene letta dalla tua copia
del gioco.

Impronta SHA-256 dello zip:
`3667751f7625df5f3d0456b98680881f4c73c87360eccff1806285c8e56b98b2`

## Segnalazioni e crediti

Traduzione: **oLd_pZ**. Segnalazioni: oldpz1@gmail.com, oppure le
[issue](../../issues) di questa pagina.

Per una segnalazione utile: uno screenshot, dove ti trovi nel gioco (capitolo,
luogo, personaggio che parla) e, per problemi di installazione, il file
`ToCS3-IT\installazione.log`.

Se la traduzione ti è piaciuta: ☕ [offrimi un caffè](https://buymeacoffee.com/oldpz).

*The Legend of Heroes: Trails of Cold Steel III* © Nihon Falcom Corporation.
Edizione occidentale di NIS America, Inc. Tutti i marchi appartengono ai
rispettivi proprietari.
