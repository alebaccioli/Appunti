# Sviluppo dell'applicazione per l'e-business

**Docente**: Alberto Cocchi ([email](mailto:a.cocchi@gammadv.it))  
**Appunti**: Alessandro Baccioli ([GitHub](https://alebaccioli.github.io/appunti/))  
**Licenza**: [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/deed.it)

**Indice**:

- [1. Aprire un e-commerce](#1-aprire-un-e-commerce)
  - [1.1. Aspetti chiave](#11-aspetti-chiave)
  - [1.2. Fare e-commerce](#12-fare-e-commerce)
  - [1.3. Sito di e-commerce](#13-sito-di-e-commerce)
  - [1.4. Drop shipping](#14-drop-shipping)
  - [1.5. Valutare la complessità](#15-valutare-la-complessità)
  - [1.6. Pagamenti e spedizioni](#16-pagamenti-e-spedizioni)
  - [1.7. Web marketing](#17-web-marketing)
- [2. PrestaShop](#2-prestashop)

## 1. Aprire un e-commerce

**Data lezione**: 10/05/2021

Aprire un e-commerce è come aprire un negozio fisico, è necessario avere un piano e delle strategie adeguate.

La presentazione di un e-commerce può essere immaginata come la parte emersa di un iceberg. La parte più grande che non vediamo equivale al sistema di gestione e alle strategie che stanno dietro al sito di e-commerce.

La pandemia ha reso importanti tanti servizi che prima venivano considerati come accessori.

### 1.1. Aspetti chiave

Per aprire un e-commerce è necessario considerare tanti aspetti:

- **budget**: serve per coprire tutti i processi richiesti per l'apertura e la gestione
- **canali di traffico**:
  - possiamo far arrivare i visitatori sul nostro e-shop sfruttando vari canali, magari iniziando a investire su un paio di essi per poi considerarne altri
  - il SEO incide sui risultati organici (non di marketing) di un motore di ricerca
  - l'advertising a pagamento incide invece sui risultati sponsorizzati
  - DEM
  - la landing page è una sorta di pagina web *di atterraggio* dove si trovano tutte le informazioni di un messaggio pubblicitario, il cui scopo è la conversione dei visitatori in clienti
  - newsletter
  - i comparatori come *TrovaPrezzi* mostrano in un'unica pagina i prodotti di vari competitor, non vendono direttamente ma con un link rimandano all'e-commerce del venditore
  - offline, cioè un negozio fisico che apre un e-shop per aumentare la possibilità di vendere (mostrando magari volantini o cataloghi online)
- **marketplace**:
  - *eBay* e *Amazon* sono degli esempi ma ce ne sono molti altri, sono simili ai comparatori in un certo senso ma a differenza di questi il marketplace è una piattaforma dove si può anche acquistare
  - richiedono dei compensi per poter vendere, es. 14% circa per la categoria abbigliamento
  - *Amazon* può anche comportarsi come competitor, osserva quali prodotti sono richiesti di più e compra l'azienda che li produce oppure crea in proprio prodotti simili e li marchia come *AmazonBasics*
  - anche *Facebook* ha un proprio marketplace
- **customer care**:
  - sempre più siti cercano di aiutare il visitatore durante l'acquisto, spesso si può vedere un'icona tipicamente in basso a destra che cliccandoci permette d'interagire con un operatore
  - richiede personale che fa assistenza oppure la possiamo affidare a un'agenzia esterna
- **logistica**:
  - serve fare un piano su dove mettere i prodotti da vendere e su come gestirli, per es. la vendita di prodotti alimentari ha delle regole sanitarie da rispettare
  - serve un piano di riserva nel caso avessimo un boom di richieste, come capitato a molte attività in tempi di pandemia che si sono rese conto di non avere sufficiente spazio per contenere tutto il materiale
- **misurazione**: per misurare e valutare la gestione dell'e-commerce
- **esperienza utente**: va curata l'interfaccia del nostro e-shop per evitare che il visitatore sia incerto sull'acquisto, per es. ha comprato un prodotto ma non sa dov'è il pacco o se l'abbiamo spedito
- **mobile**: oggi il traffico medio dei visitatori di un sito è circa 80% mobile, 5% tablet, 15% desktop, il mobile è dunque importantissimo da considerare per l'esperienza utente
- **social network**: sono molto importanti, il passaparola moderno si fa lì ed è sempre da lì che arriveranno molti dei nostri visitatori
- **servizi accessori**:
  - è buona norma scegliere i sistemi di pagamento più adeguati per il cliente
  - *PayPal* è uno tra i più usati, fa da intermediario tra il cliente e il venditore, in modo tale che i dati personali come il numero della carta di credito non vengano esposti
  - con il contrassegno si paga alla consegna, per il venditore è un po' noioso perché i soldi non arrivano subito e inoltre come servizio costa un po' di più
  - la carta di credito richiede di contattare una banca per aprire un conto corrente
- **privacy policy**:
  - dal 2016 il garante della privacy ha imposto ai siti web di avvisare il visitatore quando vengono usati i suoi dati, per es. tramite un banner che chiede di accettare o rifiutare l'utilizzo dei dati
  - i *cookie* sono piccoli file che il sito memorizza nel computer del visitatore, vengono scritte informazioni riguardanti le scelte e i comportamenti del visitatore su quel sito
  - i dati dell'utente sono importanti per la nostra attività, per es. secondo certe indiscrezioni *Zalando* pagherebbe fino a 50 euro per avere l'indirizzo email di un utente, ma dobbiamo cercare di non infastidire il visitatore
- **presenza all'estero**: dobbiamo considerare se il nostro prodotto interessa all'estero, se possiamo gestire le vendite a un mercato estero e studiare le leggi di quel paese
- **piattaforma**:
  - per costruire il nostro e-shop possiamo scegliere il tipo di piattaforma da usare
  - nel caso dell'open source alcune aziende o comunità di sviluppatori mettono a disposizione il nucleo di un programma gratuitamente, magari con servizi accessori a pagamento
  - programmi su licenza, sono piattaforme a pagamento ma in genere offrono un'assistenza più professionale
  - costruire un e-commerce da zero, serve un gruppo di programmatori dalle idee chiare, è un'operazione costosa e potenzialmente pericolosa se l'agenzia non fa le cose bene, però è altamente personalizzabile

### 1.2. Fare e-commerce

Ovviamente per iniziare serve un prodotto o un servizio (es. consulenze). Bisogna aver chiaro cosa vendere.

Serve un budget per le campagne di marketing. Come regola generale il 30% viene riservato per costruire e gestire l'e-commerce, il restante 70% viene investito in attività di marketing, per es. SEO, advertising a pagamento, landing page, social.

Serve avere degli utenti ai quali vendere e dobbiamo conoscerli. Dobbiamo creare dei profili di acquirenti tipo, ossia le *buyer personas*.

Dobbiamo avere dei canali di vendita, es. sito, marketplace. Dobbiamo avere il personale idoneo a gestire le vendite e le spedizioni e a gestire il magazzino. Sembra banale ma richiede una certa organizzazione dei prodotti in magazzino e del loro packaging.

Serve organizzare il personale per gestire gli incassi e le fatture. Il personale è inoltre richiesto per il customer care.

Per valutare la nostra attività serve analizzare i dati. Uno degli strumenti più usati è *Google Analytics* ma ce ne sono altri. È importante perché stiamo svolgendo molte azioni ma serve poi analizzare quello che facciamo per capire se lo stiamo facendo bene.

### 1.3. Sito di e-commerce

Quando si sceglie la piattaforma da usare per il nostro e-commerce, è importante capire la **portata degli utenti**.

Se un e-shop vende prodotti a una platea moderata di utenti, si può usare una tecnologia abbastanza semplice. Se invece ci troviamo in una situazione tipo *Amazon*, il traffico di visitatori sarà notevolmente superiore e serve una tecnologia diversa.

Se il sito e la tecnologia usata non sono adeguati alla portata, possono verificarsi errori e rallentamenti sul sito che infastidirebbero i clienti e li farebbero scappare. Se si sbaglia tecnologia ovviamente se ne può scegliere un'altra, ma questo richiede tempo per rifare tutti gli articoli, le foto dei prodotti e altro. Meglio capirlo subito.

Dobbiamo poi scegliere le lingue e le valute in base alla clientela che vogliamo raggiungere.

Se abbiamo tanti prodotti possiamo pensare di integrare l'e-commerce con un sistema gestionale per il magazzino. Questo permette di collegare in maniera automatica le vendite fatte sull'e-shop con le rimanenze in magazzino. Per un e-commerce piccolo può non essere necessario, ma in tal caso questi passaggi vanno fatti a mano.

### 1.4. Drop shipping

Per **drop shipping** s'intende un tipo di e-commerce che non dispone materialmente dei prodotti, ma piuttosto si occupa di trasferire la vendita al fornitore che spedirà il prodotto direttamente all'utente.

Il vantaggio di questo tipo di vendita è che abbiamo già tutto pronto, non ci dobbiamo occupare di gestire il magazzino e le spedizioni e a noi rimane solo da gestire l'e-commerce. Lo svantaggio è che non saremo i soli a fare questo tipo di attività, quindi i margini unitari sul prodotto non sono molto alti.

*Amazon* vende prodotti propri ma fa anche drop shipping. Possiamo passare il nostro catalogo di prodotti ad *Amazon* e quando questo riceve un ordine lo gira a noi.

### 1.5. Valutare la complessità

Per alcuni articoli dobbiamo considerare le varianti disponibili (es. colore, taglia, peso), le combinazioni delle varianti, i kit di prodotti, i prodotti configurabili o componibili, il carrello "intelligente" (es. mentre si sta comprando una custodia per un cellulare viene suggerito l'acquisto di un supporto per cellulari da auto).

Bisogna capire la complessità dell'offerta commerciale, dei concorrenti, dei listini, degli sconti da applicare. Studiare tutte le promozioni e le festività presenti nel calendario che possiamo sfruttare per attirare l'attenzione (es. promozioni per la festa della mamma o per Halloween).

### 1.6. Pagamenti e spedizioni

*PayPal* è il servizio di pagamento più famoso, ma ci sono altri soggetti intermediari che offrono un servizio simile. Essi guadagnano una commissione per ogni transazione di vendita.

Oggi si sta diffondendo il pagamento a rate anche su certi store online, le procedure una volta complesse adesso sono effettuabili anche con un semplice codice fiscale.

Il bonifico e il contrassegno sono molto utilizzati. Anche il bonifico ha meno problemi di una volta e le procedure sono più rapide.

Per i pagamenti dall'estero, dobbiamo essere sicuri che i clienti di altri paesi possano utilizzare il nostro sistema di pagamento.

Ovviamente alla fine dobbiamo inviare i pacchi e quindi fare accordi con i corrieri. Generalmente si paga a seconda della quantità e della dimensione media dei pacchi inviati in un certo periodo.

Ogni tanto possono capitare problemi tra venditore e compratore, è importante magari rivolgersi a un legale per tutelarci in queste situazioni e nella gestione dei resi.

### 1.7. Web marketing

Il **SEO** (Search Engine Optimization) è un'insieme di ottimizzazioni che facciamo al nostro sito per facilitare il compito a un motore di ricerca nel trovarlo e promuoverlo in pagine di risultati migliori.

Se possibile dobbiamo tracciare tutto, sempre grazie a strumenti come *Google Analytics*, per fare la profilazione dei clienti e cercare di capire i loro comportamenti raccogliendo i loro dati.

Segmentando i clienti possiamo inviare diversi tipi di newsletter, es. una diversa per ogni tipologia di sport.

Possono essere utili campagne pubblicitarie con siti affiliati, cioè partner di vendita che pubblicano la nostra pubblicità in cambio di un compenso.

La concorrenza tra siti di e-commerce c'è ed è cresciuta col tempo. Serve studiare tanto gli altri concorrenti senza però copiarli. Può essere utile comprare online per capirne il funzionamento e valutare i servizi extra offerti dai concorrenti (es. caramelle o altri regali).

Il sito [*ecommerceCANVAS*](http://www.ecommercecanvas.it/) permette di scaricare un foglio che ci aiuta nella valutazione di tutti gli aspetti necessari per la creazione del nostro e-shop.

## 2. PrestaShop

***PrestaShop*** è uno degli e-shop più famosi ed è open source.

I passaggi necessari per configurare questa piattaforma sono:

- collegarsi sul sito di [*PrestaShop*](https://www.prestashop.com/it/download), selezionare il profilo idoneo (es. freelance), inserire l'email (opzionale), accettare la politica e le condizioni di utilizzo, scaricare il file (il cui nome sarà simile a `prestashop_1.7.7.4.zip`)
- se non abbiamo un programma che gestisce i file compressi bisogna installarne uno, es. [*WinZip*](https://www.winzip.com/win/it/downwz.html), *Windows 10* ne ha già uno integrato
- scompattare l'archivio di *PrestaShop*, normalmente facendo click con il tasto destro e poi click su `Estrai in prestashop_1.7.7.4` o similare
- collegarsi sul sito di [*FileZilla*](https://filezilla-project.org/download.php?type=client), scaricare e installare il client, questo programma si occupa di prendere i file presenti sul nostro hard disk e di trasferirli sullo spazio web fornito dal docente
- aprire *FileZilla*, nella parte in alto in `host`, `nome utente` e `password` inserire i dati forniti dal docente relativi al proprio account
- fare attenzione a scrivere `nome utente` e `password` rispettando maiuscole e minuscole, questo perché l'hosting fa distinzione
- la `porta` non serve scriverla, la capisce da solo
- *FileZilla* mostra nella parte sinistra il nostro hard disk, mentre nella parte destra lo spazio web
- nella parte sinistra spostarsi tra le cartelle fino a trovare la nostra cartella di *PrestaShop* scompattata
- trascinare il contenuto nella parte destra
- il sito sarà visibile all'indirizzo `www.gammadv.it/xy`, dove `xy` corrisponde al numero del nostro account (es. `01`)
- da test fatti da me è necessario dire a *FileZilla* di non usare TLS

<!--
Data: 11/05/2021
Nome file: ok
-->

<!--
Data: 11/05/2021
Pagina: ok
Apostrofi: ok
Grammatica: ok
Numeri sezione: ok
Codice: ok
-->
