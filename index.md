---
title: Informativa privacy — SegnaBaby
---

# Informativa privacy di SegnaBaby

*Versione del `19/10/2026`.*

## 1. Chi tratta i tuoi dati

Il titolare del trattamento è Ludovico Copetti, persona fisica. Dietro SegnaBaby
non c'è nessuna società, e non c'è un responsabile della protezione dei dati. Per
qualunque domanda o richiesta scrivi a segnababy@gmail.com.

Se la richiesta riguarda i tuoi dati, allega il **codice della chat**: lo ottieni
con il comando `/licenza`. È l'unico modo per identificare il tuo gruppo Telegram.
Non conosco il tuo nome e non ho altro modo di collegarti a una chat.

## 2. Quali dati raccolgo

Solo quello che serve a far funzionare il diario.

**Sempre**, perché senza non c'è il servizio:

- l'**identificativo numerico della chat** Telegram di gruppo in cui usi il bot (il
  `chat_id`). Non raccolgo il tuo nome, il tuo numero di telefono, il tuo
  `@username`, la tua email né il tuo indirizzo IP;
- gli **eventi che registri**: sonno, pappa e cambio del pannolino, con l'ora di
  inizio e, dove ha senso, di fine;
- i **dettagli di un evento**: i millilitri di una poppata col biberon, il **lato
  del seno** in un allattamento, se il pannolino era con **pipì o cacca**. Con i
  pulsanti il bot li chiede ogni volta, prima di registrare la pappa o il cambio;
- il **nome del bambino**, che il bot chiede alla prima configurazione e usa nei
  messaggi e nei fascicoli. Puoi cambiarlo quando vuoi con `/nome`;
- la **data di nascita**, che il bot chiede alla prima configurazione: serve a
  contare i mesi di vita nei fascicoli e negli auguri. Puoi cambiarla con
  `/nascita`.

**Solo se li scrivi tu**, e il bot funziona anche senza:

- il **codice di licenza** che riscatti con `/riscatta`, con il `chat_id` in cui
  l'hai usato e la data. Serve a garantire che un codice valga una volta sola e a
  sapere fino a quando dura la licenza;
- se usi gli **inviti**: quale chat ha invitato quale, il codice invito della tua
  chat e il codice sconto creato per te. Serve a dare lo sconto a chi è invitato e i
  giorni di licenza a chi invita. Nessuna delle due chat vede i dati dell'altra: chi
  ha invitato riceve solo un messaggio che dice che una famiglia invitata ha comprato.
- la **risposta alla domanda di fine prova**, se tocchi uno dei motivi: una voce da
  un elenco chiuso, mai testo libero. Serve a capire perché chi prova il bot non
  continua.

Il testo dei tuoi messaggi non diventa un evento. Il bot risponde ai tre pulsanti e
ai comandi, e nella conversazione normale del gruppo resta muto.

## 3. Perché li tratto

- Per **far funzionare il diario**: registrare gli eventi, mostrarti riepiloghi,
  grafici e fascicoli mensili.
- Per i **dati sulla salute** elencati sopra la base è il tuo **consenso esplicito**.
  Lo dai usando quelle funzioni, e lo ritiri quando vuoi: smetti di usarle, oppure
  cancelli tutto con `/cancellami`.
- Per **gestire la licenza** e risponderti se mi scrivi.

Non c'è nessun altro scopo. Non uso i tuoi dati per profilarti, né per decisioni
automatizzate che ti riguardano.

## 4. I dati sono di un bambino

I dati che il bot conserva descrivono un minore, che non può dare alcun consenso. Lo
dà chi esercita la responsabilità genitoriale: tu, quando aggiungi il bot al gruppo e
cominci a registrare. Usando il bot dichiari di essere in quella posizione.

## 5. Dove stanno i dati, e chi altro li vede

Il database è un unico file su un server in affitto presso Hetzner, in Unione
Europea. Le copie di sicurezza, una all'ora, sono cifrate e finiscono su un bucket
privato di **Backblaze B2 in regione europea**. La regione è stata scelta all'inizio
proprio per questo, e non si può cambiare dopo.

Chi tratta i dati per conto mio, ciascuno solo per la parte tecnica che gli spetta:

| chi | cosa vede |
|---|---|
| Hetzner | il server su cui gira il bot e vive il database |
| Backblaze | le copie di sicurezza cifrate |
| Healthchecks.io | soltanto un segnale periodico che dice «il bot è vivo»; nessun dato tuo |

**Il negozio dove si compra la licenza non riceve dati dal bot.** Quando sei invitato,
il bot gli chiede di creare il tuo codice sconto: una stringa casuale, senza il tuo
nome, il nome del bambino né il codice della chat.

**Telegram è un caso a parte, e va detto per quello che è.** Tutti i messaggi fra te
e il bot passano dai server di Telegram. Telegram è un titolare autonomo, ha una
propria informativa e opera fuori dall'Unione Europea. Non è una scelta tecnica che
io possa cambiare: il bot *è* un bot Telegram. Se questo non ti sta bene, non puoi
usare il servizio.

**Io, come operatore, posso accedere ai dati** per assistenza e manutenzione. Oggi
questo comporta tre cose concrete:

- quando una nuova famiglia finisce la configurazione ricevo una notifica con
  l'identificativo della chat, il nome del bambino e la data di nascita;
- quando rispondi alla domanda di fine prova ricevo il motivo scelto, con la stessa
  riga: l'identificativo della chat, il nome del bambino e la data di nascita;
- se mi chiedi aiuto, posso leggere, correggere o cancellare i dati della tua chat.

Non cedo, non vendo e non condivido i tuoi dati con nessuno. Dentro il bot non ci
sono inserzionisti né strumenti di analisi.

## 6. Per quanto tempo li conservo

Finché usi il servizio. Non c'è una scadenza automatica: un diario che si cancella da
solo non è un diario.

Puoi cancellare tutto quando vuoi con **`/cancellami CONFERMA`**. L'effetto è
immediato e **irreversibile**: la riga della chat e tutti i suoi eventi spariscono dal
database, e non ho modo di riportarli indietro. Se ti servono i tuoi dati, esportali
**prima** con `/export`.

Una precisazione sulle copie di sicurezza, che è giusto conoscere. La cancellazione
agisce sul database, non sui backup già scritti, che sono immagini di un momento
passato. Quelle copie scadono da sole: le orarie dopo circa un mese, le mensili dopo
circa tredici mesi. Entro quel termine la cancellazione è completa. Nessuno legge un
backup, se non per rimettere in piedi il servizio dopo un guasto.

## 7. I tuoi diritti

Hai diritto di accedere ai tuoi dati, correggerli, cancellarli, limitarne il
trattamento, riceverli in un formato leggibile da un altro programma e opporti al
trattamento. Hai anche diritto di revocare il consenso. Tre di questi li eserciti da
solo dentro il bot, senza scrivere a nessuno:

| cosa vuoi | come |
|---|---|
| avere tutti i tuoi dati | `/export` — un file CSV con tutti gli eventi |
| correggere un dato sbagliato | `/correggi`, che modifica e cancella un evento alla volta |
| cancellare tutto | `/cancellami CONFERMA` |

Per tutto il resto scrivi a segnababy@gmail.com con il codice della chat. Rispondo
entro un mese.

## 8. Modifiche a questa informativa

Se cambia qualcosa di sostanziale — un nuovo fornitore, un dato in più, uno scopo
diverso — aggiorno questo documento e lo annuncio nel bot. La data in cima dice
sempre a quando risale la versione che stai leggendo.
