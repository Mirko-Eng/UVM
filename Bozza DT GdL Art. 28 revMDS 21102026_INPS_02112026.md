**_articolo 28, comma 5, del decreto legislativo 15 marzo 2024, n. 29_** 

# **Allegato 1: DISCIPLINARE TECNICO** 

#### **Indice** 

|**1. Introduzione........................................................................................................................4**|
|---|
|**2. Definizioni............................................................................................................................4**|
|**3. Soggetti, sistemi informativi e responsabilità..........................................................5**|
|3.1 Soggetti coinvolti................................................................................................................................5|
|3.2 Sistemi coinvolti..................................................................................................................................6|
|3.3 Titolarità e responsabilità delle banche dati............................................................................7|
|**4. Modello di interoperabilità..............................................................................................7**|
|4.1 Gestione e scambio delle informazioni......................................................................................7|
|4.2 Eventi applicativi................................................................................................................................8|
|4.3 Dati, banche dati e flussi informativi..........................................................................................9|
|**5. Descrizione delle fasi del procedimento di accertamento e valutazione**<br>**multidimensionale unificata della persona anziana non autosufficiente..............9**|
|5.1 Consultazione posizione INPS.......................................................................................................9|
|5.2 Presentazione dell'istanza per la valutazione multidimensionale allargata..............10|
|5.3 Consultazione delle istanze assegnate al PUA......................................................................11|
|5.4 Istruttoria dell'istanza.................................................................................................................... 12|
|5.5 Valutazione Multidimensionale core o allargata...................................................................13|
|5.5.1 Effettuazione Valutazione Multidimensionale core o allargata.....................................13|
|5.5.2 Redazione del verbale della valutazione multidimensionale.........................................14|
|5.5.3 Consultazione dati sanitari presenti in FSE ai fini della valutazione multidimensionale<br>15|
|5.6 Redazione e sottoscrizione del Progetto di Assistenza Individuale (PAI)..................16<br>5.6.1 Redazione del PAI........................................................................................................................16|
|5.6.2 Sottoscrizione del PAI.................................................................................................................16|
|5.7 Trasmissione all’INPS del verbale e della documentazione a supporto......................17|
|5.7.1 Trasmissione del verbale a INPS.............................................................................................17|
|5.7.2 Trasmissione della documentazione a supporto................................................................18|
|5.8 Generazione e reperimento dei PDF del verbale.................................................................19|
|5.9 Restituzione dei verbali firmati digitalmente........................................................................19|
|5.10 Consultazione della documentazione a supporto da parte dell’INPS........................20|
|5.11 Chiusura e archiviazione dell’istanza senza verbale........................................................21|



|5.12 Comunicazione degli esiti e consultazione del verbale di valutazione multidimensionale<br>unificata e del PAI....................................................................................................................................22|
|---|
|5.12.1 Trasmissione verbale finale al cittadino e consultazione esiti.....................................22|
|5.12.2 Trasmissione PAI al cittadino.................................................................................................23|
|5.12.3 Visualizzazione dati PAI..........................................................................................................23|
|5.13 Predisposizione della relazione annuale e trasmissione al CIPA................................24|
|5.14 Servizio trasversale di consultazione delle tipologiche e delle decodifiche............24|
|**6. Misure di sicurezza..........................................................................................................25**|
|6.1 Requisiti generali di sicurezza.....................................................................................................25|
|6.2 Identificazione e autenticazione.................................................................................................25|
|6.3 Autorizzazione e controllo degli accessi..................................................................................26|
|6.4 Tracciamento delle operazioni....................................................................................................26|
|6.5 Continuità operativa e ripristino................................................................................................27|
|**7. Dati di riferimento...........................................................................................................28**|
|7.1 Allegato A - Dati consultazione stato disabilità....................................................................28|
|7.2 Allegato B – Dati di acquisizione della domanda.................................................................29|
|7.3 Allegato C – Minimum Data Set della valutazione multidimensionale........................39|
|7.4 Allegato D – Minimum Data Set della valutazione multidimensionale allargata.....43|
|7.5 Allegato E – Dati verbale VMU....................................................................................................45|
|7.6 Allegato F – Schema PAI...............................................................................................................47|
|7.7 Allegato G – Dati elenco istanze................................................................................................51|
|7.8 Allegato H – Dati di consultazione della domanda..............................................................51|
|7.9 Allegato I – Documentazione......................................................................................................58|
|7.9 Allegato L – Archiviazione.............................................................................................................59|



### **1. Introduzione** 

Il presente disciplinare individua le modalità di condivisione delle banche dati alimentate da elementi o risultanze che, a qualunque titolo, entrano nel procedimento di accertamento e valutazione multidimensionale unificata della persona anziana non autosufficiente, al fine di dare attuazione al principio della programmazione integrata dei servizi, degli interventi e delle prestazioni sanitarie, sociali e assistenziali, come indicato dall’art. 1 comma 1 del decreto. 

Il presente documento definisce inoltre le regole tecniche, organizzative e di sicurezza necessarie a garantire la cooperazione applicativa tra i sistemi dei soggetti coinvolti all’art 2 comma 1 del decreto, assicurando l'uniformità nazionale dei processi di interoperabilità, nel rispetto delle competenze istituzionali dei soggetti partecipanti, della normativa vigente in materia di protezione dei dati personali e delle linee guida sull’interoperabilità tecnica delle pubbliche amministrazioni adottate dall’Agenzia per l’Italia digitale (AGID). 

Il presente disciplinare non modifica la titolarità delle banche dati né comporta l'istituzione di nuove banche dati centralizzate, ma disciplina esclusivamente le modalità di interoperabilità e di scambio delle informazioni tra i sistemi informativi dei soggetti coinvolti. 

Vengono garantiti: 

a) il principio dell'inserimento unico delle informazioni 

b) la riduzione degli adempimenti amministrativi a carico del cittadino; c) la continuità della presa in carico sociosanitaria; 

d) l'integrazione tra i sistemi informativi sanitari, sociali, assistenziali e previdenziali; e) l'uniformità nazionale dei processi di interoperabilità; 

f) la sicurezza dei dati personali e sanitari trattati. 

### **2. Definizioni** 

Ai fini del presente disciplinare tecnico si intende per: 

- a) API, Application Programming Interface, insieme di servizi applicativi utilizzati per l'interoperabilità tra sistemi informativi. 

- b) ATS, Ambito Territoriale Sociale, soggetti giuridici di cui all’art. 8, comma 3, lettera a), della legge quadro n. 328 del 2000 e di cui all’art. 23, comma 2, del D. Lgs. n. 147 del 2017 che prevede che gli ATS trovino coincidenza per le attività di programmazione ed erogazione integrata degli interventi con le delimitazioni territoriali dei distretti sanitari e dei centri per l'impiego. Gli ATS sono impegnati, in coerenza con quanto previsto dall’articolo 1, commi da 160 a 164, della legge di bilancio 2022 a garantire, per conto degli enti locali titolari, lo svolgimento omogeneo sul territorio di propria competenza di tutte le funzioni tecniche di programmazione, gestione, erogazione e monitoraggio degli interventi nell’ambito dei servizi sociali alle famiglie e alle persone, anche ai fini dell’attuazione dei programmi previsti nell’ambito della Missione 5, componente 2, del PNRR e in raccordo con quanto previsto dal D.M. n. 77 del 2022 sulla definizione dei modelli e standard per lo sviluppo dell’assistenza territoriale, in attuazione della Componente 1, Missione 6, Salute, del PNRR; 

- c) CAD, il decreto legislativo 7 marzo 2005, n. 82, e successive modificazioni, recante il Codice dell’amministrazione digitale 

- d) CIPA, Comitato interministeriale per le politiche in favore della popolazione anziana 

- e) CSI, Cartella Sociale Informatizzata, sistema informativo per la gestione delle informazioni relative ai servizi sociali; 

- f) FSE, Fascicolo Sanitario Elettronico, di cui all'art.  12, comma 1, del decreto-legge 18 ottobre 2012, n. 179, convertito, con modificazioni, dalla legge 17 dicembre 2012, n. 221, e successive modificazioni, disciplinato con decreto del 7 settembre 2023, recante «Fascicolo sanitario elettronico 2.0», pubblicato nella Gazzetta Ufficiale della Repubblica italiana il 24 ottobre 2023; 

- g) FSL, Fascicolo Sociale e Lavorativo 

- h) INI, Infrastruttura nazionale per l’interoperabilità, istituita ai sensi del comma 15-ter dell’art. 12 del D.L. 179/2012 

- i) INPS, Istituto Nazionale della Previdenza Sociale. 

- j) MEF, Ministero dell’Economia e delle Finanze 

- k) MLPS, Ministero del Lavoro e delle Politiche Sociali 

- l) MdS, Ministero della Salute. 

- m) PAI, Progetto di Assistenza Individuale 

- n) PUA, Punto Unico di Accesso 

- o) RBAC, Role Based Access Control 

- p) SISDA, Sistema Informativo Salute, Disabilità e Anziani 

- q) SPID, Sistema Pubblico di Identità Digitale 

- r) TLS, Transport Layer Security 

- s) UVM, Unità di Valutazione Multidimensionale 

### **3. Soggetti, sistemi informativi e responsabilità** 

#### **3.1 Soggetti coinvolti** 

Come indicato dal decreto all’art. 2 comma 1, i soggetti coinvolti sono: 

- a) il Ministero della salute (MDS); 

- b) il Ministero del lavoro e delle politiche sociali (MLPS); 

- c) l’Istituto nazionale della previdenza sociale (INPS); 

- d) l’Agenzia nazionale per i servizi sanitari regionali (AGENAS); 

- e) le Regioni e le Province Autonome di Trento e di Bolzano; 

- f) le aziende sanitarie territorialmente competenti; 

- g) i comuni e gli Ambiti Territoriali Sociali (ATS); 

- h) i Punti Unici di Accesso (PUA); 

- i) le Unità di Valutazione Multidimensionale (UVM); 

- j) gli istituti di patronato; 

- k) la persona anziana e gli altri soggetti legittimati alla presentazione della domanda per il 

- riconoscimento della condizione di non autosufficienza, ai sensi della normativa vigente. 

#### **3.2 Sistemi coinvolti** 

I sistemi informativi coinvolti sono: 

- a) **SISDA,** piattaforma informatica che fornisce all'utenza, attraverso un unico punto di accesso, tutte le informazioni e i servizi di cui ha bisogno. Offre, inoltre, un supporto intelligente, personalizzato e proattivo, finalizzato a semplificare l'esperienza dell'utente e a migliorare l'accessibilità al sistema delle prestazioni in materia di Salute, Disabilità e Anziani. La piattaforma mette a disposizione un'ampia gamma di servizi digitali rivolti ai cittadini, ai medici, al personale sanitario e agli altri utenti abilitati. Inoltre, agli stakeholder coinvolti nei processi in materia di disabilità, fornisce una rete di Back Office integrata di servizi, basata sulla cooperazione applicativa e sull'interoperabilità tra i diversi Enti coinvolti. 

- b) **CSI Nazionale,** applicativo informatico istituito presso il Ministero del lavoro e delle politiche sociali progettato al fine di garantire la necessaria uniformità di realizzazione sulla base delle “Linee guida e requisiti funzionali per la progettazione della Cartella sociale informatizzata”, adottate con Decreto del Ministro del Lavoro e delle Politiche Sociali n. 31 dell’11 marzo 2026. La CSI Nazionale permette la raccolta e la gestione delle informazioni e dei documenti relativi ai servizi erogati durante il percorso assistenziale dai comuni, dagli ambiti territoriali e dalle regioni, direttamente o tramite enti gestori. La CSI Nazionale è resa disponibile ai comuni ed agli ambiti territoriali sociali ed in particolare ai territori che ne siano sprovvisti oppure tramite interoperabilità per i territori dotati di una propria cartella sociale informatizzata. 

- c) **CSI Locale,** applicativo informatico che permette la raccolta e la gestione delle informazioni e dei documenti relativi ai servizi erogati durante il percorso assistenziale dai comuni dagli ambiti territoriali e dalle regioni, direttamente o tramite enti gestori. 

- **d) FSE,** è l'insieme dei dati e documenti digitali di tipo sanitario  e  socio-sanitario  generati  da eventi  clinici  presenti  e  trascorsi,   riguardanti   l'assistito, riferiti anche alle prestazioni erogate al  di  fuori  del  Servizio sanitario nazionale. Ogni  prestazione sanitaria  erogata  da  operatori pubblici,  privati  accreditati  e privati  autorizzati  è  inserita,   entro   cinque   giorni   dalla prestazione medesima, nel FSE. 

- e) **FSL,** piattaforma che consente l’interoperabilità dei sistemi informativi e delle basi di dati tra gli enti e le pubbliche amministrazioni che operano, secondo le proprie finalità istituzionali vincolate all’interesse pubblico, in materia di politiche sociali, lavoro, formazione e altri ambiti di interesse per la costituzione dello stesso. Il FSL è definito in attuazione delle linee guida di progettazione della Piattaforma digitale nazionale dati (PDND) di cui all’articolo 50-ter del decreto legislativo 7 marzo 2005, n. 82. 

- f) **Ulteriori sistemi informativi** comprendenti, ove presenti, i sistemi gestionali locali (anche sociosanitari) <mark>utilizzati dai soggetti di cui all’art. 2 comma 1,</mark> interoperabili con le piattaforme nazionali secondo le modalità definite nel presente disciplinare. 

<mark>I soggetti coinvolti assicurano l’interoperabilità dei sistemi di propria competenza, nel rispetto delle linee guida sull’interoperabilità tecnica delle pubbliche amministrazioni adottate dall’Agenzia per l’Italia digitale (AGID).</mark> 

**Servizi e componenti INPS.** Nell’ambito di SISDA, le componenti dell’Istituto assicurano la presentazione e la gestione delle istanze di valutazione multidimensionale allargata e l’esposizione dei servizi di interoperabilità di competenza INPS. Tali servizi consentono la consultazione dei giudizi vigenti in materia di invalidità civile, la consultazione delle istanze per PUA competente, l’acquisizione dei dati sanitari e della documentazione a supporto, la generazione e il reperimento dei verbali in PDF, la restituzione dei verbali firmati digitalmente e la comunicazione della chiusura per archiviazione. 

#### **3.3 Titolarità e responsabilità delle banche dati** 

FSE: i Titolari del trattamento del FSE sono i soggetti e gli esercenti le professioni sanitarie che prendono in cura l’assistito, presso cui sono redatti i dati e documenti sanitari che alimentano il FSE, sia nell'ambito del SSN e dei servizi socio-sanitari regionali, sia al di fuori degli stessi. 

