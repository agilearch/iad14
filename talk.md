[](#)[](#)

<table>
<col width="33%" />
<col width="33%" />
<col width="33%" />
<tbody>
<tr class="odd">
<td align="left"><p>Slide</p></td>
<td align="left"><p>Arialdo</p>
<p></p></td>
<td align="left"><p>Nicola</p></td>
</tr>
<tr class="even">
<td align="left"><p>1</p></td>
<td align="left"><p>Ciao! Questo sarà un talk un po’ particolare, perché cercheremo di sostenere due tesi diametralmente opposte.</p>
<p>Io sono Arialdo, e reciterò la parte dell’enterprise architect</p></td>
<td align="left"><p></p></td>
</tr>
<tr class="odd">
<td align="left"><p></p></td>
<td align="left"><p></p></td>
<td align="left"><p>Io sono Nicola, e proverò ad difendere la posizione di un architetto agile.</p></td>
</tr>
<tr class="even">
<td align="left"><p>2</p></td>
<td align="left"><p></p>
<p></p>
<p></p></td>
<td align="left"><p>Mi piacerebbe iniziare con una citazione di Martin Fowler:</p>
<p></p>
<p>“Perfino secondo gli standard della nostra industria i termini &quot;architetto&quot; ed &quot;architettura&quot; sono parole terribilmente sovraccaricate di significati”</p>
<p></p></td>
</tr>
<tr class="odd">
<td align="left"><p>3</p></td>
<td align="left"><p>È vero. Credo sarebbe utile, prima di confrontarci, metterci d'accordo su un significato comune di “architettura”.</p>
<p></p>
<p>E cosa c’è di meglio della definizione di IEEE, che è riconosciuta a livello internazionale?</p>
<p></p>
<p>&quot;L'architettura è il più alto livello concettuale di un sistema nel proprio ambiente&quot;.</p>
<p></p>
<p>La definizione aggiunge</p>
<p></p>
<p>“L’Architettura di un sistema software, in un dato istante, è la sua organizzazione o la struttura dei suoi componenti più significativi, i quali interagiscono attraverso interfacce”</p>
<p></p>
<p>Che ne dici?</p>
<p></p>
<p></p></td>
<td align="left"><p></p>
<p></p>
<p></p>
<p></p>
<p></p>
<p></p>
<p></p>
<p></p>
<p></p>
<p></p>
<p></p>
<p></p>
<p></p>
<p></p></td>
</tr>
<tr class="even">
<td align="left"><p>4</p></td>
<td align="left"><p></p></td>
<td align="left"><p></p>
<p>Eh, che ti dico? Che forse è proprio questo il punto! Già in partenza non siamo d'accordo sulla definizione.</p>
<p></p>
<p>Mi sembra che la definizione di IEEE faccia riferimento a qualcosa che trascende la professione dello sviluppatore, che richiede una sorta di illuminazione, un livello di concetto più alto</p>
<p></p></td>
</tr>
<tr class="odd">
<td align="left"><p>5</p></td>
<td align="left"><p>Sì, credo sia proprio così. Ti propongo questa riflessione, che mi trova molto d'accordo:</p>
<p></p>
<p>&quot;Per assicurare l'integrità concettuale è necessario che esista un pensiero centrale, forse anche perché l’architetto ritiene che i membri del team non abbiano sufficiente competenza per prendere tutte le decisioni. Spesso, queste decisioni devono essere prese con larghissimo anticipo, e l’obiettivo dell’architetto è di fornire a tutti un piano da seguire”</p>
<p></p>
<p></p></td>
<td align="left"><p></p></td>
</tr>
<tr class="even">
<td align="left"><p>6</p></td>
<td align="left"><p></p></td>
<td align="left"><p>Un piano da seguire, dici?</p>
<p>L’architettura come una ricetta alla quale attenersi?</p>
<p></p>
<p>“La qualità di una torta si valuta assaggiandola.</p>
<p>L’aderenza alla ricetta è una metrica molto debole”</p>
<p></p></td>
</tr>
<tr class="odd">
<td align="left"><p>7</p></td>
<td align="left"><p>Non di meno, converrai che una ricetta serva. O lo neghi?</p>
<p></p>
<p>Guarda, se dobbiamo confrontarci a citazioni, senti questa:</p>
<p></p>
<p>“Costruire un sistema enterprise di grandi dimensioni e complessità senza un Enteprise Architect è come tentare di costruire una città senza un piano regolatore.</p>
<p>È possibile costruire una città senza<sup><a href="#cmnt1">[a]</a></sup><sup><a href="#cmnt2">[b]</a></sup> un piano?</p>
<p>Probabilmente.</p>
<p>Ma tu in quella città ci andresti a vivere?</p>
<p>Probabilmente no.</p>
<p></p>
<p>Ovviamente, un architetto che disegni un piano regolatore non garantisce una città vivibile: semplicemente ne aumenta le probabilità.”</p>
<p></p>
<p></p></td>
<td align="left"><p></p></td>
</tr>
<tr class="even">
<td align="left"><p></p></td>
<td align="left"><p></p></td>
<td align="left"><p>Qui facebook</p></td>
</tr>
<tr class="odd">
<td align="left"><p>8</p></td>
<td align="left"><p></p></td>
<td align="left"><p>Ma, metafora a parte, vorrei portare il confronto su un altro campo.</p>
<p></p>
<p>Partiamo dal fatto che,  soprattutto nell’ultimo decennio, le critiche verso la gestione centralizzata e formale dell’architettura non sono mancate.</p>
<p></p>
<p>Leggi qui:</p>
<p></p>
<p>Negli ultimi anni, nel mondo, l’introduzione di “Enterprise Architecture” è stata un’iniziativa che ha coinvolto la maggioranza delle istituzioni finanziarie (banche, compagnie di assicurazione, governi eccetera), e il processo di adozione è tutt’ora in corso. Io ho lavorato con queste aziende, ed le ho aiutate ad evitare gli errori piu gravi. Ecco: la maggioranza delle iniziative Enterprise Architecture ha fallito. Io stimo che in più del 90% dei casi non sia sia realizzato niente di utile.”</p>
<p></p>
<p>Ci crederesti? Questa è una frase di Ivar Jacobson, uno degli autori di UML e di RUP.</p></td>
</tr>
<tr class="even">
<td align="left"><p>9</p></td>
<td align="left"><p></p></td>
<td align="left"><p>Ma, vedi? Jacobson non è il solo a muovere critiche alla definizione di IEEE.</p>
<p>Senti questa, a proposito dell’alto livello concettuale del sistema e sui suoi componenti più significativi”</p>
<p></p>
<p></p>
<p>“Non esiste “il più alto livello concettuale” di un sistema. Clienti e sviluppatori hanno una visioni differenti del sistema. Per esempio, ai clienti importa ben poco della struttura dei componenti software.</p>
<p>Ecco, forse l’architettura può essere intersa come “il più alto livello concettuale” che *gli sviluppatori* hanno del sistema.</p>
<p></p>
<p>Cos’è che rende un componente “significativo?” Solo il fatto che uno sviluppatore lo trovi significativo.“</p>
<p></p>
<p>Capisci cosa intenda?</p>
<p>Non è possibile predefinire cosa faccia parte dell’architettura e cosa no.</p>
<p></p>
<p>In un’applicazione bancaria 3-tier il database potrebbe essere una componente molto significativa dell’architettura.</p>
<p> </p>
<p>E contemporaneamnente, in un’applicazione che elabori immagini mediche, può darsi che lo stesso identico database non venga incluso nell’architettura, perché la maggior parte della complicazione sta nell’elaborazione delle immagini, non nella loro persistenza: caricare e salvare le immagini sarà una responsabilità demandata ad uno strato del software che la maggioranza degli sviluppatori tenderà ad ignorare.</p>
<p></p>
<p>Che voglio dire con questo? Che l’architettura ha molto più a che fare con la conoscenza condivisa, con una visione comune.</p>
<p></p>
<p>L’architettura è molto più un costrutto sociale che tecnico o tecnologico.</p>
<p></p>
<p></p></td>
</tr>
<tr class="odd">
<td align="left"><p>10</p></td>
<td align="left"><p></p></td>
<td align="left"><p>E permettimi di farti notare quante volte, parlando di architettura, questa frase citi il termine &quot;developer&quot;. Dopo tutto, sembra che l'architettura sia un argomento che dovrebbe interessare i developer, direttamente.</p></td>
</tr>
<tr class="even">
<td align="left"><p></p></td>
<td align="left"><p>Ok, molto romantico. Scommetto che questa frase sia di uno dei guru di agile, uno di quelli che occupano i palcoscenici delle conferenze raccontando che i manager sono inutili, che il mondo è dei developer e che tutti dovremmo iniziare ad  abbracciare gli alberi. Vero?</p></td>
<td align="left"><p></p></td>
</tr>
<tr class="odd">
<td align="left"><p></p></td>
<td align="left"><p></p></td>
<td align="left"><p>No: è di Ralph Johnson, della Gang Of Four, uno degli autori di Design Patterns.</p>
<p></p>
<p>E tu sai benissimo quanto nel mondo Agile i design pattern siano amati.</p>
<p></p>
<p>E non è che Ralph Johnson parli a caso: è stato uno dei revisori ufficiali della definizione di IEEE di architettura</p></td>
</tr>
<tr class="even">
<td align="left"><p>11</p></td>
<td align="left"><p>Ok, capisco. Senti, firmiamo una tregua e la smettiamo di farci citazioni?</p>
<p></p>
<p>Parliamo piuttosto che quello che tu proponi, in alternativa ad Enterprise Architecture: le pratiche Agile che, in qualche modo, propugnano l’idea di una struttura organizzativa più piatta.</p>
<p></p>
<p>L'idea che avanzi è molto intrigante, sono il primo a dirlo. Quello che trovo un po' fastidioso, ti confesso, è che a volte ho l'impressione che queste idee propagandate da Agile siano un po' naive: fanno sognare, fanno riferimento a principi molto democratici e accattivanti.</p>
<p></p>
<p>Ora, non so te, ma io non scelgo una metodologia in funzione di quanto mi piaccia e quanto appaghi il mio ego.</p>
<p></p>
<p>Sicché, anche se è un po' meno trend, preferisco basare le mie scelte su proposizioni scientifiche. Quindi ti domando, qual è il fondamento scientifico di quel che sostieni?</p>
<p></p>
<p>Ti voglio spiegare perché credo che sia necessario un livello di astrazione architetturale.</p>
<p></p>
<p>Conosci il Modello Dreyfus Di Acquisizione Delle Competenze&quot;?</p>
<p></p>
<p>È stato<sup><a href="#cmnt3">[c]</a></sup> ideato negli anni 80 da due docenti californiani, e non è una cosa puramente teorica: anzi, ha avuto un grande impatto, misurabile, in campo infermieristico e aziendale, in tutto il mondo.</p>
<p></p>
<p>Secondo questo modello, quando affrontiamo un problema nuovo, passiamo attraverso cinque fasi.</p>
<p></p>
<p> Inizialmente ci limitiamo ad applicare meccanicamente le regole.</p>
<p>Poi, piano piano, acquisiamo autonomia, e finiamo perfino per abbandonare le regole e affidarci all’intuito.</p>
<p></p>
<p>Guarda: alla base della piramide c'è il Novizio. Il Novizio aderisce alle regole. Gli si dice cosa fare, e lui esegue.</p>
<p></p>
<p>Sopra c’è il Principiante: segue le regole, come il Novizio, ma inizia a collegare le regole alle caratteristiche delle situazioni in cui vanno applicate.</p>
<p>È il caso del programmatore Junior che può affrontare da solo lo sviluppo di un componente se ha specifiche chiare, ma non è in grado di progettarlo da zero in autonomia.</p>
<p></p>
<p>Poi ci sono i Competenti: persone capaci di gestire la complessità, di scindere vari fattori anche quando interagiscono tra loro. Persone capaci di comprendere le conseguenze a lungo termine delle proprie azioni, pur senza coglierne tutte le implicazioni.</p>
<p></p>
<p>Sopra ci sono i Proficient: sono tecnici che affontano il problema con una prospettiva differente, con un approccio olistico e sistemico. Gente che guardando l’albero vede l’intera foresta.</p>
<p></p>
<p>Poi ci sono gli Esperti, che adottano un approccio largamente intuitivo e ricorrono a mezzi analitici solo all'occorrenza, in situazioni nuove.</p>
<p></p>
<p>Ecco, i compiti di un architetto richiedono quel livello.</p>
<p></p>
<p>L'idea che non ci sia bisogno di ruoli specifici, che in fondo si sia tutti uguali è molto romantica, ma manca di fondamento scientifico e rischia di essere molto naive.</p></td>
<td align="left"><p></p></td>
</tr>
<tr class="odd">
<td align="left"><p></p></td>
<td align="left"><p></p></td>
<td align="left"><p>Ok.</p>
<p>È evidente che partiamo da basi molto differenti.</p>
<p></p>
<p>Possiamo riassumere dicendo che facciamo riferimento a due figure molto differenti di Architetto?</p></td>
</tr>
<tr class="even">
<td align="left"><p>12</p></td>
<td align="left"><p>Sì. Il mio architetto è la persona che prende le decisioni importanti, quelle di più alto livello. Chiamiamolo Architectus Reloadus</p></td>
<td align="left"><p></p></td>
</tr>
<tr class="odd">
<td align="left"><p>13</p></td>
<td align="left"><p></p></td>
<td align="left"><p>Chiamiamo il mio Architectus Ozyrus.</p>
<p></p>
<p>Il mio architetto non così interessato a prendere le decisioni importanti.  </p></td>
</tr>
<tr class="even">
<td align="left"><p>14</p></td>
<td align="left"><p></p></td>
<td align="left"><p>L’attività più importante dell’architetto Ozyrus è di fare da mentore al team, perché ognuno possa raggiungere il livello di competenza che gli permetta di affrontare, in autonomia, problemi più complessi.</p>
<p></p>
<p>Consentire al team di aumentare le proprie abilità permette all’architetto di liberarsi dall’imcombenza di essere il solo decision maker ed elimina il rischio di divenire il collo di bottiglia dell’intero processo.</p>
<p></p></td>
</tr>
<tr class="odd">
<td align="left"><p>15</p></td>
<td align="left"><p></p></td>
<td align="left"><p>La metafora che mi sembra più appropriata è quella proposta da Mike Two: l’architetto è come una guida alpina; è la persona più skillata, che può insegnare agli altri membri come muoversi, ed è sempre disponibile per i momenti di maggiore difficoltà.</p>
<p></p></td>
</tr>
<tr class="even">
<td align="left"><p>16</p></td>
<td align="left"><p></p></td>
<td align="left"><p>In questo senso credo che il valore di un architetto sia inversamente proporzionale alla quantità di decisioni che è costretto a prendere.</p>
<p>In sostanza, l’architetto realizza il suo compito quando ha reso il team autonomo.</p></td>
</tr>
<tr class="odd">
<td align="left"><p>17</p></td>
<td align="left"><p>Quindi, è una figura che lavora per rendersi superflua?</p></td>
<td align="left"><p></p></td>
</tr>
<tr class="even">
<td align="left"><p></p></td>
<td align="left"><p></p></td>
<td align="left"><p>In un certo senso sì.</p></td>
</tr>
<tr class="odd">
<td align="left"><p>18</p></td>
<td align="left"><p>Mi sembra molto fumoso e un po’ distante dalle esigenze delle aziende enterprise, ma ne colgo il senso.</p>
<p></p>
<p>Diciamo che il mio architetto sul piano operativo è meno impegnato del tuo. Magari è più interessato a creare una visione comune, declinata dalla scelte di business.</p>
<p></p>
<p>Forse non è presente nelle singole scalate e lascia questo compito a degli alpini professionisti. Ecco, diciamo che il mio architetto è quello che si preoccupa di fornire alla spedizione una cartina dettagliata ed affidabile.</p>
<p></p>
<p>La tua guida è indispensabile ma, ecco, non offenderti, ma senza una mappa porterà (con grande esperienza) l’intera spedizione verso la direzione sbagliata.</p>
<p></p>
<p>Sai perché credo che un lavoro di design up-front sia davvero molto importante?</p></td>
<td align="left"><p></p></td>
</tr>
<tr class="even">
<td align="left"><p>19</p></td>
<td align="left"><p>Perché ci sono delle decisioni che desideri vengano prese per tempo, in un progetto, prima che diventi troppo tardi scoprire di aver impostato male il lavoro.</p>
<p>Ecco: quello è il compito dell’architetto: aiutare a definire quegli aspetti del design che sono più costosi da cambiare, in corso d’opera</p></td>
<td align="left"><p></p></td>
</tr>
<tr class="odd">
<td align="left"><p>20</p></td>
<td align="left"><p></p></td>
<td align="left"><p>Probabilmente hai toccato il punto:x puoi vedere i metodi agili come quei sistemi che consentono di contenere la complessità, riducendo l’irreversibilità.</p>
<p></p></td>
</tr>
<tr class="even">
<td align="left"><p>21</p></td>
<td align="left"><p>Di nuovo, mi sembra un po’ troppo vago.</p>
<p>È dal 1980 che Barry Boehm ha dimostrato, supportato da ampie statistiche, che il costo del software aumenta nel tempo.</p>
<p>Modificare il software in fase di analisi è molto più economico che farlo in fase di sviluppo. Una volta arivati alla produzione il costo diventa spesso proibitivo.</p>
<p>Molto meglio individuare un problema nei requisiti, prima che il danno si manifesti in produzione.</p>
<p>Pertanto, un’analisi up-front è un sistema per contenere i costi di gestione.</p></td>
<td align="left"><p></p></td>
</tr>
<tr class="odd">
<td align="left"><p>22</p></td>
<td align="left"><p></p></td>
<td align="left"><p>La scommessa di eXtreme Programming è proprio questa: se la curva di costo fosse più appiattita, ci comporteremmo in modo completamente diverso da come abbiamo sempre fatto. Cercheremmo di rimandare le decisioni al Last Responsible Moment, per massimizzare il tempo a disposizione per indagare il problema. Cercheremmo architetture semplici (KISS) senza l’ossessione di anticipare con i design pattern le esigenze del futuro.</p>
<p></p>
<p>Se la curva fosse piatta, conteremmo sul fatto che cambiare il codice il codice sia sempre economico, in fase di design come in produzione.</p>
<p></p>
<p>Appiattire la curva di costo è possibile, ma è un risultato che non arriva gratuitamente. C’è una serie di tecniche che permette di realizzare la magia: sono le tecniche che abilitano il codice ad essere trattato in modo agile: i test automatici ed il design che ne emerge (ad alta coesione e basso accoppiamento), il pairing, e così via.</p>
<p></p>
<p>Questa è la scommessa. E questo, capisci bene, cambia molto il ruolo dell’architetto, nel contesto dello sviluppo.</p></td>
</tr>
<tr class="even">
<td align="left"><p>23</p></td>
<td align="left"><p>Molto interessante. E mi torna. Non mi sembra, in effetti, che Enterprise Architecture, rifiuti tecniche come TDD.</p>
<p>Piuttosto, la domanda che mi pongo è: questo è sufficiente per far emergere un’architettura?</p>
<p>Si può essere eccellenti muratori e saper erigere case ineccepibili. Ma questo è sufficiente per realizzare una città vivibile, con una tangenziale senza ingorghi di traffico e con una bella architettura?</p>
<p></p>
<p>La domanda è: cosa proponiamo per costruire, debuggare e manutenere un sistema informatico grande e complesso?</p></td>
<td align="left"><p></p></td>
</tr>
<tr class="odd">
<td align="left"><p>24</p></td>
<td align="left"><p>Io suggerisco che si ricorra ad un’autorità, un esperto che possa occuparsi di architettare il sistema senza doversi occupare dei dettagli implementativi, perché è evidente che il suo tempo sarà particolarmente prezioso.</p>
<p>Fintanto che il team sarà in grado di seguire le linee guida, la qualità del sistema sarà assicurata.</p></td>
<td align="left"><p></p></td>
</tr>
<tr class="even">
<td align="left"><p>25</p></td>
<td align="left"><p></p></td>
<td align="left"><p>Io dico che questo approccio porta a rallentamenti e finger pointing. Con un sistema simile è chiaro che in una discussione chi avrà maggiore autorità uscirà sempre vincitore. Anzi, peggio: i developer verranno accusati di non essere bravi team player, solo per il fatto di aver contestato l’architetto</p></td>
</tr>
<tr class="odd">
<td align="left"><p>26</p></td>
<td align="left"><p></p></td>
<td align="left"><p>Piuttosto, propongo che l’architetto sia coinvolto anche nell’implementazione. È necessario che l’architetto sia costantemente informato sui cambiamenti e sul loro impatto sul design</p></td>
</tr>
<tr class="even">
<td align="left"><p>27</p></td>
<td align="left"><p>Esasperando le diversità degli approcci, mi sembra di capire che nodo della questione sia nel fatto che io propongo la figura di un architetto dedicato</p></td>
<td align="left"><p></p></td>
</tr>
<tr class="odd">
<td align="left"><p>28</p></td>
<td align="left"><p></p></td>
<td align="left"><p>E io una condivisione della responsabilità</p></td>
</tr>
<tr class="even">
<td align="left"><p>29</p></td>
<td align="left"><p>Il mio approccio pone maggiore focus sul design-upfront</p></td>
<td align="left"><p></p></td>
</tr>
<tr class="odd">
<td align="left"><p></p></td>
<td align="left"><p></p></td>
<td align="left"><p>Il mio su un’architettura evolutiva</p></td>
</tr>
<tr class="even">
<td align="left"><p>30</p></td>
<td align="left"><p>Oppure, per usare le parole del Manifesto Agile, io la Comprehensive Documentation</p></td>
<td align="left"><p></p></td>
</tr>
<tr class="odd">
<td align="left"><p></p></td>
<td align="left"><p></p></td>
<td align="left"><p>Io la concretezza il “working software”</p></td>
</tr>
<tr class="even">
<td align="left"><p></p></td>
<td align="left"><p>D’accordo.</p>
<p>Ecco, mi piacerebbe però mi spiegassi meglio il perché di tutta questa preoccupazione intorno al concetto che l’architetto sia aware, che “resti costantemente informato”.</p>
<p></p></td>
<td align="left"><p></p></td>
</tr>
<tr class="odd">
<td align="left"><p>31</p></td>
<td align="left"><p></p></td>
<td align="left"><p>Certo.</p>
<p>Voglio spiegartelo con gli Influence Diagram.</p>
<p>Considera il rapporto tra mangiare e prendere peso. Più mangio, più ingrasso. È una influenza positiva.</p>
<p>La rappresento così</p></td>
</tr>
<tr class="even">
<td align="left"><p>32</p></td>
<td align="left"><p></p></td>
<td align="left"><p>Il rapporto tra l’esercizio fisico e il peso è opposta. È un’influenza negativa. La rappresento aggiungendo un cerchio sulla freccia. D’accordo?</p></td>
</tr>
<tr class="odd">
<td align="left"><p>33</p></td>
<td align="left"><p></p></td>
<td align="left"><p>Ok. Qui ho rappresentato un circolo vizioso.</p>
<p>Parti dalla freccia che entra nel circolo.</p>
<p>Leggila così: più ingrasso, più perdo stima in me stesso; più perdo stima, più mangio.</p>
<p>Più mangio, più ingrasso.</p>
<p>E mi ritrovo all’ingresso del circolo visioso.</p></td>
</tr>
<tr class="even">
<td align="left"><p></p></td>
<td align="left"><p>Perché mi racconti questo?</p></td>
<td align="left"><p></p></td>
</tr>
<tr class="odd">
<td align="left"><p>34</p></td>
<td align="left"><p></p></td>
<td align="left"><p>Perché questo ha molto a che fare con i feedback che un architetto può ricevere. Fammici arrivare.</p>
<p>Qui ho rappresentato lo stesso identico circolo vizioso, ma ho usato dei termini che riguardano la gestione di un team. Leggilo così:</p>
<p></p>
<p>più pressioni imponi ad un team, meno test i developer produrranno; meno test avrai, più errori saranno presenti nel codice. E, con più errori, è evidente che sarai costretto a fare più pressioni, per far rispettare le scadenze</p></td>
</tr>
<tr class="even">
<td align="left"><p>35</p></td>
<td align="left"><p>D‘accordo</p></td>
<td align="left"><p></p></td>
</tr>
<tr class="odd">
<td align="left"><p></p></td>
<td align="left"><p></p></td>
<td align="left"><p>Ecco. Arriviamo al punto del perché l’architetto debba essere coinvolto anche nello sviluppo.</p>
<p>Questo diagramma di influenza descrive il tuo approccio:</p>
<p></p>
<p>L’architetto reloadus produce Documentazione. tanta più documentazione produce, tanto più lungo è il tempo che è necessario per ricevere un feedback. Maggiore è il tempo di attesa, maggiore è il costo che comporterà aver fatto scelte sbagliate.</p>
<p>E, tante più scelte sbagliate verranno fatte, tanto più sarà necessario produrre documentazione per evitarle.</p>
<p>Ma è un circolo vizioso!</p></td>
</tr>
<tr class="even">
<td align="left"><p></p></td>
<td align="left"><p>E tu cosa proponi in alternativa?</p></td>
<td align="left"><p></p></td>
</tr>
<tr class="odd">
<td align="left"><p>36</p></td>
<td align="left"><p></p></td>
<td align="left"><p>Di aggiungere tra i documenti e il team un’intensa collaborazione da parte dell’architetto.</p>
<p>Guarda: più collaborazione, significa molto feedback; e questo riduce le scelte errate. Meno scelte errate significa meno bisogno di documenti, e quindi più tempo a disposizione per un’intensa collaborazione.</p>
<p>Agile propone un circolo virtuoso!</p></td>
</tr>
<tr class="even">
<td align="left"><p>37</p></td>
<td align="left"><p>Quindi, qual è un’alternativa all’Enterprise Architecture?</p></td>
<td align="left"><p></p></td>
</tr>
<tr class="odd">
<td align="left"><p></p></td>
<td align="left"><p></p></td>
<td align="left"><p>“centralized governance”</p>
<p></p>
<p>Agile propone</p>
<p></p>
<p>“Individuals and interactions over processes and tools”</p>
<p></p>
<p>Spesso, al governo centralizzato si accompagna la tendenza a standardizzare e a convergere verso una singola piattaforma tecnologica.</p>
<p></p>
<p>Ma l’esperienza ci insegna che non tutti i problemi sono chiodi, e di conseguenza non tutte le soluzioni sono martelli.</p>
<p></p>
<p>Il trend, in questi anni, è di costruire sistemi organizzati come micro-service.</p>
<p></p>
<p>Molti team, piuttosto che affidarsi a standard scritti su qualche documento, da qualcuno sopra di loro, preferiscono produrre tool utili che altri sviluppatori possano usare per risolvere problemi simili.</p>
<p></p>
<p>Nascono le API, e insieme a loro delle comunità.</p>
<p></p>
<p>Amazon è il caso più eclatante.</p>
<p></p>
<p></p>
<p></p>
<p></p>
<p></p></td>
</tr>
<tr class="even">
<td align="left"><p>38</p></td>
<td align="left"><p>Mi trovi molto d’accordo.</p>
<p>E penso sia molto curioso che tu concluda citando Amazon.</p>
<p>Perché, se ricordi il famoso post di Steve Yegge ricorderai che Amazon è passata da essere un e-commerce di libri a una piattaforma di API per la decisione, illuminata, di un architetto visionario e autoritario.</p>
<p></p>
<p>Probabilmente, se si fosse aspettato che Amazon diventasse una immensa Service Oriented Company, per l’intervento dei suoi singoli sviluppatori, come architettura emergente, oggi non avremmo il Cloud di Amazon.</p>
<p></p>
<p>Ma è bello vedere che le nostre visioni, apparentemente così distanti, abbiano alla fine così tanti punti di contatto.</p></td>
<td align="left"><p></p></td>
</tr>
<tr class="odd">
<td align="left"><p></p></td>
<td align="left"><p></p></td>
<td align="left"><p>Sì. Voi cosa ne pensate? Ne parliamo?</p></td>
</tr>
</tbody>
</table>

[[a]](#cmnt_ref1)qui alexander: le città non evolvono

[[b]](#cmnt_ref2)Immagine di Facebook, prima (apache + php) e dopo (cloud immenso)

[[c]](#cmnt_ref3)Rendere più conciso, troooopo lungo!!
