Informatica da Autodidatta
=======================

> This document is an Italian translation of [TeachYourselfCS](https://teachyourselfcs.com), written by [Ozan Onay](https://twitter.com/oznova_) and [Myles Byrne](https://twitter.com/quackingduck).

Nota: questa guida è stata ampiamente aggiornata a maggio 2020. Per la versione precedente, [guarda qui](https://teachyourselfcs.com/2016/).

Se sei un ingegnere autodidatta o diplomato in un bootcamp, lo devi a te stesso per imparare l'informatica. Per fortuna, puoi concederti un'istruzione in Informatica di livello mondiale senza investire anni e una piccola fortuna in un corso di laurea .

Ci sono molte risorse là fuori, ma alcune sono migliori di altre. Non hai bisogno di un altro elenco di "200+ corsi online gratuiti". Hai bisogno di risposte a queste domande:

- **Quali materie** dovresti imparare e perché?
- Qual è il **miglior libro o serie di videoconferenze** per ogni materia?

Questa guida è il nostro tentativo di rispondere definitivamente a queste domande.

TL;DR (Riassunto):
------------------

Studia tutti e nove gli argomenti qui di seguito, più o meno nell'ordine presentato, utilizzando il libro di testo o la serie di video suggeriti, ma idealmente entrambi. Prova a studiare 100-200 ore su ogni argomento, quindi rivedi i tuoi preferiti durante la tua carriera .

| Argomento | Perché studiarlo? | Libro | Video |
| --- | --- | --- | --- |
| **[Programmazione](#programmazione)** | Non essere la persona che "non ha mai capito" qualcosa, come per esempio la ricorsione. | *Structure and Interpretation of Computer Programs* | Berkeley CS 61A di Brian Harvey |
| **[Architettura del Computer](#architettura-del-computer)** | Se non hai un modello mentale solido di come funziona effettivamente un computer, tutte le tue astrazioni di livello superiore saranno fragili. | *Computer Systems: A Programmer's Perspective* | Berkeley CS 61C |
| **[Algoritmi e Strutture Dati](#algoritmi-e-strutture-dati)** | Se non sai come utilizzare strutture dati onnipresenti come stack, code, alberi e grafi, non sarai in grado di risolvere problemi complessi. | *The Algorithm Design Manual* | Le lezioni di Steven Skiena |
| **[Matematica per l'Informatica](#matematica-per-linformatica)** | Informatica è fondamentalmente una branca della matematica applicata, quindi l'apprendimento della matematica ti darà un vantaggio competitivo. | *Mathematics for Computer Science* | MIT 6.042J di Tom Leighton |
| **[Sistemi Operativi](#sistemi-operativi)** | La maggior parte del codice che scrivi è eseguito da un sistema operativo, quindi dovresti sapere come interagiscono. | *Operating Systems: Three Easy Pieces* | Berkeley CS 162 |
| **[Reti di Computer](#reti-di-computer)** | Internet si è rivelato un grosso problema: capire come funziona per sbloccare tutto il suo potenziale. | *Computer Networking: A Top-Down Approach* | Stanford CS 144 |
| **[Database](#database)** | I dati sono al centro dei programmi più significativi, ma pochi capiscono come funzionano effettivamente i sistemi di database. | *Readings in Database Systems* | Berkeley CS 186 di Joe Hellerstein |
| **[Linguaggi e Compilatori](#linguaggi-e-compilatori)** | Se capisci come funzionano effettivamente i linguaggi e i compilatori, scriverai codice migliore e imparerai nuovi linguaggi più facilmente. | *Crafting Interpreters* | Il corso di Alex Aiken su edX |
| **[Sistemi Distribuiti](#sistemi-distribuiti)** | Al giorno d'oggi, *la maggior parte* dei sistemi sono sistemi distribuiti. | *Designing Data-Intensive Applications* di Martin Kleppmann | MIT 6.824 |

Ancora troppo?
--------------

Se l'idea di studiare da solo 9 argomenti in più anni ti sembra travolgente, ti suggeriamo di concentrarti su due soli libri: *Computer Systems: A Programmer 's Perspective* e *Designing Data-Intensive Applications*. Nella nostra esperienza, questi due libri forniscono un ritorno incredibilmente elevato sul tempo investito, in particolare per ingegneri autodidatti e diplomati in un bootcamp che lavorano su applicazioni in rete. Possono anche fungere da "trampolino di lancio" per gli altri argomenti e risorse sopra elencati.

Perché imparare l'informatica?
------------------------------

Esistono 2 tipi di ingegneri del software: quelli che comprendono l'informatica abbastanza bene da svolgere un lavoro stimolante e innovativo e quelli che se la cavano semplicemente perché hanno familiarità con alcuni strumenti di alto livello.

Entrambi si definiscono ingegneri del software ed entrambi tendono a guadagnare stipendi simili nelle loro prime carriere. Ma gli ingegneri di tipo 1 progrediscono verso un lavoro più appagante e ben remunerato nel tempo, che si tratti di lavoro commerciale prezioso o progetti open source innovativi, leadership tecnica o contributi individuali di alta qualità.

Gli ingegneri di tipo 1 trovano modi per apprendere in profondità l'informatica, sia attraverso mezzi convenzionali che imparando incessantemente nel corso della loro carriera. Gli ingegneri di tipo 2 in genere rimangono in superficie, apprendendo strumenti e tecnologie specifici piuttosto che le loro basi sottostanti, acquisendo nuove competenze solo quando cambiano le mode tecnlogiche.

Attualmente, il numero di persone che entrano nel settore è in rapido aumento, mentre il numero di laureati in Informatica è relativamente fisso. Questo eccesso di offerta di ingegneri di tipo 2 sta iniziando a ridurre le loro opportunità di lavoro e a tenerli fuori dal lavoro più appagante del settore. Sia che tu stia cercando di diventare un ingegnere di tipo 1 o semplicemente cercando una maggiore sicurezza sul lavoro, l'apprendimento dell'informatica è l'unico percorso affidabile.

[![](https://teachyourselfcs.com/bilotta-tweet.png)](https://twitter.com/jenna/status/838161631662092289)

Guida agli argomenti
---------------

### Programmazione

La maggior parte dei programmi di Informatica universitari inizia con una "introduzione" alla programmazione. Le migliori versioni di questi corsi si rivolgono non solo ai principianti, ma anche a coloro che hanno tralasciato concetti e modelli di programmazione utili mentre imparavano a programmare per la prima volta.

La nostra raccomandazione standard per questo contenuto è la classica *Structure and Interpretation of Computer Programs*, disponibile online gratuitamente sia come [un libro](https://mitpress.mit.edu/sites/default/files/sicp/full-text/book/book.html), che come un insieme di [videolezioni del MIT](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/). Sebbene queste lezioni siano fantastiche, il nostro suggerimento video è in realtà [le lezioni SICP di Brian Harvey](https://archive.org/details/ucberkeley-webcast-PL3E89002AA9B9879E?sort=titleSorter) (per il corso 61A a Berkeley). Questi sono più sofisticati e meglio mirati ai nuovi studenti rispetto alle lezioni del MIT.

Raccomandiamo di lavorare almeno sui primi tre capitoli di SICP e di fare gli esercizi. Per ulteriore pratica, lavora su una serie di piccoli problemi di programmazione come quelli su [exercism](http://exercism.io/).

Da quando questa guida è stata pubblicata per la prima volta nel 2016, una delle domande più frequenti è stata se raccomandiamo ora le registrazioni di un'iterazione più recente di 61A insegnata da John DeNero e/o il libro corrispondente *[Composing Programs](https ://composingprograms.com/)*, che è "nella tradizione di SICP" ma usa Python. Pensiamo che anche le risorse di DeNero siano ottime, e alcuni studenti potrebbero finire per preferirle, ma suggeriamo comunque le lezioni di SICP, Scheme e Brian Harvey come prima serie di risorse da provare.

Perché? Perché SICP è unico nella sua capacità—almeno potenzialmente—di alterare le tue convinzioni fondamentali sui computer e sulla programmazione. Non tutti sperimenteranno questa alterazione. Alcuni odieranno il libro, altri non andranno oltre le prime pagine. Ma il potenziale guadagno ricompensa lo sforzo.

Se non ti piace SICP, prova *Composing Programs*. Se ancora non ti soddisfa, prova *[How to Design Programs](http://www.htdp.org/)*. Se nessuno di questi sembra premiare il tuo sforzo, forse è un segno che dovresti concentrarti su altri argomenti per un po' di tempo e rivedere la disciplina della programmazione tra un anno o due.

Infine, una precisazione: questa guida NON è pensata per chi è completamente alle prime armi con la programmazione. Partiamo dal presupposto che tu sia un programmatore competente senza un background in Informatica, che cerca di colmare alcune lacune nelle conoscenze. Il fatto che abbiamo incluso una sezione sulla "programmazione" è semplicemente un promemoria che potrebbe esserci altro da imparare. Per coloro che non hanno mai programmato prima, ma che lo vorrebbero, potresti preferire una guida come [questa](https://www.reddit.com/r/learnprogramming/wiki/faq#wiki_getting_started).

[![Structure and Interpretation of Computer Programs](https://teachyourselfcs.com/sicp.jpg)](https://mitpress.mit.edu/sites/default/files/sicp/full-text/book/book.html)

### Architettura del Computer

L'architettura del computer—a volte chiamata "sistemi informatici" o "organizzazione computazionale"—è un importante primo sguardo all'informatica sotto la superficie del software. Nella nostra esperienza, è l'area più trascurata tra gli ingegneri del software autodidatti.

Il nostro libro introduttivo preferito è *[Computer Systems: A Programmer's Perspective](http://csapp.cs.cmu.edu/3e/home.html)* e una tipica introduzione all'architettura dei computer che utilizza il libro [coprirebbe](http://csapp.cs.cmu.edu/3e/courses.html) la maggior parte dei capitoli 1-6.

Adoriamo CS:APP per l'approccio pratico e orientato ai programmatori. Sebbene ci sia molto di più nell'architettura dei computer rispetto a ciò che è trattato nel libro, serve come un ottimo punto di partenza per coloro che desiderano comprendere i sistemi informatici principalmente per scrivere *software* più veloce, più efficiente e più affidabile.

Per coloro che preferiscono sia un'introduzione più leggera all'argomento sia un equilibrio tra problemi hardware e software, suggeriamo *Gli elementi dei sistemi informatici*, noto anche come "Nand2Tetris". Questo è un libro ambizioso che cerca di darti una comprensione coerente di come tutto funzioni in un computer. Ogni capitolo prevede la costruzione di una piccola parte del sistema complessivo, dalla scrittura di porte logiche elementari in HDL, attraverso una CPU e un assemblatore, fino a un'applicazione delle dimensioni di un gioco di Tetris.

Consigliamo di leggere i primi sei capitoli del libro e di completare i progetti associati. Questo svilupperà la tua comprensione della relazione tra l'architettura della macchina e il software che gira su di essa.

La prima metà del libro (e tutti i suoi progetti) sono disponibili gratuitamente sul [sito web di Nand2Tetris] (http://www.nand2tetris.org/). È anche disponibile [un corso Coursera con video di accompagnamento](https://www.coursera.org/learn/build-a-computer).

Nella ricerca della semplicità e della coesione, Nand2Tetris rinuncia alla profondità. In particolare, due concetti molto importanti nelle moderne architetture dei computer sono il pipelining e la gerarchia della memoria, ma entrambi sono per lo più assenti dal testo.

Una volta che ti senti a tuo agio con il contenuto di Nand2Tetris, ti suggeriamo di tornare a CS:APP o di prendere in considerazione *[Computer Organization and Design](https://smile.amazon.com/Computer-Organization-Design-Fifth-Architecture/dp/0124077269)* di Patterson e Hennessy, un ottimo testo ormai classico. Non tutte le sezioni del libro sono essenziali; suggeriamo di seguire il [corso CS61C](http://inst.eecs.berkeley.edu/~cs61c/sp15/) di Berkeley "Great Ideas in Computer Architecture" per letture specifiche. Le dispense e i laboratori sono disponibili online e le lezioni passate sono [su Internet Archive](https://archive.org/details/ucberkeley-webcast-PL-XXv-cvA_iCl2-D-FS5mk0jFF6cYSJs_).

[![Computer Systems: A Programmer's Perspective](https://teachyourselfcs.com/csapp.jpg)](http://csapp.cs.cmu.edu/3e/home.html)

> L'hardware è la piattaforma

*-- Mike Acton, Engine Director presso Insomniac Games\
([guarda il suo discorso al CppCon](https://www.youtube.com/watch?v=rX0ItVEVjHc))*

### Algoritmi e Strutture Dati

Siamo d'accordo con decenni di saggezza comune che la familiarità con algoritmi e strutture dati comuni è uno degli aspetti più abilitanti di un'educazione informatica. Questo è anche un ottimo posto per allenare le proprie capacità generali di risoluzione dei problemi, che ripagheranno in ogni altra area di studio.

Ci sono centinaia di libri disponibili, ma il nostro preferito è *[The Algorithm Design Manual](https://smile.amazon.com/Algorithm-Design-Manual-Steven-Skiena/dp/1848000693/)* di Steven Skiena. Ama chiaramente la risoluzione dei problemi algoritmica e in genere riesce a promuovere un entusiasmo simile tra i suoi studenti e lettori. A nostro avviso, i due testi suggeriti più comunemente (CLRS e Sedgewick) tendono ad essere un po' troppo densi di prove per coloro che imparano il materiale principalmente per aiutare con la risoluzione pratica dei problemi.

Per coloro che preferiscono le videoconferenze, [Skiena offre generosamente i suoi online](https://www3.cs.stonybrook.edu/~skiena/373/videos/). Ci piace molto anche il corso di Tim Roughgarden, disponibile [su Coursera](https://www.coursera.org/specializations/algorithms) e [altrove](http://timroughgarden.org/videos.html). Se preferisci lo stile di lezione di Skiena o di Roughgarden sarà una questione di preferenze personali. In effetti, ci sono dozzine di buone alternative, quindi se ti capita di trovarne un'altra che ti piace, ti incoraggiamo a seguirla!

Per la pratica, il nostro approccio preferito è che gli studenti risolvano i problemi su [Leetcode](https://leetcode.com/). Questi tendono ad essere problemi interessanti con soluzioni e discussioni di accompagnamento rispettabili. Ti aiutano anche a testare i progressi rispetto alle domande comunemente utilizzate nei colloqui tecnici presso le società di software più competitive. Ti suggeriamo di risolvere circa 100 problemi di leetcode casuali come parte dei tuoi studi.

Infine, consigliamo vivamente *[How to Solve It](https://smile.amazon.com/How-Solve-Mathematical-Princeton-Science/dp/069116407X/)* come guida eccellente e unica per la risoluzione dei problemi generali; è applicabile all'informatica quanto alla matematica.

[![The Algorithm Design Manual](https://teachyourselfcs.com/skiena.jpg)](https://smile.amazon.com/Algorithm-Design-Manual-Steven-Skiena/dp/1848000693/) [![How to Solve It](https://teachyourselfcs.com/polya.jpg)](https://smile.amazon.com/How-Solve-Mathematical-Princeton-Science/dp/069116407X/)

> Ho solo un metodo che consiglio ampiamente—si chiama pensa prima di scrivere.

*— Richard Hamming*

### Matematica per l'Informatica

In un certo senso, l'informatica è un ramo troppo cresciuto della matematica applicata. Sebbene molti ingegneri del software provino—e in vari gradi ci riescano—a ignorarlo, ti incoraggiamo ad abbracciarlo con lo studio diretto. Farlo con successo ti darà un enorme vantaggio competitivo rispetto a coloro che non lo fanno.

L'area più rilevante della matematica per l'Informatica è generalmente chiamata "matematica discreta", dove "discreta" è l'opposto di "continuo" ed è vagamente una raccolta di interessanti argomenti di matematica applicata al di fuori del calcolo. Data la definizione vaga, non ha senso cercare di coprire l'intera ampiezza della "matematica discreta". Un obiettivo più realistico è quello di costruire una comprensione pratica di logica, combinatoria e probabilità, teoria degli insiemi, teoria dei grafi e un po' della teoria dei numeri relativa alla crittografia. L'algebra lineare è un'ulteriore area di studio utile, data la sua importanza nella computer grafica e nell'apprendimento automatico.

Il nostro punto di partenza suggerito per la matematica discreta è l'insieme di [appunti delle lezioni di László Lovász](http://www.cs.elte.hu/~lovasz/dmbook.ps). Il professor Lovász ha fatto un buon lavoro nel rendere il contenuto accessibile e intuitivo, quindi questo serve come punto di partenza migliore rispetto a testi più formali.

Per una trattazione più avanzata, suggeriamo *[Mathematics for Computer Science](https://web.archive.org/web/20210504123148/https://courses.csail.mit.edu/6.042/spring17/mcs.pdf)*, gli appunti delle lezioni dell'omonimo corso MIT. Anche le videolezioni di quel corso sono [disponibili gratuitamente](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-fall-2010/video-lectures/), e sono le nostre videoconferenze consigliate per la matematica discreta.

Per l'algebra lineare, suggeriamo di iniziare con la serie di video [Essence of linear algebra](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab), seguita dal [libro](https://www.amazon.com/Introduction-Linear-Algebra-Gilbert-Strang/dp/0980232775/) di Gilbert Strang e le sue [video lezioni](https://ocw.mit.edu/courses/mathematics/18-06-linear-algebra-spring-2010/video-lectures/).

> Se le persone non credono che la matematica sia semplice, è solo perché non si rendono conto di quanto sia complicata la vita.

*— John von Neumann*

### Sistemi Operativi

*[Operating System Concepts](https://www.amazon.com/dp/1118063333/)* (il "libro dei Dinosauri") e *[Modern Operating Systems](https://www.amazon.com/dp/013359162X/)* sono i libri "classici" sui sistemi operativi. Entrambi hanno attirato critiche per la loro mancanza di chiarezza e la generale ostilità verso gli studenti.

*Operating Systems: Three Easy Pieces* è una buona alternativa [disponibile gratuitamente online](http://pages.cs.wisc.edu/~remzi/OSTEP/). Ci piace particolarmente la struttura e la leggibilità del libro e riteniamo che gli esercizi valgano la pena.

Dopo OSTEP, ti invitiamo a esplorare le decisioni di progettazione di sistemi operativi specifici, attraverso libri in stile "Parti interne di {Nome Sistema Operativo}" come *[Lions' Commentary on Unix](https://www.amazon.com/Lions-Commentary-Unix-John/dp/1573980137/)*, *[The Design and Implementation of the FreeBSD Operating System](https://www.amazon.com/Design-Implementation-FreeBSD-Operating-System/dp/0321968972/)* e *[MAC OS X Internals](https://www.amazon.com/Mac-OS-Internals-Systems-Approach/dp/0321278542/)*. Per Linux, suggeriamo il fantastico [Linux Kernel Development](https://www.amazon.com/Linux-Kernel-Development-Robert-Love/dp/0672329468) di Robert Love.

Un ottimo modo per consolidare la tua comprensione dei sistemi operativi è leggere il codice di un piccolo kernel e aggiungere funzionalità. Una scelta è [xv6](https://pdos.csail.mit.edu/6.828/2016/xv6.html), una trasposizione di Unix V6 su ANSI C e x86, mantenuto per un corso al MIT. OSTEP ha un'appendice di potenziali [laboratori xv6](http://pages.cs.wisc.edu/~remzi/OSTEP/lab-projects-xv6.pdf) piena di grandi idee per potenziali progetti.

[![Operating Systems: Three Easy Pieces](https://teachyourselfcs.com/ostep.jpeg)](http://pages.cs.wisc.edu/~remzi/OSTEP/)

### Reti di Computer

Dato che gran parte dell'ingegneria del software si trova su server e client Web, una delle aree di maggior valore dell'informatica è il networking. I nostri studenti autodidatti che studiano metodicamente il networking scoprono di comprendere finalmente termini, concetti e protocolli da cui erano stati circondati per anni.

Il nostro libro preferito sull'argomento è *[Computer Networking: A Top-Down Approach](https://smile.amazon.com/Computer-Networking-Top-Down-Approach-7th/dp/0133594149/)*. Vale la pena fare i piccoli progetti ed esercizi nel libro, e ci piacciono particolarmente i "Laboratori di Wireshark", che hanno [fornito generosamente online](http://www-net.cs.umass.edu/wireshark-labs/).

Per coloro che preferiscono le lezioni video, suggeriamo il *[Introduction to Computer Networking](https://www.youtube.com/playlist?list=PLvFG2xYBrYAQCyz4Wx3NPoYJOFjvU7g2Z)* di Stanford precedentemente disponibile tramite la piattaforma MOOC di Stanford Lagunita, ma purtroppo ora disponibile solo come playlist non ufficiali su Youtube.

> Non puoi guardare nella sfera di cristallo e vedere il futuro. Ciò che Internet diverrà nel futuro sarà plasmato dalla società.

*— Bob Kahn*

[![Computer Networking: A Top-Down Approach](https://teachyourselfcs.com/top-down.jpg)](https://smile.amazon.com/Computer-Networking-Top-Down-Approach-7th/dp/0133594149/)

### Database

Ci vuole più lavoro per imparare da soli sui sistemi di database rispetto alla maggior parte degli altri argomenti. È un campo di studi relativamente nuovo (cioè dopo gli anni '70) con forti incentivi commerciali affinché le idee rimangano a porte chiuse. Inoltre, molti autori di libri di testo potenzialmente eccellenti hanno preferito unirsi o avviare aziende.

Date le circostanze, incoraggiamo gli autodidatti a evitare generalmente i libri di testo e iniziare con [registrazioni di CS 186](https://www.youtube.com/user/CS186Berkeley/videos), il corso sui database di Joe Hellerstein a Berkeley e progredire per poi leggere gli articoli.

Un documento particolarmente degno di nota per i nuovi studenti è "[Architecture of a Database System](http://db.cs.berkeley.edu/papers/fntdb07-architecture.pdf)", che fornisce in modo univoco una visione di alto livello di come funzionano i sistemi di gestione di database relazionali (RDBMS). Questo servirà come base utile per ulteriori studi.

*Readings in Database Systems*, meglio conosciuto come [il "Libro Rosso" dei database](http://www.redbook.io/), è una raccolta di articoli compilati e modificati da Peter Bailis, Joe Hellerstein e Michael Stonebraker. Per coloro che sono andati oltre il livello del contenuto CS 186, il Libro Rosso dovrebbe essere la prossima tappa.

Se sei irremovibile sull'utilizzo di un libro di testo introduttivo, ti suggeriamo *[Database Management Systems](https://smile.amazon.com/Database-Management-Systems-Raghu-Ramakrishnan/dp/0072465638/)* di Ramakrishnan e Gehrke. Per gli studenti più avanzati, il classico di Jim Gray *[Transaction Processing: Concepts and Techniques](https://www.amazon.com/Transaction-Processing-Concepts-Techniques-Management/dp/1558601902)* è utile, ma non t incoraggiare l'uso di questo come prima risorsa.

Infine, la modellazione dei dati è un aspetto trascurato e poco insegnato del lavoro con i database. Il nostro libro suggerito sull'argomento è *[Data and Reality: A Timeless Perspective on Perceiving and Managing Information in Our Imprecise World](https://www.amazon.com/Data-Reality-Perspective-Perceptive-Information/dp/1935504215)*.

[![Readings in Database Systems](https://teachyourselfcs.com/redbook.jpg)](http://www.redbook.io/) [![Data and Reality](https://teachyourselfcs.com/data-reality.jpg)](https://www.amazon.com/Data-Reality-Perspective-Perceiving-Information/dp/1935504215)

### Linguaggi e Compilatori

La maggior parte dei programmatori imparano i linguaggi, mentre la maggior parte degli scienziati informatici imparano *a proposito* dei linguaggi. Questo dà allo scienziato informatico un netto vantaggio rispetto al programmatore, anche nel campo della programmazione! La loro conoscenza si generalizza; sono in grado di comprendere il funzionamento di un nuovo linguaggio in modo più profondo e rapido di coloro che hanno semplicemente appreso linguaggi specifici.

Il nostro testo introduttivo suggerito è l'eccellente *[Crafting Interpreters](https://craftinginterpreters.com/contents.html)* di Bob Nystrom, disponibile gratuitamente online. È ben organizzato, molto divertente e adatto a coloro il cui obiettivo principale è semplicemente comprendere meglio i propri linguaggi e dei relativi strumenti. Ti suggeriamo di dedicare del tempo alla lettura dell'intero libro, tentando qualsiasi delle "sfide" che sostengano il tuo interesse.

Una raccomandazione più tradizionale è *[Compilers: Principles, Techniques, and Tools](https://smile.amazon.com/Compilers-Principles-Techniques-Tools-2nd/dp/0321486811)*, comunemente chiamato "Il libro del Drago". Sfortunatamente, non è progettato per lo studio autonomo, ma piuttosto per gli istruttori che scelgono 1-2 semestri di argomenti per i loro corsi.

Se scegli di utilizzare il libro del Drago, è quasi essenziale scegliere accuratamente gli argomenti, idealmente con l'aiuto di un mentore. In effetti, il nostro modo suggerito per utilizzare il libro del Drago, se lo desideri, è come riferimento supplementare per una serie di conferenze video. Il nostro consigliato è di [Alex Aiken, su edX](https://www.edx.org/course/compilers).

[![Compilers: Principles, Techniques, and Tools](https://teachyourselfcs.com/dragon.jpg)](https://smile.amazon.com/Compilers-Principles-Techniques-Tools-2nd/dp/0321486811)

> Non essere un programmatore standard. Invece, crea strumenti per utenti e altri programmatori. Prendi nota storica delle industrie tessili e siderurgiche: vuoi costruire macchine e strumenti o vuoi far funzionare quelle macchine?

*— Ras Bodik all'inizio del suo corso di compilatori*

### Sistemi Distribuiti

Poiché i computer sono aumentati di numero, si sono anche *diffusi*. Mentre in precedenza le aziende acquistavano mainframe sempre più grandi, ora è tipico che anche applicazioni molto piccole vengano eseguite su più macchine. I sistemi distribuiti è lo studio di come ragionare sui compromessi della loro implementazione.

Il nostro libro suggerito per l'autoapprendimento è *[Designing Data-Intensive Applications](https://smile.amazon.com/Designing-Data-Intensive-Applications-Reliable-Maintainable-ebook/dp/B06XPJML5D/)* di Martin Kleppmann. Molto meglio di un libro di testo tradizionale, DDIA è un libro altamente leggibile progettato per i professionisti, che in qualche modo evita di sacrificare profondità o rigore.

Per coloro che cercano un testo più tradizionale o che preferirebbero uno disponibile gratuitamente online, suggeriamo *[Distributed Systems, 3a edizione](https://www.distributed-systems.net/index.php/books/ds3/)* di Maarten van Steen e Andrew Tanenbaum.

Per chi preferisce il video, un ottimo corso con video disponibili online è [MIT's 6.824](https://www.youtube.com/watch?v=cQP8WApzIQQ&list=PLrw6a1wE39_tb2fErI4-WkMbsvGQk9_UB), un corso di laurea tenuto da Robert Morris con letture disponibili [qui](https://pdos.csail.mit.edu/6.824/schedule.html).

Indipendentemente dalla scelta del libro di testo o di altre risorse secondarie, lo studio dei sistemi distribuiti impone assolutamente la lettura di articoli. Una buona lista è [qui](http://dsrg.pdos.csail.mit.edu/papers/), e raccomandiamo vivamente di partecipare al gruppo nella tua zona di [Papers We Love](http://paperswelove.org/).

[![Designing Data-Intensive Applications](https://teachyourselfcs.com/ddia.jpg)](https://smile.amazon.com/Designing-Data-Intensive-Applications-Reliable-Maintainable-ebook/dp/B06XPJML5D/)

Domande frequenti
-----------------

#### Chi è il pubblico ideale di questa guida?

Abbiamo in mente che sei un ingegnere del software autodidatta, un diplomato in un bootcamp o uno studente di liceo precoce, o uno studente universitario che cerca di integrare la sua istruzione formale con uno studio autonomo. La domanda su quando intraprendere questo viaggio è del tutto personale, ma la maggior parte delle persone tende a trarre vantaggio dall'avere una certa esperienza professionale prima di immergersi troppo in profondità nella teoria dell'Informatica. Ad esempio, notiamo che gli studenti *adorano* conoscere i sistemi di database se hanno già lavorato con i database a livello professionale, o le reti di computer se hanno lavorato su uno o due progetti web.

#### Che dire di AI/grafica/tema-alla-moda-X?

Abbiamo cercato di limitare la nostra lista agli argomenti di informatica che riteniamo *ogni ingegnere del software professionista* dovrebbe conoscere, indipendentemente dalla specializzazione o dal settore, ma con un focus sui sistemi. Nella nostra esperienza, questi saranno gli argomenti con il ROI (ritorno di investimento) più elevato per la stragrande maggioranza degli ingegneri autodidatti e dei diplomati in un bootcamp e forniranno una solida base per ulteriori studi. Successivamente, sarai in una posizione molto migliore per prendere libri di testo o articoli e apprendere i concetti fondamentali senza molto aiuto. Ecco i nostri punti di partenza suggeriti per un paio di "corsi a scelta" comuni:

- Per l'Intelligenza Artificiale: fai [L'introduzione di Berkeley al corso di Intelligenza Artificiale](http://ai.berkeley.edu/) guardando i video e completando gli eccellenti progetti Pacman. Come libro di testo, usa *Intelligenza artificiale: un Approccio Moderno* di Russell e Norvig.
-   Per il Machine Learning: segui il corso Coursera di Andrew Ng. Sii paziente e assicurati di aver compreso i fondamenti prima di precipitarti su nuovi brillanti argomenti come il deep learning.
- Per la Computer Grafica: esamina il materiale [Berkeley's CS 184](http://inst.eecs.berkeley.edu/~cs184/fa12/onlinelectures.html) e utilizza [Computer Grafica: Principi e Pratica](https://www.amazon.com/Computer-Graphics-Principles-Practice-3rd/dp/0321399528) come libro di testo.

#### Quanto è rigorosa la sequenza suggerita?

Realisticamente, tutti questi argomenti hanno una notevole quantità di sovrapposizioni e si riferiscono ciclicamente l'uno all'altro. Prendiamo ad esempio la relazione tra matematica discreta e algoritmi: imparare prima la matematica ti aiuterebbe ad analizzare e comprendere i tuoi algoritmi in modo più approfondito, ma imparare prima gli algoritmi fornirebbe maggiore motivazione e contesto per la matematica discreta. Idealmente, tornerai su questi argomenti molte volte durante la tua carriera.

In quanto tale, la nostra sequenza suggerita è principalmente lì per aiutarti *solo per iniziare*... se hai una ragione convincente per preferire una sequenza diversa, allora fallo. I "prerequisiti" più significativi a nostro avviso sono: l'architettura del computer prima dei sistemi operativi o dei database e il networking e i sistemi operativi prima dei sistemi distribuiti.

#### Come si paragona con i corsi di Open Source Society o freeCodeCamp?

Quando questa guida è stata scritta per la prima volta nel 2016, la [guida OSS](https://github.com/open-source-society/computer-science) aveva troppi argomenti, suggeriva risorse inferiori per molti di essi e non forniva alcuna motivazione o indicazioni sul perché o su quali aspetti di particolari corsi sono preziosi. Ci siamo sforzati nel limitare il nostro elenco di corsi a quelli che *davvero dovresti conoscere* come ingegnere del software, indipendentemente dalla tua specialità, e per aiutarti a capire perché ogni corso è stato incluso. Negli anni successivi, la guida OSS è migliorata, ma continuiamo a pensare che questa fornisca un percorso più chiaro e coeso.

freeCodeCamp si concentra principalmente sulla programmazione, non sull'informatica. Per sapere perché potresti voler imparare l'informatica, vedi [sopra](#perch%C3%A9-imparare-linformatica). Se non conosci la programmazione, ti suggeriamo di dare la priorità a questa e di tornare a questa guida tra un anno o due.

#### E il linguaggio X?

L'apprendimento di un particolare linguaggio di programmazione è su un piano completamente diverso dall'apprendimento di un'area dell'informatica—l'apprendimento di un linguaggio è molto *più facile* e molto *meno prezioso*. Se conosci già un paio di linguaggi, ti consigliamo vivamente di seguire semplicemente la nostra guida e di adattare l'acquisizione del linguaggio negli spazi vuoti o di lasciarla per dopo. Se hai imparato bene la programmazione (ad esempio attraverso *Struttura e Interpretazione dei Programmi per Computer*), e soprattutto se hai imparato i compilatori, dovresti impiegare poco più di un fine settimana per imparare gli elementi essenziali di un nuovo linguaggio, dopodiché può conoscere le librerie/gli strumenti/l'ecosistema sul lavoro.

#### E la tecnologia di tendenza X?

Nessuna singola tecnologia è così importante che imparare a usarla dovrebbe essere una parte fondamentale della tua formazione. D'altra parte, è fantastico che tu sia entusiasta di conoscere questa cosa. Il trucco è lavorare a ritroso dalla particolare tecnologia al campo o concetto sottostante e impararlo in profondità prima di vedere come la tua tecnologia alla moda si inserisce nel quadro più ampio.

#### Perché stai ancora consigliando SICP?

Provala. Alcune persone trovano il SICP strabiliante, una caratteristica condivisa da pochissimi altri libri. Se non ti piace, puoi sempre provare qualcos'altro e magari tornare a SICP più tardi.

#### Perché stai ancora raccomandando il libro del Drago?

Il libro del Drago è ancora la risorsa singola più completa per i compilatori. Ha un po' di cattiva reputazione, in genere per enfatizzare eccessivamente determinati argomenti che sono meno di moda da trattare in dettaglio in questi giorni, come l'analisi. Il fatto è che il libro non è mai stato concepito per essere studiato dall'inizio alla fine, solo per fornire materiale sufficiente a un istruttore per mettere insieme un corso. Allo stesso modo, un autodidatta può scegliere la propria avventura attraverso il libro, o meglio ancora seguire i suggerimenti che i docenti dei corsi pubblici hanno dato nei loro schemi di corso.

#### Come posso ottenere libri di testo a buon mercato?

Molti dei libri di testo che proponiamo sono disponibili gratuitamente online, grazie alla generosità dei loro autori. Per coloro che non lo sono, suggeriamo di acquistare copie usate di edizioni precedenti. Come regola generale, se ci sono state più di un paio di edizioni di un libro di testo, è molto probabile che un'edizione precedente sia perfettamente adeguata. È certamente improbabile che la versione più recente sia 10 volte migliore di una precedente, anche se questa è la differenza di prezzo!

#### Chi ha scritto questa guida?

Questa guida è stata originariamente scritta da [Oz Nova](https://twitter.com/oznova_) e [Myles Byrne](https://twitter.com/quackingduck), con gli aggiornamenti del 2020 di Oz. Si basa sulla nostra esperienza nell'insegnamento dell'informatica di base a oltre 1000 ingegneri per lo più autodidatti e diplomati in un bootcamp in piccoli gruppi a San Francisco e dal vivo online. Grazie a tutti i nostri studenti per il vostro continuo feedback sulle risorse di autoapprendimento.

Siamo molto fiduciosi che tu possa imparare tutto quanto riportato sopra, supponendo che ci sia abbastanza tempo e motivazione. Ma se preferisci un programma intensivo, strutturato e guidato da un istruttore, potresti essere interessato al nostro [Intensivo di Informatica] (https://bradfieldcs.com/csi/). Noi [NON](https://ozwrites.com/masters/) suggeriamo di ottenere un master.

Per aggiornamenti a questa guida e notizie e risorse di informatica generale, potresti anche iscriverti alla mailing list di Bradfield nella pagina di [teachyourselfcs](https://teachyourselfcs.com/#field_0).

#### Chi ha tradotto questa guida?

La versione Italiana di questa guida è stata tradotta da [Fabio Cicerchia](https://fabiocicerchia.it), per renderla disponibile a tutti coloro che ne hanno bisogno. Spero di essere stato utile a chi sta leggendo.

Sentiti libero di contattarmi per suggerimenti, correzioni o qualsiasi motivo.

Buono Studio!
