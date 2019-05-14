Servizi
=======

Modelli di classificazione dei servizi
--------------------------------------

Secondo le pubblicazioni più autorevoli sul tema [67]_, i servizi offerti da un
CERT possono essere suddivisi in quattro categorie principali:

- *Servizi Reattivi*: volti a gestire gli incidenti quando si
  verificano, riducendone il danno conseguente e a rispondere alle richieste di
  assistenza dalla constituency di riferimento. Possono avere origine da
  notifiche di terzi o dalle capacità interne/esterne di monitoraggio e
  individuazione delle minacce.

- *Servizi Proattivi*: orientati alla prevenzione degli incidenti,
  mediante la condivisione delle informazioni e/o l’utilizzo di strumenti
  specifici. Sono concepiti per migliorare quindi le infrastrutture e i processi
  di sicurezza della comunità di riferimento prima che si verifichi o sia
  rilevato un incidente o evento di sicurezza. Includono anche le attività volte
  a gestire e distribuire le informazioni ottenute da fornitori e altre comunità
  che possono aiutare a limitare la diffusione di attacchi analoghi o futuri.

- *Servizi di Gestione della Qualità della Sicurezza*: comprendono
  tutte le pratiche volte a migliorare la sicurezza generale di un membro della
  constituency, concepite per incorporare i riscontri e gli insegnamenti tratti
  sulla base delle conoscenze acquisite rispondendo a incidenti, vulnerabilità e
  attacchi.

- *Gestione degli Artefatti*: prevede la raccolta e l’analisi di
  qualsiasi elemento o evidenza (file, codici malevoli, tracce in memoria) che
  sono impiegati o in generale sono coinvolti nella realizzazione di azioni
  malevole.

.. [67] ENISA, “*Un approccio graduale alla creazione di un CSIRT*”,
   Documento WP2006/5.1(CERT-D1/D2) (2006); CMU-SEI “*Handbook for
   Computer Security Incident Response Teams*” (2003).

Una possibile declinazione dei servizi afferenti alle categorie precedentemente
illustrate è rappresentata nella tabella a seguire:

.. table:: Elenco dei servizi CERT (fonte: CERT/CC, ENISA)
   :name: elenco-servizi-cert

   +---------------------+----------------------+------------------------+--------------------------+
   | Servizi reattivi    | Servizi proattivi    | Gestione della qualità | Gestione degli artefatti |
   |                     |                      | della sicurezza        |                          |
   +=====================+======================+========================+==========================+
   | - Allarmi e avvisi  | - Annunci            | - Analisi dei          | - Analisi degli          |
   |                     |                      |   rischi               |   artefatti              |
   | - Gestione degli    | - Controllo          |                        |                          |
   |   incidenti         |   tecnologico        | - Continuità           | - Risposta agli          |
   |                     |                      |   operativa e          |   artefatti              |
   | - Analisi degli     | - Revisioni e        |   ripristino in caso   |                          |
   |   incidenti         |   valutazioni della  |   di disastro          | - Coordinamento della    |
   |                     |   sicurezza          |                        |   risposta agli          |
   | - Sostegno della    |                      | - Consulenza sulla     |   artefatti              |
   |   risposta agli     | - Configurazione e   |   sicurezza            |                          |
   |   incidenti         |   mantenimento della |                        |                          |
   |                     |   sicurezza          | - Sensibilizzazione    |                          |
   | - Coordinamento     |                      |                        |                          |
   |   della risposta    | - Sviluppo di        |                        |                          |
   |   agli incidenti    |   strumenti di       | - Istruzione /         |                          |
   |                     |   sicurezza          |   formazione           |                          |
   | - Risposta agli     |                      |                        |                          |
   |   incidenti in loco | - Servizi di         | - Valutazione o        |                          |
   |                     |   rilevamento        |   certificazione dei   |                          |
   | - Gestione delle    |   intrusioni         |   prodotti*            |                          |
   |   vulnerabilità     |                      |                        |                          |
   |                     | - Divulgazione di    |                        |                          |
   | - Analisi delle     |   informazioni       |                        |                          |
   |   vulnerabilità     |   relative alla      |                        |                          |
   |                     |   sicurezza          |                        |                          |
   | - Risposta alle     |                      |                        |                          |
   |   vulnerabilità     |                      |                        |                          |
   |                     |                      |                        |                          |
   | - Coordinamento     |                      |                        |                          |
   |   della risposta    |                      |                        |                          |
   |   alle              |                      |                        |                          |
   |   vulnerabilità     |                      |                        |                          |
   +---------------------+----------------------+------------------------+--------------------------+