CSI Nazionale: i Titolari del trattamento della CSI Nazionale sono il Ministero del lavoro e delle politiche sociali e i soggetti e gli esercenti le professioni sociali dei comuni, dagli ambiti territoriali che prendono in carico al fine di permettere la raccolta e la gestione delle informazioni e dei documenti relativi ai servizi erogati durante il percorso assistenziale. 

CSI Locale: i Titolari del trattamento della CSI Locale sono i soggetti e gli esercenti le professioni sociali dei comuni, dagli ambiti territoriali e dalle regioni che prendono in carico al fine di permettere la raccolta e la gestione delle informazioni e dei documenti relativi ai servizi erogati durante il percorso assistenziale. 

**INPS:** l’Istituto assicura la gestione delle informazioni e dei documenti acquisiti nei propri sistemi e dei servizi di propria competenza, nel rispetto dei ruoli di trattamento da formalizzare tra le amministrazioni coinvolte. Il PUA cura la trasmissione e la corretta associazione delle informazioni all’istanza di competenza; restano in capo all’UVM e al Presidente della Commissione competente, secondo i rispettivi ruoli, la responsabilità dei contenuti valutativi e la sottoscrizione dei verbali. L’INPS provvede alla produzione documentale sulla base dei dati ricevuti, all’acquisizione dei verbali firmati, alla registrazione della conclusione della pratica, alla notifica al cittadino e all’alimentazione del FSE secondo le modalità applicabili. La produzione automatica dei PDF non sostituisce la valutazione sanitaria né la firma del soggetto competente. 

### **4. Modello di interoperabilità** 

### **4.1 Gestione e scambio delle informazioni** 

I sistemi informativi coinvolti consentono la consultazione, la trasmissione e, ove previsto, l'aggiornamento delle informazioni da parte dei soggetti autorizzati, secondo le modalità disciplinate dal presente documento. 

Lo scambio delle informazioni è finalizzato a garantire il corretto svolgimento del procedimento amministrativo e avviene nel rispetto dei seguenti criteri: 

- utilizzo delle informazioni già disponibili presso l'amministrazione competente, evitando duplicazioni non necessarie; 

- trattamento dei soli dati necessari allo svolgimento delle attività previste dal procedimento; 

- disponibilità delle informazioni ai soggetti legittimati, secondo i profili di autorizzazione previsti; 

- coerenza delle informazioni utilizzate nell'ambito del procedimento; 

- sicurezza, riservatezza e protezione dei dati trattati, nel rispetto della normativa vigente; 

- tracciabilità delle operazioni di consultazione, trasmissione e aggiornamento, ove previste. 

Le modalità operative di scambio delle informazioni e i relativi flussi sono descritti nei paragrafi successivi del presente disciplinare. 

#### **4.2 Eventi applicativi** 

L'attivazione dei servizi di interoperabilità avviene esclusivamente al verificarsi di specifici eventi inerenti il procedimento di accertamento e valutazione multidimensionale unificata della persona anziana non autosufficiente. 

Per evento applicativo si intende qualsiasi evento che determina la necessità di rendere disponibili, acquisire o aggiornare informazioni tra due o più sistemi informativi. 

Costituiscono eventi applicativi, a titolo esemplificativo: 

- a) accoglienza e prevalutazione per l’identificazione del bisogno; 

- b) presentazione dell’istanza per la valutazione multidimensionale allargata; 

- c) istruttoria dell’istanza; 

- d) valutazione multidimensionale core o allargata; 

- e) redazione e sottoscrizione del Progetto di Assistenza Individuale (PAI); 

- f) trasmissione del verbale della valutazione multidimensionale unificata; 

- g) trasmissione dell’eventuale documentazione a supporto; 

- h) comunicazione degli esiti del procedimento; 

- i) trasmissione e consultazione del Progetto di Assistenza Individuale (PAI); 

Per i servizi INPS costituiscono inoltre eventi applicativi: la richiesta dei giudizi vigenti; la richiesta dell’elenco e del dettaglio delle istanze di competenza territoriale del PUA; la corretta acquisizione dei dati del verbale e della documentazione necessaria; la generazione e la richiesta dei PDF integrale e con omissis; la restituzione dei documenti firmati digitalmente dal Presidente della Commissione competente; la registrazione della conclusione con emissione del verbale; la notifica al cittadino e l’alimentazione del FSE; la richiesta motivata di chiusura e archiviazione senza emissione di verbale. Gli esiti delle singole operazioni sono distinti, affinché la sola ricezione tecnica non sia equiparata alla conclusione del procedimento. 

Ogni evento determina l'attivazione dei soli servizi di interoperabilità necessari allo svolgimento della specifica fase procedimentale. 

#### **4.3 Dati, banche dati e flussi informativi** 

Il presente disciplinare regola lo scambio delle informazioni tra i sistemi informativi coinvolti. 

In ogni fase del procedimento si individua almeno: 

- a) il sistema che rende disponibile l'informazione; 

- b) il sistema destinatario; 

- c) le amministrazioni titolari dei sistemi coinvolti; 

- d) il contenuto informativo oggetto della trasmissione; 

- e) l’output atteso 

### **<mark>5. Descrizione delle fasi del procedimento di accertamento e valutazione multidimensionale unificata della persona anziana non autosufficiente</mark>** 

### **Requisiti di accesso e profilazione** 

L’accesso è subordinato alla preventiva identificazione del sistema chiamante e dell’utente che opera tramite il sistema esterno. La richiesta reca almeno l’identificativo dell’amministrazione e del sistema, l’identificativo univoco dell’operatore, il ruolo o la funzione esercitata, l’ambito territoriale di competenza e la finalità della consultazione. 

L’INPS verifica, per ogni invocazione, l’abilitazione del sistema, la validità delle credenziali, gli scope autorizzativi e la coerenza tra il soggetto consultato, la competenza territoriale dichiarata e la finalità del trattamento. Eventuali consultazioni fuori ambito territoriale sono ammesse esclusivamente in presenza di una specifica base autorizzativa, da rappresentare nella richiesta e sottoporre a tracciamento rafforzato. 

La risposta distingue almeno i seguenti esiti: posizione vigente disponibile; posizione non presente; soggetto non rientrante nell’ambito autorizzato; richiesta non autorizzata; indisponibilità tecnica del servizio. Non sono restituiti dati ulteriori rispetto a quelli previsti dal profilo attribuito. 

Tutte le consultazioni sono registrate mediante identificativo di correlazione, data e ora, sistema e operatore richiedente, codice fiscale consultato, finalità, esito e ambito territoriale applicato. 

#### **5.1 Consultazione posizione INPS** 

||i      i  t|**C**<br>i      i  t|**ONSULTA**<br>i      i  t|**ZIONE POSIZIO**<br>i      i  t|**NE INPS**<br>i      i  t|i      i  t|
|---|---|---|---|---|---|---|
|**DESCRIZIONE DELLA**<br>**FASE**<br>|Consult   i      i  t<br>momen|azione   i      i  t<br>to della|dei giudizi vi      i  t<br>richiesta,t|igenti in materia    i  t<br>ramite servizio e|i   di invalidità civile ri  t<br>sposto dall’INPS.|i      iferiti al soggetto al|
|**ATTIVITÀ**<br>**PRINCIPALE**|Consult i|azione i|dati||||
|**SOGGETTI**||PUA|||||
|**COINVOLTI**||UVM|||||
|**AMMINISTRAZIONI**||INPS|||||
|**COINVOLTE**||MLPS|||||
|**SISTEMI COINVOLTI**|<br><br>|SISDA<br>Gestio<br>CSI Naz|inale locale (<br>ionale|i  anche sociosanit|i   ario)||
||**Uten**|**te**|**Da**|**A**|**Intermediario**<br>**di**<br>**Interoperabilit**|**Note**|
|**SCAMBIO DATI**||||i|**à**||
||PUA/||SISD|Gestionale<br>locale|-|Intervento<br>utente/manual|
||UVM||A BE|(anche<br>socio-||e|



||||sanitario)/CS<br>i Locale|||
|---|---|---|---|---|---|
||PUA/<br>UVM|SISD<br>A BE|SISDA FE||Intervento<br>utente/manual<br>e|
||PUA/<br>UVM|SISD<br>A BE|CSI<br>NAZIONALE|FSL|Intervento<br>utente/manual<br>e|
|**OUTPUT DELLA**<br>**FASE**|Restituzion   i   i i<br>disponibili;i<br>effettuare l|ie dei giudizi vii   i i<br>indicazione disi<br>ft a consultazion|i   genti e dei relativi i<br>tinta dell’assenza<br>ft  e.|i   i   i riferimenti t<br>i  di giudizi e d|i   i   i i emporali e<br>documentali<br>i     ell’impossibilità tecnica di|
|**DATI DI**<br>**RIFERIMENTO**|ft<br>Allegato A – i|ft<br>Dati consulta|ft<br>i zione stato disabili|i   tà||



### **Dettaglio Servizio** 

Il servizio INPS consente ai sistemi esterni autorizzati di interrogare, mediante codice fiscale, la posizione vigente del soggetto in materia di invalidità civile. La risposta è limitata alle informazioni strettamente necessarie alle finalità istituzionali del soggetto richiedente e al profilo autorizzativo dell’operatore. L’esito della fase consiste nella consultazione dei dati secondo il tracciato definito nell’Allegato A. 

#### **5.2 Presentazione dell'istanza per la valutazione multidimensionale allargata** 

|**PRESENTAZIONE DE**<br>|**LL'ISTANZA PER**<br>|**LA VALUTA**<br>|**ZIONE MU**<br> i|**LTIDIMENSIONAL**<br>i|**E ALLARGATA**<br>i|
|---|---|---|---|---|---|
|**DESCRIZIONE DELLA FASE**|Presentazione|della doman|aper ricon i|oscimento benefici|i statali|
|**ATTIVITÀ PRINCIPALE**|Compilazione e<br>t|acquisizione<br>t|della dom|anda||
||<br>Cittadi|tno||||
|**SOGGETTI COINVOLTI**|<br>Patron<br><br>Operat|ato<br>ore PUA||||
|**AMMINISTRAZIONI**<br>**COINVOLTE**|INPS|||||
|**SISTEMI COINVOLTI**|SISDA|||||
||**Utente**|**Da**|**A**|**Intermediario di**<br>**Interoperabilità**|**Note**|
||Cittadino|SISDA<br>FE|SISDA<br>BE|-||
|**SCAMBIO DATI**|Patronato|SISDA<br>FE|SISDA<br>BE||Presentazione<br>della domanda<br>tramitepatronato|
||Operatore<br>PUA|SISDA<br>FE|SISDA<br>BE|||
|**OUTPUT DELLA FASE**|Acquisizione d<br>|omanda<br>i||||
|**DATI DI RIFERIMENTO**|Allegato B–Da|tidomanda||||



### **Dettaglio Servizio** 

La presente fase attiene alla compilazione e all'acquisizione, tramite la piattaforma SISDA, della domanda di riconoscimento dei benefici statali connessi alla non autosufficienza, nell’ambito della valutazione multidimensionale allargata di cui al successivo paragrafo 5.4. 

La domanda può essere presentata, tramite il front-end di SISDA: 

- dal cittadino, 

- dal patronato, ai sensi della legge 30 marzo 2001, n. 152; 

- dall'operatore del PUA autorizzato; 

In tutti i casi, i dati acquisiti tramite il front-end di SISDA sono resi disponibili al back-end della piattaforma, a disposizione dell'INPS per i successivi adempimenti di competenza. L'esito della fase è costituito dall'acquisizione della domanda, secondo il tracciato dati di cui all'Allegato B. 

#### **5.3 Consultazione delle istanze assegnate al PUA** 

||**C**|**ONSULTA**|**ZIONE ISTANZE**|||
|---|---|---|---|---|---|
|**DESCRIZIONE DELLA FASE**|Faseprelimin|areper l’it|struttoria,tramit|e servizio esposto da|ll’INPS.|
|**ATTIVITÀ PRINCIPALE**|Consultazion|e delle ista|nze assegnate al|PUA di riferimento||
|**SOGGETTI COINVOLTI**|<br>PUA<br><br>UVM|||||
|**AMMINISTRAZIONI**<br>**COINVOLTE**|<br>INPS<br><br>MLPS|||||
|**SISTEMI COINVOLTI**|<br>SISDA<br><br>Gesti<br><br>CSI N|ionale loca<br>azionale|i le (anche sociosa|i   nitario)||
||**Utente**|**Da**|**A**<br>i|**Intermediario di**<br>**Interoperabilità**|**Note**|
|**SCAMBIO DATI**|PUA/UVM|SISDA<br>BE|Gestionale<br>locale (anche<br>socio-<br>sanitario)/CSi<br>Locale|-|Intervento<br>utente/manuale|
||PUA/UVM|SISDA<br>BE|SISDA FE||Intervento<br>utente/manuale|
||PUA/UVM|SISDA<br>|CSI<br>|FSL|Intervento<br>utente/manuale|
|||BE|NAZIONALE|||
|**OUTPUT DELLA FASE**|Consultazion<br>i|e istanze<br>i|i|||
|**DATI DI RIFERIMENTO**|Allegato G – i|Dati Elenc|i o istanze|||



### **Dettaglio Servizio** 

Il servizio INPS consente ai sistemi esterni autorizzati la consultazione dell’elenco delle istanze assegnate al PUA il cui accesso è consentito esclusivamente agli operatori profilati per il PUA competente e limitatamente alle istanze ricadenti nell’ambito territoriale e organizzativo attribuito. 

Il servizio consente la ricerca mediante l'identificativo dell’istanza, il codice fiscale, lo stato di lavorazione e il periodo di acquisizione. 

L’esito della fase consiste nella consultazione dei dati secondo il tracciato definito nell’Allegato G. 

#### **5.4 Istruttoria dell'istanza** 

|||**IST**|**RUTTORIA**|**DELL'ISTAN**|**ZA**||
|---|---|---|---|---|---|---|
|**DESCRIZIONE DELLA FASE**|Fase ist<br>i|truttor<br>i|tia, prelimin<br>i|are alla valuta<br>i|zione allargata<br>i|i|
|**ATTIVITÀ PRINCIPALE**|Verific<br>valutaz i|ia della<br>ione mi|i  completezz<br>ultidimens|i  a delle inform<br>iionale allarga|i    azioni necessarie all’<br>ta|i      avvio della|
|**SOGGETTI COINVOLTI**|PUA||||||
|**AMMINISTRAZIONI**||INPS|||||
|**COINVOLTE**||MLPS|||||
|||SISDA|||||
|**SISTEMI COINVOLTI**|<br>|GEST<br>CSI|IONALE LOC|ALE|||
||**Ute**|**nte**|**Da**|**A**<br>i|**Intermediario di**<br>**Interoperabilità**|**Note**|
|**SCAMBIO DATI**|PUA||SISDA BE|Gestionale<br>locale<br>(anche<br>socio-<br>sanitario)/<br>CSI Locale|-|Intervento<br>utente/manuale|
||PUA||SISDA BE|SISDA FE|-|Accesso operatore<br>PUA al SISDA FSE|
||PUA||SISDA BE|CSI<br>Nazionale|FSL|Intervento<br>utente/manuale|
|**OUTPUT DELLA FASE**|||i||||
|**DATI DI RIFERIMENTO**|Allegat|o H Da|tidi consult|azione della|domanda||



