Sicurezza
=========

Sicurezza fisica
----------------

La gestione della sicurezza fisica concerne l’identificazione e l’adozione di
tutte le misure necessarie per proteggere le aree, i sistemi e le persone che
operano sui sistemi informativi e le informazioni (riservate, sensibili, ecc.)
da questi raccolte, trattate e conservate.

La sicurezza fisica degli ambienti del CERT deve essere progettata in modo tale
da garantire dei livelli appropriati di protezione delle informazioni gestite.
Alcuni aspetti più immediati da considerare sono la disponibilità di aree
dedicate per ogni rappresentanza all’interno del CERT, aree sicure per tutti i
server e le repository di dati del CERT, così come casseforti o armadi blindati
per le informazioni e i dati non elettronici, e la disponibilità di linee
cifrate e sicure di comunicazione interna ed esterna (telefoni, fax, email,
schemi crittografici), al fine di impedire accessi non autorizzai, danni o
interferenze.

La sicurezza delle aree concerne la protezione degli ambienti che ospitano le
persone e i sistemi, impedendo accessi non autorizzati, danni e interferenze,
danneggiamento delle informazioni e impedimento allo svolgimento dei servizi e
dei processi informatici.

È importante osservare che l’adozione di alcune misure minime di sicurezza
fisica delle strutture che ospitano i CERT deve essere assicurata per poter
soddisfare i requisiti di accreditamento ed affiliazione richiesti da
organizzazioni ed associazioni di riferimento quali ENISA, Carnegie Mellon,
FIRST, Trusted Introducer.

In particolare sono di seguito riportate alcune delle misure minime da
implementare, ovvero:

- Stabilire un luogo specifico per ogni locale del CERT, con in
  aggiunta una struttura protetta per le riunioni (war room).

- Assicurare la chiusura delle porte di accesso ai locali del CERT.

- Rafforzare i controlli fisici di accesso (badge, chiavi) al fine di
  impedire accessi non autorizzati alle strutture del CERT.

- Rendere disponibile in ogni locale del CERT un deposito sicuro
  (armadio chiuso a chiave, cassaforte) per archiviare la
  documentazione riservata ed il disco di backup.

- Dotare i locali di distruggi documenti.

- Adottare, in conformità con i termini di legge, sistemi di
  videosorveglianza per proteggere i perimetri esterni e registrare gli
  accessi alle aree riservate.

- Attivare all’interno dei locali sistemi di allarme con sensori di
  movimento quando personale del CERT o altro personale autorizzato
  (vigilanza, servizi di pulizia, ecc.) non sono presenti.

- Adottare le dovute contromisure per proteggere le conversazioni
  telefoniche confidenziali, per non renderle accessibili a terzi non
  autorizzati.

Altre misure, per quanto raccomandabili al fine garantire il raggiungimento di
livelli di sicurezza superiori, possono ritenersi opzionali, anche in
considerazione della relativa complessità e dei costi implementativi.

Un’ulteriore area di sicurezza fisica da considerare concerne quella delle
apparecchiature, ovvero l’insieme delle misure in grado di assicurare la
protezione delle risorse ICT e dei supporti da danneggiamenti accidentali o
intenzionali e la sicurezza ambientale demandata principalmente agli impianti di
alimentazione e di condizionamento. Tali misure sono da valutare ed implementare
quando il CERT ha in gestione esclusiva anche la componente di data center e
delle apparecchiature informatica. I fattori da tenere in considerazione in
questi casi sono:

- *Posizionamento delle apparecchiature*: le apparecchiature devono
  essere disposte su pavimenti flottanti, a distanza da condutture di
  liquidi. I server e gli apparati di rete devono essere posti in
  appositi armadi (rack).

- *Sistemi di climatizzazione*: deve essere implementato un sistema di
  controllo del livello di temperatura ambientale e di umidità, almeno
  nelle aree che ospitano i server, al fine di garantire le condizioni
  ambientali volute.

- *Sistema rilevamento allarmi ambientali*: comprendono i sistemi di
  rivelazione fumo e sistemi antincendio, con attivazione dei relativi
  impianti di spegnimento degli incendi, progettati in conformità con
  le normative di settore al fine di non mettere a rischio la sicurezza
  delle persone né danneggiare i sistemi, e impianti di allarme
  anti-allagamento da posizionare al di sotto del pavimento flottante.