Nell’ambito della presente trattazione, si propone di adottare, ai fini della
definizione del catalogo dei servizi essenziali offerti da un CERT Regionale, un
modello alternativo di classificazione dei servizi, il modello “IRPA” (Incident
Response PA), in uso presso il CERT-PA. Tale scelta è orientata alla possibilità
di sfruttare eventuali sinergie e definire, con riferimento ai CERT Regionali,
un insieme di servizi supplementari offerti rispetto a quanto oggi realizzato
dal CERT-PA verso la propria constituency.

Gli obiettivi principali del modello IRPA nel dominio della PA italiana sono:

- prevenire e/o ridurre gli impatti di incidenti sulla sicurezza delle
  informazioni;

- stabilire un modello strategico per i ruoli e le responsabilità dei
  differenti attori nel processo di gestione degli incidenti di sicurezza
  informatica;

- raccordare e mantenere le diverse politiche e dottrine esistenti in
  un piano strategico di IRPA che sia unitario e contestualizzato;

- facilitare la consapevolezza, la condivisione delle informazioni, il
  coordinamento e l’esecuzione durante la gestione ordinaria e soprattutto
  durante la gestione delle crisi;

- stabilire quando e come le attività operative debbano scalare ad
  attività di risposta coordinata su tutta la PA o a livello nazionale;

- focalizzare gli incidenti con impatti sulla sicurezza, sulla salute,
  sull’economia dei cittadini e sulla credibilità della PA.

Il modello IRPA definisce pertanto un sistema di indirizzamento e coordinamento
trasversale che supporta le Amministrazioni Pubbliche, le infrastrutture
critiche e le organizzazioni private nelle:

- attività di analisi delle minacce e di nuovi scenari di rischio
  tecnologico o organizzativo;

- attività di prevenzione e contenimento dei rischi derivanti da
  incidenti informatici che possano pregiudicare, direttamente o
  indirettamente, il mantenimento delle funzioni vitali della società,
  della salute, della sicurezza, del benessere economico e sociale
  della Nazione e dei suoi Cittadini.

Il modello IRPA propone 16 servizi complessivi organizzati in cinque fasi
distinte:

- *fase di preparazione e prevenzione*, finalizzata alla stesura delle
  regole da adottare su base nazionale sulla sicurezza della PA, basate anche
  sull’esperienza data dagli incidenti passati, nonché sulla diffusione di
  informative e/o alert di sicurezza che favoriscano l’innalzamento del livello
  di consapevolezza all’interno della PA verso tematiche di cyber security;

- *fase di rilevazione*, finalizzata al rilevamento di incidenti
  attraverso l’utilizzo di apparati di sicurezza di monitoraggio, la
  condivisione delle informazioni, l’open- e il closed-source intelligence;

- *fase di analisi*, finalizzata all’analisi e classificazione di
  incidenti segnalati dalle PA facenti parte della constituency, con ulteriore
  raccolta ed analisi approfondita delle evidenze;

- *fase di risposta*, finalizzata alla definizione e coordinamento
  delle attività di risposta tra le PA, gli ISP, i media ed il CERT-Nazionale,
  con contestuale valutazione ed applicazione delle normative di riferimento (ad
  es. ingaggio delle autorità competenti in caso di frodi o crimini
  informatici);

- *fase di ripristino*, finalizzata alla definizione delle modalità di
  ripristino dei servizi una volta che la minaccia è stata neutralizzata.

I servizi proposti dal modello IRPA sono illustrati nella tabella seguente:

.. table:: Modello dei servizi basato su IRPA
   :name: modello-servizi-basato-su-irpa

   +----------------------------+-------------------------------------------+
   | Fase Modello IRPA          | Servizi                                   |
   +============================+===========================================+
   | Preparazione e prevenzione | -  Accreditamento e linee guida           |
   |                            |                                           |
   |                            | -  Informative                            |
   |                            |                                           |
   |                            | -  Formazione e awareness                 |
   |                            |                                           |
   |                            | -  Supporto al risk mapping               |
   |                            |                                           |
   |                            | -  Security assessment e consulenza       |
   +----------------------------+-------------------------------------------+
   | Rilevazione                | -  Ticketing                              |
   |                            |                                           |
   |                            | -  Threat intelligence                    |
   +----------------------------+-------------------------------------------+
   | Analisi                    | -  Correlazione                           |
   |                            |                                           |
   |                            | -  Analisi incidente                      |
   |                            |                                           |
   |                            | -  Triage & escalation                    |
   +----------------------------+-------------------------------------------+
   | Risposta                   | -  Coordinamento della risposta           |
   |                            |                                           |
   |                            | -  Supporto alle azioni di risposta       |
   |                            |                                           |
   |                            | -  Monitoraggio della risposta            |
   +----------------------------+-------------------------------------------+
   | Ripristino                 | -  Analisi post-incidente e coordinamento |
   |                            |                                           |
   |                            | -  Monitoraggio del ripristino            |
   +----------------------------+-------------------------------------------+
   | Tutte le fasi              | -  Information Sharing                    |
   +----------------------------+-------------------------------------------+

Servizi offerti dai CERT Regionali
----------------------------------

I servizi che un CERT Regionale può offrire sono molteplici. La selezione
dell’insieme dei servizi da offrire costituisce una decisione di cruciale
importanza per il raggiungimento degli obiettivi prefissati e lo sviluppo delle
relative capacità operative.

In primo luogo, i servizi offerti da un CERT Regionale dovranno essere
determinati a partire dall’analisi delle necessità della propria constituency,
identificando sin da subito i servizi minimi ed essenziali, o a maggior
rilevanza per la comunità delle PAL interessate. Un approccio troppo ambizioso,
volto all’erogazione di un numero di servizi eccessivo rispetto al reale
fabbisogno della constituency o alla effettiva disponibilità di risorse del
CERT, rischierebbe di minare in partenza la fattibilità realizzativa del
costituendo CERT e, nel lungo periodo, la sua sostenibilità. L’attivazione di
servizi specifici potrà avvenire progressivamente, potendo al termine di una
fase pilota valutare eventualmente l’espansione del portafoglio di servizi
offerti, aggiungendone di nuovi. Tale decisione sarà presa anche sulla base del
riscontro dato dalla comunità di riferimento.

In secondo luogo, il modello di servizio definito dai CERT Regionali dovrà
essere supplementare rispetto a quello definito ed implementato dal CERT-PA. È
auspicabile in tal senso che il CERT Regionale, almeno in una fase iniziale, si
impegni ad attivare quei servizi (*servizi di base/essenziali*) per i quali una
maggiore prossimità al territorio potrebbe determinare significativi
miglioramenti dei livelli di efficacia garantiti nei confronti della
constituency locale rispetto a quanto possibile realizzare attraverso un’unica
azione centralizzata da parte del CERT-PA.

Non si escludono comunque in linea di principio la possibilità e l’opportunità
per i CERT Regionali di costruire ed attuare un percorso di crescita che passi
attraverso il progressivo sviluppo di servizi caratterizzati da un maggiore
livello di complessità tecnica e di contenuto. In tal senso, a fronte di livelli
di maturità raggiunti più elevati, il CERT Regionale potrà valutare, in base
alle risorse disponibili, quali ulteriori servizi offrire, basando tale
valutazione, possibilmente, su un processo di valutazione dei rischi che
identifichi le maggiori priorità per la constituency.

I due fattori da prendere in considerazione per individuare i servizi essenziali
che il CERT Regionale dovrà offrire sono il grado di complessità realizzativa
del servizio abbinato alla sua rilevanza per la comunità di riferimento. Nei
paragrafi successivi sono illustrati i servizi di base per il CERT Regionale,
ovvero quei servizi che un CERT deve necessariamente fornire alla propria
constituency, considerando però anche il livello di risorse necessario
all’erogazione.