### **Dettaglio Servizio** 

A seguito dell'acquisizione della domanda, come indicato nel precedente paragrafo, i dati e le informazioni associati all'istanza sono resi disponibili ai sistemi utilizzati dal PUA territorialmente competente, secondo le seguenti modalità: 

- a) dal back-end di SISDA (dove è stata acquisita la domanda) al gestionale locale, anche sociosanitario, o alla CSI Locale; 

- b) dal back-end di SISDA alla CSI Nazionale, mediante interoperabilità attraverso il Fascicolo Sociale e Lavorativo (FSL); 

- c) mediante accesso dell'operatore PUA autorizzato alle funzionalità rese disponibili attraverso il front-end di SISDA, nei casi in cui sia necessario consultare direttamente le informazioni presenti sulla piattaforma. 

<mark>Il PUA, sulla base delle informazioni acquisite, effettua le verifiche istruttorie necessarie e, in particolare:</mark> 

- a) verifica la presenza e la completezza dei dati e delle informazioni richiesti ai fini della successiva fase in cui viene effettuata la valutazione multidimensionale allargata; 

- b) consulta, ove necessario, le informazioni già disponibili nei sistemi coinvolti, evitando richieste informative o duplicazioni non necessarie; 

- c) integra o aggiorna, secondo le modalità previste dai sistemi utilizzati, gli elementi informativi di propria competenza; 

- d) rende disponibili all'UVM le informazioni necessarie all'avvio della fase di valutazione di cui al successivo paragrafo 5.5. 

L’esito della fase consiste nella consultazione dei dati della domanda secondo il tracciato definito nell’Allegato H. 

#### **5.5 Valutazione Multidimensionale core o allargata** 

#### **5.5.1 Effettuazione Valutazione Multidimensionale core o allargata** 

|**EFFETTUAZI**|**ONE VA**<br>ft   i|**LUTAZIONE MU**<br>ft   i|**LTIDIMENSION**<br>ft   i|**ALE CORE O ALLARG**<br>ft   i|**ATA**<br>|
|---|---|---|---|---|---|
|**DESCRIZIONE DELLA FASE**|Effettua   i<br>i|ftzione della Valuta i<br>i|ft  zione Multidim<br>i|ft   iensionale core o allarg<br>i|ata|
|**ATTIVITÀ PRINCIPALE**|Valutazi i|one Multidimensi|ionale core o all|i   argata||
|**SOGGETTI COINVOLTI**|UVM|||||
|**AMMINISTRAZIONI**<br>**COINVOLTE**|MLPS|||||
|**SISTEMI COINVOLTI**|<br><br>|CSI<br>FSL<br>Gestionale Locale|i|||
||**Utente**|**Da**<br>i|**A**<br>i|**Intermediario di**<br>**Interoperabilità**|**Note**|
|**SCAMBIO DATI**|UVM|Gestionale<br>locale socio-<br>sanitario/CSI<br>Locale|Gestionale<br>locale socio-<br>sanitario/CSI<br>Locale|-|Intervento<br>utente/manuale|
||UVM|CSI Nazionale|CSI<br>Nazionale|FSL|Intervento<br>utente/manuale|
|**OUTPUT DELLA FASE**||||||
|**DATI DI RIFERIMENTO**|<br>|Allegato C–Mini<br>Allegato D–Mini<br>allargata|mum Data Set d<br>mum Data Set d|ella valutazione multid<br>ella valutazione multid|imensionale<br>imensionale|
|||Integrazione info<br>da INPS|rmazioni a supp|orto del tracciato dati|del Verbale definito|



### **Dettaglio Servizio** 

In questa fase l'UVM acquisisce, consulta e aggiorna i dati, le informazioni e la documentazione necessari allo svolgimento delle attività valutative, secondo quanto previsto dall'articolo 7, comma 4, del decreto. <mark>Le attività sono svolte mediante i sistemi informativi disponibili nel territorio di riferimento e, in particolare:</mark> 

   - <mark>CSI Nazionale;</mark> 

   - <mark>CSI Locale o gestionale locale, anche socio-sanitario</mark> 

- <mark>I contenuti informativi della valutazione sono definiti:</mark> 

   - <mark>per la valutazione core, dal Minimum Data Set di cui all'Allegato C;</mark> 

   - <mark>per la valutazione allargata, dal Minimum Data Set di cui all'Allegato D.</mark> 

#### **5.5.2 Redazione del verbale della valutazione multidimensionale** 

|**REDAZIO**|**NE DEL V**|**ERBALE DELLA VA**|**LUTAZIONE MUL**|**TIDIMENSIONALE**||
|---|---|---|---|---|---|
|**DESCRIZIONE DELLA FASE**|Redazio|ne verbale VM||||
|**ATTIVITÀ PRINCIPALE**|Redazio|ne verbale VM||||
|**SOGGETTI COINVOLTI**|UVM|||||
|**AMMINISTRAZIONI**|<br>|MLPS||||
|**COINVOLTE**|<br>|INPS||||
||<br>|SISDA||||
|**SISTEMI COINVOLTI**|<br> <br><br>|GESTIONALE LOCAL<br>CSI|E|||
||**Utente**|**Da**|**A**|**Intermediario di**<br>**Interoperabilità**|**Note**|
|**SCAMBIO DATI**|UVM|Gestionale locale<br>socio-sanitario/C<br>SI Locale|Gestionale locale<br>socio-sanitario/C<br>SI Locale|-|Intervento<br>utente/manuale|
||UVM|CSI Nazionale|CSI Nazionale|FSL|Intervento<br>utente/manuale|
||UVM|SISDA FE|SISDA BE|-|Intervento<br>utente/manuale|
|**OUTPUT DELLA FASE**|Verbale<br>|compilato<br>i||||
|**DATI DI RIFERIMENTO**|Allegato|E–DatiVerbale V|MU|||



### **Dettaglio Servizio** 

Al termine della valutazione, l’UVM provvede alla redazione del verbale contenente gli esiti della valutazione. 

<mark>Il verbale può essere predisposto:</mark> 

- <mark>a) mediante gestionale socio-sanitario locale;</mark> 

- <mark>b) mediante CSI Locale;</mark> 

- <mark>c) mediante CSI Nazionale;</mark> 

- <mark>d) direttamente attraverso la piattaforma SISDA.</mark> 

Il verbale rappresenta il documento ufficiale contenente gli esiti della valutazione multidimensionale e costituisce il presupposto per le successive attività previste dal procedimento. 

#### **5.5.3 Consultazione dati sanitari presenti in FSE ai fini della valutazione** 

#### **multidimensionale** 

##### **CONSULTAZIONE DATI SANITARI PRESENTI IN FSE AI FINI DELLA VALUTAZIONE** **<u>MULTIDIMENSIONALE</u>** 

|**DESCRIZIONE DELLA**<br>**FASE**<br>|Consultazione dati sanitari presenti in FSE ai fini della valutazione multidimensionale|
|---|---|
|**ATTIVITÀ PRINCIPALE**|Consultazione FSE area dedicata|
|**SOGGETTI COINVOLTI**|UVM|
|**AMMINISTRAZIONI**|<br>MLPS|



|**COINVOLTE**||MdS||||
|---|---|---|---|---|---|
|**SISTEMI COINVOLTI**|<br><br>|CSI<br>FSE<br>FSL||||
||**Utente**|**Da**|**A**|**Intermediario di**<br>**Interoperabilità**|**Note**|
|**SCAMBIO DATI**|UVM|CSI Nazionale<br>i|FSE|FSL|Intervento<br>utente/manuale|
||UVM|Gestionale locale<br>socio-sanitario/C<br>SI locale|FSE|INI|Intervento<br>utente/manuale|
|**OUTPUT DELLA FASE**|Dati san|i itari acquisiti ai fini   i|i  i della valutazion i|i  i  e multidimensionale.||
|**DATI DI RIFERIMENTO**|-|||||



### **Dettaglio Servizio** 

#### **5.6 Redazione e sottoscrizione del Progetto di Assistenza Individuale (PAI)** 

#### **5.6.1 Redazione del PAI** 

|||**REDAZION**|**E DEL PAI**|||
|---|---|---|---|---|---|
|**DESCRIZIONE DELLA FASE**<br>|Redazio|ne PAI||||
|**ATTIVITÀ PRINCIPALE**|Redazio|ne PAI||||
|**SOGGETTI COINVOLTI**|UVM|||||
|**AMMINISTRAZIONI**<br>**COINVOLTE**|<br><br><br>|MLPS<br>MdS||||
|**SISTEMI COINVOLTI**|<br><br><br><br><br>|CSI<br>FSE<br>FSL||||
||<br>|INI||||
|||||**Intermediario di**||
||**Utente**|**Da**|**A**|<br>**Interoperabilità**|**Note**|
||UVM|CSI Locale<br>i|CSI Nazionale/FSE|FSL|Intervento<br>utente/manuale|
|**SCAMBIO DATI**|UVM|Gestionale locale<br>socio-sanitario|FSE|INI|Intervento<br>utente/manuale|
||UVM|CSI Nazionale<br>i|CSI Nazionale/FSE|FSL|Intervento<br>utente/manuale|
||UVM|Gestionale<br>Sanitario|FSE|INI|Intervento<br>utente/manuale|
|||locale/regionale||||
|**OUTPUT DELLA FASE**||||||
|**DATI DI RIFERIMENTO**|Allegato|F - Schema PAI||||



### **Dettaglio Servizio** 

#### **5.6.2 Sottoscrizione del PAI** 

||**SOTTOSCRIZ**<br>t|**IONE PAI**|||
|---|---|---|---|---|
|**DESCRIZIONE DELLA FASE**|Sottoscrizione PAI<br>t||||
|**ATTIVITÀ PRINCIPALE**|Sottoscrizione PAI||||
|**SOGGETTI COINVOLTI**|<br>UVM<br><br>Cittadino||||
|**AMMINISTRAZIONI**|<br>MLPS||||
|**COINVOLTE**|<br>MdS||||
||<br>CSI||||
|**SISTEMI COINVOLTI**|<br>FSE<br><br>FSL<br><br>INI||||
||**Utente**<br>**Da**<br>i|**A**|**Intermediario di**<br>**Interoperabilità**|**Note**|
||UVM<br>Gestionale locale<br>sociosanitario|FSE|INI|Intervento<br>utente/manuale|
|**SCAMBIO DATI**|UVM<br>CSI Nazionale<br>i|CSI<br>Nazionale/FSE|FSL|Intervento<br>utente/manuale|
||UVM<br>Gestionale<br>Sanitario<br>locale/regionale|FSE|INI|Intervento<br>utente/manuale|
||Cittadino<br>-|FSE|INI|Intervento<br>|
||t|||utente/manuale|
|**OUTPUT DELLA FASE**|||||
|**DATI DI RIFERIMENTO**|||||



### **Dettaglio Servizio** 

#### **5.7 Trasmissione all’INPS del verbale e della documentazione a supporto** 

#### **5.7.1 Trasmissione del verbale a INPS** 

||**TRASMISSIONE DEL VE**|**RBALE A IN**|**PS**||
|---|---|---|---|---|
|**DESCRIZIONE DELLA FASE**<br>|Trasmissione verbale a INPS||||
|**ATTIVITÀ PRINCIPALE**|Trasmissione verbale VM||||
|**SOGGETTI COINVOLTI**|UVM||||
|**AMMINISTRAZIONI**|<br>MLPS||||
|**COINVOLTE**|<br>INPS||||
||<br>CSI||||
|**SISTEMI COINVOLTI**|<br>SISDA<br><br>FSL||||
|**SCAMBIO DATI**|**Utente**<br>**Da**|**A**|**Intermediario di**<br>**Interoperabilità**|**Note**|



||UVM|Gestionale locale<br>socio-sanitario/C<br>SI Locale|SISDA BE|FSL/CSI|Modalità<br>automatica|
|---|---|---|---|---|---|
||UVM|CSI Nazionale|SISDA BE|FSL|Modalità<br>automatica|
||UVM|SISDA FE|SISDA BE||Intervento<br>utente/manuale|
|**OUTPUT DELLA FASE**|Dati Del v<br>|i  erbale acquisiti da I<br>i|i  NPS<br>|||
|**DATI DI RIFERIMENTO**|Allegato|E–DatiVerbale VMU||||



### **Dettaglio Servizio** 

Il sistema esterno trasmette all’INPS i dati strutturati del verbale, associandoli univocamente all’istanza. L’INPS esegue controlli formali e di coerenza, verificando almeno l’esistenza e lo stato dell’istanza, la competenza del soggetto trasmittente, la completezza delle informazioni obbligatorie e la conformità del contenuto al tracciato vigente. 

La ricezione tecnica non determina la conclusione del procedimento. In caso di esito positivo, i dati sono acquisiti in uno stato intermedio e resi disponibili per la successiva generazione dei documenti. In caso di esito negativo, il servizio restituisce le anomalie rilevate in forma codificata, senza acquisire definitivamente il verbale. 

L’esito della fase consiste nella trasmissione del verbale secondo il tracciato definito nell’Allegato E. 

#### **5.7.2 Trasmissione della documentazione a supporto** 

||**TRASMISSIONE DOCUMEN**|**TAZIONE A S**|**UPPORTO**||
|---|---|---|---|---|
|**DESCRIZIONE DELLA FASE**|Trasmissione documentazione|a supporto|||
|**ATTIVITÀ PRINCIPALE**|Trasmissione documentazione<br>della bozza di Regolamento ar|a supporto ve<br>t. 27 comma 7|rso INPS, come previ<br>|sto da Art. 6 c. 8|
|**SOGGETTI COINVOLTI**|UVM||||
|**AMMINISTRAZIONI**|<br>MLPS||||
|**COINVOLTE**|<br>INPS||||
||<br>CSI||||
|**SISTEMI COINVOLTI**|<br>SISDA<br><br>GESTIONALE LOCALE||||
||**Utente**<br>**Da**<br>i|**A**|**Intermediario di**<br>**Interoperabilità**|**Note**|
|**SCAMBIO DATI**|UVM<br>Gestionale locale<br>sociosanitario/CSI<br>Locale|SISDA BE|FSL|Modalità<br>automatica|
||UVM<br>CSI Nazionale|SISDA BE|FSL|Modalità<br>automatica|
||UVM<br>SISDA FE|SISDA BE||Intervento<br>utente/manuale|
|**OUTPUT DELLA FASE**|Documentazione acquisita e a|ssociata all'ist|anza||



