# Modalità di accesso all'informazione

**Docente**: Lorenzo Cristofori ([sito](https://www.lorenzocristofori.it/))  
**Appunti**: Alessandro Baccioli ([GitHub](https://alebaccioli.github.io/appunti/))  
**Licenza**: [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/deed.it)

**Indice**:

- [1. Hardware](#1-hardware)
- [2. Memoria](#2-memoria)
  - [2.1. Cartelle](#21-cartelle)
  - [2.2. File](#22-file)
  - [2.3. Collegamenti](#23-collegamenti)
  - [2.4. Unità di misura](#24-unità-di-misura)
- [3. Digitalizzare le informazioni](#3-digitalizzare-le-informazioni)
- [4. Sintetizzazione delle informazioni](#4-sintetizzazione-delle-informazioni)
  - [4.1. Modifica della comunicazione](#41-modifica-della-comunicazione)
  - [4.2. Informazioni tramite immagini](#42-informazioni-tramite-immagini)
  - [4.3. Infografiche](#43-infografiche)
  - [4.4. PowerPoint](#44-powerpoint)
- [5. Internet](#5-internet)
  - [5.1. WWW](#51-www)
  - [5.2. HTML](#52-html)

## 1. Hardware

**Data lezione**: 07/04/2021

Per **hardware** si intende l'insieme delle componenti meccaniche che costituiscono un dispositivo come un computer. La definizione comprende anche dispositivi esterni, chiamati **periferiche**, che permettono di inviare e di ricevere informazioni da un computer.

Le periferiche possono essere suddivise in periferiche di **input** o di **output**:

- **input**: inseriscono informazioni all'interno di un computer, es. scanner, mouse, tastiera, webcam
- **output**: ricevono informazioni da un computer, es. stampante, casse, monitor
- **input/output**: appartengono a entrambe le categorie
  - il touchscreen di un cellulare fa sia da schermo che da input dei tocchi sullo schermo
  - un gamepad invia comandi al computer ma riceve anche un *feedback* della vibrazione

## 2. Memoria

Una **memoria** permette di archiviare le informazioni. Possiamo vederla come un grande contenitore, all'interno del quale posso mettere altri contenitori più piccoli. Questo permette di organizzare le informazioni in modo da recuperarle più velocemente.

### 2.1. Cartelle

Per esempio, possiamo creare un contenitore, cioè una **cartella**, per archiviare le nostre foto. Ma nel caso avessimo migliaia di foto sarebbe comunque difficile andare a recuperare foto relative a un certo periodo. Possiamo quindi creare ulteriori cartelle, per esempio una per ogni anno, in modo da organizzarle meglio.

Ogni file ha un indirizzo che permette di individuarlo all'interno della memoria. L'indirizzo è composto da un insieme di contenitori, partendo dal contenitore più grande fino a quello più specifico. Nei sistemi *Windows*, il contenitore più grande prende tipicamente il nome di `C:`. Il simbolo `\` serve per separare i nomi dei contenitori. Esempio:

```
C:\Foto\2020\spiaggia.jpg
```

Quindi ogni indirizzo contiene dei contenitori (cartelle) e dei contenuti (file).

### 2.2. File

I **file** possono essere documenti, foto, musica, film. Anche i programmi sono composti da file. Essi contengono informazioni scritte in un **codice binario** (cioè una sequenza formata da `0` e `1`) che viene letto dal dispositivo.

Un dispositivo è in grado di riconoscere un tipo di un file (es. un documento o un'immagine) grazie all'**estensione**. L'estensione segue il nome del file ed è separata da esso da un punto (es. `spiaggia.jpg`, `spiaggia` è il nome e `jpg` è l'estensione).

Esempi di estensioni:

- **testo**: docx, doc, txt, odt
- **immagini**: jpg, jpeg, png, tiff, gif, psd
- **audio**: mp3, wav, aac
- **video**: mp4, avi, mov, mpeg
- **fogli di calcolo**: xlsx, xls, ods
- **pagine Internet**: html, php
- **multiformato**: pdf

*Windows* normalmente non mostra l'estensione dei file per sicurezza, perché modificando impropriamente l'estensione di un file questo potrebbe poi non essere riconosciuto dal dispositivo.

### 2.3. Collegamenti

**Data**: 14/04/2021

Spesso abbiamo bisogno di un file o una cartella, memorizzati da qualche parte nella nostra memoria, in una posizione più facile da raggiungere, per esempio sul desktop.

Un **collegamento** è un puntatore a un file o a una cartella. Possiamo vederlo come un interruttore che ci permette di utilizzare una lampadina posta più distante. Le icone dei collegamenti si distinguono grazie alla presenza di una freccia.

Dentro al menù *Start* abbiamo una lista dei programmi che possiamo avviare, ma questi non sono memorizzati all'interno del menù *Start*, ma piuttosto da qualche parte nella memoria. Nel menù *Start* abbiamo quindi dei collegamenti che puntano ai file che avviano i programmi.

Anche il web è fatto di collegamenti: ciascuna pagina può avere al proprio interno dei collegamenti ad altri file.

### 2.4. Unità di misura

L'unità di misura di una memoria è il **bit** (b), un'informazione che può avere il valore di `0` o `1`.

Molto spesso si usa anche un'altra unità di misura, il **Byte** (B) che corrisponde a un gruppo di 8 bit. Il Byte viene storicamente usato per rappresentare un carattere di testo in un computer.

I multipli di un Byte sono:

- 1024 B = 1 KiloByte (KB)
- 1024 KB = 1 MegaByte (MB)
- 1024 MB = 1 GigaByte (GB)
- 1024 GB = 1 TeraByte (TB)

## 3. Digitalizzare le informazioni

**Digitalizzare** significa trasformare un'informazione in linguaggio informatico, nello specifico in codice binario. Per esempio, possiamo prendere un documento cartaceo e digitalizzarlo usando uno scanner, oppure creare direttamente un documento digitale.

Digitalizzare permette di avere certi vantaggi:

- avere tanti contenuti in un piccolo spazio organizzato, invece di copie cartacee che occupano spazio fisico e che possono rendere difficile recuperare con facilità le informazioni di cui abbiamo bisogno
- condividere i documenti con altre persone tramite Internet, con una copia fisica siamo molto più limitati
- le informazioni all'interno di un documento possono essere collegate a informazioni presenti in altri documenti, per esempio collegamenti tra pagine web o informazioni di clienti collegati a un prodotto a sua volta collegato a un fornitore, cosa impossibile da fare con documenti cartacei

Possono esserci anche degli svantaggi:

- un problema sulla sicurezza quando condividiamo informazioni, quindi servono sistemi che impediscono l'accesso a persone non autorizzate
- i dati possono essere persi a causa di fallimento delle memorie, servono quindi backup in base alla frequenza di produzione dei dati, su hard disk esterno o in cloud

È importante digitalizzare nel formato giusto. Normalmente uno scanner converte un'informazione in formato immagine (tipo una foto): questo impedisce di accedere al testo in una forma utilizzabile per altri scopi.

È quindi consigliabile utilizzare un **OCR** (Optical Character Recognition), un riconoscimento ottico dei caratteri capace di riconoscere il testo di un'immagine e di convertirlo in caratteri utilizzabili in un computer.

## 4. Sintetizzazione delle informazioni

**Data lezione**: 21/04/2021

L'informatizzazione ha obbligato a modificare il modo con cui vengono comunicate le informazioni. Internet ha apportato una maggiore comunicazione, spesso fino ad arrivare ad un eccesso. Viene sempre più richiesta oggigiorno una sintetizzazione delle informazioni anche facendo uso di immagini.

### 4.1. Modifica della comunicazione

Una volta si tendeva a comunicare senza delle regole ben precise, l'importante era che l'informazione arrivasse in qualche modo. Oggi è diverso: se inviassi un'email con i caratteri scritti tutti in maiuscolo (su Internet ha il significato di urlare) il messaggio risulterebbe fastidioso aldilà delle informazioni che contiene. È importante quindi anche il modo di comunicare.

Un tipo di scrittura a mano può comunicare qualcosa a chi legge, mentre un testo digitale di per sé è asettico. È importante quindi scegliere un carattere giusto rispetto al contesto: un invito ad una festa elegante richiederà un tipo di carattere differente rispetto a un invito ad una festa per bambini. Scegliere un tipo di carattere arzigogolato solo perché sembra bello a noi può invece inficiare la leggibilità di chi legge.

### 4.2. Informazioni tramite immagini

Le informazioni vengono sempre più spesso veicolate tramite un sistema digitale, ma la tendenza degli ultimi tempi è quella di spostarsi verso una sintetizzazione tramite immagini, un'**iconografia**.

Le icone di uno smartphone rappresentano le applicazioni che possiamo usare. Esse trasmettono un'informazione istantaneamente, per esempio il simbolo di una persona che corre già ci comunica la funzionalità dell'applicazione che ci aspettiamo di trovare.

A seconda del contesto possiamo usare differenti tipi di immagini. Una foto raffigurante una persona che corre sulla spiaggia ci porta una serie di informazioni che magari sono rivolte più a un pubblico maschile o femminile o atletico. Mentre l'immagine stilizzata di una persona che corre all'interno di un'icona ci porta direttamente l'informazione senza messaggi ulteriori.

Le icone si stanno sintetizzando ulteriormente rispetto al passato in modo che l'informazione arrivi in maniera ancor più immediata. Anche su sistemi diversi (es. *Apple*, *Android*) un utente è in grado di riconoscere certi simboli universali, come una cornetta per telefonare.

### 4.3. Infografiche

Quando viene fatta una presentazione al pubblico, spesso si usano delle slide per accompagnare quello che viene esposto in modo che l'informazione venga recepita meglio. Ma certe volte le slide vengono utilizzate in modo sbagliato, per esempio utilizzando slide piene di testo scritto. Non ha molto senso mettere grandi quantità di testo da leggere mentre l'interlocutore sta parlando, non aiuta molto la comunicazione.

Anche certi articoli pubblicati sul web con testi esageratamente lunghi difficilmente verranno letti. Non è un tipo di comunicazione basato su strumenti di vecchio stampo.

In questi casi le **infografiche** sono degli utili strumenti. Rappresentano le informazioni tramite grafici con testo molto ridotto, in modo che i concetti vengano sintetizzati e resi più leggibili.

![Esempio di infografica](immagini/infografica-esempio.jpg)

[Freepik](https://www.freepik.com/): sito per risorse grafiche

Creare un'infografica del genere richiede generalmente un discreto impiego di programmi di grafica, anche se esistono alcuni strumenti che ci permettono di creare infografiche semplici. L'importante è riuscire a collegare piccole informazioni a elementi grafici in modo da far arrivare il concetto molto rapidamente.

*PowerPoint* è tra gli strumenti più tipicamente utilizzati per fare infografiche non troppo complesse, ma in generale si può usare anche *Word*.

Per creare un'infografica serve:

1. definire gli obiettivi dell'infografica, es. quante persone vaccinate in un territorio
1. raccolta dei dati per l'infografica, es. dati dei vaccinati
1. visualizzare i dati nell'infografica, cioè dare un'impostazione grafica e logica ai dati
1. strutturare gli elementi del design, collegando dati a descrizioni
1. dare uno stile al design dell'infografica, in modo che sia gradito a chi la vede

Questa serie di passaggi testuali può essere sintetizzata proprio da un'infografica:

![Infografica creata con Word](immagini/infografica-word.png)

### 4.4. PowerPoint

***PowerPoint*** è un software che utilizza delle **diapositive** (o **slide**) per raggruppare i contenuti. Qualsiasi concetto voglia inserire in *PowerPoint* devo organizzarlo in un collage di diapositive, in modo da potersi spostare da una all'altra a seconda dell'argomento trattato in aula.

Possiamo scegliere una dimensione delle diapositive adatte per la proiezione, ma esistono anche dimensioni più adatte per la stampa cartacea sebbene lo scopo della presentazione sia generalmente la proiezione su schermo.

Una **casella di testo** rappresenta un contenitore di testo che possiamo inserire nella diapositiva. Oltre a testo possiamo inserire immagini, forme, grafici. Possiamo mettere una serie di immagini una sopra l'altra e possiamo scegliere l'ordine di sovrapposizione. Le ***SmartArt*** ci permettono di creare velocemente piccole infografiche.

Trascinando un'immagine da un angolo possiamo allargare o ridurre l'immagine mantenendo il rapporto altezza/larghezza originale dell'immagine, mentre trascinandola di lato l'immagine non mantiene il rapporto e viene deformata.

Si possono applicare animazioni su certi elementi (es. un'immagine) e transizioni tra una slide e l'altra. Non sono obbligatorie, ma se fatte bene attirano l'attenzione su un elemento particolare della nostra slide aiutando la comunicazione.

## 5. Internet

Per **Internet** si intende un insieme di computer e dispositivi collegati tra loro. Nello specifico una parte della memoria interna di quel dispositivo è collegato a Internet. È il principio di condivisione.

I computer che offrono i servizi Internet come il web, chiamati **server**, sono continuamente collegati a Internet. La prima arcaica versione di Internet fu creata per scopi militari e si chiamava *ARPAnet*. Poi Internet venne diffusa tra le università, ma allora era possibile scambiarsi solo piccoli messaggi date le ridotte capacità dei calcolatori. 

### 5.1. WWW

Solo a partire dagli anni '90 ci fu una rivoluzione conosciuta come il **WWW** (World Wide Web). Un WWW (spesso abbreviato in **web**) è un'insieme di cartelle all'interno delle quali sono inserite altre cartelle. Ciascun **sito** è una cartella del web all'interno della quale troviamo le **pagine**. I siti Internet quindi funzionano come le cartelle all'interno di un computer.

Internet, oltre al WWW, permette di usufruire di altri servizi come la posta elettronica, l'instant messaging (le chat), le video conferenze.

Quando scrivo il nome di un sito, es. www.lorenzocristofori.it, un sistema automatico mi porta alla **pagina indice** del sito. Un sito è da considerare come un insieme di pagine, non esiste un sito senza pagine.

Le pagine sono collegate tra loro tramite un **link** (collegamento). I link possono essere **interni** (all'interno del mio sito) o **esterni** (portano a un sito diverso).

### 5.2. HTML

Le pagine sono create tramite un'insieme di linguaggi, in particolar modo l'**HTML** (HyperText Markup Language). Si tratta di semplice testo abbinato a una  serie di ***marker*** (chiamati **tag**) che definiscono come deve essere visualizzato quel testo. Non viene considerato come un vero linguaggio di programmazione ma piuttosto di marcazione, è un concetto leggermente diverso. 

I tag HTML iniziano con il simbolo di minore `<`, poi abbiamo il nome del tag e infine il simbolo di maggiore `>`, es `<html>`. Molti tag (ma non tutti) devono essere chiusi da qualche parte inserendo lo stesso tag ma con il simbolo `/` davanti al nome, es. `</html>`. All'interno di due tag aperto e chiuso mettiamo il contenuto che vogliamo.

Il tag `<html>` è il più importante perché definisce l'area all'interno della quale abbiamo il codice della nostra pagina. I file che contengono le pagine devono avere un estensione `.html`.

Anche se il nostro testo ha delle rientranze, queste vengono normalmente ignorate dall'HTML. È necessario avvisarlo che si vuole andare accapo per esempio inserendo un tag `<p>` che definisce un **paragrafo** di testo.

I tag possono avere degli **attributi** che ne definiscono le proprietà. La sintassi è `<tag attributo="valore">Testo</tag>`.

```html
<html>
<p align="center"><font color="red" size="10">Digital Skill</font></p>
<p>Teseo Formazione</p>
<img src="immagine.jpg">
</html>
```

In questo esempio abbiamo il codice per generare:

- un paragrafo di testo allineato al centro, con testo rosso e dimensione del testo `10`
- un paragrafo normale senza formattazione
- un'immagine (da notare che `<img>` non richiede tag di chiusura)

Il **browser**, cioè il programma che ci consente di visualizzare le pagine come *Chrome*, riceve questo codice e lo interpreta. Come si può vedere dal codice, le pagine *non* contengono le immagini, ma solo dei riferimenti ad esse. Un documento in *Word* invece integra l'immagine all'interno del documento stesso.

Si può vedere il codice HTML di una pagina cliccando col tasto destro su una pagina e poi su *Visualizza sorgente pagina* o similare.

<!--
Data: 26/04/2021
Nome file: ok
Apostrofi: ok
-->

<!--
Data: 26/04/2021
Grammatica: ok
Codice: ok
Sezioni e TOC: ok
Pagina: ok
-->

<!--
Data: 29/04/2021
Grammatica: ok
Sezioni e TOC: ok
Info corso: ok
-->
