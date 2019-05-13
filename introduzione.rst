Introduzione
============

Le Tecnologie dell’Informazione e della Comunicazione (Information and
Communication Technology, ICT) sono in rapida espansione e condizionano ormai
completamente un numero crescente di settori vitali dell’economia e di servizi
offerti dalle Pubbliche Amministrazioni. L’ampliamento dei settori coinvolti e
delle conoscenze richieste è una conseguenza della digitalizzazione
dell’economia e della dipendenza di numerose attività dai servizi digitali;
molte azioni quotidiane si svolgono infatti nel cosiddetto spazio cibernetico o
*cyberspace* [1]_. In prospettiva la crescita dell’internet delle cose
(*Internet of Things*, IoT), ossia l’insieme di dispositivi connessi in grado di
svolgere operazioni nel mondo fisico, aprirà sia le attività domestiche alla
dimensione cibernetica, in modo qualitativamente diverso rispetto a quanto
accade attualmente. Alle nuove tecnologie si accompagnano tuttavia nuovi e
crescenti rischi; tra questi particolarmente rilevante è quello cibernetico
(*cyber risk*). I dispositivi, il software e le connessioni di rete che
compongono lo spazio cibernetico presentano vulnerabilità tecnologiche e
organizzative che possono essere sfruttate in modo malevolo, come dimostra il
moltiplicarsi degli attacchi informatici che riguardano ormai i vari settori
della società. Uno spazio cibernetico non sicuro costituisce una debolezza grave
in una società digitalizzata, non solo per i danni diretti che gli attacchi
possono arrecare alle strutture colpite, ma anche perché una diffusa percezione
di insicurezza può minare il funzionamento di quei settori che si basano sulla
disponibilità, sull’integrità e sulla riservatezza di dati digitali.

.. [1] Il cyberspace è definito come «*l’insieme delle infrastrutture
   informatiche interconnesse, comprensivo di hardware, software, dati
   ed utenti nonché delle relazioni logiche, comunque stabilite, tra di
   essi. Include tra l’altro internet, reti di comunicazione, sistemi
   attuatori di processo ed apparecchiature mobili dotate di connessione
   di rete*», cfr. Presidenza del Consiglio dei Ministri
   (2013a).

Il rischio cibernetico non è nuovo. Nelle fasi iniziali del processo di
digitalizzazione tuttavia erano in numero limitato sia le potenziali vittime sia
gli attori della minaccia. Solo i settori informatizzati (come la difesa e le
telecomunicazioni) costituivano un target sufficientemente appetibile per gli
attacchi cibernetici; inoltre le conoscenze e le risorse necessarie per
progettare e sferrare tali aggressioni esistevano quasi esclusivamente in ambito
militare e in alcuni centri di ricerca. Negli anni l’uso di dispositivi
informatici e l’accesso alle reti telematiche si sono enormemente estesi,
moltiplicando il numero di obiettivi. Inoltre le competenze necessarie per
programmare codici malevoli sono ormai a disposizione di molte organizzazioni
criminali, che sviluppano strumenti offensivi e talvolta li offrono a basso
costo a un’ampia platea di clienti ed utenti. Anche ormai il cittadino e i suoi
rapporti con la Pubblica Amministrazione sono divenuti nel tempo oggetto di
attenzione per gli attacchi cibernetici, con la finalità di colpire e
compromettere il legame di fiducia esistente tra gli stessi.

La sicurezza cibernetica dei sistemi informativi delle organizzazioni e della
relativa rete di interconnessione viene assicurata dall’azione, e dal relativo
coordinamento, di diverse strutture di gestione della cyber security operanti
nei diversi ambiti di competenza, tra cui i Computer Emergency Response Team
(CERT [2]_). Nel nostro ordinamento, come evidenziato più in dettaglio nelle
successive sezioni del documento, l'attuale quadro legislativo ha determinato
l’allocazione delle funzioni e dei compiti aventi rilievo per la sicurezza
cibernetica a livello nazionale ad una molteplicità di attori istituzionali. In
particolare, tale assetto è oggi in corso di evoluzione in risposta alle
disposizioni provenienti dall’Unione Europea e che hanno portato alla
costituzione del CSIRT Italia, che accoglierà al proprio interno le
responsabilità e le competenze fino ad oggi ripartite tra CERT-PA e CERT
Nazionale.