<u>Allegato I - Documentazione</u> 

**<mark>DATI DI RIFERIMENTO</mark>** 

### **Dettaglio Servizio** 

Il sistema esterno trasmette all’INPS la documentazione a supporto della valutazione, associandola univocamente all’istanza di riferimento. Per ciascun documento sono trasmessi i file e le relative informazioni descrittive previste dal tracciato di servizio. L’INPS esegue i controlli formali e di coerenza previsti, verificando almeno l’esistenza e lo stato dell’istanza, la competenza del soggetto trasmittente, la presenza delle informazioni obbligatorie, la tipologia e il formato del documento e il rispetto degli eventuali limiti dimensionali previsti. L’esito della fase consiste nell’acquisizione della documentazione a supporto e nella relativa associazione all’istanza di riferimento. 

#### **5.8 Generazione e reperimento dei PDF del verbale** 

||i|**Generazione e r**<br>i|**eperimento PD**<br>|**F**||
|---|---|---|---|---|---|
|**DESCRIZIONE DELLA FASE**|Generaz  i<br>i|ione del filepdf del<br>i|verbale<br>i|||
|**ATTIVITÀ PRINCIPALE**|Generaz    i|ione e accesso ai doi|cumenti PDF|||
|**SOGGETTI COINVOLTI**|UVM|||||
|**AMMINISTRAZIONI**<br>**COINVOLTE**|<br><br><br>|MLPS<br>INPS||||
||<br>|CSI||||
|**SISTEMI COINVOLTI**|<br><br><br>|SISDA<br>GESTIONALE LOCAL|E|||
||**Utente**|**Da**<br>i|**A**|**Intermediario di**<br>**Interoperabilità**|**Note**|
||UVM|Gestionale locale<br>socio-sanitario/C<br>SI Locale|SISDA BE|FSL/CSI|Modalità<br>automatica|
|**SCAMBIO DATI**|UVM|CSI Nazionale|SISDA BE|FSL|Modalità<br>automatica|
||UVM|SISDA FE|SISDA BE||Intervento<br>utente/manuale|
|**OUTPUT DELLA FASE**|Predispo<br>nella ver|sizione del verbale<br>sione con omissis.|in formato PDF,|scaricabile nella versi|one integrale e|
|**DATI DI RIFERIMENTO**||||||



### **Dettaglio Servizio** 

A seguito della corretta acquisizione dei dati del verbale, l’INPS genera il documento in formato PDF in versione integrale e, ove previsto, in versione con omissis. I documenti sono prodotti esclusivamente sulla base dei dati strutturati acquisiti e sono associati all’istanza, alla versione del tracciato e a un identificativo univoco del documento. 

Il soggetto esterno autorizzato può richiedere il reperimento dei PDF mediante un servizio dedicato. La richiesta è ammessa solo per l’istanza di competenza e restituisce il documento, il relativo identificativo, la versione, la data di generazione e gli elementi necessari a verificarne l’integrità. La generazione del PDF non equivale alla sottoscrizione né alla conclusione del procedimento. 

L’esito della fase consiste nella generazione e nella messa a disposizione del verbale in formato PDF, in versione integrale e, ove previsto, con omissis. 

#### **5.9 Restituzione dei verbali firmati digitalmente** 

|||**Trasmission**|**e file firmat**|||
|---|---|---|---|---|---|
|**DESCRIZIONE DELLA FASE**|Restituz   ii<br>tt|iione dei verbali firmi<br>tt|i   iati digitalmen<br>tt|te<br>tt|tt|
|**ATTIVITÀ PRINCIPALE**|Trasmiss       tt<br>digitalm|ione a INPS del ver   tt<br>ente dal soggetto c|bale precedent  tt<br>t ompetente|emente generato, sottt|toscritto|
|**SOGGETTI COINVOLTI**|UVM|||||
|**AMMINISTRAZIONI**<br>**COINVOLTE**|<br><br><br>|MLPS<br>INPS||||
||<br>|CSI||||
|**SISTEMI COINVOLTI**|<br><br><br>|SISDA<br>GESTIONALE LOCAL|E|||
||**Utente**|**Da**|**A**|**Intermediario di**<br>**Interoperabilità**|**Note**|
||UVM|Gestionale locale<br>socio-sanitario/C<br>SI Locale|SISDA BE|FSL/CSI|Modalità<br>automatica|
|**SCAMBIO DATI**|UVM|CSI Nazionale|SISDA BE|FSL|Modalità<br>automatica|
||UVM|SISDA FE|SISDA BE||Intervento<br>utente/manuale|
|**OUTPUT DELLA FASE**|Acquisiz       tt<br>relativa|ione da parte di INP   tt<br>i istanza|S del verbale stt|ottoscritto digitalment|tt e e associato alla|
|**DATI DI RIFERIMENTO**|Allegato|I-Documentazion|e|||



### **Dettaglio Servizio** 

Il Presidente della Commissione competente, o il soggetto titolato secondo l’ordinamento applicabile, sottoscrive digitalmente i PDF generati dall’INPS utilizzando il servizio di firma digitale PAdES. Il sistema esterno trasmette all’Istituto i documenti firmati mediante un servizio di caricamento dedicato, indicando l’istanza e l’identificativo del documento originariamente generato. 

L’INPS verifica l’associazione con l’istanza, la corrispondenza del documento firmato con il PDF generato, l’integrità del file, la validità tecnica della firma e la completezza delle versioni richieste. Solo a seguito dell’esito positivo dei controlli il verbale è acquisito come documento finale e può essere utilizzato per la conclusione della pratica, la notifica al cittadino e l’alimentazione del Fascicolo Sanitario Elettronico secondo le modalità applicabili. 

L’esito della fase consiste nell’acquisizione del verbale sottoscritto digitalmente in formato PAdES e nella relativa associazione all’istanza di riferimento. 

#### **5.10 Consultazione della documentazione a supporto da parte dell’INPS** 

||**Consultazione documentazione**|
|---|---|
|**DESCRIZIONE DELLA FASE**|Consultazione della documentazione a supporto daparte dell’INPS<br>i  i|
|**ATTIVITÀ PRINCIPALE**|Consultazione,daparte degli utenti INPS autorizzati,della documentazione a|



||supportoprecedentemente trasmessa e ass|ociata all’istanza||
|---|---|---|---|
|**SOGGETTI COINVOLTI**|INPS|||
|**AMMINISTRAZIONI**<br>**COINVOLTE**|INPS|||
|**SISTEMI COINVOLTI**|SISDA|||
||**Utente**<br>**Da**<br>**A**|**Intermediario di**<br>**Interoperabilità**|**Note**|
|**SCAMBIO DATI**|Operator<br>e INPS<br>SISDA FE<br>SISDA BE||Intervento<br>utente/manuale|
|**OUTPUT DELLA FASE**|Documentazione a supporto resa disponibil  i  i<br>verifiche di competenza|e agli utenti INPS autoi|i  rizzati per le|
|**DATI DI RIFERIMENTO**|i|||



### **Dettaglio Servizio** 

La documentazione trasmessa a supporto del verbale è resa disponibile alle strutture INPS autorizzate per le verifiche di competenza. La consultazione è limitata ai casi in cui il verbale richieda verifica, integrazione o riesame e consente all’Istituto di confermare l’esito trasmesso oppure di procedere, secondo la disciplina applicabile, alla definizione mediante i propri sistemi. 

Gli accessi alla documentazione sono profilati per ruolo e pratica, sottoposti al principio di minimo privilegio e integralmente tracciati. L’esito della verifica INPS è registrato separatamente dalla mera acquisizione tecnica dei dati e dei documenti. 

L’esito della fase consiste nella messa a disposizione della documentazione a supporto agli utenti INPS autorizzati per le successive verifiche di competenza. 

#### **5.11 Chiusura e archiviazione dell’istanza senza verbale** 

||**CHIUSURA ISTANZA**|
|---|---|
|**DESCRIZIONE DELLA FASE**|Chiusura e archiviazione dell’istanza senza verbale|
|**ATTIVITÀ PRINCIPALE**|Chiusura dell’istanza nei casi in cui il procedimento non determini la redazione di<br>un verbale,con registrazione della relativa causale di archiviazione|
|**SOGGETTI COINVOLTI**|PUA|
|**AMMINISTRAZIONI**|<br>MLPS|
|**COINVOLTE**|<br>INPS|
||<br>CSI|
|**SISTEMI COINVOLTI**|<br>SISDA<br><br>GESTIONALE LOCALE|



||**Utente**|**Da**<br>i|**A**|**Intermediario di**<br>**Interoperabilità**|**Note**|
|---|---|---|---|---|---|
||PUA|Gestionale locale<br>socio-sanitario/C<br>SI Locale|SISDA BE|FSL/CSI|Modalità<br>automatica|
|**SCAMBIO DATI**|PUA|CSI Nazionale|SISDA BE|FSL|Modalità<br>automatica|
||PUA|SISDA FE|SISDA BE||Intervento<br>utente/manuale|
|**OUTPUT DELLA FASE**|Istanza c<br>data di c|hiusa e archiviata s<br>hiusura|enza verbale, c|on registrazione della c|ausale e della|
|**DATI DI RIFERIMENTO**|Allegato|L-Archiviazione||||



### **Dettaglio Servizio** 

Per le istanze assegnate, il PUA può richiedere la chiusura senza emissione del verbale nei casi previsti, inclusi la mancata presentazione del cittadino alla visita e la rinuncia all’istanza. La richiesta reca l’identificativo dell’istanza, la causale codificata, la data dell’evento, l’eventuale nota esplicativa e l’identificativo dell’operatore responsabile. 

L’INPS verifica l’esistenza e lo stato dell’istanza, l’assegnazione al PUA, l’abilitazione dell’operatore e l’ammissibilità della causale. In caso di esito positivo registra la chiusura per archiviazione, impedisce ulteriori trasmissioni del verbale salvo riapertura autorizzata e restituisce l’identificativo dell’operazione. La chiusura è distinta dai casi di rigetto o definizione con verbale ed è integralmente tracciata. 

L’esito della fase consiste nella chiusura e archiviazione dell’istanza senza produzione del verbale, con registrazione della relativa causale di chiusura. 

#### **5.12 Comunicazione degli esiti e consultazione del verbale di valutazione multidimensionale unificata e del PAI** 

#### **5.12.1 Trasmissione verbale finale al cittadino e consultazione esiti** 

|**TRASMISS**|**IONE VERBALE FINALE AL CITTADINO E CONSULTAZIONE ESITI**|
|---|---|
|**DESCRIZIONE DELLA**<br>**FASE**|Trasmissione verbale finale al cittadino e consultazione esiti<br>i  t|
|**ATTIVITÀ PRINCIPALI**|A1.1 - Trasmissione verbale finale al cittadino<br>i|
||A1.2 - Consultazione esitiprocedimento|
||<br>INPS|
|**SOGGETTI COINVOLTI**|<br>PUA/UVM<br><br>Cittadino / Patronato / Operatore PUA|
|**AMMINISTRAZIONI**<br>**COINVOLTE**|<br>MLPS<br><br>INPS|
||<br>CSI|
|**SISTEMI COINVOLTI**|<br>SISDA<br><br>GESTIONALE LOCALE|
|**SCAMBIO DATI**||



||**ID**<br>**Attività**|**Utente**|**Da**|**A**|**Intermediario di**<br>**Interoperabilità**|**Note**|
|---|---|---|---|---|---|---|
||A1.1|INPS|SISDA BE|-|-|Modalità<br>automatica|
||A1.2|PUA/UVM|SISDA BE|CSI Nazionale|FSL|Modalità<br>automatica|
||A1.2|PUA/UVM|SISDA BE|Gestionale<br>locale (anche<br>socio-<br>sanitario)/CSI<br>Locale|FSL|Modalità<br>automatica|
||A1.2|PUA/UVM|SISDA BE|SISDA FE|-|Intervento<br>utente/manuale|
||A1.2|Cit./Patr./<br>O. PUA|SISDA BE|SISDA FE||Intervento<br>utente/manuale|
|**OUTPUT DELLA FASE**|Esito e ve i|rbale finale|i resi dispon|ibili ai soggetti i|ti autorizzati||
|**DATI DI RIFERIMENTO**|||||||



### **Dettaglio Servizio** 

A seguito della conclusione del procedimento, l’INPS rende disponibile al cittadino l’esito della valutazione multidimensionale unificata e il relativo verbale finale, associati univocamente all’istanza di riferimento. Il sistema verifica lo stato dell’istanza e la disponibilità del verbale finale, consentendone la consultazione e il reperimento esclusivamente a seguito del completamento delle fasi previste dal procedimento. Il cittadino può consultare l’esito della valutazione e accedere al verbale finale attraverso i canali messi a disposizione dall’INPS. In caso di indisponibilità del verbale o di mancata conclusione del procedimento, il sistema non rende disponibile il documento finale e restituisce all’utente l’informazione relativa allo stato dell’istanza. 

L’esito della fase consiste nella comunicazione dell’esito della valutazione e nella messa a disposizione del verbale finale al cittadino per la relativa consultazione. 

#### **5.12.2 Trasmissione PAI al cittadino** 

||**TRASMISSIONE PAI AL CITTAD**<br>t|**INO**|||
|---|---|---|---|---|
|**DESCRIZIONE DELLA FASE**|Trasmissione PAI al cittadino<br>t||||
|**ATTIVITÀ PRINCIPALE**|Trasmissione PAI al cittadino||||
|**SOGGETTI COINVOLTI**|UVM||||
|**AMMINISTRAZIONI**|<br>MLPS||||
|**COINVOLTE**|<br>MdS||||
|**SISTEMI COINVOLTI**|<br>CSI<br><br>FSE||||
||**Utente**<br>**Da**|**A**|**Intermediario di**<br>**Interoperabilità**|**Note**|
|**SCAMBIO DATI**|UVM<br>CSI Locale/CSI<br>Nazionale/gestionale<br>sociosanitario|FSE|-||
|**OUTPUT DELLA FASE**|||||
|**DATI DI RIFERIMENTO**|||||



### **Dettaglio Servizio** 

#### **5.12.3 Visualizzazione dati PAI** 

