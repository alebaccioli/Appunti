# Identificazione del target e indicizzazione

**Docente**: Alberto Cocchi ([email](mailto:a.cocchi@gammadv.it))  
**Appunti**: Alessandro Baccioli ([GitHub](https://alebaccioli.github.io/appunti/))  
**Licenza**: [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/deed.it)

**Indice**:

- [1. Motori di ricerca](#1-motori-di-ricerca)
  - [1.1. Motori meno usati](#11-motori-meno-usati)
  - [1.2. Google](#12-google)
  - [1.3. Linee guida](#13-linee-guida)
  - [1.4. Fattori di ranking](#14-fattori-di-ranking)
- [2. SEM](#2-sem)
  - [2.1. SEO](#21-seo)
    - [2.1.1. SEO on-page](#211-seo-on-page)
      - [2.1.1.1. Tag title](#2111-tag-title)
      - [2.1.1.2. Meta description](#2112-meta-description)
      - [2.1.1.3. URL](#2113-url)
      - [2.1.1.4. Tag alt](#2114-tag-alt)
      - [2.1.1.5. Headline](#2115-headline)
    - [2.1.2. SEO off-page](#212-seo-off-page)
    - [2.1.3. Link juice](#213-link-juice)
  - [2.2. SEA](#22-sea)
- [3. Strumenti di monitoraggio](#3-strumenti-di-monitoraggio)
  - [3.1. Google Analytics](#31-google-analytics)
  - [3.2. Google Search Console](#32-google-search-console)
  - [3.3. Google Trends](#33-google-trends)
  - [3.4. Google PageSpeed Insights](#34-google-pagespeed-insights)
  - [3.5. SEOZoom](#35-seozoom)
- [4. Google Ads](#4-google-ads)
  - [4.1. Rete](#41-rete)
  - [4.2. Asta](#42-asta)
  - [4.3. Punteggio di qualità](#43-punteggio-di-qualità)
  - [4.4. Campagne pubblicitarie](#44-campagne-pubblicitarie)
    - [4.4.1. Obiettivo](#441-obiettivo)
    - [4.4.2. Tipo di campagna](#442-tipo-di-campagna)
    - [4.4.3. Campagna](#443-campagna)
    - [4.4.4. Gruppo di annunci](#444-gruppo-di-annunci)
    - [4.4.5. Annuncio](#445-annuncio)
  - [4.5. Monitoraggio](#45-monitoraggio)
- [5. PrestaShop](#5-prestashop)
  - [5.1. Catalogo](#51-catalogo)
  - [5.2. Moduli](#52-moduli)
  - [5.3. Parametri Negozio](#53-parametri-negozio)
- [6. WordPress](#6-wordpress)
  - [6.1. Yoast SEO](#61-yoast-seo)

## 1. Motori di ricerca

Il **motore di ricerca** è un sistema automatico che restituisce una lista di risultati in base a ciò che l'utente ha cercato.

La **SERP** (Search Engine Results Page) è la pagina che contiene i risultati della ricerca fatta dall'utente su un motore di ricerca.

### 1.1. Motori meno usati

***Bing*** è il motore di ricerca di *Microsoft*. In Italia ha circa il 9% della fetta di mercato, piccola ma comunque va presa in considerazione. Anche lui ha la sua parte di advertising, chiamata *Bing Ads*. Alcune campagne fatte su *Google* possono essere integrate su *Bing*.

***Yahoo!*** e ***Virgilio*** erano molto in voga anni fa, ma adesso sono meno utilizzati. Utilizzano lo stesso motore e gli stessi dati di *Bing*, quindi un sito indicizzato su *Bing* comparirà anche su questi motori.

***Yandex*** e ***Baidu*** sono motori di ricerca utilizzati più all'estero, il primo in Russia e il secondo in Cina. Seguono logiche e alfabeti diversi.

***DuckDuckGo*** e ***Qwant*** puntano maggiormente su aspetti come user experience, privacy e integrazione con i social.

È difficile ottimizzare un sito per tutti i motori, ma è bene tenere in considerazione almeno i principali.

### 1.2. Google

***Google*** è indubbiamente il motore di ricerca più usato. È gestito da un'enorme azienda che punta al profitto. L'obiettivo principale è garantire agli utenti un'esperienza di ricerca eccellente con risultati fedeli alle aspettative.

Il 90% dei ricavi arriva dalle campagne PPC (Pay Per Click) di ***Google Ads*** (precedentemente chiamato *Google AdWords*).

Gli annunci di questo tipo vengono mostrati in alto nella pagina dei risultati (generalmente massimo 3) e hanno la scritta *Annuncio* accanto all'indirizzo della pagina.

Proseguendo nella SERP arriviamo ai risultati organici (non a pagamento). Ogni tanto è possibile trovare altri annunci a fine pagina.

*Google* negli ultimi anni ha assunto dei **quality rater**, cioè delle persone che verificano che i risultati di ricerca siano di qualità.

Inoltre sta focalizzando l'attenzione su certe tematiche riassumibili con **YMYL** (Your Money or Your Life), che riguardano aspetti fondamentali della vita come felicità, salute, finanze, sicurezza.

### 1.3. Linee guida

L'algoritmo che definisce il posizionamento è nascosto, ma *Google* offre delle linee guida chiamate [*Istruzioni per i webmaster*](https://developers.google.com/search/docs/advanced/guidelines/webmaster-guidelines?hl=it).

Quando si progetta un sito, è bene pensare alla **gerarchia** delle sezioni e dei link testuali. Più questa gerarchia è piatta meglio è, sono da evitare ramificazioni troppo lunghe.

I link presenti nella **barra di navigazione principale** sono importanti non solo per l'utente, ma anche per *Google* che attribuirà ad essi un peso maggiore rispetto agli altri link presenti nella pagina.

La **mappa del sito** è una pagina che contiene i link principali del sito. Può essere utile all'utente in caso di smarrimento, ma è sicuramente utile al motore di ricerca perché in questo modo capisce la struttura del sito.

Bisogna pensare alle **parole chiave** che l'utente può ricercare sul nostro sito e assicurarsi che siano inserite bene nei contenuti delle pagine.

Utilizzare l'attributo **`alt`** nelle immagini. *Google* non è in grado di estrarre il testo all'interno delle immagini, questo attributo gli permette di capirne la descrizione. Inoltre è utile per gli utenti che usano gli screen reader.

Gli elementi HTML **`title`** e **`description`** permettono di definire il titolo e la descrizione dei risultati nelle SERP.
Vanno ottimizzati dal punto di vista SEO e devono essere attinenti ai contenuti.

I **link non funzionanti** (*broken links*) vanno rimossi perché vengono penalizzati da *Google*.

L'**URL** corrisponde all'indirizzo Internet della pagina. Può essere:

- **statico**: è l'indirizzo di una pagina che ha contenuti fissi
  - es. `https://gammadv.it/come-migliorare-il-posizionamento-su-google/`
- **dinamico**: è l'indirizzo di una pagina i cui contenuti possono variare a seconda della richiesta fatta e delle informazioni presenti nel database
  - es. `https://www.amazon.it/B06XSGYM2W/ref=sr_1_4?ie=UTF8&qid=1509725153&sr=8-4&keywords=libri+narrativa`

Ai fini SEO è meglio che le pagine abbiano un URL statico piuttosto che dinamico, alcuni motori non eseguono la scansione degli URL dinamici. I CMS utilizzano di base URL dinamici, ma spesso è possibile configurarli in modo da convertirli in statici.

Da **evitare trucchi** per migliorare il posizionamento, es. riempire la pagina con parole chiave ripetute all'infinito. Se *Google* se ne accorge, le pagine possono essere rimosse dai risultati.

Oltre alle ottimizzazioni è importante cercare di rendere il proprio sito web **unico** e **coinvolgente**, in modo da potersi distinguere nel tempo.

Cose da *non* fare:

- generare contenuti automaticamente, cioè esportare contenuti di altri siti in maniera automatica
- partecipare a schemi di link, cioè siti che si mettono d'accordo per scambiarsi i link tra loro
- creare pagine senza o con pochi contenuti originali
- inserire testi o link nascosti
- appropriarsi indebitamente di contenuti
- caricare pagine con parole chiave irrilevanti
- creare pagine dal comportamento dannoso, es. virus o phishing
- utilizzare illecitamente il markup nel rich snippet

### 1.4. Fattori di ranking

Esistono alcuni fattori che possono incidere sul **ranking** della pagina, ossia sul suo posizionamento nei risultati di ricerca. Sono basati su una ricerca di *Backlinko*.

La lista comprende:

1. **backlink**: è un link presente su un sito esterno che rimanda al nostro sito, è probabilmente il fattore più importante e il numero e la qualità dei backlink fanno la differenza nel posizionamento
2. **link authority**: più il sito esterno linkante è attinente in termini di argomenti con quello linkato e maggiore sarà la qualità del ranking, es. un sito di sport che riceve un link da un altro sito di sport
3. **contenuti in-depth**: la pubblicazione di contenuti molto focalizzati che approfondiscono in dettaglio un singolo argomento aumenta il ranking
4. **contenuti di circa 2000 parole**: la maggior parte degli articoli nei migliori risultati hanno una lunghezza media di 1890 parole, numero che normalmente permette di raggiungere livelli qualitativi sufficienti per ottenere le posizioni migliori
5. **https**: le pagine posizionate meglio utilizzano *https*, cioè un protocollo con dei certificati di sicurezza che garantiscono la privacy dei dati scambiati, non è obbligatorio per siti generici ma può esserlo per certi e-commerce
6. **`schema.org`**: sono linee guida per strutturare i contenuti dei siti, non sembra essere un fattore importante e forse non lo è mai stato
7. **immagini**: le pagine con almeno un'immagine si posizionano meglio rispetto a quelle che non ne hanno, non serve però riempire la pagina di immagini perché dopo la prima le altre non apportano grandi benefici al ranking
8. **tag title**: emerge una scarsa relazione tra SEO del tag `title` e il ranking della pagina, si pensava ci fosse un forte collegamento ma oggi i motori si basano più sulla ricerca semantica dei contenuti
9. **velocità**: le pagine caricate su siti molto rapidi hanno ottenuto un ranking molto più elevato rispetto a pagine analoghe ma caricate su siti lenti, quindi la velocità è molto importante per il posizionamento
10. **anchor text**: creare dei link il cui nome descrive fedelmente il contenuto della pagina di destinazione rappresenta un forte fattore di ranking
11. **basso tasso di rimbalzo**: si è visto che i siti che hanno bassi tassi di rimbalzo, cioè quelli che trattengono meglio gli utenti, hanno alti valori di ranking, quindi più gli utenti interagiscono con un sito e meglio è considerato da *Google*

## 2. SEM

Per **SEM** (Search Engine Marketing) si intende l'insieme delle attività di marketing volte alla promozione di un sito web nei motori di ricerca.

Tra le principali attività abbiamo:

- **SEO** (Search Engine Optimization): è l'insieme delle ottimizzazioni che possiamo fare per migliorare il posizionamento del sito nei risultati organici (non a pagamento)
- **SEA** (Search Engine Advertising): sono campagne pubblicitarie a pagamento che consentono di promuovere maggiormente l'attività e di definire il target

Nella concezione comune si identifica il SEM con il SEA, mentre si vede il SEO come uno strumento separato. In realtà il SEM è un concetto di marketing più ampio e comprende le attività di SEO e SEA.

### 2.1. SEO

L'obiettivo del **SEO** è migliorare il posizionamento del sito web nei risultati di ricerca. Ci sono ottimizzazioni che possiamo fare direttamente nelle pagine del sito web e altre esternamente.

Il SEO è una strategia a medio-lungo termine, può richiedere tra i 6 e i 12 mesi per vederne i risultati.

Se vogliamo risultati subito possiamo optare per delle inserzioni a pagamento, ma i risultati di questo tipo non sono duraturi e quindi gli investimenti vanno costantemente ripetuti.

#### 2.1.1. SEO on-page

Per **SEO on-page** s'intende l'insieme delle ottimizzazioni che possiamo fare sulle pagine del nostro sito.

I metadati rappresentano le informazioni più importanti su cui possiamo lavorare e comprendono:

- tag `title`
- meta `description`
- URL
- tag `alt`
- headline

##### 2.1.1.1. Tag title

Il tag **`title`** è probabilmente l'elemento più importante che *Google* considera per l'indicizzazione e il ranking. Corrisponde al titolo del risultato di ricerca.

Un buon tag `title` deve:

- essere descrittivo della pagina
- contenere le parole chiave pertinenti alla pagina
- essere compatto, max 60 caratteri perché *Google* taglia il resto
- destare curiosità e interesse
- essere persuasivo

Oltre al numero dei caratteri, pare che *Google* consideri anche il numero dei pixel occupati. Es. due `title` da 38 caratteri, ma uno usa il maiuscolo e occupa più pixel.

##### 2.1.1.2. Meta description

La meta **`description`** di una pagina web è la descrizione libera ed esaustiva del contenuto della pagina. Viene mostrata sotto al titolo del risultato.

Una descrizione fatta bene invoglia l'utente ad entrare e di conseguenza aumenta il CTR (Click Through Rate).

Una buona meta `description` deve:

- essere esaustiva e accattivante
- dare un piccolo assaggio del contenuto della pagina
- catturare l'attenzione dell'utente fino a spingerlo al click
- max 140 caratteri, poi viene tagliata

##### 2.1.1.3. URL

L'**URL** (Uniform Resource Locator) indica l'indirizzo univoco di una pagina web. È composto dal dominio e dal cosiddetto *slug* (o *permalink* su *WordPress*).

L'URL viene mostrato sopra il titolo nei risultati di ricerca. Lo *slug* è la versione abbreviata dell'URL, è solitamente tutto minuscolo e contiene solo lettere, numeri e trattini.

[*Nic*](https://www.nic.it/) è l'autorità italiana che gestisce i domini `.it`. È possibile verificare se un dominio è già registrato e in tal caso vedere i contatti del proprietario, ma solo per i domini `.it`.

Per gli altri siti è possibile usare [*Whois*](https://www.whois.com/). Fornisce meno informazioni, i contatti del proprietario sono spesso nascosti per la privacy. Anche [*Aruba*](https://www.aruba.it/) permette di vedere i dettagli di un dominio.

Un buon URL deve:

- essere parlante, ovvero descrittivo della pagina
- contenere le keyword più importanti
- essere abbastanza compatto

##### 2.1.1.4. Tag alt

Il tag **`alt`** è l'insieme delle keyword che permettono di categorizzare le immagini di una pagina web. Aiuta i motori di ricerca a trovare le immagini e a organizzarle nei risultati di ricerca.

In *WordPress* si chiama *testo alternativo*.

##### 2.1.1.5. Headline

Mentre il `title` è il titolo dell'intera pagina, l'**headline** è un titolo dei contenuti di una pagina.

I contenuti possono avere più titoli, rappresentati in HTML dai tag da `h1` a `h6` e ordinati in base a un'importanza decrescente.

Una pagina ben strutturata dovrebbe avere un unico `h1` e un `h2` per ogni sezione o articolo principale della pagina. Poi possiamo usare gli altri tag, da `h3` a `h6`, per strutturare meglio articoli particolarmente complessi.

Un buon headline deve:

- avere al suo interno le keyword di riferimento
- essere convincente
- fare una sorta di promessa capace di generare attesa, curiosità e aspettativa

Spesso basta accostare termini noti ad altri meno noti per destare curiosità. Possono essere di successo anche titoli ironici o che creano contraddittorio.

Il **copywriter** è la persona che scrive i testi sfruttando le migliori strategie creative per coinvolgere l'utente.

#### 2.1.2. SEO off-page

Ci sono diverse ottimizzazioni che possiamo fare esternamente al sito web per migliorarne la posizione.

Si può studiare la **concorrenza** analizzando i punti di forza e di debolezza dei siti dei concorrenti, in particolar modo di quelli che competono per le nostre stesse keyword nei primi 20 risultati della SERP.

Possiamo usare strumenti come *Semrush*, che fornisce delle funzionalità che rendono semplice l'analisi dei competitor.

Si può cercare di fare **link building**, cioè aumentare la quantità e qualità di link esterni che rimandano al nostro sito. È importante per il SEO, ma solo se provengono da domini affidabili e tematicamente vicini al nostro.

Generalmente si ottengono proponendo contenuti che siano utili alla comunità del web e che rispondano alle domande degli utenti. Un altro modo è contattare altri siti tematicamente vicini e chiedere di mettere un link al nostro sito, spesso è richiesto un compenso.

Anche una buona attività di **social media marketing** permette di innescare una condivisione tale da aumentare la visibilità dei link che rimandano al nostro sito.

Questo tipo di backlink viene preso in considerazione da *Google*, magari attribuendogli un peso minore rispetto a un backlink di un grande portale.

#### 2.1.3. Link juice

Il **link juice** è l'autorevolezza che viene trasferita attraverso l'utilizzo di un link da una pagina web ad un'altra. È come se fosse un liquido che può essere travasato da una pagina all'altra tramite un link.

I link che rimandano al nostro sito, inseriti in siti autorevoli e attinenti al nostro settore, permettono di migliorare il posizionamento nella SERP.

L'homepage di un sito è generalmente la pagina che riceve maggiore juice. Più link riceve e maggiore sarà l'autorevolezza.

Dall'homepage è poi possibile distribuire il juice alle pagine tramite link interni. La quantità di juice trasmesso dipende dal numero di link presenti all'interno della pagina di partenza: più link ci sono meno juice verrà trasmesso a ciascuna pagina.

È quindi importante evitare di trasferire juice a pagine inutili, peggio ancora a pagine non più esistenti.

Di base i link sono di tipo **follow**, cioè trasferiscono normalmente il juice. I link di tipo **nofollow** indicano al motore di ricerca di non trasferire il juice. Per definire un link nofollow si inserisce l'attributo `rel="nofollow"` nel relativo tag `a`.

Per aumentare il link juice di origine è importante progettare bene l'attività di link building.

### 2.2. SEA

L'obiettivo del **SEA** è la promozione del sito web tramite annunci nei motori di ricerca e nei siti partner.

*Google Ads* è una delle piattaforme più importanti per questo scopo.

Tra le alternative principali abbiamo:

- piattaforme di affiliazione: es. *Tradedoubler*, *Sprintrade*
- accordi diretti con merchant: es. *Amazon*
- piattaforme di Real Time Bidding: es. *DoubleClick*, *Adform*
- circuiti display alternativi: es. *AdRoll*, *Criteo*

## 3. Strumenti di monitoraggio

### 3.1. Google Analytics

***Google Analytics*** è uno strumento che permette di monitorare l'andamento di un sito web. Ha molte funzionalità ed è pensato principalmente per mostrare le interazioni dell'utente con il sito.

Una volta creato un account è possibile definire una **proprietà**, cioè la risorsa da analizzare come un sito web o un'app.

Viene così creato un **codice di monitoraggio** che va inserito nel sito. Possiamo inserirlo a mano nelle pagine oppure nel caso di *PrestaShop* configurare il modulo *Google Analytics*. Inoltre possiamo usare *Google Tag Manager*, che è uno strumento che permette di gestire più codici di monitoraggio.

In ***home page*** abbiamo una panoramica delle misurazioni principali fatte sul sito come numero di visitatori, paese di provenienza, orari di visualizzazione.

In ***tempo reale*** vengono mostrate le misurazioni degli utenti che sono attivi in questo momento.

In ***pubblico*** sono presenti numerose opzioni che permettono di analizzare i comportamenti dell'utente, per es. pagine visualizzate per sessione, durata media di una sessione, frequenza di rimbalzo, lingue, browser e altri dati tecnici.

Alcuni dettagli che vanno ancora più in profondità sul profilo dell'utente richiedono ulteriori strumenti di *Google*.

In ***acquisizione*** vengono mostrate le origini del traffico sul nostro sito, per esempio da un motore di ricerca o da un social.

Per maggiori dettagli è possibile collegare la proprietà a *Google Search Console*.

In ***comportamento*** è possibile visualizzare il flusso di pagine che mediamente viene visualizzato da un utente, cioè come si sposta un utente all'interno del sito dopo esserci entrato. È possibile vedere anche la velocità di caricamento delle pagine.

### 3.2. Google Search Console

***Google Search Console*** è un altro strumento di *Google* per monitorare il traffico di un sito. Rispetto a *Google Analytics*, si concentra maggiormente sull'interazione di *Google* con il sito. È utilizzato principalmente dal webmaster.

Possiamo decidere di monitorare tutto il dominio oppure un URL specifico.

Ci sono diversi modi per collegare il proprio account con un sito. Possiamo caricare una pagina specifica nella cartella del sito, inserire uno specifico tag HTML nelle pagine, usare *Google Analytics* o *Google Tag Manager* se già configurati. Esiste anche una verifica tramite record DNS, ma in tal caso va contattato il provider del dominio.

In ***introduzione*** abbiamo una panoramica generale sull'andamento del sito.

In ***controllo URL*** possiamo vedere statistiche dettagliate su singole pagine.

In ***risultati di ricerca*** possiamo vedere le *impressioni totali*, cioè quante volte è stato visualizzato il link al nostro sito, e i *click totali* su di esso. Il rapporto tra i due è chiamato *CTR*.

Vengono inoltre mostrate le parole scritte dagli utenti su *Google* per trovare il nostro sito. Vi sono ulteriori informazioni sulle principali pagine visitate, paesi di provenienza e statistiche sui dispositivi.

In ***copertura*** vengono mostrati eventuali errori e avvisi relativi alle pagine.

In ***sitemap*** è possibile inserire un file che contiene tutte le URL delle pagine che compongono il sito. La sitemap può aiutare l'utente in caso di disorientamento, ma in particolar modo aiuta il motore di ricerca a capire come è strutturato il sito.

In ***rimozioni*** possiamo chiedere a *Google* di evitare di indicizzare certe pagine.

In ***usabilità su dispositivi mobili*** vengono elencati i problemi di visualizzazione su dispositivi come smartphone. Da tenere in considerazione vista la loro importanza.

In ***AMP*** possiamo vedere i problemi relativi alle pagine AMP (Accelerated Mobile Pages). Queste pagine sono un progetto di *Google* per creare pagine ottimizzate per i dispositivi mobile e abbassare i tempi di caricamento. Generalmente sono utilizzate dai siti d'informazione.

In ***Link*** è possibile visualizzare i siti da cui provengono i link al nostro sito e i più frequentati link interni.

### 3.3. Google Trends

***Google Trends*** permette di vedere le tendenze nelle ricerche e l'interesse nel tempo di certe keywords.

Possiamo vedere i paesi che maggiormente cercano quella keyword, gli argomenti correlati e le query di ricerca associate.

### 3.4. Google PageSpeed Insights

***Google PageSpeed Insights*** è uno strumento che analizza il contenuto di una pagina web per verificarne la velocità di caricamento.

Una volta analizzata la pagina viene mostrata una valutazione della velocità da 0 a 100. Raggiungere valori vicini a 100 è molto complesso, richiede una grande ottimizzazione del sito e delle risorse impiegate.

Sono presenti numerosi dettagli anche molto tecnici. Alcuni suggerimenti permettono al webmaster di capire quali sono i punti critici da andare a ottimizzare.

### 3.5. SEOZoom

***SEOZoom*** è uno strumento online per analizzare e monitorare un sito web, simile ad altri come *Semrush*. È un progetto italiano e alcune funzionalità sono gratuite.

Tra le funzionalità presenti abbiamo la possibilità di fare un'**analisi delle keyword**.

La *keyword difficulty* è la difficoltà di posizionamento di una chiave, mentre la *keyword opportunity* rappresenta l'opportunità di posizionarsi per quella keyword considerando i competitor.

Viene mostrata la SERP per quella keyword, i trend e la competizione dei backlink. Vengono inoltre mostrate keyword secondarie attinenti e i competitor in dettaglio.

È possibile fare un'**analisi di un sito web** e metterlo in diretto confronto con un competitor.

Tra le funzionalità accessorie, una interessante è fornita dal **SEO Spider**. Questo fornisce una lista esportabile di tutti i link del sito.

Se facciamo modifiche importanti alla piattaforma e i link alle pagine vengono cambiati, dobbiamo avvisare il motore di ricerca che le pagine si sono spostate dal vecchio al nuovo indirizzo. È importante perché altrimenti i risultati di ricerca punterebbero a pagine non più raggiungibili.

Una volta ottenuti i vecchi indirizzi, applichiamo delle regole di reindirizzamento nel file `.htaccess` che indicano a *Google* lo spostamento delle pagine dai vecchi ai nuovi indirizzi. *Screaming Frog* è un programma con una funzionalità simile.

Infine possiamo generare dei **report** periodici, magari da dare al committente per metterlo al corrente dei risultati.

## 4. Google Ads

***Google Ads*** è la piattaforma di servizi pubblicitari di *Google* che permette di far visualizzare annunci promozionali agli utenti.

Le sue peculiarità comprendono:

- **sistema premiale**: il rendimento degli annunci incide sul costo e sulla visibilità
- **forti potenzialità di targeting**: è possibile mostrare annunci estremamente mirati, anche se la piattaforma è complessa
- **sistema di reti**: sono i luoghi dove vengono visualizzati gli annunci e comprendono molti siti di *Google* e dei partner

### 4.1. Rete

La **rete** è l'insieme dei posizionamenti in cui può essere pubblicato un annuncio. Comprende i siti di *Google* e dei suoi partner e altri posti come le app per cellulari.

La rete è suddivisa in gruppi:

- **Rete di ricerca** - *Google Search Network* (GSN):
  - comprende le SERP di *Google*, di altri suoi siti come *Google Maps* e dei siti partner
  - ha come obiettivo principale la conversione e la generazione di lead, è molto importante per gli e-commerce, sostanzialmente serve per far cliccare l'utente
- **Rete Display** - *Google Display Network* (GDN):
  - comprende siti di *Google* come *YouTube* e *Gmail* e tantissimi altri siti dei partner
  - ha come obiettivo principale il branding, in questo caso sono più importanti le visualizzazioni piuttosto che i click

Ovviamente una non esclude l'altra, si possono provare entrambe e decidere poi su quale investire di più.

Per esempio, quando cerchiamo qualcosa su *Google*, spesso vediamo annunci testuali (Rete di ricerca) in un numero fino a 4 nella parte alta della pagina e fino a 3 nella parte bassa.

Di fianco ai risultati è talvolta visibile un'area con dei prodotti pubblicizzati (Shopping ads o Product Listing Ads).

In alcuni siti è possibile vedere in mezzo o a fianco dei contenuti annunci in formato immagine o video (Rete Display).

### 4.2. Asta

Quando si pubblica un annuncio, questo entra in competizione con quelli degli altri inserzionisti. Si crea così un'**asta** che premia gli annunci con un ranking superiore.

Nello specifico:

1. quando un utente effettua una ricerca, *Google Ads* raggruppa tutti gli annunci pertinenti alle parole chiave ricercate
2. vengono scartati gli annunci non idonei, per es. quelli indirizzati ad altri paesi
3. tra i rimanenti vengono pubblicati quelli con il ranking più alto

Il **ranking** dell'annuncio dipende dall'ammontare investito, dal punteggio di qualità e da altri fattori.

### 4.3. Punteggio di qualità

Il **punteggio di qualità** è uno strumento che permette di analizzare la qualità dell'annuncio in modo da migliorarne il suo rendimento rispetto a quelli dei concorrenti.

Si basa su tre punti principali:

- **tasso di click**: la probabilità che l'annuncio riceva un click quando viene pubblicato
- **pertinenza**: il grado di corrispondenza tra l'annuncio e le parole chiave ricercate dall'utente
- **esperienza d'uso**: il livello di utilità della pagina di destinazione per l'utente, l'originalità dei testi, la velocità di caricamento

Risulta quindi evidente che oggi non basta più pagare. Sono necessari altri criteri come testi originali e pertinenti.

La landing page deve essere il più interessante possibile per l'utente. L'annuncio deve puntare a una pagina specifica che mostra immediatamente all'utente ciò che stava cercando.

Il **CPC** (Cost Per Click) è quanto ci costa un singolo click fatto dall'utente sull'annuncio. Il suo valore effettivo in *Google Ads* equivale al rapporto tra il ranking dell'inserzionista immediatamente sotto e il proprio punteggio di qualità.

### 4.4. Campagne pubblicitarie

*Google Ads* fornisce un'interfaccia guidata per generare **campagne pubblicitarie**. Sono in qualche modo simili a quelle di *Facebook Business Manager*, ma quest'ultimo riesce ad attingere a un database di profilazione utente ben più vasto.

I passaggi principali sono:

- selezione dell'obiettivo
- selezione del tipo di campagna
- configurare la campagna
- configurare il gruppo di annunci
- creare l'annuncio

L'annuncio poi verrà analizzato da *Google* per verificare che rispetti le normative pubblicitarie.

#### 4.4.1. Obiettivo

L'**obiettivo** della campagna rappresenta il traguardo principale della promozione.

La lista comprende:

- **vendita**: incentiva le vendite online, nell'app, per telefono o in negozio
- **lead**: genera lead e altre conversioni incoraggiando l'utente ad agire
- **traffico sul sito web**: invita gli utenti a visitare il sito web
- **considerazione del prodotto e del brand**: incentiva l'utente a scoprire i prodotti o i servizi offerti
- **notorietà del brand e copertura**: raggiunge una vasta base di pubblico per creare awareness
- **promozione di app**: aumenta il numero di installazioni e interazioni di un'app
- **promozioni e visite ai negozi locali**: incentiva le visite ai negozi locali
- **campagna senza obiettivo**: fornisce una maggiore personalizzazione della campagna per i più esigenti

#### 4.4.2. Tipo di campagna

Il **tipo di campagna** determina dove gli utenti visualizzano gli annunci e le opzioni disponibili nelle impostazioni della campagna.

La lista comprende:

- **ricerca**: annunci testuali nella SERP di *Google* e dei siti partner
- **display**: annunci in forma di immagini e video presenti nei siti collegati a questa rete
- **shopping**: annunci con schede prodotto di un e-commerce
- **video**: annunci video su *YouTube* e siti partner
- **app**: annunci per la promozione di app su *Google Play* e altre reti
- **intelligente**: lasciamo a *Google Ads* il compito di selezionare le reti migliori
- **pagine locali**: annunci specialmente su *Google Maps* e in ricerca per promuovere le visite presso le sedi locali
- **discovery**: annunci altamente personalizzati che si basano sui dati di monitoraggio del nostro sito

#### 4.4.3. Campagna

Nelle impostazioni della **campagna** possiamo selezionare i parametri principali della promozione.

Tra le impostazioni che possiamo personalizzare abbiamo:

- rete: ricerca e/o display
- targeting: possiamo scegliere località, lingue, segmenti di pubblico in base a dati demografici, interessi, remarketing e altro
- budget: ammontare giornaliero medio da assegnare alla campagna
- estensioni: link e informazioni supplementari all'annuncio, es. bottone "Chiama ora"

È consigliabile creare una campagna separata per ogni:

- area geografica e/o linguistica
- necessità di budget differenti
- tipo di rete

#### 4.4.4. Gruppo di annunci

Nelle impostazioni del **gruppo di annunci** possiamo raggruppare gli annunci in base alle stesse parole chiave e a un tema comune.

*Google Ads* può mostrarci dei suggerimenti per le parole chiave più attinenti.

Le parole chiave possono avere una **corrispondenza**:

- **generica** (es. *parola chiave*): è il metodo predefinito, gli annunci potrebbero essere mostrati a seguito di ricerche correlate alla parola chiave, la corrispondenza è approssimativa
- **a frase** (es. *"parola chiave"*): gli annunci potrebbero essere mostrati a seguito di ricerche che includono il significato della parola chiave, la corrispondenza è moderata
- **esatta** (es. *[parola chiave]*): gli annunci potrebbero essere mostrati a seguito di ricerche che hanno lo stesso significato della parola chiave, la corrispondenza è stretta

È possibile escludere una parola chiave aggiungendo il segno meno all'inizio di essa. L'annuncio non verrà mostrato se durante la ricerca è stata inserita quella keyword.

È consigliabile creare un gruppo di annunci separato per ogni:

- categoria o raggruppamento omogeneo di prodotti o servizi
- ricerca che include il nostro brand
- ricerca con nomi dei marchi dei principali competitor: non molto corretto ma spesso efficace
- target di utenza mirato
- canale display diverso: es. *YouTube*, *Gmail*

#### 4.4.5. Annuncio

L'**annuncio** rappresenta la parte creativa della campagna.

Tra le opzioni di configurazione abbiamo:

- l'URL mostrato nell'annuncio
- il titolo: è possibile inserirne diversi e questi verranno mostrati a rotazione di volta in volta
- la descrizione: anch'essa a rotazione

*Google Ads* mostra dei suggerimenti sull'efficacia dell'annuncio e una sua anteprima.

### 4.5. Monitoraggio

Una volta creata una campagna, *Google Ads* permette di monitorarne l'andamento attraverso numerosi parametri.

Tra i vari parametri abbiamo:

- numero di visualizzazioni totali degli annunci (*impressioni*)
- numero di click sugli annunci
- rapporto percentuale tra click e visualizzazioni totali (*CTR*)
- costo totale della campagna
- costo per click
- statistiche sulle parole chiave scelte
- dettagli sui dispositivi utilizzati dagli utenti
- punteggio di qualità e statistiche sulla pagina di destinazione
- statistiche sui segmenti di pubblico
- reti di *Google* e siti dove sono stati pubblicati gli annunci

## 5. PrestaShop

### 5.1. Catalogo

In ***Prodotti*** possiamo modificare un prodotto per poi configurare le opzioni SEO, per es. definire un titolo e una descrizione personalizzata. Se non mettiamo nulla li genera da solo.

Se la pagina di un prodotto è indicizzata da un motore di ricerca, cosa succede se rimuoviamo il prodotto? Abbiamo diverse opzioni, per esempio reindirizziamo l'utente a una categoria o un prodotto correlato. Possiamo farlo temporaneamente se pensiamo che il prodotto mancante ritornerà in vendita oppure permanentemente.

### 5.2. Moduli

Il modulo ***Google Analytics*** permette di collegare il proprio account di *Google Analytics* al nostro e-shop per misurarne l'andamento.

Il modulo ***Google sitemap*** permette di scegliere gli URL da includere nella sitemap e la sua frequenza di aggiornamento.

La sitemap si può aggiornare manualmente, ma è ovviamente sconveniente. Possiamo in alternativa chiedere all'hosting di impostare un *Cron Task* che aggiorna la sitemap in maniera automatica.

Una volta creata la sitemap la possiamo collegare a *Google Search Console*.

### 5.3. Parametri Negozio

***Traffico & SEO*** mostra una lista delle pagine principali del sito.

Per ciascuna di esse possiamo definire il *titolo* e la *meta descrizione*, due elementi che compongono lo snippet nelle SERP e quindi molto importanti.

Possiamo definire delle *parole chiave* per segnalare al motore di ricerca gli argomenti della pagina, ma oggi non sono molto importanti per il ranking.

In *Impostazione URL* possiamo convertire gli URL dinamici richiesti da *PrestaShop* per funzionare in URL statici preferiti dai motori di ricerca. Esempio:

```text
Dinamico: http://gammadv.eu/01/index.php?id_category=13&controller=category
 Statico: http://gammadv.eu/01/13-smartphone
```

Possiamo anche cambiare lo *schema degli URL* predefiniti.

Se abbiamo più pagine che descrivono un prodotto con caratteristiche simili, il motore di ricerca li vedrebbe come duplicati e questo sarebbe penalizzante ai fini SEO. L'URL canonico è una pagina che dichiariamo essere la principale per tutte le pagine simili.

Il file `robots.txt` contiene le regole che indicano a un motore di ricerca quali pagine del sito indicizzare o meno. *PrestaShop* permette di selezionare le sezioni da includere e da vietare nell'indicizzazione.

Per esempio è certamente utile indicizzare le pagine prodotto, ma non lo è le pagine tecniche che servono per far funzionare la piattaforma.

## 6. WordPress

***WordPress*** è un CMS simile a *PrestaShop*, ma è nato in ambito editoriale per poi evolversi come piattaforma per la costruzione di siti.

Possiamo creare articoli e organizzarli in categorie, creare pagine statiche e un portfolio di prodotti o servizi.

Come in *PrestaShop*, le funzionalità della piattaforma possono essere estese grazie ai moduli, qua chiamati **plugin**.

Oltre ai plugin sono presenti dei **widget**, piccoli elementi che vanno a completare il sito. Per es. sezioni che mostrano gli articoli o i commenti recenti.

*Avada* è un **tema** a pagamento che permette di creare pagine dal layout flessibile senza grandi competenze tecniche.

### 6.1. Yoast SEO

***Yoast SEO*** è un plugin per il SEO tra i più usati. Fornisce molte indicazioni su come scrivere un articolo in ottica SEO e leggibilità. È gratuito, ma la versione a pagamento aggiunge altre funzionalità.

Per esempio avverte se il `title` è troppo corto o la `description` non contiene abbastanza parole chiave.

Inoltre avvisa se l'articolo contiene poche parole, se le frasi sono troppo lunghe o poco variegate, se i titoli come `h2` sono usati in maniera corretta.

Permette di applicare regole avanzate per i motori di ricerca e fornisce ottimizzazioni specifiche per i social.

<!--
Data: 19/06/2021
Nome file: ok
-->

<!--
Data: 19/06/2021
Pagina: ok
Apostrofi: ok
Lint: ok
Grammatica: ok
Codice: ok
Numeri sezione: ok
-->

<!--
Data: 25/06/2021
Pagina: ok
Apostrofi: ok
Lint: ok
Grammatica: ok
Codice: ok
Numeri sezione: ok
-->