Accreditamento
~~~~~~~~~~~~~~

L’Accreditamento è un servizio che, relativamente a un CERT regionale, che è una
struttura intermedia tra il CERT-PA e le PAL, presenta due aspetti:

1. il CERT regionale si accredita nei confronti del CERT-PA entrando a
   far parte della sua constituency

2. la singola PAL si accredita nei confronti del CERT regionale entrando
   a far parte della sua constituency

Per quanto riguarda il primo punto, il CERT-PA mette a disposizione della
propria constituency un portale dedicato attraverso il quale

- ricevere aggiornamenti, in modo manuale e/o automatico [68]_, su nuove
  vulnerabilità/minacce. La modalità manuale comporta la distribuzione di News e
  Bollettini, blacklist e l’accesso al portale di Infosharing
  (https://infosec.cert-pa.it/). La modalità automatica fa uso di STIX/TAXII e
  MISP;

- accedere a un’area riservata ove poter scaricare materiale rivolto ai
  membri della constituency e informazioni riservate (IOC, dump di
  username/password disponibili sul “mercato” hacker);

- accedere ai servizi di Threat Intelligence

- utilizzare un canale riservato e criptato GPG per la trasmissione di
  informazioni sensibili o potenziali malware;

- partecipare ad eventuali eventi di formazioni organizzati dal CERT;

- ricevere assistenza consulenziale dedicata.

.. [68] Maggiori dettagli su questa modalità nel seguito

Nel secondo caso, invece, un potenziale membro della constituency di un CERT
Regionale (nel senso che rispetta i requisiti [69]_ necessari per poterne far
parte) ne richiede effettivamente l’ingresso. Le motivazioni sono quelle già
viste e cioè la possibilità di usufruire dei servizi che il CERT mette a
disposizione alla propria utenza. Al momento della richiesta di Accreditamento,
il Referente della sicurezza informatica della PAL provvede a contattare il CERT
Regionale attraverso i canali preposti e, dopo essersi fatto adeguatamente
riconoscere cioè dopo aver fornito la prova della propria identità e ruolo
nell’ente, si impegna a fornire al CERT le informazioni richieste per una
corretta trattazione degli incidenti di sicurezza e, in particolare:

- *Identificazione delle persone dell’ente in grado di intervenire in
  caso di incidente informatico e comunicazione delle relative modalità di
  contatto* – le figure identificate devono essere in grado di poter gestire una
  crisi informatica in tutti i suoi aspetti con particolare riferimento al
  trattamento delle informazioni sensibili che possano essere state esfiltrate
  durante l’attacco cibernetico, alla comunicazione dell’incidente sia verso
  l’interno che verso l’esterno dell’organizzazione, al coordinamento di tutte
  le figure e le aree dell’organizzazione necessarie al contenimento del
  problema e al ripristino dell’operatività nonché alla raccolta di evidenze per
  eventuali prosecuzioni a livello processuale. Di tali figure dovrebbero essere
  forniti, oltre ai nominativi, il ruolo aziendale, le modalità di contatto
  (numero di telefono fisso, cellulare, e-mail e quant’altro necessario), la
  fascia oraria di contatto e, al di fuori di essa, degli eventuali sostituti.
  Tale elenco di informazioni deve essere assolutamente tenuto aggiornato nel
  tempo (a prova cioè di dimissioni, trasferimento di ruolo, pensionamento,
  trasferimento a altre sedi ecc.). Va tenuto presente che il Referente della
  sicurezza informatica della PAL, o la persona da lui preposta, è la prima
  persona che verrà avvertita in caso di un’eventuale crisi di sicurezza
  cibernetica e il fatto che non sia disponibile quando necessario può portare a
  un pericoloso ritardo nella gestione della crisi stessa.

- *La presenza o meno di una procedura documentata per la gestione di
  incidenti di sicurezza* – questa informazione serve al CERT per capire il
  livello di maturità dell’ente relativamente alla gestione dell’incidente e
  l’eventuale adozione di best practice al riguardo ma anche se l’ente è in
  grado di raccogliere le informazioni necessarie al trattamento dell’incidente.

- *La presenza o meno di una documentazione di analisi del rischio e
  della classificazione di informazioni* – questa informazione serve al CERT per
  capire se l’ente è conscio dell’eventuale effetto domino che un incidente di
  sicurezza può causare e, in particolare, se è in grado di valutarne l’impatto.

- *L’elenco dei domini e degli indirizzi di rete che afferiscono
  all’ente*

- *Un elenco dell’hardware e del software utilizzato* – questo permette
  al CERT di comunicare in modo più efficace eventuali nuove vulnerabilità
  scoperte inviando solo le informazioni di pertinenza e riducendo quelle non
  necessarie. L’informazione trasmessa, quindi, ha già subito un’iniziale
  scrematura.

.. [69] Ad es. nel caso di un CERT regionale, che ha fondamentalmente
   giurisdizione territoriale, il fatto di avere la sede nel territorio
   di competenza

Più in generale, il CERT deve essere visto come un servizio “amico” e di
supporto, un prezioso partner nella gestione degli incidenti di sicurezza con
cui condividere tutte le informazioni necessarie, ovviamente nel rispetto di
regolamenti e policies. D’altra parte, un CERT non può assolutamente sostituirsi
alle best practice interne all’ente e alla corretta gestione “da buon padre di
famiglia”. Un CERT deve avvertire, consigliare, aiutare (e tutto ciò in modalità
best effort sulla base delle risorse assegnate) ma non può e non deve
assolutamente coprire le mancanze nella gestione dell’ente facente parte della
constituency e, in ultima analisi, non ha comunque responsabilità degli
eventuali problemi interni all’ente causati da un incidente informatico.

Una volta che la procedura di Accreditamento è andata a buon fine l’ente in
generale potrà accedere a tutti i servizi che il CERT regionale mette a
disposizione della propria constituency.

Informative
~~~~~~~~~~~

Il servizio di Informative è lo strumento che permette al CERT-Regionale di
diffondere alle PAL accreditate, sotto forma di alert periodici, bollettini di
sicurezza, generiche informative o segnalazioni di sicurezza, informazioni su:

- nuovi scenari di rischio di tipo tecnologico, normativo ed
  organizzativo, che presentano un impatto rilevante per le PAL facenti parte
  della constituency;

- insorgenza di nuove minacce o di nuove vulnerabilità ai danni di
  sistemi e applicazioni in uso presso tali PAL;

- presenza di attacchi in corso ai danni di PAL, che possono
  determinare un certo grado di impatto per l’infrastruttura tecnologica
  gestita;

- azioni sviluppate da altri soggetti operanti nella comunità delle PAL
  in risposta ad eventi e/o incidenti di sicurezza.

Tale servizio è in grado di agevolare la diffusione di informazioni tempestive e
immediatamente utilizzabili su nuovi scenari di rischio, attacchi in corso,
trend di fenomeni cyber indirizzati a specifici settori e possibili impatti per
le PAL e la loro utenza. Facilitando l’attività informativa di prevenzione sul
territorio, i CERT Regionali possono quindi agire come unità capaci di
esercitare un controllo più diretto a livello locale nei confronti della
constituency e garantire in questo modo la divulgazione di informazioni mirate.

Formazione e Awareness
~~~~~~~~~~~~~~~~~~~~~~

Il servizio di Formazione e Awareness è volto ad aumentare il livello di
consapevolezza del personale delle PAL addetto alla gestione dei processi di
sicurezza informatica su:

- principi di gestione della sicurezza delle informazioni e di cyber security;

- tematiche specifiche, quali risk management e gestione degli incidenti di
  sicurezza;

- processi e procedure adottate nel dominio della PA per favorire l’interazione
  e la cooperazione tra enti locali e CERT Regionali.

Tale servizio potrà essere attivato a fronte di richieste specifiche da parte
delle PAL accreditate. Il servizio può prevedere corsi periodici di formazione
in aula o da remoto (attraverso l’accesso a un sito di didattica remota), oppure
essere realizzato attraverso iniziative di sensibilizzazione definite a tale
scopo (workshop, eventi su base locale, ecc.). Inoltre, possono essere promosse
campagne informative a livello territoriale rispetto ai rischi di sicurezza
informatica affrontati dagli enti locali.

Ticketing
~~~~~~~~~

Il servizio di Ticketing costituisce il punto di ingresso per il processo di
Incident Response ed ha il compito di tenere traccia di tutti i potenziali
incidenti e delle informazioni ad essi correlate tramite l’ausilio di una
piattaforma tecnologica di trouble ticketing. Utilizzando tale piattaforma:

- gli utenti abilitati di ciascuna PAL accreditata può aprire
  direttamente o richiedere l’apertura di un ticket verso il CERT Regionale per
  la segnalazione di incidenti di sicurezza all’interno del proprio Ente;

- gli analisti del CERT Regionale di riferimento aggiornano le
  informazioni contenute nei ticket attraverso l’inserimento dei risultati delle
  analisi effettuate in ciascuna fase del processo di gestione degli incidenti,
  allegando eventuale documentazione raccolta (mail scambiate con vendor,
  documenti analizzati, contenuto di eventuali comunicazioni verbali, ecc.).

Tramite la piattaforma di ticketing, gli analisti del CERT Regionale possono
aprire a loro volta ticket ad altre strutture e monitorare lo stato di
avanzamento nella lavorazione di ciascun evento segnalato. Possono inoltre
tenere traccia dello stato di lavorazione di ciascun incidente segnalato,
semplificando le attività di monitoraggio dei livelli di servizio e di tutte le
attività effettuate dagli attori coinvolti.

Il servizio di ticketing offre inoltre l’opportunità di raccogliere e
centralizzare tutte le informazioni relative agli incidenti, alimentando
pertanto la knowledge base con la quale il CERT Regionale è in grado di
effettuare tutte le analisi di propria competenza, correlando tra loro, ove
necessario, segnalazioni provenienti da PAL distinte ed evidenziando eventi
sospetti o schemi di attacco ripetuti.

Correlazione
~~~~~~~~~~~~

Il servizio di Correlazione permette al CERT regionale di mettere in relazione
le segnalazioni provenienti dal ticketing e le informazioni raccolte da altre
fonti, tra cui il CERT-PA, per fornire al servizio di analisi dell’incidente una
visione di insieme su ciascuna segnalazione pervenuta.

In particolare, tramite la piattaforma di trouble ticketing e la knowledge base
da essa alimentata, si cercano correlazioni tra ticket diversi, indice di:

- pattern di attacco ripetuti nel tempo o verso target diversi;

- eventuali eventi ad impatto sistemico o trasversale tra diverse PAL.

Analisi degli incidenti
~~~~~~~~~~~~~~~~~~~~~~~

Rispetto ad un incidente segnalato e classificato autonomamente da una PAL, il
gruppo di analisti di sicurezza del CERT Regionale attiva il servizio di Analisi
Incidente, per:

- la verifica e l’analisi delle informazioni inviate dalla PAL e
  allegate al ticket;

- la verifica della classificazione effettuata dalla PAL e l’eventuale
  ri-classificazione dell’evento stesso, valutandone l’impatto in un’ottica di
  tipo sistemico ed incrociando le informazioni ricevute con ulteriori
  indicazioni ad esso correlate, ricevute da altre PAL.

Triage & escalation
~~~~~~~~~~~~~~~~~~~

Con il servizio di Triage e Escalation il CERT Regionale effettua una
normalizzazione degli incidenti segnalati, esprimendo la criticità
dell’incidente secondo una scala ordinale su più livelli di impatto [70]_.

.. [70] Si suggerisce in tal senso l’adozione di una scala ordinale a cinque
   livelli di impatto (livello 0 - livello 4) analoga a quella in uso
   presso il CERT-PA e che verrà descritta più avanti.

Al termine della fase di triage il CERT Regionale può procedere con le seguenti
azioni:

- de-classifica dell’incidente in caso di falso positivo, inviando una
  comunicazione alla PAL coinvolta e chiudendo il ticket, nel quale viene
  allegato il risultato delle analisi effettuate.

- modifica del livello di classificazione precedentemente assegnato e
  comunicato dalla PAL segnalante;

- avvio delle necessarie attività di trattamento dell’incidente,
  secondo le procedure operative condivise con le PAL in fase di accreditamento.

In caso di incidenti distribuiti, che presentano quindi impatti di sicurezza su
PAL distinte appartenenti alla propria constituency, il CERT Regionale invierà
una segnalazione urgente alle PA coinvolte, coordinando tutte le seguenti
attività di gestione incidente.

In caso di incidenti di Livello massimo (es. livello 3 secondo la scala che
verrà descritta più avanti), il CERT Regionale dovrà attivare lo stato di
Emergenza ed effettuata un’escalation verso il CERT-PA, coordinandosi con lo
stesso per tutte le seguenti attività di gestione incidente.

Supporto alle azioni di risposta
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

In fase di Supporto alle Azioni di Risposta il CERT Regionale supporta le PAL
della propria constituency fornendo possibili soluzioni agli incidenti in
termini di procedure, modalità ed eventualmente competenze sullo specifico
attacco in caso l’Ente ne fosse sprovvisto.

In particolare il CERT Regionale supporterà la PAL nella definizione del piano
di trattamento dove vengono indicati:

- i servizi e i sistemi coinvolti nell’attacco, con il relativo livello
  di classificazione;

- le misure di contrasto e contenimento progettate per il trattamento
  dell’incidente ed il rientro nello stato ordinario;

- i risultati attesi dall’applicazione delle suddette contromisure.

Nel caso di incidenti a rilevanza sistemica, il CERT Regionale procede al
coinvolgimento delle PAL interessate dall’incidente, inviando tutte le
informazioni necessarie per il trattamento dell’incidente in corso.

Information Sharing
~~~~~~~~~~~~~~~~~~~

L’Information Sharing costituisce lo scheletro di funzionamento dei processi del
CERT e di tutta la rete di CERT ed altre entità a livello nazionale ed
internazionale con cui lo stesso può entrare in contatto, in quanto definisce le
regole e le modalità di condivisione delle informazioni in ingresso ed in uscita
con tutti gli interlocutori. L’Information Sharing deve assicurare la
comunicazione tempestiva delle informazioni a tutte le parti interessate. Una
corretta condivisione di informazioni deve consentire al CERT di raccogliere
l’input, elaborare e processare l’output, mantenendo i livelli di
classificazione previsti.

La condivisione di informazioni – quali ad esempio quelle ricavate attraverso il
processo di Cyber Threat Intelligence - con altre strutture permette inoltre di
aumentare la capacità reattiva e proattiva di tutti gli attori coinvolti,
accrescendo il livello di maturità dei partecipanti al processo di Information
Sharing oltre ad arricchire l’informazione originaria in modo da consentire
valutazioni sempre più precise.

Condividere informazioni complesse in maniera non strutturata, non
contestualizzata e in alcuni casi persino duplicata, non consente l’automazione
necessaria ed utile a diminuire il caricamento e la relativa correlazione di
quanto ricevuto. Le informazioni scambiate devono pertanto essere
“*actionable*”, ovvero immediatamente utilizzabili in ambito operativo e
possono riguardare:

-  minacce ed agenti di minaccia;
-  campagne in corso;
-  vulnerabilità;
-  exploit [71]_;
-  indicatori di compromissione (IOC).

.. [71] Ovvero programmi dannosi che contengono dati o codici eseguibili in
   grado di sfruttare una o più vulnerabilità di un software presente su
   un sistema.

Le informazioni condivise provengono sia dalle attività di monitoraggio e
analisi (Threat Intelligence) svolte dal CERT sia da scambi informativi con
altri soggetti qualificati della comunità di riferimento.

Alcuni dei principi alla base della condivisione delle informazioni sono:

- fiducia nei confronti dei soggetti e delle entità con cui si coopera
  nello scambio delle informazioni;

- adozione di schemi e modelli di classificazione delle informazioni.
  Molte iniziative di condivisione delle informazioni si basano ormai su schemi
  standard accettati dalla comunità professionale, come il *Traffic Light
  Protocol* (TLP, si veda successivamente per approfondimenti) per stabilire il
  modo in cui le informazioni da condividere devono essere gestite;

- definizione del livello di accuratezza necessario per consentire
  un’efficace azione di contrasto sulle minacce in esame. Il grado di
  accuratezza necessario dovrà essere valutato in coerenza con le reali
  necessità; ad esempio, in una situazione di emergenza potrebbe essere comunque
  accettabile la condivisione di informazioni seppure parziali e in corso di
  perfezionamento se necessarie a contrastare per tempo una minaccia;

- tempestività delle comunicazioni per contrastare adeguatamente
  l’azione di un attore malintenzionato;

- possibilità di anonimizzare la fonte delle informazioni e la presenza
  di qualsiasi dato sensibile o che non è possibile/opportuno condividere con la
  constituency nella sua interezza.

Le modalità di attuazione del processo di information sharing sono molteplici.
In particolare si segnalano le seguenti come rilevanti con riferimento
all’azione di un CERT:

- *Raccolta di informazioni da fonti multiple*: un CERT può raccogliere
  informazioni relative a minacce e vulnerabilità sia dall’esterno della propria
  constituency, come ad esempio da fornitori di servizi di Threat Intelligence
  (nelle forme di rapporti, interazioni, ecc.) o CERT operanti anche in altri
  settori rispetto alla comunità di appartenenza, che all’interno, attraverso le
  segnalazioni ricevute dai membri della consitituency relativamente ad eventi o
  incidenti di sicurezza registrati.

- *Distribuzione di alerts, bollettini, informative*: un CERT può
  inviare informazioni alla propria constituency fornendo i dettagli descrittivi
  e tecnici su nuove vulnerabilità e minacce, nella forma di alert, bollettini o
  generiche informative.

- *Comunicazioni periodiche*: il CERT può organizzare incontri
  periodici, workshop o seminari per condividere informazioni verso la propria
  constituency e/o community. A seconda del livello di confidenzialità dei temi
  da discutere tali eventi possono essere limitati ad un numero ristretto di
  partecipanti.

A fianco degli strumenti già descritti nel par 8.2.1 con cui può avvenire la
condivisione di informazioni in modalità manuale (bollettini e Avvisi, portale
di infosharing, mail, ecc.) è di fondamentale importanza stabilire anche
strumenti e metodologie standard per la trasmissione automatizzata. Questo deve
avvenire, in modo particolare, con le liste di IOC (Indicators of Compromise) da
fornire in input a strumenti perimetrali come firewall, SIEM, IDS ecc. che
possano così generare le opportune blacklist e gli allarmi relativi.

L’obiettivo è quello di creare una rete di CERT collegati tra loro che,
utilizzando magari scelte tecnologiche anche differenti, possano scambiarsi
informazioni in tempo reale in modalità Producer-to-Consumer usando standard
comuni e una tassonomia condivisa, cioè un insieme di dati e metadati per la
descrizione di eventi di sicurezza, campagne cyber, malware e così via.

CERT-PA in tal senso ha avviato da tempo una sperimentazione che ha coinvolto un
gruppo di lavoro di attori pubblici e privati per la definizione di tali regole
di trasmissione. Il risultato utilizza STIX 2.0 e TAXII per il trasporto.
L’architettura usa anche Minemeld per aggregare, collezionare e processare i
dati prima di inviarli al nodo di uscita. Lato Consumer, invece, è possibile
utilizzare varie piattaforme compatibili con OpenTaxii tra cui MISP. A tal fine,
CIRCL ( Computer Incident Response Center Luxembourg ) mette a disposizione una
libreria per il pull dei dati da un Server TAXII locale o remoto.

I dettagli tecnici sono oggetto di un documento separato che verrà pubblicato
nei prossimi mesi da AGID CERT-PA e che invitiamo a consultare come riferimento
qualora si desideri implementare la trasmissione condivisa automatica di
informazioni con il CERT-PA.

.. discourse::
   :topic_identifier: 9724
