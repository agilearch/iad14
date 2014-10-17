[](#)[](#)

<table border="1" bordercolor="#cccccc" cellpadding="4" cellspacing="0">
	<col width="10%" />
	<col width="45%" />
	<col width="45%" />
	<thead>
		<tr class="odd">
			<td align="left">
				<p>#</p></td>
			<td align="left">
				<h2>Arialdo</h2></td>
			<td align="left">
				<h2>Nicola</h2></td>
		</tr>
	</thead>
	<tbody>
		<tr class="even">
			<td align="left"><p>1</p></td>
			<td align="left">
				<p>
					Ciao!
					Questo sar&agrave; un talk un po' particolare, perch&egrave; cercheremo
					di sostenere due tesi diametralmente opposte.</p>
				<p>
					Io sono Arialdo, e reciter&ograve; la parte dell'<strong>enterprise architect</strong>.</p></td>
			<td></td>
		</tr>
		<tr class="odd">
			<td></td>
			<td></td>
			<td align="left">
				<p>Io sono Nicola, e prover&ograve; a vestire i panni dell'<strong>agile architect</strong>.</p>
				<p>Senti, se sei d'accordo io romperei il ghiaccio con una citazione di Fowler:</p>
				<p><em>&quot;Perfino secondo gli standard della nostra industria i termini 'architetto' ed 'architettura' sono parole terribilmente sovraccaricate di significati&quot;</em></p></td>
		</tr>
		<tr class="odd">
			<td align="left"><p>3</p></td>
			<td align="left">
				<p>
					&Egrave; vero.
					Credo sarebbe utile, prima dar luogo al confronto, trovare un accordo su un significato comune di &quot;architettura&quot;.
					<br />
					Ebbene, secondo IEEE, la cui autorit&agrave; non credo avrai il coraggio di mettere in discussione,
					propone questa:</p>
				<p>
					<em>&quot;L'architettura &egrave; il pi&ugrave; alto livello concettuale di un sistema nel proprio ambiente&quot;</em>.</p>
				<p>La definizione aggiunge:</p>
				<p>
					<em>&quot;L'architettura di un sistema software, in un dato istante, 
					&egrave; la sua organizzazione o la struttura dei suoi componenti pi&ugrave;
					significativi, i quali interagiscono attraverso interfacce&quot;</em>.</p>
				<p>Cosa dici, ti ritrovi in questa definizione?</p></td>
			<td></td>
		</tr>
		<tr class="even">
			<td align="left"><p>4</p></td>
			<td align="left"></td>
			<td align="left">
				<p>
					No, Arialdo. Siamo gi&agrave; in disaccordo in questa fase preliminare.
					<br />
					Cio&egrave;, io trovo che la definizione proposta da IEEE faccia riferimento a
					qualcosa che arrivi addirittura <strong>trascendere</strong> la professione dello
					sviluppatore.
					Insomma, da come me la descrivi, sembra che l'architettura rappresenti lo stadio
					finale nel suo processo evolutivo!</p></td>
		</tr>
		<tr class="odd">
			<td align="left"><p>5</p></td>
			<td align="left">
				<p>
					S&igrave;, siamo di diverso avviso gi&agrave; sulla definizione.
					Senti, ti propongo questa riflessione, che mi trova molto d'accordo:</p>
				<p>
					&quot;<em>Per garantire l'<strong>integrit&agrave; concettuale</strong> &egrave;
					necessario un pensiero centrale&quot;</em>.
					<br />
					(Questo non deve necessariamente essere
					a carico di una singola persona; anzi, sarebbe auspicabile che tale pensiero
					fosse manifestato da una sorta di comitato.
					<br />
					<em>&quot;Tale esigenza nasce dal fatto che l'architetto ritiene che i membri di un team non
					abbiano maturato sufficienti competenze per assumere un certo tipo di decisioni.
					Spesso, queste devono essere prese con larghissimo anticipo, ragion per cui
					l'architetto deve essere in grado di fornire a tutti un <strong>piano</strong> da
					seguire.&quot;</em>.</p></td>
			<td></td>
		</tr>
		<tr class="even">
			<td align="left"><p>6</p></td>
			<td></td>
			<td align="left">
				<p>
					Un piano da seguire, dici?
					<br />
					Quindi, secondo te l'architettura &egrave; una ricetta alla quale attenersi
					scrupolosamente?</p>
				<p>
					<em>&quot;La qualit&agrave; di una torta la si valuta assaggiandola.
					<br />
					L'aderenza alla ricetta &egrave; una metrica molto debole&quot;</em>.</p></td>
		</tr>
		<tr class="odd">
			<td align="left"><p>7</p></td>
			<td align="left">
				<p>
					Non di meno, converrai che una ricetta sia necessaria.
					<br />
					Guarda, se il confronto deve esser portato avanti a suon di citazioni,
					allora ti propongo questa:</p>
				<p>
					<em>&quot;Costruire un sistema enterprise di grandi dimensioni e 
					complessit&agrave; senza un Enteprise Architect &egrave; come tentare 
					di costruire una citt&agrave; senza un piano regolatore&quot;</em>.</p>
				<p>
					&Egrave; possibile costruire una citt&agrave; senza 
					<sup><a href="#cmnt1">[a]</a> <a href="#cmnt2">[b]</a></sup> un piano?
					<br />
					Probabilmente.</p>
				<p>
					E tu andresti a vivere in quella citt&agrave;?
					<br />
					Probabilmente no.</p>
				<p>
					Ovviamente, un architetto che disegni un piano regolatore non
					garantisce una citt&agrave; vivibile: semplicemente, ne aumenta le
					probabilit&agrave;.</p></td>
			<td></td>
		</tr>
		<tr class="even">
			<td></td>
			<td></td>
			<td align="left">
				<p>
					Ok, hai tirato in ballo un'argomentazione interessante, sulla
					quale sento di poterti ribattere in maniera molto efficace.
					<br />
					Nella slide corrente ho cercato di mostrare l'evoluzione
					architetturale conosciuta da Facebook dai suoi albori ad oggi.
					Se, al contrario, applichiamo lo stesso ragionamento a, non so,
					l'<em>Empire State Building</em>, non sembrano delinearsi evoluzioni
					di particolar rilievo.
					<br />
					Forse, uno degli aspetti che maggiormente differenzionano l'architettura
					<em>tradizionale</em> da quella del software &egrave; che quest'ultimo
					deve essere pensato per <strong>evolvere</strong> nel futuro. Spesso,
					nell'<strong>immediato</strong> futuro!
					<br />
					E, mi dispiace, il garantire l'<em>integrit&agrave; concettuale</em>,
					come hai sostenuto in precedenza, non mi offre alcuna garanzia in tal
					senso!</p></td>
		</tr>
		<tr class="odd">
			<td align="left"><p>7 bis</p></td>
			<td></td>
			<td align="left">
				<p>
					Per concludere, voglio mettere sul piatto la questione legata alla
					<em>carenza di standard</em>.</p>
				<p style="color: red">
					<strong>[TODO: tradurre e mettere nelle slide: http://fyi.oreilly.com/2009/02/we-released-a-beautiful-book.html]</strong>
					<em>&quot;Building architects can look back at thousands of years of history
					to see what architects have done in the past;
					<br />
					In software we have only a few decades of history and our
					designs are often not public&quot;</em>.</p></td>
		</tr>
		<tr class="even">
			<td></td>
			<td align="left">
				<p>
					Mi fi piacere che tu abbia fatto menzione del caso &quot;Facebook&quot;.
					Quello che mi vuoi dire &egrave; che ci&ograve; che mi stati mostrando
					&egrave; il frutto di <em>design emergente</em> e di qualche ciclo di
					<em><font color="red">red</font>/<font color="green">green</font>/<font color="blue">refactoring</font></em>?</p>
				<p style="color: red">
					<strong>[TODO] Qu&igrave;, forse, l'architetto reloadus dovrebbe dire qualcosina in 
					pi&ugrave;</strong>.</p></td>
			<td></td>
		</tr>
		<tr class="odd">
			<td align="left"><p>8</p></td>
			<td></td>
			<td align="left">
				<p>
					No, naturalmente; ma questo non necessariamente va ad implicare che ci&ograve; sia da
					attribuirsi alla <em>centralizzazione del pensiero</em>.
					<br />
					Possiamo ritagliarci qualche minuto per parlare, appunto, di <em>centralizzazione</em>?
					Perch&egrave;, soprattutto nell'ultimo decennio, le critiche verso la gestione centralizzata e formale dell'architettura non sono certo mancate.
					Leggi quanto segue:</p>
				<p>
					<em>Negli ultimi anni, nel mondo, l'introduzione di &quot;Enterprise Architecture&quot; &egrave; stata un'iniziativa che ha coinvolto la maggioranza delle istituzioni finanziarie (banche, compagnie di assicurazione, governi eccetera), e il processo di adozione &egrave; tutt'ora in corso. Io ho lavorato con queste aziende, e le ho aiutate ad evitare gli errori pi&ugrave; gravi. Ecco: la maggioranza delle iniziative <strong>Enterprise Architecture</strong> ha fallito. Io stimo che in pi&ugrave; del 90% dei casi non sia sia realizzato niente di utile&quot;.</em></p>
				<p>
					Ci crederesti? Questa &egrave; una frase di <em>Ivar Jacobson</em>, uno degli autori
					di UML e di RUP.</p></td>
		</tr>
		<tr class="even">
			<td align="left"><p>9</p></td>
			<td></td>
			<td align="left">
				<p>
					Ma, vedi? Jacobson non &egrave; il solo a muovere critiche alla definizione di IEEE.
					Senti questa, a proposito dell'<em>alto livello concettuale del sistema e sui suoi componenti
					pi&ugrave; significativi</em>:</p>
				<p>
					<em>&quot;Non esiste <strong>il pi&ugrave; alto livello concettuale</strong> di un sistema.
					Clienti e sviluppatori hanno visioni differenti del medesimo.
					Ad esempio, ai clienti importa ben poco della struttura dei componenti software.
					<br />
					Ecco, forse l'architettura pu&ograve; essere intersa come <strong>il pi&ugrave; alto livello concettuale</strong> che <u><strong>gli sviluppatori</strong></u> hanno del sistema.
					<br />
					Cos'&egrave; che rende un componente <strong>significativo</strong>?
					Solo il fatto che uno sviluppatore <u>esperto</u> lo riconosca come tale&quot;</em>.</p>
				<p>
					Insomma, non &egrave; possibile predefinire cosa faccia parte o meno dell'architettura.
					<br />
					Prendi, ad esempio, una classica applicazione bancaria <em>3-tier</em>.
					Ipoteticamente, il database potrebbe rappresentare una componente molto significativa dell'architettura.
					<br />
					E, contemporaneamnente, in un'applicazione che elabori immagini mediche, pu&ograve;
					darsi che lo stesso identico database non venga incluso nell'architettura,
					perch&egrave; gran parte della complesit&agrave; &egrave; spostata sul fronte
					dell'elaborazione delle immagini, non nella loro persistenza: caricare e salvare
					le immagini sar&agrave; una responsabilit&agrave; demandata ad uno strato di
					software che la maggioranza degli sviluppatori tender&agrave; ad ignorare.</p>
				<p>
					Cosa voglio dire?
					<br />
					Che l'architettura ha molto pi&ugrave; a che fare con la conoscenza
					condivisa, con una visione comune.
					<br />
					L'architettura ha, in qualche modo, molte connotazioni &quot;sociali&quot;, oltre a
					quelle tecniche o tecnologiche.</p></td>
		</tr>
			<tr class="odd">
				<td align="left"><p>10</p></td>
				<td></td>
				<td align="left">
					<p>
						E permettimi di farti notare quanto la citazione che ti ho mostrato insista
						particolarmente sugli &quot;sviluppatori&quot;.
						Dopo tutto, sembra che l'architettura sia un argomento che dovrebbe coinvolgerli
						direttamente.</p></td>
		</tr>
			<tr class="even">
				<td></td>
				<td align="left">
					<p>
						Ok, molto romantico.
						Scommetto che l'autore di questa frase sia proprio uno di quei guru
						&quot;agile&quot;, uno di quelli che occupano i palcoscenici delle
						conferenze raccontando che i manager sono inutili, che il mondo
						&egrave; degli sviluppatori e che tutti dovremmo iniziare ad
						abbracciare gli alberi.
						<br />
						Mi sto sbagliando?</p></td>
				<td></td>
		</tr>
		<tr class="odd">
			<td></td>
			<td></td>
			<td align="left">
				<p>
					Beh, l'autore &egrave; <em>Ralph Johnson</em>, membro della <em>Gang Of Four</em>,
					uno degli autori della &quot;bibbia&quot; sui <em>Design Patterns</em>.</p>
				<p>
					Oltretutto, Johnson non sta parlando a &quot;ruota libera&quot;, poich&egrave;
					nell'occasione vestiva proprio i panni di revisore ufficiale della definizione di IEEE di
					<em>architettura</em>.</p></td>
		</tr>
		<tr class="even">
			<td align="left"><p>11</p></td>
			<td align="left">
				<p>
					Ok, capisco.
					<br />
					Senti, direi di sancire una tregua sulle citazioni. Sei d'accordo?
					<br />
					Parliamo, piuttosto, di quello che proponi tu in alternativa 
					ad <em>Enterprise Architecture</em>: delle pratiche <em>agile</em>; le quali, in qualche
					modo, propugnano l'idea di una struttura organizzativa sostanzialmente
					<em>appiattita</em>.
					<br />
					L'idea che avanzi &egrave; certamente molto intrigante, sono il primo ad ammetterlo.
					Quello che trovo un po' fastidioso, ti confesso, &egrave; che a volte ho
					l'impressione che queste idee propagandate da <em>agile</em> siano un po' naive:
					fanno sognare, fanno riferimento a principi molto democratici e accattivanti.
					<br />
					Ebbene, io scelgo una metodologia <strong>non</strong> in funzione di quanto
					mi piaccia o di quanto sia in grado di appagare il mio ego.
					<br />
					Sicch&egrave;, anche se un po' meno <em>trendy</em>, preferisco basare le mie
					scelte su proposizioni scientifiche. Quindi ti domando, qual &egrave; il
					fondamento scientifico di quello che sostieni?
					Cercher&ograve; quindi di motivarti la necessit&agrave; per il livello di
					astrazione al quale abbiamo accennato in precedenza.
					<br />
					Conosci il Modello Dreyfus di <em>&quot;Acquisizione Delle Competenze&quot;</em>?
					<br />
					&Egrave; stato <sup><a href="#cmnt3">[c]</a></sup> ideato nel corso degli anni
					80 da due docenti californiani, e non si tratta di qualcosa di puramente teorico:
					al contrario, ha avuto un grande impatto, misurabile sia in campo
					infermieristico che aziendale.
					<br />
					Secondo questo modello, quando affrontiamo un problema nuovo, passiamo
					attraverso cinque fasi.
					<br />
					Inizialmente ci limitiamo ad applicare meccanicamente le regole.
					<br />
					Poi, gradualmente, acquisiamo autonomia, e finiamo perfino per abbandonare
					le regole e affidarci all'intuito.
					<br />
					Guarda: alla base della piramide c'&egrave; il <em>novizio</em>. Egli aderisce
					alle regole. Gli si dice cosa deve fare, e lui si limita ad eseguire diligentemente.
					<br />
					Sopra abbiamo il <em>principiante</em>: segue le regole, come il <em>novizio</em>,
					ma inizia a collegarle alle caratteristiche delle situazioni in cui
					vanno applicate.
					&Egrave; il caso del programmatore <em>junior</em>, che pu&ograve; affrontare da
					solo lo sviluppo di un componente se dispone di specifiche chiare, ma non &egrave;
					in grado di progettarlo da zero in autonomia.
					<br />
					Poi ci sono i <em>competenti</em>: persone capaci di gestire la complessit&agrave;,
					di scindere vari fattori - anche quando interagiscono tra loro.
					Persone capaci di comprendere le conseguenze a lungo termine delle proprie azioni,
					pur senza coglierne tutte le implicazioni.
					<br />
					Arriviamo, poi, ai <em>proficient</em>: sono tecnici che affontano il problema
					con una prospettiva differente, con un approccio olistico e sistemico. Soggetti
					che, osservando l'albero, sono in grado di visualizzare l'intera foresta.
					<br />
					Infine, abbiamo gli <em>esperti</em>, che adottano un approccio largamente intuitivo
					e ricorrono a mezzi analitici solo all'occorrenza, in situazioni nuove.
					<br />
					Ecco, i compiti di un architetto richiedono tale livello.
					<br />
					L'idea secondo la quale non vi sia effettivo bisogno di ruoli specifici - che in
					fondo, di fronte alla complessit&agrave;, <em>siamo tutti uguali</em> - &egrave;
					molto romantica, ma manca di fondamento scientifico e rischia di apparire troppo
					naive.</p></td>
			<td></td>
		</tr>
		<tr class="odd">
			<td></td>
			<td></td>
			<td align="left">
				<p>
					Ok, a me pare evidente che partiamo da basi molto differenti.
					<br />
					Possiamo riassumere asserendo che facciamo riferimento a due figure
					molto differenti di <em>architetto</em>?</p></td>
		</tr>
		<tr class="even">
			<td align="left"><p>12</p></td>
			<td align="left">
				<p>
					S&igrave;, il mio architetto &egrave; la persona che prende le 
					decisioni importanti, quelle di pi&ugrave; alto livello.
					<br />
					Chiamiamolo <em>Architectus Reloadus</em>.</p></td>
			<td align="left"></td>
		</tr>
		<tr class="odd">
			<td align="left"><p>13</p></td>
			<td align="left"></td>
			<td align="left">
				<p>
					Chiamiamo il mio <em>Architectus Ozyrus</em>.
					<br />
					Il mio architetto non cos&igrave; interessato a prendere decisioni
					importanti.</p></td>
		</tr>
		<tr class="even">
			<td align="left"><p>14</p></td>
			<td></td>
			<td align="left">
				<p>
					L'attivit&agrave; pi&ugrave; importante dell'architetto <em>Ozyrus</em>
					consiste nel fungere da <em>mentore</em> per i team, in modo tale da consentire
					a ciascuno dei loro membri di raggiungere un livello di competenze tali da permettergli
					di affrontare autonomamente problematiche sempre pi&ugrave; complesse.
					<br />
					Incrementare le abilit&agrave; dei team consente all'architetto
					di svincolarsi dall'imcombenza di fungere da solo &quot;decision maker&quot; e
					rimuove il rischio di gravare sull'intero processo come &quot;collo di bottiglia&quot;.</p></td>
		</tr>
		<tr class="odd">
			<td align="left"><p>15</p></td>
			<td></td>
				<td align="left">
					<p>
						La metafora che mi sembra pi&ugrave; appropriata &egrave; quella proposta da
						<em>Mike Two</em>: l'architetto &egrave; come una &quot;guida alpina&quot;; &egrave;
						la persona pi&ugrave; skillata, che pu&ograve; insegnare agli altri membri come
						muoversi ed &egrave; sempre un riferimento nei momenti di maggior difficolt&agrave;.</p></td>
		</tr>
		<tr class="even">
			<td align="left"><p>16</p></td>
			<td></td>
			<td align="left">
				<p>
					In questo senso, credo che il valore di un architetto sia inversamente
					proporzionale alla quantit&agrave; di decisioni che &egrave;
					costretto a prendere.
					<br />
					In sostanza, l'architetto realizza il suo compito quando ha reso il
					team autonomo.
					<br />
					E, se ci pensi bene, &egrave; la medesima connotazione che James Shore
					attribuisce alla figura del <em>coach</em> nel libro <em>The Art of Agile
					Development</em>.</p></td>
		</tr>
		<tr class="odd">
			<td align="left"><p>17</p></td>
			<td align="left">
				<p>
					Quindi, mi stai parlando di una figura che si adopera per rendersi
					superflua?</p></td>
			<td></td>
		</tr>
		<tr class="even">
			<td></td>
			<td></td>
			<td align="left">
				<p>
					In un certo senso, s&igrave;.</p></td>
		</tr>
		<tr class="odd">
			<td align="left"><p>18</p></td>
			<td align="left">
				<p>
					A me appare tutto piuttosto fumoso e un po' distante dalle reali esigenze
					delle aziende enterprise, ma ne colgo il senso.
					<br />
					Diciamo che il mio architetto sul piano operativo &egrave; meno impegnato
					del tuo. Magari &egrave; pi&ugrave; interessato a creare una visione
					comune, declinata dalla scelte di business.
					<br />
					Forse non &egrave; presente nelle singole scalate e lascia questo compito a degli alpini professionisti.
					Ecco, diciamo che il mio architetto &egrave; quello che si preoccupa di fornire
					alla spedizione una cartina dettagliata ed affidabile.
					La tua guida &egrave; indispensabile ma - ecco, non offenderti - senza una
					mappa porter&agrave; l'intera spedizione a prendere una direzione sbagliata.
					<br />
					Sai perch&egrave; credo che un lavoro di design up-front sia davvero
					molto importante?</p></td>
			<td></td>
		</tr>
		<tr class="even">
			<td align="left"><p>19</p></td>
			<td align="left">
				<p>
					Perch&egrave; esistono delle decisioni che vanno prese
					con largo anticipo, prima che sia troppo tardi; prima di
					scoprire che le fondamenta sulle quali il progetto si reggeva
					erano incosistenti.
					<br />
					Ecco, quello &egrave; il compito dell'architetto: aiutare a
					definire quegli aspetti del design che sono pi&ugrave; costosi
					da cambiare in corso d'opera.</p></td>
			<td align="left"></td>
		</tr>
		<tr class="odd">
			<td align="left"><p>20</p></td>
			<td align="left"></td>
			<td align="left">
				<p>
					Probabilmente hai toccato il punto: puoi vedere le metodologie &quot;Agile&quot;
					come un mezzo volto al contenimento della complessit&agrave;, riducendo
					l'irreversibilit&agrave;.</p></td>
		</tr>
		<tr class="even">
			<td align="left"><p>21</p></td>
			<td align="left">
				<p>
					Di nuovo, mi sembra un po' troppo vago.
					<br />
					&Egrave; dal 1980 che <em>Barry Boehm</em> ha dimostrato, supportato da
					ampie statistiche, che il costo del software aumenta nel tempo.
					<br />
					Modificare il software in fase di analisi &egrave; molto pi&ugrave;
					economico che farlo in fase di sviluppo. Una volta arivati alla
					produzione il costo diventa spesso proibitivo.
					<br />
					Molto meglio individuare un problema nei requisiti, prima che il
					danno si manifesti in produzione.
					Pertanto, un'analisi up-front rappresenta uno strumento finalizzato
					al contenimento dei costi di gestione.</p></td>
			<td align="left"></td>
		</tr>
		<tr class="odd">
			<td align="left"><p>22</p></td>
			<td align="left"></td>
			<td align="left">
				<p>
					La scommessa di <em>eXtreme Programming</em> &egrave; proprio questa: se
					la curva di costo fosse pi&ugrave; appiattita, ci comporteremmo in modo
					completamente differente da come abbiamo sempre fatto.
					Cercheremmo di rimandare le decisioni al &quot;Last Responsible Moment&quot;,
					con il fine di massimizzare il tempo a disposizione per indagare il problema.
					<br />
					Se la curva si appiatisse, potremmo contare sul fatto che cambiare il codice
					si traduca in un'operazione sempre economico, in fase di design come
					in produzione.
					<br />
					Appiattire la curva dei costi &egrave; possibile, ma &egrave; un risultato
					che non arriva gratuitamente. Esistono una serie di tecniche che consentono
					di realizzare tale &quot;magia&quot;: mirano a ridurre l'accoppiamento,
					incrementare la coesione, tutelarsi da fenomeni di regressione e distribuire
					la conoscenza.
					<br />
					Questa &egrave; la scommessa. E questo, capisci bene, cambia molto il ruolo
					dell'architetto, nel contesto del processo di sviluppo.</p></td>
		</tr>
		<tr class="even">
			<td align="left"><p>23</p></td>
			<td align="left">
				<p>
					Ci mancherebbe, sono d'accordo. Ma, in effetti, non vedo come <em>Enterprise
					Architecture</em> possa rifiutare tecniche quali <em>Test-Driven Development</em>.
					<br />
					Piuttosto, la domanda che mi pongo &egrave;: questo &egrave; sufficiente per far emergere un'architettura?
					<br />
					Si pu&ograve; essere eccellenti muratori e saper erigere case ineccepibili.
					Ma questo &egrave; sufficiente per realizzare una citt&agrave; vivibile,
					con una tangenziale senza ingorghi di traffico e con una bella architettura?
					<br />
					Cosa proponiamo per costruire, debuggare e manutenere un ampio sistema informatico
					ad alto grado di complessit&agrave;?</p></td>
			<td></td>
		</tr>
		<tr class="odd">
			<td align="left"><p>24</p></td>
			<td align="left">
				<p>
					Io suggerisco che si ricorra ad un'autorit&agrave;, un esperto che possa
					occuparsi di congeniare il sistema senza doversi occupare dei dettagli
					implementativi, perch&egrave; &egrave; evidente che il suo tempo
					sar&agrave; particolarmente prezioso.
				<p style="color : red">
					<strong>
						[TODO: forse &egrave; il caso di far notare che, trattandosi di un &quot;esperto&quot;,
						&egrave; anche una persona pagata profumatamente. Non la si vuole &quot;sprecare&quot;
						in attivit&agrave; quali la scrittura del codice.]</strong></p>
				<p>
					Fintanto che il team sar&agrave; in grado di seguire le linee guida,
					la qualit&agrave; del medesimo verr&agrave; garantita.</p></td>
			<td></td>
		</tr>
		<tr class="even">
			<td align="left"><p>25</p></td>
			<td></td>
			<td align="left">
				<p>
					Al contrario, io ritengo che questo approccio porti a rallentamenti e <em>finger
					pointing</em>. Con un sistema simile &egrave; chiaro che, nell'ambito di in
					una discussione, chi avr&agrave; maggiore autorit&agrave; ne uscir&agrave;
					sempre vincitore. Anzi, peggio: gli sviluppatori verranno accusati di
					non essere buoni &quot;team player&quot;, solo perch&egrave; hanno contestato
					l'architetto</p></td>
		</tr>
		<tr class="odd">
			<td align="left"><p>26</p></td>
			<td></td>
			<td align="left">
				<p>
					Piuttosto, propongo che l'architetto sia coinvolto anche nell'implementazione.
					&Egrave; necessario che egli sia costantemente informato sui cambiamenti e sull'impatto
					che questi producono sul design.</p></td>
		</tr>
		<tr class="even">
			<td align="left"><p>27</p></td>
			<td align="left">
				<p>
					Esasperando le diversit&agrave; dei due approcci, mi sembra di capire che
					nodo della questione risieda nel fatto che io propongo la figura di
					un architetto <em>dedicato</em></p></td>
			<td></td>
		</tr>
		<tr class="odd">
			<td align="left"><p>28</p></td>
			<td></td>
			<td align="left">
				<p>
					E io faccio invece leva sulla condivisione della responsabilit&agrave;</p></td>
		</tr>
		<tr class="even">
			<td align="left"><p>29</p></td>
			<td align="left">
				<p>
					Il mio approccio pone maggiore focus sul design-upfront.</p></td>
			<td></td>
		</tr>
		<tr class="odd">
			<td></td>
			<td></td>
			<td align="left">
				<p>
					Il mio su un'architettura <em>evolutiva</em>.</p></td>
		</tr>
		<tr class="even">
			<td align="left"><p>30</p></td>
			<td align="left">
				<p>
					Oppure, per usare le parole del <em>Manifesto Agile</em>, io faccio
					affidamento sulla <em>Comprehensive Documentation</em>.</p></td>
			<td></td>
		</tr>
		<tr class="odd">
			<td></td>
			<td></td>
			<td align="left">
				<p>
					Io, invece, mi affido alla concretezza del <em>working software</em>.</p></td>
		</tr>
		<tr class="even">
			<td></td>
			<td align="left">
				<p>
					Bene.
					<br />
					Ecco, mi piacerebbe, per&ograve;, che tu mi offrissi maggiori dettagli
					sulle motivazioni dietro alla tua preoccupazione intorno al concetto di
					un architetto &quot;aware&quot;, che &quot;resti costantemente informato&quot;.</p></td>
			<td></td>
		</tr>
		<tr class="odd">
			<td align="left"><p>31</p></td>
			<td></td>
			<td align="left">
				<p>
					Certamente.
					<br />
					Se me lo concedi, vorrei avvalermi degli <em>Influence Diagram</em>.
					Considera il rapporto tra il mangiare e il prendere peso.
					Pi&ugrave; mangio, pi&ugrave; ingrasso. &egrave; una influenza positiva.
					La rappresento in questo modo:</p></td>
		</tr>
		<tr class="even">
			<td align="left"><p>32</p></td>
			<td></td>
			<td align="left">
				<p>
					Il rapporto tra l'esercizio fisico e il peso &egrave; opposta.
					&Egrave; un'influenza negativa.
					La rappresento aggiungendo un cerchio sulla freccia. Mi segui?</p></td>
		</tr>
		<tr class="odd">
			<td align="left"><p>33</p></td>
			<td></td>
			<td align="left">
				<p>
					Ok, come puoi notare ho rappresentato un circolo vizioso.
					<br />
					Parti dalla freccia che entra nel circolo.
					<br />
					Leggila in questo modo:
					<br />
					Pi&ugrave; ingrasso, pi&ugrave; perdo stima in me stesso;
					<br />
					Pi&ugrave; perdo stima, pi&ugrave; mangio.
					<br />
					Pi&ugrave; mangio, pi&ugrave; ingrasso.
					<br />
					E mi ritrovo nuovamente all'ingresso del circolo visioso.</p></td>
		</tr>
		<tr class="even">
			<td></td>
			<td align="left">
				<p>
					Perch&egrave; mi racconti questo?</p></td>
			<td align="left"><p></p></td>
		</tr>
		<tr class="odd">
			<td align="left"><p>34</p></td>
			<td></td>
			<td align="left">
				<p>
					Perch&egrave; questo ha molto a che fare con i feedback che un architetto pu&ograve;
					ricevere. Lascia che ti spieghi.
					<br />
					Qu&igrave; ho rappresentato lo stesso identico circolo vizioso,
					ma ho usato dei termini che riguardano la gestione di un team.
					Leggilo cos&igrave;:
					<br />
					Pi&ugrave; pressioni imponi ad un team, meno test gli sviluppatori arriveranno
					a produrre; meno test avrai, pi&ugrave; errori saranno presenti nel codice.
					E, con pi&ugrave; errori, &egrave; evidente che sarai costretto, a sua volta,
					a far maggiore pressione, per far rispettare le scadenze.</p></td>
		</tr>
		<tr class="even">
			<td align="left"><p>35</p></td>
			<td align="left">
				<p>
					D'accordo.</p></td>
			<td></td>
		</tr>
		<tr class="odd">
			<td></td>
			<td></td>
			<td align="left">
				<p>
					Ecco. Arriviamo al punto del perch&egrave; l'architetto debba essere
					coinvolto anche nello sviluppo.
					<br />
					Questo diagramma di influenza descrive il tuo approccio:
					<br />
					L'architetto <em>Reloadus</em> produce <em>documentazione</em>.
					<br />
					Tanta pi&ugrave; documentazione produce, minore &egrave; il numero
					di feedback che si ricevono;
					<br />
					Meno feedback si ricevono, maggiore sar&agrave; il numero di scelte errate
					compiute.
					<br />
					E, a fronte di un alto numero di scelte sbagliate, sar&agrave; necessario
					produrre documentazione con il fine che vengano evitate.
					<br />
					Come vedi, anche in questo caso siamo di fronte ad un circolo vizioso.</p></td>
		</tr>
		<tr class="even">
			<td align="left"><p></p></td>
			<td align="left">
				<p>
					E tu cosa proponi in alternativa?</p></td>
			<td></td>
		</tr>
		<tr class="odd">
			<td align="left"><p>36</p></td>
			<td></td>
			<td align="left">
				<p>
					Guarda, ti mostro come sia possibile invertire la tendenza.
					<br />
					Se faccio leva sulla collaborazione, produco molti feedback;
					<br />
					Questo riduce il numero di scelte errate.
					<br />
					Meno scelte errate comporta una abbattimenti del numero di documenti e, quindi,
					maggior tempo a disposizione per una collaborazione intensiva.
					<br />
					Come puoi constatare, il modello che propongo alimenta un circolo virtuoso!</p></td>
		</tr>
		<tr class="even">
			<td align="left"><p>37</p></td>
			<td align="left">
				<p>
					Quindi, quale &egrave; l'alternativa ad <em>Enterprise Architecture</em>?</p></td>
			<td align="left"><p></p></td>
		</tr>
		<tr class="odd">
			<td></td>
			<td></td>
			<td align="left">
				<p>
					&quot;centralized governance&quot;.
					<br />
					Agile propone: <em>&quot;Individuals and interactions over processes and
					tools&quot;</em>.
					<br />
					Spesso, al governo centralizzato si accompagna la tendenza a standardizzare e
					a convergere verso una singola piattaforma tecnologica.
					<br />
					Ma l'esperienza ci insegna che non tutti i problemi sono chiodi e,
					di conseguenza, non tutte le soluzioni sono martelli.
					<br />
					Il trend, in questi anni, &egrave; di costruire sistemi organizzati come
					<em>micro-service</em>.
					<br />
					Molti team, piuttosto che affidarsi a standard scritti su qualche documento,
					da qualcuno sopra di loro, preferiscono produrre tool utili che altri
					sviluppatori possano utilizzare per risolvere problemi simili.
					<br />
					Nascono le API e, assieme a loro, delle &quot;community&quot;.
					<br />
					Se ci pensi bene, Amazon&trade; ne rappresenta un caso
					molto significativo.</td>
		</tr>
		<tr class="even">
			<td align="left"><p>38</p></td>
			<td align="left">
				<p>
					Mi trovi molto d'accordo.
					<br />
					E penso sia molto curioso che tu concluda citando Amazon&trade;.
					<br />
					Perch&egrave;, se ricordi il famoso post di <em>Steve Yegge</em> ricorderai
					che Amazon&trade; &egrave; passata dall'essere un e-commerce di libri ad
					una piattaforma di servizi per la decisione illuminata di un architetto
					visionario e autoritario.
					<br />
					Probabilmente, se si fosse aspettato che Amazon&trade; diventasse una
					immensa <em>Service Oriented Company</em>, per l'intervento dei suoi singoli
					sviluppatori, come architettura emergente, oggi non avremmo il &quot;Cloud&quot;
					di Amazon&trade;.
					<br />
					Ma &egrave; bello vedere che le nostre visioni, apparentemente cos&igrave;
					distanti, abbiano alla fine cos&igrave; tanti punti di contatto.</p></td>
			<td></td>
		</tr>
		<tr class="odd">
			<td></td>
			<td></td>
			<td align="left">
				<p>
					S&igrave;. Voi cosa ne pensate? Ne parliamo?</p></td>
		</tr>
	</tbody>
</table>
<table>
	<tbody>
		<tr>
			<td></td>
		</tr>
		<tr>
			<td>
				<p>[[a]](#cmnt_ref1) Qui alexander: le citt&agrave; non evolvono.</p></td>
		<tr>
			<td>
				<p>
					[[b]](#cmnt_ref2) Immagine di Facebook, prima (apache + php) e dopo (infrastruttura immensa).</p></td>
		</tr>
		<tr>
			<td>
				<p>
					[[c]](#cmnt_ref3) Rendere pi&ugrave; conciso, troppo lungo!</p></td>
		</tr>
	</tbody>
</table>