|**DESCRIZIONE DELLA**<br>**FASE**|Visuali i|**VISUAL**<br>zzazione dati P|**IZZAZIONE DA**<br>i AI|**TI PAI**|
|---|---|---|---|---|
|**ATTIVITÀ PRINCIPALI**|Consul|tazione PAI|||
|**SOGGETTI COINVOLTI**|PUA/U|VM|||
|**AMMINISTRAZIONI**<br>**COINVOLTE**|<br>|MLPS<br>MDS|||
|**SISTEMI COINVOLTI**|<br><br><br>|CSI<br>FSE<br>FSL<br>INI|||
|||||**Intermediario di**|
||**Uten**|**te**<br>**Da**|**A**|<br>**Interoperabilità**<br>**Note**|
|**SCAMBIO DATI**|PUA/<br>UVM|FSE|CSI<br>Locale/CSI<br>Nazionale<br>i|FSL|
||PUA/<br>UVM|FSE|Gestionale<br>sociosanitario<br>i|INI|
||PUA/<br>UVM|FSE|Gestionale<br>sanitario|INI|
|**OUTPUT DELLA FASE**|||||
|**DATI DI RIFERIMENTO**|<br><br>|Allegato C– <br>Allegato D– <br>allargata<br>Allegato F - S|Minimum Data<br>Minimum Data<br>chema PAI|Set della valutazione multidimensionale<br>Set della valutazione multidimensionale|
|**Dettaglio Servizio**|||||



#### **5.13 Predisposizione della relazione annuale e trasmissione al CIPA.** 

Annualmente, come descritto all’art. 10 del decreto, il Ministero del lavoro e delle politiche sociali e il Ministero della salute provvedono alla raccolta e all’elaborazione dei dati di sintesi relativi al procedimento di accertamento e valutazione multidimensionale unificata della persona anziana non autosufficiente, nonché alle misure attivate a seguito dello stesso. <mark>La relazione è trasmessa al CIPA…</mark> 

#### **5.14 Servizio trasversale di consultazione delle tipologiche e delle decodifiche** 

||**SERVIZIO TRASVERSALE**|
|---|---|
|**DESCRIZIONE DELLA**<br>**FASE**|Estrazione decodifiche|
|**ATTIVITÀ PRINCIPALI**|Estrazione decodifiche|



|**SOGGETTI COINVOLTI**|<br>ML<br><br>INP|PS<br>S||||
|---|---|---|---|---|---|
|**AMMINISTRAZIONI**<br>**COINVOLTE**|MLPS<br>i|i|i|i||
|**SISTEMI COINVOLTI**|<br>Gei<br><br>CSI|stionale loc|i ale (anche socio|i   sanitario)||
||**Utente**|**Da**|**A**<br>i|**Intermediario di**<br>**Interoperabilità**|**Note**|
|**SCAMBIO DATI**|-|SISDA BE|Gestionale<br>locale socio-<br>sanitario/CSI<br>Locale||Modalità automatica<br>i|
||-|SISDA BE|CSI Nazionale||Modalità automatica|
|**OUTPUT DELLA FASE**|Decodifich|ie/informazi   i|oni di servizio rei|stituite al sistema|i   richiedente|
|**DATI DI RIFERIMENTO**||||||



### **Dettaglio Servizio** 

Il servizio trasversale supporta le diverse fasi del processo di valutazione multidimensionale unificata e rende disponibile funzionalità comuni necessarie alla gestione e allo scambio delle informazioni tra i sistemi coinvolti. 

Tale servizio consente, in funzione delle specifiche esigenze del processo, il reperimento delle informazioni associate all’istanza, la consultazione dello stato della lavorazione, l’acquisizione delle informazioni di servizio e delle decodifiche necessarie alla corretta gestione dei dati. 

Il servizio trasversale non determina autonomamente l’avanzamento o la conclusione del procedimento, ma fornisce funzionalità di supporto utilizzabili nell’ambito delle diverse fasi del processo. 

### **<mark>6. Misure di sicurezza</mark>** 

#### **<mark>6.1 Requisiti generali di sicurezza</mark>** 

<mark>Le Amministrazioni coinvolte, ciascuna per i sistemi e i servizi di propria competenza, adottano misure tecniche e organizzative adeguate a garantire un livello di sicurezza commisurato ai rischi connessi al trattamento dei dati e ai processi di interoperabilità, ai sensi dell’articolo 32 del Regolamento (UE) 2016/679 (GDPR) e dell’articolo 51 del decreto legislativo 7 marzo 2005, n. 82 (CAD).</mark> 

<mark>I requisiti di sicurezza riguardano, in particolare:</mark> 

- <mark>a) identificazione e autenticazione;</mark> 

- <mark>b) autorizzazione e controllo degli accessi; c) tracciamento delle operazioni e gestione dei log;</mark> 

- <mark>d) continuità operativa e ripristino dei servizi.</mark> 

<mark>Ciascuna Amministrazione assicura, per i sistemi di propria competenza, la protezione dei servizi, delle interfacce applicative, dei canali di comunicazione e dei dati trattati, nonché l’adozione di misure per la prevenzione, l’individuazione e la gestione delle vulnerabilità e degli incidenti di sicurezza. Le eventuali violazioni di dati personali sono gestite in conformità agli articoli 33 e 34 del GDPR.</mark> 

<mark>Ciascuna Amministrazione è responsabile dell’attuazione delle misure di sicurezza relative ai propri sistemi e servizi e assicura che gli eventuali soggetti terzi coinvolti nel trattamento adottino misure coerenti con i requisiti del presente disciplinare.</mark> 

<mark>Le modalità tecniche di attuazione sono definite da ciascuna Amministrazione per i sistemi di propria competenza, nel rispetto dei requisiti di seguito stabiliti.</mark> 

#### **<mark>6.2 Identificazione e autenticazione</mark>** 

<mark>L’accesso ai sistemi utilizzati per lo scambio, la consultazione e la predisposizione dei dati è consentito esclusivamente a soggetti o sistemi preventivamente identificati e autenticati mediante meccanismi commisurati al livello di rischio.</mark> 

<mark>Per le comunicazioni tra sistemi sono adottati meccanismi idonei a garantire l’identificazione e l’autenticazione delle parti comunicanti e la protezione delle comunicazioni, mediante certificati digitali X.509 e Mutual TLS (mTLS) o meccanismi equivalenti.</mark> 

<mark>L’autenticazione degli utenti avviene, ove applicabile, mediante i sistemi di identificazione elettronica previsti dall’articolo 64 del CAD, in conformità alla normativa e alle Linee guida vigenti. Per i servizi applicativi basati su API possono essere utilizzati standard riconosciuti, quali OAuth 2.0, OpenID Connect e JSON Web Token (JWT), o standard equivalenti, secondo le modalità previste dalle Linee guida AgID applicabili.</mark> 

<mark>Le Amministrazioni assicurano, per i sistemi di rispettiva competenza:</mark> 

- <mark>la gestione sicura del ciclo di vita dei certificati digitali e delle credenziali;</mark> 

- <mark>il rinnovo o la rotazione delle credenziali di servizio secondo periodicità commisurate al rischio;</mark> 

- <mark>la tempestiva revoca delle credenziali non più valide o compromesse;</mark> 

- <mark>l’autenticazione multifattore per gli accessi privilegiati e negli ulteriori casi individuati sulla base dell’analisi dei rischi.</mark> 

Per i servizi INPS, l’identità applicativa del sistema chiamante non sostituisce l’identificazione dell’operatore. Ove l’operazione sia avviata da una persona fisica, il sistema esterno propaga all’INPS, con modalità verificabili, l’identificativo univoco dell’utente, l’ente di appartenenza, il ruolo esercitato, il PUA o la struttura di riferimento e gli ulteriori attributi necessari all’autorizzazione. 

#### **<mark>6.3 Autorizzazione e controllo degli accessi</mark>** 

<mark>L’accesso ai dati, ai sistemi e ai servizi è consentito esclusivamente ai soggetti autorizzati, in relazione alle rispettive competenze e secondo i principi di necessità e minimo privilegio. I sistemi di autorizzazione assicurano, ove applicabile:</mark> 

- <mark>l’attribuzione dei privilegi sulla base di ruoli o funzioni, mediante modelli Role Based Access Control (RBAC) o equivalenti;</mark> 

- <mark>l’applicazione del principio del minimo privilegio (Least Privilege);</mark> 

- <mark>la verifica periodica delle autorizzazioni e la loro tempestiva modifica o revoca al venir meno dei relativi presupposti.</mark> 

<mark>Per i servizi basati su API, l’autorizzazione è verificata a ogni invocazione mediante token di accesso, scope autorizzativi o meccanismi equivalenti.</mark> 

L’autorizzazione ai servizi INPS combina attributi di ruolo, amministrazione di appartenenza, PUA o struttura competente, ambito territoriale, finalità dell’operazione e stato dell’istanza. Le regole devono impedire la consultazione o la modifica di posizioni non pertinenti, salvo specifiche eccezioni formalmente abilitate e tracciate. 

La profilazione degli operatori è gestita dall’amministrazione di appartenenza, che assicura il censimento, l’aggiornamento e la revoca tempestiva delle abilitazioni. L’INPS conserva la facoltà di sospendere credenziali, sistemi o profili in caso di uso anomalo, perdita dei requisiti o violazione delle regole di sicurezza. 

#### **<mark>6.4 Tracciamento delle operazioni</mark>** 

<mark>Ciascuna Amministrazione assicura, per i sistemi di propria competenza, il tracciamento degli accessi ai dati e delle azioni effettuate dagli utenti, mediante appositi sistemi di logging, al fine di garantire la tracciabilità delle attività svolte e consentire l’individuazione di eventuali anomalie, accessi non autorizzati o utilizzi impropri.</mark> 

<mark>I log contengono almeno, ove applicabili:</mark> 

- <mark>l’identificativo dell’utente o del sistema che ha effettuato l’accesso;</mark> 

- <mark>la data e l’ora dell’evento;</mark> 

- <mark>la tipologia di azione effettuata;</mark> 

- <mark>l’esito dell’operazione.</mark> 

<mark>Ai fini della sicurezza e della verifica della liceità del trattamento:</mark> 

- <mark>i log sono protetti mediante misure idonee a garantirne l’integrità, l’inalterabilità e la riservatezza;</mark> 

- <mark>l’accesso ai log è consentito esclusivamente ai soggetti autorizzati;</mark> 

- <mark>i log sono conservati per un periodo commisurato alle finalità per le quali sono raccolti e successivamente cancellati, secondo i tempi di conservazione definiti da ciascuna Amministrazione nel rispetto della normativa applicabile.</mark> 

<mark>Nell’ambito dei servizi di interoperabilità sono altresì tracciati gli eventi di invio e ricezione delle informazioni e gli elementi necessari a correlare le richieste alle relative risposte, al fine di consentire la ricostruzione del ciclo delle transazioni.</mark> 

#### **<mark>6.5 Continuità operativa e ripristino</mark>** 

<mark>Le Amministrazioni adottano misure tecniche e organizzative commisurate alla criticità dei sistemi e dei servizi, al fine di garantirne la continuità operativa e il tempestivo ripristino in caso di eventi che ne compromettano il funzionamento. Sono assicurati, ove applicabili:</mark> 

- <mark>procedure periodiche di backup dei dati, delle configurazioni e delle componenti necessarie al ripristino;</mark> 

- <mark>verifica periodica dell’integrità e della possibilità di ripristino delle copie di sicurezza;  piani di Business Continuity e Disaster Recovery, sottoposti a verifiche e test periodici;  monitoraggio della disponibilità dei servizi di interoperabilità e dei relativi endpoint;  meccanismi di gestione delle indisponibilità e di recupero o ritrasmissione delle richieste non completate;</mark> 

- <mark>definizione e monitoraggio di Recovery Time Objective (RTO) e Recovery Point Objective (RPO) commisurati alla criticità dei sistemi e agli eventuali livelli di servizio definiti.</mark> 

## **<mark>7. Dati di riferimento</mark>** 

### **<mark>7.1 Allegato A - Dati consultazione stato disabilità</mark>** 

|**Campo**|**Descrizione**|**Valore Codificato**|**Note**|
|---|---|---|---|
||**ELENCO ULTIMI**|**GIUDIZI VIGENTI**||
|**Numero identificativo**|Identificativo richiesta|Stringa||
|**Tipo verifica**|Tipo verifica|Stringa|(es. ordinaria)|
|**Sistema provenienza**|Sistema di provenienza|Stringa|(es. NIC,InvCIv…)|
|**Data apertura**|Data apertura richiesta|Formato gg/mm/aaaa||
|**Data definizione**|Data definizione richiesta|Formato gg/mm/aaaa||
|**Data revisione**|Data revisione richiesta|Formato gg/mm/aaaa||
||**DETTAGLIO**|**GIUDIZIO**||
|**Numero identificativo**|Identificativo prestazione|Stringa||
|**Codice tipologia giudizio**|codice tipologia giudizio|Stringa|Descrizione tipologia giudizio<br>decodificata tramite il servizio<br>trasversale di consultazione<br>delle tipologiche|
|**Codice grado**|codice grado|Stringa|Descrizione giudizio<br>decodificata tramite il servizio<br>trasversale di consultazione<br>delle tipologiche|
|**Percentuale**|percentuale|numerico||
||**ELENCO**|**BENEFICI**||
|**Codice tipologia Beneficio**|Codice tipologia beneficio|Stringa|Descrizione beneficio|





decodificato tramite il servizio trasversale di consultazione delle tipologiche 

### **7.2 Allegato B – Dati di acquisizione della domanda** 

|**Campo**|**Descrizione**|**Valore Codificato**|**Note**|
|---|---|---|---|
||**DATI D**|**EL RICHIEDENTE**||
|**Codice Fiscale**|Codice fiscale del richiedente|Stringa alfanumerica|Recuperati da arca|
|**Nome**|Nome del richiedente|Stringa|Recuperati da arca|
|**Cognome**|Cognome del richiedente|Stringa|Recuperati da arca|
|**Sesso**|Sesso anagrafico del richiedente|Stringa<br>(Valori ammessi: Maschile;<br>Femminile; Non specificato)|Recuperati da arca|
|**Data di Nascita**|Data di nascita del richiedente|Formato gg/mm/aaaa|Recuperati da arca|
|**Comune di nascita**|Comune di nascita del richiedente|Stringa<br>(Codice ISTAT del Comune)|Recuperati da arca|
|**Provincia di nascita**|Provincia di nascita del richiedente|Stringa|Recuperati da arca|
|**Stato di nascita**|Stato di nascita del richiedente|Stringa|Recuperati da arca|
|||Stringa|Recuperati da arca|
|**Indirizzo di Residenza**|Indirizzo di residenza del richiedente|(Concatenazione di Via/Piazza con il<br>civico della residenza)||
|**CAP**|CAP di residenza del richiedente|Stringa|Recuperati da arca|
|**Comune**|Comune di residenza del richiedente|Stringa|Recuperati da arca|