.. [2] Per ragioni di comodità espositiva si farà utilizzo nel resto del
   documento della denominazione CERT in luogo di altre con significati
   del tutto analoghi quali CSIRT (Computer Security Incident Response
   Team), IRT (Incident Response Team), CIRT (Computer Incident Response
   Team) o SERT (Security Emergency Response Team). Si precisa tuttavia che
   l’utilizzo della denominazione CERT dovrebbe considerare
   i seguenti criteri di base: (i) l’acronimo CERT è un marchio
   registrato della CMU-SEI e pertanto l’utilizzo dello stesso deve
   essere autorizzato da tale organizzazione; (ii) la mission primaria
   del CERT, secondo le convenzioni internazionali associate
   all’utilizzo di questo acronimo, deve essere fondata sulla gestione
   degli incidenti di Cyber Security, anche se focalizzata su aspetti di
   coordinamento e supervisione.

In accordo con gli indirizzi strategici nazionali [3]_, devono quindi essere
create le condizioni per sviluppare un'azione integrata che metta a fattor
comune le diverse attribuzioni istituzionali delineate, anche al fine di avere
un maggior presidio ed assicurare una maggiore efficacia delle azioni sul
territorio e nel rispetto delle esigenze delle relative *constituency*. In
quest’ottica si inserisce l’esigenza di definire un modello organizzativo ed
operativo per la costituzione e l’avvio di CERT regionali nell’ambito della
Pubblica Amministrazione italiana, che possa delineare uno standard nazionale
rispetto al quale basare ogni implementazione degli stessi su base locale,
tenendo in considerazione ed indirizzando al meglio le esigenze dei singoli
settori, dell’industria ed i vincoli specifici delle singole amministrazioni.

.. [3] Indirizzo Operativo 5 “*Operatività delle strutture nazionali,
   di incident prevention, response e remediation*”, Piano Nazionale
   per la protezione cibernetica e la sicurezza informatica, Marzo 2017.

All’interno del presente documento sono illustrati gli aspetti significativi da
considerare per poter avviare ed operare un CERT e che potranno essere presi a
riferimento per la costituzione di CERT regionali. Tali aspetti riguardano:

- modello funzionale di riferimento;
- struttura amministrativa ed organizzativa;
- catalogo dei servizi da erogare;
- carta dei processi e matrice delle responsabilità;
- risorse necessarie, in termini di personale, informazioni (*modello dati*),
  modelli tecnologici e applicativi e facilities;
- requisiti di sicurezza fisica e logica da implementare;
- modalità di analisi e valutazione dei risultati raggiunti;
- opportunità di finanziamento per iniziative nel nostro Paese;
- piano di attuazione.

Nella definizione del modello sono state prese in considerazione le
indicazioni e Best Practice fornite dalle organizzazioni internazionali di
riferimento del settore (ENISA - *Agenzia Europea per la sicurezza delle reti e
dell’informazione*; CERT/CC – *CERT Coordination Center della Carnegie Mellon
University - Software Engineering Institute*; FIRST - *Forum of Incident
Response and Security Teams*; TI - *Trusted Introducer*) e le pratiche attuate
dal CERT-PA [4]_.

.. [4] Si rimanda ai par. 2.2 e 2.3 per un elenco più dettagliato dei
   riferimenti considerati.

Il documento è organizzato nelle seguenti sezioni:

- **Sezione 1 -** *Cosa è un CERT*: presentazione degli aspetti fondamentali
  alla base della dell’organizzazione di un CERT e del contesto in
  cui lo stesso è chiamato ad operare (Cap. 4-7);

- **Sezione 2** - *Cosa fa un CERT regionale*: descrizione del modello
  funzionale di riferimento per un CERT regionale, con presentazione degli
  elementi costitutivi dello stesso in termini di servizi, processi e risorse
  necessarie; vengono inoltre illustrati alcuni modelli per l’analisi delle
  performance (metriche e indicatori) (Cap. 8-12);

- **Sezione 3** - *Come avviare un CERT regionale*: vengono inoltre
  forniti una panoramica sui fondi disponibili per finanziare la costituzione e
  l’esercizio di un CERT regionale e un possibile piano di attuazione (Cap.
  13-14);

- **Appendici:** *Glossario dei termini*.