- *Impianti di alimentazione elettrica*: deve essere garantita
  l’alimentazione elettrica delle apparecchiature e degli impianti. Ciò
  può avvenire configurando le linee di alimentazione elettrica in modo
  che provengano da sorgenti separate, attraverso l’uso di UPS
  (Uninterruptible Power Supply) e batterie tampone (per protezione da
  brevi black-out o discontinuità elettriche) e di gruppi elettrogeni
  (per protezione in caso di lunghi black-out, purché sia garantita la
  disponibilità di combustibile per alimentarli). UPS, batterie e
  generatori devono avere la potenza necessaria per sostenere tutte le
  apparecchiature ad essi collegate durante il periodo di
  indisponibilità dell’alimentazione elettrica.

- *Cablaggi*: i cavi di alimentazione elettrica e di telecomunicazione
  devono essere disposti in canaline sotto un pavimento flottante o
  aeree per evitare danneggiamenti involontari. Tali canaline devono
  essere opportunamente distinte tra i cablaggi di alimentazione e
  quelli di telecomunicazione, per evitare interferenze reciproche, ed
  etichettate all’inizio e alla fine per consentirne rapidamente il
  riconoscimento della funzione. Ove possibile, è auspicabile corazzare
  le canaline se transitano fuori dalla sede (per evitare manomissioni
  volontarie o danneggiamenti durante interventi ordinari e
  straordinari sulle aree esterne (es. scavi).

Archivi fisici
~~~~~~~~~~~~~~

Gli archivi fisici possono essere utilizzati per conservare documenti su
supporto non digitale (carta, fotografie, ecc.) o digitale (hard disk, nastri,
CD, DVD, ecc.). L’accesso agli archivi fisici deve essere regolamentato
attraverso l’assegnazione di opportune autorizzazioni e meccanismi di controllo
degli accessi condivisi, come chiavi tradizionali o combinazioni, oppure
personali, spesso basati sulla lettura di tessere magnetiche, smart card o
caratteristiche biometriche. Per evitare che i documenti o i supporti siano
danneggiati, devono essere controllati costantemente da controllare temperatura
e umidità degli archivi.

All’intero degli uffici e delle aree critiche tutti i documenti devono essere
conservati negli archivi e sulla scrivania essere presenti solo quelli
strettamente indispensabili per evitare che persone non autorizzate le possano
leggere (clear desk policy).

Sicurezza logica
----------------

Se da un lato la sicurezza fisica rappresenta un primo livello di protezione dei
dati, dall’altro la sicurezza logica costituisce uno strato indispensabile per
la difesa di sistemi e reti informatiche. Infatti, in ragione della natura delle
informazioni trattate dal CERT in caso di vulnerabilità ed incidenti, oltre alle
misure di sicurezza per i canali di comunicazione, dovrebbero essere
implementati controlli logici di sicurezza per proteggere la riservatezza e
l'integrità delle informazioni.

Una base di partenza può essere validamente rappresentata, nel contesto
nazionale italiano, dalle Misure minime di Sicurezza ICT per la PA [76]_,
ovvero quell’insieme di controlli volti a garantire una sicurezza di base a
tutte le organizzazioni esposte alle minacce di tipo cyber.

.. [76] AGID “*Misure minime di sicurezza ICT per le pubbliche amministrazioni*”
   (2017).

I suddetti controlli possono essere raccolti nei seguenti ambiti di sicurezza:

- *Inventario dispositivi e software*: individuare i sistemi (hardware,
  software), i servizi e le risorse che gestiscono i dati informatici
  trattati da proteggere.

- *Governance*: identificare e rispettare le leggi e/o i regolamenti
  con rilevanza in tema di cyber security applicabili al contesto.

- *Protezione da malware*: i dispositivi in perimetro quando possibile
  devono utilizzare software di protezione, ad esempio antivirus /
  anti-malware, regolarmente aggiornato.

- *Gestione password e account*: assicurare una complessità adeguata
  delle password e gestire le utenze secondo i principi di *need to
  know* e *least privilege*.

- *Formazione e consapevolezza*: sensibilizzare il personale sui rischi
  di cyber security e sulle pratiche da adottare per l’impiego sicuro
  degli strumenti aziendali.

- *Protezione dei dati*: i sistemi devono essere configurati tramite
  procedure di hardening e backup periodici devono essere effettuati.

- *Protezione delle reti*: le reti e i sistemi devono essere protetti
  da accessi non autorizzati attraverso componenti hardware / software.

- *Prevenzione e mitigazione*: i software utilizzati vanno mantenuti
  aggiornati o dismessi in caso risultino obsoleti e non più
  aggiornabili. Nel caso di un incidente informatico devono essere
  informati i responsabili di sicurezza che seguiranno il processo di
  gestione degli incidenti interno.

.. discourse::
   :topic_identifier: 9727