|**Provincia**|Provincia di residenza del richiedente|Stringa<br>(Codice ISTAT del Comune)|Recuperati da arca|
|---|---|---|---|
|**Tipo documento identità**|Tipo documento identità del<br>richiedente|Stringa<br>(Valori ammessi: Carta d'Identità;<br>Passaporto; Patente)|i dati del documento di identità del<br>richiedente vengono richiesti e quindi<br>registrati dalla Domanda solo nel caso<br>di utente Patronato|
|**Numero Documento di**<br>**Identità**|Numero del documento|Stringa|Nessun controllo bloccante|
|**Rilasciato da**|Ente emittente|Stringa|Nessun controllo bloccante|
|**Data di Rilascio**|Data rilascio documento|Stringa|Nessun controllo bloccante|
|**Data di scadenza**|Data scadenza documento del<br>richiedente|Formato gg/mm/aaaa||
|**Stato civile**|Stato civile del richiedente|Stringa<br>(Valori ammessi: Celibe/Nubile;<br>Vedovo/a;<br>Divorziato/a;<br>Coniugato/a;<br>Separato/a;<br>Unito/a civilmente;<br>Sciolto/a da unione civile;<br>Vedovo/a da unione civile)|Recuperati da arca|
|**Cittadinanza**|Cittadinanza del richiedente|Stringa<br>(Valori ammessi: Italiano;<br>S. Marino;<br>U.E. (con data iscrizione anagrafe e<br>comune);<br>Extracomunitario (con dati<br>permesso);<br>apolide;<br>rifugiato;|Recuperati da arca|



|||prot. Sussidiaria)||
|---|---|---|---|
|**Dati Permesso di Soggiorno**|Questura di rilascio, validità dal/al,<br>data scadenza|Formato gg/mm/aaaa||
|**Dichiarazione Rinnovo**<br>**Permesso**|Dichiarazione Rinnovo Permesso di<br>soggiorno|Valori ammessi: Sì / No|Flag obbligatorio "Dichiaro di aver<br>richiesto rinnovo" se data scadenza<br>superata|
|**Allegato Permesso**|Allegato|File|Allegare permesso di soggiorno o<br>ricevuta di pagamento del rinnovo|
||**CONTA**|**TTI DI SCOPO**||
|**Ulteriore**<br>**Cellulare**|Numero di cellulare per comunicazioni|Stringa||
|**Ulteriore Mail**|Indirizzo e-mail per comunicazioni|Stringa||
|**Rappresentante legale**|**DATI DEL RAPP**<br>Rappresentante legale|**RESENTANTE LEGALE**<br>Stringa<br>(Valori ammessi: Tutore;<br>Curatore;<br>Amministratore di sostegno)||
|**Nome e Cognome**|Nominativo del rappresentante|Stringa|Recuperati da arca|



|**Codice Fiscale**|CF del rappresentante|Stringa alfanumerica||
|---|---|---|---|
|**Data di Nascita**|Data di Nascita del rappresentante|Formato gg/mm/aaaa|Recuperati da arca|
|**Comune di nascita**|Comune di nascita del rappresentante|Stringa<br>(Codice ISTAT)|Recuperati da arca|
|**Provincia di nascita**|Sigla provincia di nascita del<br>rappresentante|Stringa|Recuperati da arca|
|**Stato di nascita**|Stato di nascita del rappresentante|Stringa|Recuperati da arca|
|**Provincia di residenza**|Provincia di residenza del<br>rappresentante|Stringa|Recuperati da arca|
|**Comune di residenza**|Comune di residenza del<br>rappresentante|Stringa<br>(Codice ISTAT del Comune)|Recuperati da arca|



|**Indirizzo di Residenza**|Indirizzo di residenza del<br>rappresentante|Stringa<br>(concatenazione Via/Piazza e Numero<br>Civico)|Recuperati da arca|
|---|---|---|---|
|**CAP di residenza**|Codice Avviamento Postale|Stringa|Recuperati da arca|
|**Tribunale**|**DECRE**<br>Sede del Tribunale e Sezione|**TO DI NOMINA**<br>Stringa|I dati del decreto di nomina sono<br>richiesti solo in caso di accesso da<br>Patronato|
|**Numero**|Numero del decreto|Stringa|I dati del decreto di nomina sono<br>richiesti solo in caso di accesso da<br>Patronato|
|**Data**|Data del decreto|Formato gg/mm/aaaa|I dati del decreto di nomina sono<br>richiesti solo in caso di accesso da<br>Patronato|
|**Validità dal**|Periodo iniziale di validità della<br>nomina|Formato gg/mm/aaaa|I dati del decreto di nomina sono<br>richiesti solo in caso di accesso da<br>Patronato|
|**Validità al**|Periodo finale di validità della nomina|Formato gg/mm/aaaa|I dati del decreto di nomina sono<br>richiesti solo in caso di accesso da<br>Patronato|



||**DATI C**|**ONIUGE**||
|---|---|---|---|
|**Nome**|Nome del coniuge del richiedente|Stringa|Se Stato Civile richiedente uguale a<br>Coniugato/a o<br>Unito/a civilmente<br>Recuperato da arca|
|**Cognome**|Cognome del coniuge del richiedente|Stringa|Se Stato Civile richiedente uguale a<br>Coniugato/a o<br>Unito/a civilmente<br>Recuperato da arca|
|**Data di Nascita**|Data di nascita del coniuge|Formato gg/mm/aaaa|Recuperato da arca|
|**Codice Fiscale**|Codice Fiscale del coniuge<br>**DATI DELLA PRESC**<br>i   t|Stringa alfanumerica<br>**RIZIONE PER LA VMU**<br>|Sempre presente. Obbligatorio se<br>cittadinanza = Italiana; facoltativo se<br>comunitaria/extracomunitaria|
|**Nome medico**|Nominativo del medico prescrittore|Stringa||
|**Cognome medico**|Nominativo del medico prescrittore|Stringa||
|**n. prescrizione**|Codice/Numero identificativo<br>prescrizione|Stringa||



|**data prescrizione**|Data emissione|Formato gg/mm/aaaa|
|---|---|---|
||**DICHIARAZIONI (C**|**OMPROMISSIONI E STATO)**|
|**Cecità**|Segnalazione presenza di<br>compromissione|Valori ammessi: Si; No|
|**Sordità**|Segnalazione presenza di<br>compromissione|Valori ammessi: Si; No|
|**Sordocecità**|Segnalazione presenza di<br>compromissione|Valori ammessi: Si; No|
|**Assenza altre domande**|Dichiarazione ex art. 56, c. 2, L.<br>69/2009 (pendenza esame)|Valori ammessi: Sì / No|
|**Presenza di invalidità civile**|Dichiarazione di essere già invalido<br>civile|Valori ammessi: Sì / No|
|**Causa**|Causa invalidità|Valori ammessi: Lavoro;<br>Guerra; servizio|
|**Legge 80/2006**|Affetto da malattia neoplastica in atto|Valori ammessi: Sì / No|
|**Intrasportabilità**|Sussistenza controindicazioni mediche<br>per spostamento|Valori ammessi: Sì / No|
|**Legge 114/2014**|Affetto da patologia in situazione di<br>gravità (D.M. 2 agosto 2007)|Valori ammessi: Sì / No|
|**Illecito di terzi**|Infermità dipendente da fatto illecito<br>di terzi (Art. 41 L.183/2010). Rimanda<br>a modello AS1|Valori ammessi: Sì / No|



|**Flag Ricovero**|**DA**<br>Dichiarazione di ricovero alla data<br>attuale|**TI RICOVERO**<br>Valori ammessi: Si; No||
|---|---|---|---|
|**Ricovero indennizzato**|Ricovero indennizzato|Valori ammessi: Si; No||
|**Data inizio ricovero**|Data inizio ricovero|Formato gg/mm/aaaa||
|**Data fine ricovero**|Data fine ricovero|Formato gg/mm/aaaa||
|**Denominazione struttura**|Denominazione struttura|Stringa||
|**Indirizzo struttura**|Indirizzo struttura|Stringa||
|**Tipologia di spesa**|Tipologia di spesa|Stringa||
|||**REDDITI**||
|**Dichiarazione Redditi**<br>**Titolare**|Dichiarazione redditi titolare|Valori ammessi: Non possiedo redditi<br>oltre pensioni INPS;<br>Possiedo altri redditi/rendite estere||
|**Redditi del Coniuge**|Redditi del coniuge|Valori ammessi: Non possiedo redditi<br>oltre pensioni INPS;<br>i|Se Stato civile richiedente = 4.<br>Coniugato/a e 6. Unito/a civilmente|
||**Tabella Rei**|Possiedo altri redditi/rendite estere<br>**dditi (Modello AP70)**<br>i||
|**Tipologia reddito**|Tipologia reddito|Valori ammessi: Redditi da lavoro<br>autonomo, redditi fondiari – terreni…||
|**Soggetto**|Soggetto|Valori ammessi: richiedente/coniuge||
|**Periodo**|Periodo|Formato gg/mm/aaaa||





<!-- Start of picture text -->
Importo Importo Stringa<br>MODALITÀ DI PAGAMENTO<br>Stringa<br>(Valori ammessi: Contanti<br>Modalità di pagamento (<1000€);<br>Modalità pagamento<br>Conto Corrente; Postale  Libretto;<br>Risparmio;<br>Carta Prepagata IBAN)<br>Stringa<br>(Valori ammessi: Codice ABI;<br>Codice CAB;<br>Coordinate bancarie/postali<br>Coordinate bancarie/postali Codice IBAN;<br>CAB/Frazionario (Richiesto per<br>tutte le modalità postali con<br>IBAN)<br>Stringa<br>Intestazione conto/libretto   (Valori ammessi: Intestato al solo<br>Intestazione conto/libretto<br>titolare;<br>  Cointestato)<br>RISCOSSIONE DA PARTE DI TERZI<br>Delega alla riscossione ex  Consenso alla delega della riscossione<br>Valori ammessi: Si; No<br>art.21, c. 2 DPR 445/2000 benefici economici<br>Codice Fiscale Codice Fiscale delegato Stringa<br><!-- End of picture text -->

|**Nome**|Nome delegato|Stringa|Recuperati da arca|
|---|---|---|---|
|**Cognome**|Cognome delegato|Stringa|Recuperati da arca|
|**cittadinanza**|Nazionalità|Stringa|Recuperati da arca|
|**Data di nascita**|Data di nascita|Formato gg/mm/aaaa|Recuperati da arca|
||**SEZIONE FIN**|**ALE E CONSENSI**||
|**Numero di protocollo**|Numero identificativo di protocollo<br>della domanda|Stringa||
|**Consenso Trasferimento**<br>**PUA**|Consenso trasferimento domanda al<br>PUA competente (Art. 27 Dlgs<br>29/2024)|Valori ammessi: Si; No||
|**Consenso Condivisione INPS**|Consenso condivisione informazioni e<br>verifiche INPS ex art. 27 D.Lgs 29/2024<br>(Database integrato)|Valori ammessi: Si; No||
|**Consenso Privacy**|Trattamento dati in base<br>all'informativa ex art. 13 Regolamento<br>(UE) 2016/679|Valori ammessi: Si; No||
|**Dichiarazione**|Dichiarazione visione dell’informativa<br>sul trattamento dei dati personali (art.<br>13 D.Lgs. 196/2003)|Valori ammessi: Si; No||



### **7.3 Allegato C – Minimum Data Set della valutazione multidimensionale** 

Le informazioni riportate nella seguente tabella fanno riferimento ai dati dell’allegato 3.1 del Regolamento art. 27 c. 7. 

|**CAMPO**|**DESCRIZIONE**|**VALORE CODIFICATO**|**NOTE**|
|---|---|---|---|
||**SOCIO-ANA**|**GRAFICA**||
|**Età**|Età||Valori ammessi:<br>65-70<br>70-79<br>>80 anni|
|**Titolo di studio**|Titolo di studio|||
|**Pensione/ Professione**|Pensione / Professione|||
|**Invalidità civile**|Invalidità civile|||
|**Indennità di accompagnamento**|Indennità di<br>accompagnamento|||
|**Composizione nucleo familiare**|Composizione nucleo familiare|||
|**Rete sociale e supporto informale**|Rete sociale e supporto<br>informale|||
|**Solitudine/ isolamento**|Solitudine / isolamento|||
|**Disponibilità di caregiver**|Disponibilità di caregiver|||
|**MMG (o altro medico di riferimento)**|MMG (o altro medico di<br>|||
|<br>|riferimento)<br>**ABITA**<br>|**TIVA**||
|**Idoneità abitazione**<br>**t**|Idoneità abitazione<br>t|||
|**Barriere architettoniche**|Barriere architettoniche||fii|
|**Zona disagiata**|Zona disagiata||servizipubblici inefficienti|
|**Autonomia o supporto economico per**<br>**l'assistenza**|**ECONO**<br>Autonomia o supporto<br>economico per l'assistenza<br>**FUNZIO**|**MICA**<br>**NALE**|fii<br>ISEE <6000€|





<!-- Start of picture text -->
Indice di Barthel Indice di Barthel Valori scala ADL<br>Scala di Lawton-Brody Scala di Lawton-Brody Valori scala IADL<br>STATO COGNITIVO E COMPORTAMENTALE<br>Presenza di demenza, deficit cognitivi,<br>disorientamento<br>Stato cognitivo  Stato cognitivo<br>Comportamenti problematici (agitazione,<br>aggressività, vagabondaggio)<br>Linguaggio  Linguaggio [Comunicazione verbale e comprensione]<br>VALUTAZIONE SANITARIA<br>Diagnosi prevalente Diagnosi prevalente SI Codifica ICD10 o ICPC-3<br><!-- End of picture text -->

|**Malattie croniche**|Malattie croniche|
|---|---|
|**ti**<br>**Dolore, piaghe da decubito, infezioni ricorrenti**|ti<br>Dolore, piaghe da decubito,<br>infezioni ricorrenti|
|**Trattamenti specialistici previsti**|Trattamenti specialistici<br>previsti<br>i|
|**Farmaci assunt**|Farmaci assunti|
||**SENSORIALE**|
|**Udito**|Udito|
|**Vista**|Vista|
|**Dolore**|Dolore|
||**MOBILITÀ E RISCHI**|
|**Capacità di deambulare**|Capacità di deambulare|
|**Rischio di cadute**|Rischio di cadute|
|**Necessità di ausili**|Necessità di ausili|
||**BISOGNI ASSISTENZIALI**|
||Tipoloia e intensità|
|**Tipologia e intensità dell'assistenza richiesta**<br>**(24h, diurna, occasionale)**|g<br>dell'assistenza richiesta (24h,<br>diurna,occasionale)|
|**Supporto necessario per l’igiene personale,**<br>**l’alimentazione, la**<br>**sorveglianza**|Supporto necessario per<br>l’igiene personale,<br>l’alimentazione, la<br>sorveglianza|
|**Vittima di maltrattamento/abuso o violenza**<br>**assistita**|Vittima di<br>maltrattamento/abuso o<br>violenza assistita|
||**ASPETTI PSICOLOGICI E COMPORTAMENTALI**|
|**Ansia opreoccupazione**|Ansia opreoccupazione|
|**Depressione**|Depressione|
|**Insonnia o disturbi del sonno (comprende**<br>**irrequietezza notturna)**|Insonnia o disturbi del sonno<br>(comprende irrequietezza<br>notturna)|
|**Comportamenti aggressivi o antisociali**<br>**fi**|Comportamenti aggressivi o<br>antisociali<br>fi|
|**Difficoltà relazionali**|Difficoltà relazionali|



|**Irrequietezza di giorno / tendenza a scappare e**<br>**perdersi**|Irrequietezza di giorno /<br>tendenza a scappare eperdersi|
|---|---|
|**i**|**SOCIEVOLEZZA**|
|**Relazioni amicali o familiari frequenti (esclusi**<br>**conviventi)**|Relazioni amicali o familiari<br>frequenti(esclusi conviventi)<br>ti|
|**Partecipazione ad attività ricreative o sociali**<br>**i**|Partecipazione ad attività<br>ricreative o sociali<br>i|
|**Uscite di casa nell'ultimo mese**|Uscite di casa nell'ultimo mese<br>t|
|**Letture (libri, giornali, TV, Internet)**|Letture (libri, giornali, TV,<br>Internet)|
||**CARICO ASSISTENZIALE DEI FAMILIARI**|
|**Sensazione di stress/solitudine**|Sensazione di stress/solitudine|
|**Educazione sanitaria su bisogni e assistenza**|Educazione sanitaria su bisogni<br>e assistenza|
|**Relazione conflittuale con i servizi territoriali**|Relazione conflittuale con i<br>servizi territoriali|
||**INDICI SINTETICI**<br>**(PUNTEGGI O GRADI DI NON-AUTONOMIA)**|
|**Attribuzione del punteggio di non autosufficienza**|Attribuzione del punteggio di<br>non autosufficienza|
|**Proposta di inserimento in struttura o attivazione**<br>**di servizi domiciliari**|**ESITO DELLA VALUTAZIONE**<br>Proposta di inserimento in<br>struttura o attivazione di<br>servizi domiciliari|



### **7.4 Allegato D – Minimum Data Set della valutazione multidimensionale allargata** 

Le informazioni riportate nella seguente tabella fanno riferimento ai dati dell’allegato 3.2 del Regolamento art. 27 c. 7, e rappresentano informazioni aggiuntive rispetto alla valutazione core. 



<!-- Start of picture text -->
CAMPO DESCRIZIONE VALORE CODIFICATO NOTE<br>Se in condizione di disabilità:<br> Percentualizzazione<br> Riconoscimento dell’indennità di<br>accompagnamento (indicando<br>Funzionamento specifiche ICD delle patologie<br>maggiormente ricorrenti)<br> Livello di sostegno / sostegno<br>intensivo e fascia: lieve, medio,<br>elevato o molto elevato<br>Valori ammessi:<br>100% di invalidità totale;<br>67–99% di invalidità medio-grave;<br>Invalidità civile Invalidità civile<br>34–66% di invalidità lieve;<br>Soggetti non riconosciuti invalidi<br>(<34%)<br>Valori ammessi:<br>cieco assoluto;<br>Cecità civile Cecità civile cieco parziale;<br>Privo delle minorazioni visive<br>previste dalla norma<br>Valori ammessi:<br>Sordità civile Sordità civile Sordo;<br>Non sordo<br>Persone anziane non autosufficienti che<br>Prestazione Universale rispondono ai seguenti requisiti:<br>a) Almeno 80 anni<br><!-- End of picture text -->

||b) ISEE sociosanitario valido non<br>superiore a 6.000 euro<br>c) Titolari dell'indennità di<br>accompagnamento o, comunque, in<br>possesso dei requisitiper beneficiarne<br>i|||
|---|---|---|---|
|**Documentazione**<br>**7.5 Allegato E – Dati ver**|Documentazione pertinente<br>all’accertamento della condizione di<br>disabilità<br>**bale VMU**||In caso di sussistenza delle<br>condizioni ex Art. 6, comma 8, della<br>bozza di Regolamento|
|**CAMPO**<br>**iii**|**DESCRIZIONE**<br>**DETTAGL**<br>iii|**VALORE CODIFICATO**<br>**I VM**|**NOTE**|
|**Numero identificativo**|Identificativo richiesta<br>ft|Stringa|ti|
|**Data valutazione**|Data in cui viene effettuata la valutazione|Formatogg/mm/aa|visita/atti|
|**Ora visita**|Ora in cui viene effettuata la valutazione|Formato hh:mm||
|**Data definizione**|Data di definizione del verbale|Formatogg/mm/aa<br>i||
|**Tipo valutazione**|Modalità di svolgimento della valutazione|Valori ammessi: codici previsti dalla<br>relativa tipologica, consultabile<br>tramite il servizio trasversale di<br>consultazione delle tipologiche<br>i|visita/atti|
|**Tipo accertamento**|Tipologia della seduta valutativa<br>**ANAGRA**<br>t|Valori ammessi: codici previsti dalla<br>relativa tipologica, consultabile<br>tramite il servizio trasversale di<br>consultazione delle tipologiche<br>**FICA**|Primo accertamento / Aggravamento/<br>Revisione<br>i|
|**C.F.**|Codice Fiscale del cittadino|Stringa|Altri campi recuperati su arca|
||**DATI IDEN**|**TITA’**||



|**Tipo documento**|Tipo documento|Valori ammessi: codici previsti dalla<br>relativa tipologica, consultabile<br>tramite il servizio trasversale di<br>consultazione delle tipologiche||
|---|---|---|---|
|**Numero documento**|Numero documento|Stringa||
|**Data rilascio**|Data rilascio|Formatogg/mm/aa<br>i||
|**Rilasciato da**|Rilasciato da|Valori ammessi: codici previsti dalla<br>relativa tipologica, consultabile<br>tramite il servizio trasversale di<br>consultazione delle tipologiche||
|**Data scadenza**|Data scadenza|Formatogg/mm/aa||
|**Luogo rilascio**|Luogo rilascio|Stringa||
||**VALUTAZIO**<br>i  i|**NE CLINICA**||
|**Documentazione acquisita**|Elenco dei documenti sanitari raccolti|Stringa||
|**Anamnesi/catamnesi**|Storia clinica del cittadino|Stringa||
|**Esame obiettivo**|t<br>Esito dell'esame obiettivo|Stringa||
|**Diagnosi**|Diagnosi clinica|Stringa||
||**ELENCO D**|**IAGNOSI**<br>i||
|**Codice ICD9**<br>**fi**|Codice diagnosi<br>**GIUDIZIO CO**<br>fi|Valori ammessi: codici previsti dalla<br>relativa tipologica, consultabile<br>tramite il servizio trasversale di<br>consultazione delle tipologiche<br>**NCLUSIVO**|Riferimento Art 2 c1 lettera c) del|
|**Non autosufficienza**|Stato autosufficienza|Valori ammessi: si, no|.  ., t<br>D.Lgs 29/2024|
|||Valori ammessi: codici previsti dalla<br>i i||
|**Codice Sostegno disabilità**|Necessità di sostegno|relativa tipologica, consultabile<br>tramite il servizio trasversale di<br>consultazione delle tipologiche|Riferimento alla legge L104/92 art. 3, c.<br>1 e art. 3, c. 3|
|**Data decorrenza disabilità**|Data decorrenza disabilità|Formatogg/mm/aa||
|**Codice Indicatore disabilità**|Codice identificativo dell’indicatore di<br>disabilità|Valori ammessi: codici previsti dalla<br>relativa tipologica, consultabile<br>tramite il servizio trasversale di<br>consultazione delle tipologiche||
||**ELENCO GIUDIZI(SANITARIO, LIQ**|**UIDAZIONE, SORDITA’, CECITA’)**||



|**Codice tipologia giudizio**|Codice tipologia giudizio|Valori ammessi: codici previsti dalla<br>relativa tipologica, consultabile<br>tramite il servizio trasversale di<br>consultazione delle tipologiche<br>i|
|---|---|---|
|**Codice grado**|Codice grado|Valori ammessi: codici previsti dalla<br>relativa tipologica, consultabile<br>tramite il servizio trasversale di<br>consultazione delle tipologiche|
|**Data decorrenza**|Data inizio validità|Formatogg/mm/aa|
|**Percentuale**|Percentuale di invalidità riconosciuta|Numerico|
|**Diagnosi**|Diagnosi|Stringa|
||**IPOVISU**|**S**|
|**Codice ipovisus**|Codice ipovisus<br>**i**|Valori ammessi: codici previsti dalla<br>relativa tipologica, consultabile<br>tramite il servizio trasversale di<br>consultazione delle tipologiche<br>|
||**ELENCO Requisiti Art**|**. 4 D.L. 5/2012**<br>i|
|**Codice art4**|Codice requisito|Valori ammessi: codici previsti dalla<br>relativa tipologica, consultabile<br>tramite il servizio trasversale di<br>consultazione delle tipologiche|
|**t**|**REVISIO**<br>t|i<br>**NE**|
|**Soggetto a revisione**|Indica se il verbale è soggetto a revisione|Valori ammessi: si,no|
|**Data di revisione**|Data di revisione|Formato mm/aa|
|**Segnalazione rivalsa terzi ai sensi**<br>**art.41 L.183/2010**|Presenza di illeciti causati da terzi (Art.41<br>L.183/2010)|Valori ammessi: si, no|
|||Valori ammessi: recuperati tramite|
|**codice ipotesi**|codice ipotesi|il servizio trasversale di<br>consultazione delle tipologiche|
|**Note Rivalsa**|Note rivalsa|Stringa|
|**Notegiudizio complessivo**|Notegiudizio complessivo|Stringa|
||**ELENCO COMPONENTI**<br>i|**COMMISSIONE**|
|**Codice fiscale**|Codice fiscale del componente della<br>commissione|Stringa<br>i|
|**Tipo componente**|Tipo componente|Valori recuperati tramite il servizio|





<!-- Start of picture text -->
trasversale di consultazione delle<br>tipologiche<br>7.6 Allegato F – Schema PAI<br>Contenuti del PAI: Progetto assistenziale  Contenuti del PAI: Progetto assistenziale<br>NOTE MLPS per componente<br>individuale – contenuti condivisi da Agenas  individuale – contenuti condivisi da MLPS<br>sociale/approfondimento<br>[02/07/26] [23/06/2026]<br>Età:<br> 65-70<br> 70-79<br> >80 anni<br>Titolo di studio<br>Pensione / Professione<br>Dati anagrafici del soggetto assistito Invalidità civile<br>Indennità di accompagnamento<br>Composizione nucleo familiare<br>Rete sociale e supporto informale<br>Solitudine / isolamento<br>Disponibilità di caregiver<br>MMG (o altro medico di riferimento)<br>Esplicitare riferimento a campi dei tracciati:<br>SCHEMA REG art. 27 co. 7 ALL. 3.1. - Minimum<br>data set per la VMD-core, basato sulle dimensioni<br>OECD<br>Bisogni della persona (da precedente valutazione  Esiti della valutazione multidimensionale  SCHEMA REG art. 27 co. 7 ALL. 3.2. - Minimum<br>multidimensionale) integrata<br>data set per la VMD-allargata (informazioni<br>aggiuntive ulteriori rispetto alla valutazione core)<br>[Necessario integrazione con campo ulteriore<br>sintesi bisogno?]  Allineamento con Ministero<br><!-- End of picture text -->



<!-- Start of picture text -->
Salute e AGENAS<br>Obiettivi clinico-assistenziali di presa in carico  [Campo aperto?] Allineamento con Ministero<br>Obiettivi di cura<br>(sanitari, socio-sanitari e sociali) (elenco aperto) Salute e AGENAS<br>1. Periodico<br>Carattere Prestazione  2. Occasionale<br>Programmata (unica<br>soluzione)<br>Data Programmata  Data prevista di inizio<br>Inizio Prestazione in  prestazione<br>caso di prestazione  (obbligatoria in caso di<br>Periodica prestazione Periodica)<br>Data Programmata  Data prevista di fine<br>Fine Prestazione in  prestazione (solo in<br>Interventi e attività previsti, modulati secondo<br>caso di prestazione  caso di prestazione<br>intensità (h24, diurna, occasionale), frequenza<br>Periodica Periodica)<br>settimanale e durata<br>Data prevista di<br>Data Programmata<br>Interventi e attività modulati secondo la durata e  erogazione della<br>Erogazione<br>l’intensità del bisogno e le figure professionali  Prestazione in caso di  prestazione<br>coinvolte (obbligatoria in caso di<br>prestazione<br>prestazione<br>Occasionale<br>Occasionale)<br>Indicare il numero di<br>Ore Servizio Mensile  ore di servizio<br>Programmate programmate<br>mensilmente<br>Setting e servizi da attivare<br>sanitari e sociosanitari: domiciliare, domiciliare<br>palliativo, residenziale, semiresidenziale,<br>farmaceutica, specialistica, altri<br>Inserire riferimento a nomenclatore SIUSS.<br>sociali: domiciliare, residenziale, sostegno<br>Tabella 1 Decreto 206/2014 e successive<br>economico, altri.<br>modificazioni.<br>Codifica figure professionali operatori sociali.<br>Responsabilità, compiti e modalità di svolgimento<br>Figure professionali coinvolte nella presa in  Riferimento “Allegato 7 – Banca dati delle<br>dell’attività degli operatori sanitari e sociali che<br>carico, per ciascuna figura: professioni sociali e degli operatori sociali” -<br>intervengono nella presa in carico della persona<br>Decreto ministeriale 103 del 22 agosto 2019<br><!-- End of picture text -->



<!-- Start of picture text -->
SIOSS e successive modificazioni<br>Necessità di allineamento campi e tracciato con<br>Responsabilità (rispetto agli obiettivi)<br>Ministero Salute<br>Necessità di allineamento campi e tracciato con<br>Tipo di attività, frequenza e modalità<br>Ministero Salute<br>[Nome casemanager]<br>[Cognome casemanager]<br>[Codice fiscale casemanager]<br>Case manager [Ente di appartenenza casemanager]<br>Allineamento con Ministero Salute e AGENAS<br>Necessità di allineamento campi e tracciato con<br>Eventuale Budget di salute Budget di cura e assistenza<br>Ministero Salute e AGENAS<br>[Campo aperto?] Allineamento con Ministero<br>Risorse personali<br>Apporto della famiglia e degli altri soggetti che  Salute e AGENAS<br>collaborano alla realizzazione del PAI, ivi inclusi  [Campo aperto?] Allineamento con Ministero<br>Risorse del nucleo familiare e caregiver<br>gli enti del terzo settore e i soggetti che  Salute e AGENAS<br>compongono la rete dei servizi di cui all’articolo  [Campo aperto?] Allineamento con Ministero<br>Risorse del terzo settore e della comunità<br>25 del decreto legislativo n. 29 del 2024. Salute e AGENAS<br>[Campo aperto?] Allineamento con Ministero<br>Collegamenti tra le istituzioni/enti coinvolti<br>Salute e AGENAS<br>Piano di riabilitazione individuale (PRI)  - secondo<br>le indicazioni dell’articolo 34 del decreto del<br>Presidente del Consiglio dei ministri 12 gennaio<br>2017, delle Linee di indirizzo per l’individuazione<br>di percorsi appropriati nella rete di riabilitazione,  Secondo le indicazioni dell’articolo 34 del decreto<br>adottate con accordo sancito in sede di  del Presidente del Consiglio dei ministri 12<br>Conferenza permanente per i rapporti tra lo Stato,  gennaio 2017<br>le regioni e le province autonome di Trento e di<br>Bolzano nella seduta del 4 agosto 2021<br>(124/CSR), e del decreto del Ministro della salute<br>n. 77 del 2022.<br>[Data Inizio]<br>Durata del PAI Tempistiche degli interventi e delle verifiche di<br>[Data Fine]<br><!-- End of picture text -->

|Rivalutazione p|rogrammata||[Data rivalutazione programmata]|
|---|---|---|---|
|Rivalutazione in via di u<br>indiffer|rgenza per esigenze<br>ibili||[Data rivalutazione di urgenza]|
|Indicatori per la verific<br>dell’assistenza fornita|a periodica e finale<br>e degli esiti ottenuti|attuazione.|Necessità di allineamento con la bozza di<br>Decreto articolo 23 del Dlgs. 29/2024 – Sistema<br>di monitoraggio dei livelli essenziali delle<br>prestazioni.|
|Conclusione: m|otivo e data||Motivo: [Campo aperto o identificare valori di<br>campo?] Allineamento con Ministero Salute e<br>AGENAS<br>Data:[Data conclusione PAI]|
|Firme degli operatori sa<br>autori del do|nitari e sociosanitari<br>cumento||[Campo firma operatori]|
|Firme del paziente o del fa<br>rappresen|miliare nominato quale<br>tante||[Campo firme del paziente o del familiare<br>nominato quale rappresentante]|
|**7.7 Allegato G – Dat**|**i elenco istanze**|||
|**Campo**|**Descrizione**|**Valore Codificato**|**Note**|
|**Numero richiesta**|Identificativo richiesta|Stringa||
|**Codice fiscale**|Codice fiscale richiedente|Stringa||
|**Data acquisizione**|Data acquisizione domanda|Formato gg/mm/aaaa||
|**Stato domanda**|Stato corrente della domanda|Valori recuperati tramite il servizio<br>trasversale di consultazione delle<br>tipologiche||
|**Comune**|Comunedel richiedente|Stringa||
|**Data nascita**|Data nascita del richiedente|Formato gg/mm/aaaa||
|**Sordità**|Accertamento sordità|Valori: Si; No||
|**Cecità**|Accertamento cecità|Valori: Si; No||



### **7.8 Allegato H – Dati di consultazione della domanda** 

L'Allegato H è un sottoinsieme delle informazioni della domanda (Allegato B) rese disponibili ai soggetti autorizzati nella fase istruttoria. 

|**Campo**|**Descrizione**|**Valore Codificato**|**Note**|
|---|---|---|---|
||**DATI D**|**EL RICHIEDENTE**||
|**Codice Fiscale**|Codice fiscale del richiedente|Stringa alfanumerica|Recuperati da arca|
|**Nome**|Nome del richiedente|Stringa|Recuperati da arca|
|**Cognome**|Cognome del richiedente|Stringa|Recuperati da arca|
|**Sesso**|Sesso anagrafico del richiedente|Stringa<br>(Valori ammessi: Maschile;<br>Femminile; Non specificato)|Recuperati da arca|
|**Data di Nascita**|Data di nascita del richiedente|Formato gg/mm/aaaa|Recuperati da arca|
|**Comune di nascita**|Comune di nascita del richiedente|Stringa<br>(Codice ISTAT del Comune)|Recuperati da arca|
|**Provincia di nascita**|Provincia di nascita del richiedente|Stringa|Recuperati da arca|
|**Stato di nascita**|Stato di nascita del richiedente|Stringa|Recuperati da arca|
|**Indirizzo di Residenza**|Indirizzo di residenza del richiedente|Stringa<br>(Concatenazione di Via/Piazza con il<br>civico della residenza)|Recuperati da arca|
|**CAP**|CAP di residenza del richiedente|Stringa|Recuperati da arca|
|**Comune**|Comune di residenza del richiedente|Stringa|Recuperati da arca|
|**Provincia**|Provincia di residenza del richiedente|Stringa<br>(Codice ISTAT del Comune)|Recuperati da arca|
|**Tipo documento identità**|Tipo documento identità del|Stringa|i dati del documento di identità del|



||richiedente|(Valori ammessi: Carta d'Identità;<br>Passaporto; Patente)|richiedente vengono richiesti e quindi<br>registrati dalla Domanda solo nel caso<br>di utente Patronato|
|---|---|---|---|
|**Numero Documento di**<br>**Identità**|Numero del documento|Stringa|Nessun controllo bloccante|
|**Rilasciato da**|Ente emittente|Stringa|Nessun controllo bloccante|
|**Data di Rilascio**|Data rilascio documento|Stringa|Nessun controllo bloccante|
|**Data di scadenza**|Data scadenza documento del<br>richiedente|Formato gg/mm/aaaa||
|**Stato civile**|Stato civile del richiedente|Stringa<br>(Valori ammessi: Celibe/Nubile;<br>Vedovo/a;<br>Divorziato/a;<br>Coniugato/a;<br>Separato/a;<br>Unito/a civilmente;<br>Sciolto/a da unione civile;<br>Vedovo/a da unione civile)|Recuperati da arca|
|**Cittadinanza**|Cittadinanza del richiedente|Stringa<br>(Valori ammessi: Italiano;<br>S. Marino;<br>U.E. (con data iscrizione anagrafe e<br>comune);<br>Extracomunitario (con dati<br>permesso);<br>apolide;<br>rifugiato;<br>prot. Sussidiaria)|Recuperati da arca|



|**Dati Permesso di Soggiorno**|Questura di rilascio, validità dal/al,<br>data scadenza|Formato gg/mm/aaaa||
|---|---|---|---|
|**Dichiarazione Rinnovo**<br>**Permesso**|Dichiarazione Rinnovo Permesso di<br>soggiorno|Valori ammessi: Sì / No|Flag obbligatorio "Dichiaro di aver<br>richiesto rinnovo" se data scadenza<br>superata|
|**Allegato Permesso**|Allegato|File|Allegare permesso di soggiorno o<br>ricevuta di pagamento del rinnovo|
||**CONTA**|**TTI DI SCOPO**||
|**Ulteriore**<br>**Cellulare**|Numero di cellulare per comunicazioni|Stringa||
|**Ulteriore Mail**|Indirizzo e-mail per comunicazioni|Stringa||
||**DATI DEL RAPP**|**RESENTANTE LEGALE**||
|**Rappresentante legale**|Rappresentante legale|Stringa<br>(Valori ammessi: Tutore;<br>Curatore;<br>Amministratore di sostegno)||
|**Nome e Cognome**|Nominativo del rappresentante|Stringa|Recuperati da arca|



|**Codice Fiscale**|CF del rappresentante|Stringa alfanumerica||
|---|---|---|---|
|**Data di Nascita**|Data di Nascita del rappresentante|Formato gg/mm/aaaa|Recuperati da arca|
|**Comune di nascita**|Comune di nascita del rappresentante|Stringa<br>(Codice ISTAT)|Recuperati da arca|
|**Provincia di nascita**|Sigla provincia di nascita del<br>rappresentante|Stringa|Recuperati da arca|
|**Stato di nascita**|Stato di nascita del rappresentante|Stringa|Recuperati da arca|
|**Provincia di residenza**|Provincia di residenza del<br>rappresentante|Stringa|Recuperati da arca|
|**Comune di residenza**|Comune di residenza del<br>rappresentante|Stringa<br>(Codice ISTAT del Comune)|Recuperati da arca|



|**Indirizzo di Residenza**|Indirizzo di residenza del<br>rappresentante|Stringa<br>(concatenazione Via/Piazza e Numero<br>Civico)|Recuperati da arca|
|---|---|---|---|
|**CAP di residenza**|Codice Avviamento Postale|Stringa|Recuperati da arca|
|**Tribunale**|**DECRE**<br>Sede del Tribunale e Sezione|**TO DI NOMINA**<br>Stringa|I dati del decreto di nomina sono<br>richiesti solo in caso di accesso da<br>Patronato|
|**Numero**|Numero del decreto|Stringa|I dati del decreto di nomina sono<br>richiesti solo in caso di accesso da<br>Patronato|
|**Data**|Data del decreto|Formato gg/mm/aaaa|I dati del decreto di nomina sono<br>richiesti solo in caso di accesso da<br>Patronato|
|**Validità dal**|Periodo iniziale di validità della<br>nomina|Formato gg/mm/aaaa|I dati del decreto di nomina sono<br>richiesti solo in caso di accesso da<br>Patronato|
|**Validità al**|Periodo finale di validità della nomina|Formato gg/mm/aaaa|I dati del decreto di nomina sono<br>richiesti solo in caso di accesso da<br>Patronato|



|**Nome medico**|**DATI DELLA PRESC**<br>Nominativo del medico prescrittore|**RIZIONE PER LA VMU**<br>Stringa|
|---|---|---|
|**Cognome medico**|Nominativo del medico prescrittore|Stringa|
|**n. prescrizione**|Codice/Numero identificativo<br>prescrizione|Stringa|
|**data prescrizione**|Data emissione|Formato gg/mm/aaaa|
||**DICHIARAZIONI (COM**<br>Senalazione resenza di|**PROMISSIONI E STATO)**|
|**Cecità**|g p<br>compromissione|Valori ammessi: Si; No|
|**Sordità**|Segnalazione presenza di<br>compromissione|Valori ammessi: Si; No|
|**Sordocecità**|Segnalazione presenza di<br>compromissione|Valori ammessi: Si; No|
|**Assenza altre domande**|Dichiarazione ex art. 56, c. 2, L.<br>69/2009 (pendenza esame)|Valori ammessi: Sì / No|
|**Presenza di invalidità civile**|Dichiarazione di essere già invalido<br>civile|Valori ammessi: Sì / No|



|**Causa**|Causa invalidità|Valori ammessi: Lavoro;<br>Guerra;<br>servizio|
|---|---|---|
|**Legge 80/2006**|Affetto da malattia neoplastica in atto|Valori ammessi: Sì / No|
|**Intrasportabilità**|Sussistenza controindicazioni mediche<br>per spostamento|Valori ammessi: Sì / No|
|**Legge 114/2014**|Affetto da patologia in situazione di<br>gravità (D.M. 2 agosto 2007)|Valori ammessi: Sì / No|
|**Illecito di terzi**|Infermità dipendente da fatto illecito<br>di terzi (Art. 41 L.183/2010). Rimanda<br>a modello AS1|Valori ammessi: Sì / No|
||**SEZIONE FIN**|**ALE E CONSENSI**|
|**Numero di protocollo**|Numero identificativo di protocollo<br>della domanda|Stringa|
|**Consenso Trasferimento**<br>**PUA**|Consenso trasferimento domanda al<br>PUA competente (Art. 27 Dlgs<br>29/2024)|Valori ammessi: Si; No|
||Consenso condivisione informazioni e|Valori ammessi: Si; No|
|**Consenso Condivisione INPS**|verifiche INPS ex art. 27 D.Lgs 29/2024<br>(Database integrato)||
|**Consenso Privacy**|Trattamento dati in base<br>all'informativa ex art. 13 Regolamento<br>(UE) 2016/679|Valori ammessi: Si; No|
|**Dichiarazione**|Dichiarazione visione dell’informativa<br>sul trattamento dei dati personali (art.<br>13 D.Lgs. 196/2003)|Valori ammessi: Si; No|



### **7.9 Allegato I – Documentazione** 

|**Campo**|**Descrizione**|**Valore Codificato**|**Note**|
|---|---|---|---|
|**Numero richiesta**|Identificativo richiesta|Stringa||
|**Identificativo documento**|Identificativo univoco del file|Stringa||
|**iii**<br>**Categoria funzionale**|Contesto di utilizzo del documento|Valori ammessi: ’Documentazione da<br>allegare /’Documentazione firmata’||
|**Tipologia documento**|Tipologia del documento trasmesso|Valori recuperati tramite il servizio<br>trasversale di consultazione delle<br>tipologiche|Filtrata in funzione della categoria<br>funzionale|
|**Nome file**|Nome file Nome del file comprensivo<br>di estensione|Stringa||
|**Formato/MIME type**|Formato documento|Stringa|Valore ammesso: application/pdf|
|**Hash del documento**|Hash del file|Stringa|Utilizzato per verificarne l’integrità|
|**Note**|Note del documento|Stringa||
|**Contenuto**|Contenuto file|Binary/Base64|Documento pdf|



### **7.9 Allegato L – Archiviazione** 

|**Campo**|**Descrizione**|**Valore Codificato**|**Note**|
|---|---|---|---|
|**Numero richiesta**|Identificativo richiesta|Stringa||
|**Causale chiusura**|Codice che identifica il motivo della<br>chiusura senza emissione del verbale|Stringa|Valore della descrizione recuperato<br>tramite il servizio trasversale di<br>consultazione delle tipologiche|



|**Data chiusura**|Data chiusura|Formato gg/mm/aaaa|
|---|---|---|
|**Motivazione archiviazione**|Motivazione della chiusura|Stringa|





