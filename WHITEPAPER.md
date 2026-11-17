# FIÐEX — Whitepaper

**Infrastruttura mutualistica per la protezione degli utenti nei mercati crypto**

| | |
|---|---|
| Versione | 0.1 — bozza di lavoro |
| Data | 17 novembre 2026 |
| Stato | Non approvata. Non destinata alla pubblicazione |
| Impronta | Da calcolare e pubblicare nel protocollo all'approvazione |
| Statuto di riferimento | Versione 0.3 del 16 novembre 2026 |

Questo documento è interamente parte informativa ai sensi dell'art. 48bis dello statuto. Descrive; non stabilisce. Diritti e obblighi dei membri sono nello statuto e nel Regolamento di governance, che prevalgono in ogni caso.

FIÐEX non è un'impresa di assicurazione e non offre polizze. Non promette rendimento, rimborso o protezione automatica.

---

## Indice

- Sintesi
- 1\. Il problema
- 2\. Visione, missione e scopi
- 3\. Modello di partecipazione
- 4\. Architettura: Pass e $FXS
- 5\. Patrimonio, compartimenti e fondi di terzi
- 6\. Raccolta, livelli e incentivi
- 7\. Soglie operative
- 8\. Protezione futura e processo di esame delle richieste
- 9\. Servizi: FIÐEX Resolve
- 10\. Governance
- 11\. Struttura giuridica
- 12\. Gruppo di lavoro e responsabilità
- 13\. Rischi e limiti
- 14\. Percorso di sviluppo
- 15\. Documentazione e avvertenze

---

# Sintesi

*Questa sintesi non sostituisce la lettura del documento, dello statuto e del Regolamento.*

**Che cosa è FIÐEX.** FIÐEX è un'infrastruttura mutualistica in costruzione, orientata alla protezione degli utenti nei mercati crypto. Ha la forma di un'associazione senza scopo di lucro di diritto svizzero. Chi partecipa non acquista uno strumento: aderisce a uno statuto, diventa membro e concorre alle decisioni comuni. L'immagine che guida il progetto è il faro, che non elimina la tempesta ma rende visibile la costa.

**Il problema.** Il rischio nei mercati crypto è misurabile e persistente: i registri pubblici contano perdite per miliardi di dollari, concentrate in pochi eventi di grande entità e distribuite in famiglie di cause molto diverse, in parte indipendenti dalla qualità del codice. A queste si aggiungono i danni che nascono dai rapporti tra le persone, dove la blockchain prova un trasferimento ma non che fosse dovuto. Chi vi è esposto dispone di informazioni disperse, di strumenti di protezione la cui solidità non è verificabile, di fondi comuni poco leggibili e di forme di partecipazione deboli.

**La risposta.** FIÐEX non propone una promessa ma una struttura. Rende pubblici e verificabili i fondi, le regole e le decisioni; separa le risorse per destinazione; affida l'amministrazione a persone identificate, sottoposte a un organo di controllo e revocabili; costruisce la capacità di ricostruire e documentare i casi. La protezione economica è l'ultimo passo, non il primo.

**Che cosa è attivo e che cosa non lo è.** Dall'avvio sono previsti l'adesione, il registro dei membri, la pubblicazione dei fondi, la raccolta dei contributi e il voto. Non è attivo alcun meccanismo di protezione. Non esiste $FXS come strumento trasferibile. L'associazione non custodisce fondi altrui. Queste funzioni sono moduli che lo statuto vieta di offrire o annunciare finché non siano attivati con delibera qualificata dei soci e con le autorizzazioni che la legge richiede. Possono non essere mai attivati.

**Partecipazione.** Si aderisce firmando l'impronta dei testi vigenti, versando una quota fissata nel controvalore di 5 dollari e comunicando la propria identità al Consiglio. È socio chi dimostra di essere una persona unica, tramite World ID o nelle altre forme previste; gli altri membri sono aderenti. Il Pass attesta la partecipazione, non è trasferibile e non dà diritti economici. Tre livelli di contributo determinano una sola cosa: il peso del voto ponderato.

**Strumenti.** $FXS è lo strumento della governance e oggi esiste soltanto come registrazione non trasferibile, che non rappresenta quote del patrimonio e non dà diritto a rendimento o a protezione. $FDX è un token di comunità emesso da terzi, esterno all'associazione e privo di ogni diritto nei suoi confronti; l'associazione può accettarlo come attivo e riceve proventi collegati ai suoi scambi, destinati alla riserva.

**Fondi.** Il patrimonio appartiene all'associazione ed è vincolato allo scopo. È tenuto in quattro compartimenti, in wallet a firma multipla, e può essere impiegato soltanto in strumenti liquidi e a basso rischio, il cui risultato resta al patrimonio. I compartimenti sono una separazione interna e non proteggono dai creditori. I fondi eventualmente detenuti per conto di terzi sono estranei al patrimonio.

**Raccolta.** I contributi volontari sono definitivi. La soglia minima è il controvalore di 600.000 USDT; fino al suo raggiungimento almeno l'80% dei contributi resta vincolato, poi una quota crescente, dal 40% al 70%, è destinata alla riserva. Se la soglia non è raggiunta entro dodici mesi, ciò che resta dei contributi è ripartito tra chi li ha versati: non è una garanzia di restituzione e l'importo può essere inferiore al versato. Al gruppo di lavoro non sono attribuiti strumenti di governance a titolo gratuito.

**Governance.** Ogni delibera richiede due maggioranze: quella delle persone e quella dei voti ponderati. Il peso cresce con la radice quadrata del contributo ed è soggetto a un tetto. L'assemblea indirizza e controlla; il Consiglio amministra; il Board di controllo vigila. Voti e conteggi sono pubblici e riproducibili.

**Servizi.** Il programma FIÐEX Resolve prevede servizi documentali, assistenza, composizione dei rapporti e deposito vincolato, da attivare per fasi e nei limiti della legge. Nessuno è attivo.

**Rischi.** Il progetto è in fase iniziale. La soglia può non essere raggiunta, le funzioni future possono non realizzarsi, i fondi possono perdere valore, la qualificazione giuridica di più elementi non è accertata e un'autorità potrebbe imporre la cessazione di attività o la restituzione di quanto raccolto. Chi contribuisce dovrebbe poter sopportare la perdita integrale di quanto versa. Nessuno dovrebbe aderire nell'aspettativa di ricevere protezione o un rendimento.

**Dove stanno le regole.** Questo documento descrive; non stabilisce. Diritti e obblighi dei membri sono nello statuto e nel Regolamento di governance, che prevalgono in ogni caso.

---

# 1. Il problema


## 1.1 Un rischio misurabile e persistente

La finanza decentralizzata ha reso verificabili operazioni che nei mercati tradizionali restano affidate a intermediari. Non ha reso verificabile, nella stessa misura, il rischio a cui espone chi la utilizza. I dati pubblici mostrano un fenomeno di dimensioni stabili nel tempo: al 2 luglio 2026 il registro di DeFiLlama censisce circa 16,66 miliardi di dollari di valore compromesso da attacchi informatici nell'intero settore, di cui circa 7,86 miliardi riferiti ai protocolli di finanza decentralizzata in senso stretto e circa 3,26 miliardi ai bridge tra reti. Nel solo perimetro dei protocolli, Immunefi conta 460 incidenti tra il 2020 e il 2025.

La serie storica non descrive un'emergenza superata. Le perdite dei protocolli hanno toccato 2,62 miliardi di dollari nel 2022, sono scese a 534 milioni nel 2024 e sono risalite a 680 milioni nel 2025. Nello stesso periodo la perdita mediana per incidente è passata da circa 6 milioni a circa 1,5 milioni di dollari. La sicurezza media è dunque migliorata, ma il primo semestre del 2026 ha registrato di nuovo eventi di grande entità: il solo insieme degli incidenti più rilevanti supera, a inizio luglio, i 600 milioni di dollari.

## 1.2 Perdite concentrate, cause eterogenee

Due caratteristiche rendono questo rischio difficile da governare per il singolo utente. La prima è la concentrazione: pochi eventi spiegano la maggior parte delle perdite di ogni anno. Nel 2022 circa il 73% del valore sottratto ai protocolli è dipeso da attacchi ai bridge; nell'aprile 2026 due soli incidenti, Drift e KelpDAO, hanno prodotto perdite prossime a 290 milioni di dollari ciascuno. Chi partecipa a un protocollo non è esposto a un danno frequente e modesto, ma a un evento raro e potenzialmente totale.

La seconda è l'eterogeneità. Non esiste un unico «rischio di attacco»: l'analisi degli incidenti distingue almeno dieci famiglie di cause, con frequenza e gravità molto diverse. Vi rientrano i difetti di logica dei contratti, la manipolazione degli oracoli di prezzo, la compromissione delle chiavi private, gli attacchi ai meccanismi di governance, le vulnerabilità dei bridge, la compromissione delle interfacce e dei fornitori terzi, gli errori di progettazione economica. Ciascuna richiede una valutazione propria. Un giudizio indistinto sulla «sicurezza» di un protocollo non descrive nessuna di esse.

A ciò si aggiunge la correlazione. Molti protocolli condividono codice derivato dallo stesso progetto, gli stessi oracoli, gli stessi bridge, le stesse procedure di firma. Un difetto in una componente comune si trasmette a più sistemi nello stesso momento, e il valore dichiarato come depositato in un protocollo non è sempre verificabile con metodi uniformi: la ricerca della Banca dei regolamenti internazionali ha proposto una nozione di valore depositato «verificabile» proprio per ridurre questa opacità di misura.

## 1.3 Dal codice alle persone e alle dipendenze

Negli ultimi anni la natura del rischio è cambiata. Le categorie di attacco ripetibili, che nel 2022 colpivano più protocolli con la stessa tecnica, si sono ridotte: nel 2025, secondo Immunefi, l'89% delle perdite dei protocolli è dipeso da difetti di logica specifici del singolo sistema, e la quota dei bridge è scesa al 3%. Il rischio residuo è più difficile da prevedere, perché non si ripete uguale.

Gli eventi più gravi del 2026 indicano inoltre che la perdita non nasce necessariamente da un errore nel codice. Nel caso Drift l'attacco è stato preparato per mesi con tecniche di ingegneria sociale e ha colpito la procedura di approvazione amministrativa, senza un difetto elementare nei contratti. Nel caso KelpDAO la causa è stata la configurazione di un bridge affidata a un solo verificatore. In altri incidenti recenti il punto debole è stato un fornitore dell'interfaccia. La revisione del codice resta necessaria, ma non copre queste superfici: procedure di firma, dipendenze esterne, gestione degli aggiornamenti, comportamento delle persone che amministrano il sistema.

Anche la governance è una superficie di rischio. La letteratura sulle organizzazioni decentralizzate documenta concentrazione del voto, partecipazione ridotta e diritti di voto liberamente trasferibili: sono le condizioni che rendono possibile l'acquisizione ostile di una decisione collettiva. Il Financial Stability Board osserva, più in generale, che la finanza decentralizzata riproduce funzioni della finanza tradizionale e può ripeterne o amplificarne le fragilità.

## 1.4 Il rischio che non passa dal codice: i rapporti tra le parti

Una parte rilevante dei danni non deriva da attacchi a un protocollo, ma dalla relazione tra soggetti: frodi, fondi trattenuti da una piattaforma, prestazioni pagate e non eseguite, impossibilità di ottenere una risposta da una controparte. In questi casi la blockchain offre una prova parziale. La registrazione attesta che un trasferimento è avvenuto; non dimostra che la prestazione corrispondente fosse dovuta, che il consenso fosse valido o che quanto consegnato fosse conforme all'accordo.

Tra l'esecuzione tecnica di un trasferimento e l'esecuzione conforme di un accordo resta quindi uno spazio che il codice non presidia. Chi subisce un danno si trova spesso senza una ricostruzione ordinata dei fatti, senza un interlocutore individuato e senza una procedura riconosciuta per accertare chi dovesse fare che cosa. Il costo di organizzare da soli queste attività supera di frequente il valore della singola controversia, e l'iniziativa individuale viene abbandonata.

## 1.5 Che cosa manca a chi è esposto

Di fronte a questo quadro, gli strumenti a disposizione dell'utente restano insufficienti per quattro ragioni.

La prima è la leggibilità. Le informazioni che permettono di valutare un rischio esistono, ma sono disperse tra relazioni tecniche, registri specialistici e analisi successive agli incidenti, e richiedono competenze che la maggior parte dei partecipanti non possiede.

La seconda è la verificabilità di chi offre protezione. Le iniziative che hanno promesso una protezione immediata, senza una riserva adeguata, senza procedure e senza regole di governo, sono state ripetutamente smentite dai cicli di mercato. L'esperienza più duratura del settore è quella di una struttura mutualistica in cui l'intervento è deciso dai membri, è limitato dal capitale disponibile ed è stato attivato solo dopo il raggiungimento di una soglia minima di riserva. La distanza tra i due modelli non è sempre riconoscibile dall'esterno.

La terza è la gestione delle risorse comuni. Dove esistono fondi collettivi, la loro consistenza, la loro destinazione e le regole con cui se ne dispone non sono sempre pubbliche né separabili per funzione. Chi contribuisce non è in grado di distinguere ciò che finanzia lo sviluppo da ciò che resta a presidio del rischio.

La quarta è la partecipazione. I meccanismi decisionali sono spesso più dichiarati che esercitati, e il peso di ciascun partecipante dipende da strumenti che possono essere accumulati o trasferiti senza alcun legame con una persona identificabile come unica.

## 1.6 Risorse disperse

Esiste infine un problema di scala. Le reti fondate sulla prova di unicità della persona, tra cui World, distribuiscono periodicamente risorse digitali a un numero molto ampio di esseri umani verificati. Per il singolo destinatario l'importo è modesto e, in assenza di un impiego ordinato, si disperde. Considerate nel loro insieme, quelle stesse risorse rappresentano una capacità collettiva che oggi non trova una forma mutualistica: una struttura in cui contributi individualmente piccoli, riferiti a persone verificate, concorrano a un'infrastruttura comune le cui regole e i cui fondi siano pubblici.

## 1.7 Sintesi

Il rischio nei mercati crypto è misurabile, concentrato, eterogeneo e in parte indipendente dalla qualità del codice. Riguarda i protocolli e riguarda i rapporti tra le persone che li usano. Chi vi è esposto dispone di informazioni disperse, di strumenti di protezione la cui solidità non è verificabile, di fondi comuni poco leggibili e di forme di partecipazione deboli. Il problema non è l'esistenza del rischio, che non può essere eliminato, ma l'assenza di un'infrastruttura che lo renda visibile, documentato e governabile da chi lo sopporta.

### Fonti del capitolo

DeFiLlama, registro degli attacchi informatici (dato al 2 luglio 2026). Immunefi, rilevazioni sulle perdite dei protocolli di finanza decentralizzata, 2020–2025. Chainalysis, analisi degli attacchi ai bridge (2022) e dell'incidente KelpDAO (aprile 2026). TRM Labs, analisi dell'incidente Drift (aprile 2026). Banca dei regolamenti internazionali, ricerca sul valore depositato verificabile. Financial Stability Board, rapporto sui rischi della finanza decentralizzata. Documentazione pubblica di Nexus Mutual. FIÐEX, «Rischi della DeFi e giustificazione tecnica», rapporto interno con cronologia degli incidenti fino al 4 luglio 2026.

---

# 2. Visione, missione e scopi

*Gli scopi dell'associazione sono stabiliti dall'art. 3 dello statuto, che prevale su questo capitolo.*

## 2.1 Che cosa è FIÐEX

FIÐEX è un'infrastruttura mutualistica in costruzione, orientata alla protezione degli utenti nei mercati crypto attraverso la trasparenza verificabile, la partecipazione regolata e una governance che matura per gradi. Assume la forma di un'associazione senza scopo di lucro di diritto svizzero, i cui membri sono persone che aderiscono allo statuto e partecipano alle decisioni comuni.

La parola «in costruzione» ha un significato preciso. Alla data di questo documento sono attive l'adesione, la registrazione pubblica dei contributi e dei fondi e gli strumenti di partecipazione. Non è attivo alcun meccanismo di protezione. Ogni funzione descritta come futura in questo documento dipende da condizioni dichiarate: sviluppo tecnico, capacità della riserva, delibera dei membri e adempimenti di legge. Il capitolo 7 espone queste condizioni.

## 2.2 Visione: il faro

L'immagine che guida il progetto è il faro. Un faro non placa la tempesta e non promette l'approdo. Rende visibile la costa, segnala gli ostacoli e permette a chi naviga di decidere con cognizione. È un presidio collettivo: funziona perché qualcuno lo mantiene acceso per tutti, e la sua utilità non dipende da chi lo ha costruito.

La visione di FIÐEX è diventare un'infrastruttura di riferimento per la protezione mutualistica nei mercati crypto, nella quale il rapporto tra chi contribuisce, chi decide e chi custodisce i fondi comuni sia leggibile da chiunque. Il risultato atteso non è un mercato privo di rischio, ma un mercato in cui il rischio è conosciuto da chi lo sopporta.

## 2.3 Missione

Il capitolo 1 ha descritto un rischio misurabile ma poco leggibile, strumenti di protezione la cui solidità non è verificabile, fondi comuni opachi e forme di partecipazione deboli. La missione di FIÐEX è rispondere a queste mancanze con una struttura, non con una promessa.

In concreto, la missione consiste nel rendere il rischio visibile, attraverso informazioni ordinate e pubbliche; documentato, attraverso registri che chiunque può verificare; e governabile, attraverso regole decise dai membri. Gli strumenti sono la tracciabilità dei fondi, la loro separazione per funzione, un registro pubblico dei membri e delle decisioni, una governance che si attiva per gradi e lo sviluppo prudente dei meccanismi di protezione.

La missione non è eliminare il rischio. È costruire le condizioni perché chi vi è esposto possa conoscerlo, condividerlo e decidere insieme come affrontarlo.

## 2.4 Scopi dell'associazione

Lo statuto assegna all'associazione uno scopo ideale e non economico, articolato in tre direzioni.

La prima è lo sviluppo e il mantenimento di infrastrutture mutualistiche aperte e verificabili, che rendano il rischio nei mercati crypto più visibile, governabile e documentato. È lo scopo da cui discendono il protocollo, il registro, la governance e, in futuro e a determinate condizioni, i meccanismi di protezione.

La seconda è la promozione dell'educazione finanziaria e della cultura civica. Un rischio diventa governabile solo se chi lo sopporta dispone degli strumenti per comprenderlo. L'associazione considera la conoscenza una forma di protezione che precede ogni altra, ed è disponibile a tutti, senza condizioni di accesso.

La terza è la promozione della cultura scientifica e tecnologica e del software a codice aperto. Il codice del protocollo è pubblicato con licenza aperta e i diritti su di esso spettano all'associazione.

L'associazione non persegue lucro e non distribuisce utili o avanzi di gestione ai membri. Può svolgere attività strumentali allo scopo, tra cui i servizi documentali descritti nel capitolo 9. Le attività operative che richiedono una forma diversa, quali i servizi professionali, potranno essere affidate a un ente distinto, costituito con delibera dei soci dopo il raggiungimento della soglia minima di raccolta.

## 2.5 Principi

Cinque principi ordinano le scelte di progetto e ne costituiscono il criterio di verifica.

**Trasparenza verificabile.** Fondi raccolti, destinazione, saldi, criteri di accesso, decisioni e limiti del sistema devono poter essere controllati da chiunque, senza dover credere a una dichiarazione. La trasparenza si misura sull'architettura e sui registri, non sulle intenzioni.

**Prudenza.** Nessuna funzione è presentata come disponibile prima che lo sia. Un percorso di sviluppo non è un impegno, e una funzione futura è sempre descritta insieme alle condizioni da cui dipende.

**Separazione delle responsabilità.** Raccolta, spesa operativa, riserva e fondi di terzi sono tenuti distinti. Chi decide le regole non decide le singole pratiche; chi sviluppa il protocollo non ne detiene le chiavi; chi amministra risponde a un organo di controllo eletto dai membri.

**Partecipazione.** Chi aderisce è un membro, con diritto di voto, di proposta e di controllo. Il rapporto con l'associazione è una partecipazione regolata dallo statuto, non l'acquisto di una prestazione.

**Responsabilità e resilienza.** Le persone che amministrano sono identificate e rispondono dei loro atti. L'associazione non dipende da un sito, da un fornitore o da una persona: ogni membro può riprodurre l'interfaccia e verificare gli atti dalle registrazioni pubbliche.

A questi principi si accompagna un orientamento di valore. FIÐEX si riconosce nella solidarietà tra i membri, nella parità di trattamento e nella sostenibilità delle tecnologie che adotta. Intende impiegare l'automazione al servizio di persone verificate, e non al loro posto: i processi automatici eseguono regole decise dai membri, e le decisioni che richiedono giudizio restano affidate a persone.

## 2.6 Umanità verificata e rete aperta

FIÐEX considera la prova di unicità della persona un fondamento della mutualità. Una struttura in cui ogni voto e ogni posizione corrispondono a un essere umano distinto resiste meglio alla concentrazione del potere e alle identità fittizie, e rende significativo anche un contributo di importo modesto. Per questa ragione la piena qualità di socio richiede una verifica di unicità, che può avvenire tramite World ID o con le altre forme previste dallo statuto.

Il progetto condivide i principi su cui queste reti si fondano: identità riferita alla persona e non al patrimonio, infrastruttura distribuita, codice aperto. Adotta World Chain come rete di riferimento e prevede un'applicazione all'interno di World App come canale di partecipazione.

FIÐEX è un progetto indipendente. Non è affiliato a World, a Tools for Humanity né alla World Foundation, e non è da essi promosso, approvato o controllato.

## 2.7 Che cosa FIÐEX non è

La definizione del progetto comprende i suoi confini. FIÐEX non è un'impresa di assicurazione e non offre polizze. Non è un investimento, un fondo o una forma di gestione collettiva del risparmio. Non promette rendimento, rimborso o protezione automatica, e nessuna disposizione dello statuto attribuisce ai membri diritti di questo tipo. Non presenta come attive funzioni che non lo sono.

Chi aderisce sostiene la costruzione di un'infrastruttura comune e acquisisce il diritto di partecipare alle decisioni che la riguardano. Ogni meccanismo di protezione futuro avrà natura mutualistica e sarà attivato soltanto alle condizioni stabilite dallo statuto.

---

# 3. Modello di partecipazione

*La materia è disciplinata dagli artt. 8–16 dello statuto e dal Regolamento di governance, che prevalgono su questo capitolo.*

## 3.1 Dall'utente al membro

Nei progetti crypto il rapporto più diffuso è quello tra un emittente e un acquirente: si acquista uno strumento e se ne attende l'andamento. FIÐEX adotta un rapporto diverso. Chi partecipa aderisce a un'associazione e ne diventa membro: accetta uno statuto, versa una quota, è iscritto in un registro e acquisisce il diritto di concorrere alle decisioni comuni.

Questa scelta ha conseguenze precise. La posizione di membro è personale, non si cede e non si trasmette. Non incorpora diritti sul patrimonio dell'associazione. È regolata da norme che il membro conosce prima di aderire e che possono essere modificate soltanto con le maggioranze previste dallo statuto.

## 3.2 L'adesione

Possono aderire le persone fisiche maggiorenni. Ogni persona può avere una sola posizione di membro.

L'adesione si compone di tre atti. Il primo è la firma, con il proprio wallet, di un messaggio che contiene l'impronta crittografica delle versioni vigenti dello statuto, del Regolamento e di questo documento: chi firma sa esattamente a quali testi aderisce, e quei testi restano identificabili nel tempo. Il secondo è il versamento della quota di adesione tramite il protocollo. Il terzo è la comunicazione al Consiglio, attraverso un canale cifrato, del proprio nome e indirizzo.

L'ammissione spetta al Consiglio e si perfeziona con l'iscrizione nel registro dei membri. Il Consiglio può rifiutarla entro un termine breve, per i motivi indicati dal Regolamento; in tal caso l'adesione si considera mai avvenuta e la quota è riversata al wallet di origine. La firma e l'identificativo della transazione costituiscono insieme l'atto di adesione, che resta verificabile anche senza il sito dell'associazione.

A chi aderisce in qualità di consumatore il protocollo fornisce, prima della firma, le informazioni previste dalla legge del suo luogo di residenza. Il membro consumatore può recedere entro quattordici giorni senza indicare motivi, e riceve quanto ha versato nell'attivo e nell'importo nominale originari.

## 3.3 Soci e aderenti

L'associazione distingue due categorie di membri, in base alla verifica di unicità della persona.

È **socio** chi, oltre ad aderire, ha dimostrato di essere una persona distinta da ogni altro membro. La verifica può avvenire in tre forme: tramite World ID; mediante identificazione presso il Consiglio con un documento d'identità; oppure, in via transitoria, con la garanzia di soci già verificati. La garanzia è limitata nel numero, non può essere prestata da chi è stato a sua volta ammesso per garanzia e cessa di valere con l'attivazione di $FXS.

È **aderente** chi ha aderito senza completare la verifica.

La distinzione incide sul voto. Le decisioni di maggiore rilievo, tra cui la modifica dello statuto, l'elezione e la revoca degli organi e l'attivazione dei moduli futuri, sono riservate ai soci. Nelle materie ordinarie votano tutti i membri, ciascuno con un voto. Il voto ponderato secondo il livello di contributo spetta ai soli soci verificati con World ID o identificati presso il Consiglio. Il capitolo 10 espone il funzionamento della governance.

La ragione della distinzione è la tutela del principio per cui a ogni persona corrisponde una voce. Senza una verifica di unicità, una quota di adesione di importo contenuto permetterebbe a un solo soggetto di moltiplicare le proprie posizioni e di alterare l'esito delle decisioni.

## 3.4 Il Pass

Il Pass è la credenziale digitale che attesta la partecipazione. Collega il wallet del membro alla sua posizione nel registro e consente l'accesso agli strumenti del protocollo.

Il Pass non è trasferibile, in modo permanente. Non incorpora la qualità di membro, che resta legata alla persona e all'iscrizione nel registro. Non rappresenta diritti sul patrimonio né altri diritti economici, e non è uno strumento destinato allo scambio.

## 3.5 I livelli di contributo

La partecipazione si articola in tre livelli. Il Livello I coincide con la quota di adesione, è dovuto una sola volta ed è fissato dal Regolamento iniziale nel controvalore di 5 dollari: una soglia volutamente bassa, perché l'accesso sia aperto a ogni persona verificata. I Livelli II e III corrispondono a contributi maggiori, che il Regolamento iniziale colloca a partire dal controvalore di 1.000 e di 10.000 dollari.

Il livello determina una sola cosa: il peso del voto ponderato del socio verificato, calcolato con una formula che cresce meno che proporzionalmente al contributo ed è soggetta a un tetto per membro. Non attribuisce diritti sul patrimonio, né diritto a rendimento o a protezione, né precedenza nell'accesso a funzioni future, salvo diversa delibera dell'assemblea. Oltre alla quota, i membri non hanno obblighi di versamento.

Prima della firma il protocollo mostra a chi aderisce, in forma chiara, che cosa ciascun livello comporta e che cosa non comporta.

## 3.6 Che cosa comporta la partecipazione

Il membro accede al protocollo dell'associazione, che comprende il Genesis Observatory, il registro dei membri e il sistema di voto. Il Genesis Observatory è lo spazio in cui lo stato dell'associazione è reso leggibile: fondi per compartimento, contributi registrati, documenti, decisioni e loro esecuzione. Al suo interno la Genesis Board è il luogo della discussione, nel quale si formano le proposte.

Il membro può votare nelle materie di sua competenza, presentare proposte e raccomandazioni rivolte al Consiglio, delegare il proprio voto a un altro membro nei limiti del Regolamento e chiedere, insieme a un quinto dei membri, la convocazione di una finestra di voto straordinaria. Può consultare la propria posizione nel registro, chiederne la rettifica e impugnare le delibere e gli atti contrari alla legge o allo statuto.

La partecipazione non comporta alcun diritto a prestazioni economiche. I meccanismi di protezione mutualistica non sono attivi e la qualità di membro non ne anticipa l'accesso: le condizioni della loro eventuale attivazione sono esposte nei capitoli 7 e 8.

## 3.7 Registro e riservatezza

Il registro dei membri è tenuto in forma elettronica ed è diviso in due parti. La parte pubblica riporta, per ogni wallet, la categoria, il livello di contributo, il peso del voto, il metodo di verifica, le deleghe e le eventuali esclusioni dal voto; la sua impronta è ancorata periodicamente a una blockchain pubblica, così che chiunque possa verificarne l'integrità. La parte riservata contiene l'identità del membro e il suo legame con il wallet: è conservata in Svizzera ed è accessibile soltanto al Consiglio.

Nessun dato identificativo, e nessuna sua impronta, è scritto su una blockchain. Il membro è dunque pseudonimo verso il pubblico e verso gli altri membri, ma è identificato verso l'associazione. I dati sono trattati secondo la legge svizzera sulla protezione dei dati e, per chi vi è soggetto, secondo il regolamento generale europeo.

## 3.8 Canali e mezzi di partecipazione

L'adesione avviene tramite il pannello di adesione del protocollo, raggiungibile dal sito dell'associazione. È prevista inoltre un'applicazione all'interno di World App, pensata per chi dispone già di una verifica World ID: permette di aderire, consultare la propria posizione e seguire lo stato dell'associazione dal medesimo ambiente in cui la verifica è stata compiuta. Il sito resta il riferimento completo; l'applicazione ne è un'estensione e si fonda sugli stessi registri.

I versamenti possono avvenire in qualsiasi attivo accettato dal Consiglio. Di ciascuno si registrano l'importo nominale nell'attivo versato e il suo valore al momento del versamento.

## 3.9 Uscita ed esclusione

Ogni membro può uscire dall'associazione con una dichiarazione firmata nel protocollo, rispettando il preavviso previsto dallo statuto. L'uscita è immediata quando viene modificato lo scopo dell'associazione o quando una modifica statutaria aggrava gli obblighi dei membri, per chi non l'ha approvata.

L'esclusione è ammessa soltanto per i motivi indicati dallo statuto, quali la violazione grave delle regole o le dichiarazioni false in sede di adesione. È decisa dai soci su proposta motivata del Consiglio, dopo che il membro ha potuto essere sentito.

Chi esce o è escluso non ha diritti sul patrimonio sociale. La quota e i contributi versati restano all'associazione, salvi i casi di recesso del consumatore, di rifiuto dell'ammissione e di ripartizione previsti dallo statuto.

---

# 4. Architettura: Pass e $FXS

*La materia è disciplinata dagli artt. 10, 37, 40 e 41 dello statuto e dal Regolamento di governance, che prevalgono su questo capitolo.*

## 4.1 Due strumenti, funzioni separate

L'architettura di FIÐEX si fonda su due strumenti digitali, il Pass e $FXS, che rispondono a domande diverse. Il Pass risponde alla domanda «chi partecipa»: attesta che una persona è membro dell'associazione. $FXS risponde alla domanda «con quale peso si concorre alle decisioni»: è lo strumento della governance.

Nessuno dei due risponde alla domanda «a chi appartiene il patrimonio». Il patrimonio appartiene all'associazione ed è destinato esclusivamente al suo scopo. Lo statuto stabilisce che gli strumenti digitali di governance non rappresentano quote del patrimonio, e questa separazione è il presupposto di tutto ciò che segue.

Un terzo elemento, $FDX, è esterno all'associazione e non fa parte della sua architettura. È descritto al paragrafo 4.6 per completezza di informazione.

## 4.2 Il Pass

Il Pass è la credenziale di partecipazione descritta nel capitolo 3. Nell'architettura svolge una funzione di collegamento: associa un wallet a una posizione del registro dei membri e, attraverso questa, a una categoria, a un livello di contributo e a un metodo di verifica.

Fino a quando il relativo contratto non sarà stato sottoposto a verifica indipendente del codice, la posizione del membro risulta dall'iscrizione nel registro, la cui impronta è ancorata a una blockchain pubblica. Successivamente il Pass sarà emesso come credenziale digitale non trasferibile. In entrambe le forme vale la stessa regola: il Pass attesta la partecipazione, non la incorpora e non attribuisce diritti economici.

## 4.3 $FXS oggi: una registrazione di partecipazione

Alla data di questo documento $FXS non esiste come strumento trasferibile. Esiste come registrazione: una annotazione nel registro dell'associazione, riferita a un membro, che ne documenta la partecipazione alla fase iniziale e il peso nella governance.

Il Regolamento iniziale prevede tre casi di attribuzione. Il primo riguarda chi versa contributi volontari al fondo comune, secondo una tabella pubblicata nel protocollo prima del versamento. Il secondo riguarda il socio che completa la verifica con World ID, al quale è attribuita una registrazione pari al controvalore del Livello I. Il terzo riguarda i riconoscimenti del programma PSRP, il budget unico degli incentivi della fase iniziale, alle condizioni del relativo documento. Nessuna registrazione è attribuita gratuitamente a chi lavora per l'associazione.

Le registrazioni sono soggette a quattro limiti stabiliti dallo statuto. Non sono trasferibili. Non danno diritti sul patrimonio, né diritto a rendimento o a protezione. Non sono oggetto di annuncio o di richiesta di ammissione a una piattaforma di negoziazione. Le nuove attribuzioni si sospendono quando il totale raccolto nei dodici mesi o il numero di persone raggiunte in uno Stato dell'Unione europea toccano le soglie indicate dallo statuto, finché non siano adempiuti gli obblighi di legge che ne derivano; il Consiglio tiene e pubblica i due contatori.

Nella fase attuale le registrazioni hanno una funzione delimitata. Il voto ponderato in assemblea si calcola sul livello di contributo del socio verificato, non su $FXS. Le registrazioni determinano invece il peso con cui i soci verificati eleggono il Board di controllo, l'organo che vigila sull'operato del Consiglio.

## 4.4 $FXS domani: moduli non attivi

Lo statuto individua alcune funzioni come moduli non attivi. Due riguardano $FXS: la sua emissione come strumento trasferibile e ogni legame tra strumenti di governance e valori della tesoreria. Finché un modulo non è attivo, la funzione corrispondente non può essere offerta né annunciata come disponibile.

L'attivazione richiede che ricorrano insieme più condizioni: una delibera dei soci con la maggioranza dei due terzi e la maggioranza ponderata; il raggiungimento della soglia minima di raccolta; il rilascio delle autorizzazioni e il compimento degli adempimenti che la legge richiede per quella funzione. Per l'emissione come strumento trasferibile lo statuto indica la notifica e la pubblicazione del documento informativo previsto dal regolamento europeo sui mercati delle cripto-attività, oppure il prospetto qualora $FXS fosse qualificato come strumento finanziario, e in Svizzera l'affiliazione a un organismo di autodisciplina in materia di riciclaggio se fosse qualificato come mezzo di pagamento. La qualificazione giuridica di $FXS non è ancora accertata ed è parte delle verifiche che precedono ogni decisione.

Lo statuto regola fin d'ora gli effetti dell'eventuale attivazione sulla governance. Il voto ponderato si calcolerebbe sul $FXS detenuto dai soci verificati, in luogo del livello di contributo e con il tetto previsto dal Regolamento. Resterebbe ferma la doppia maggioranza, per persone e ponderata: il peso di $FXS non potrebbe mai prevalere da solo sulla maggioranza dei soci. La delibera di attivazione fisserebbe la data del passaggio e la conversione delle registrazioni virtuali.

L'orientamento di progetto è che la circolazione di $FXS, se attivata, resti limitata ai membri verificati e non sia destinata alla negoziazione su piattaforme aperte. Tra le ipotesi allo studio vi è un modello in cui l'emissione e il ritiro dello strumento siano riferiti al valore contabile della riserva, sull'esempio delle strutture mutualistiche già esistenti nel settore. Si tratta di un'ipotesi, non di una regola adottata: richiederebbe l'attivazione del modulo relativo al legame con la tesoreria, con tutte le condizioni indicate, e non costituisce un'aspettativa per chi oggi riceve una registrazione.

## 4.5 Che cosa $FXS non è

$FXS non è una quota del patrimonio dell'associazione, né un titolo rappresentativo della riserva. Non è una partecipazione al capitale e non dà diritto a utili, che l'associazione non distribuisce. Non attribuisce un diritto a prestazioni di protezione. Il risultato dell'impiego dei fondi dell'associazione resta al patrimonio sociale e non è collegato a $FXS.

Chi riceve una registrazione acquisisce un peso nella governance e la documentazione della propria partecipazione. Nient'altro è promesso, e nulla di quanto potrebbe essere attivato in futuro è dovuto.

## 4.6 $FDX

$FDX è un token di comunità promosso dal fondatore del progetto ed emesso tramite una piattaforma di terzi, che ne gestisce il contratto. Non è emesso dall'associazione e lo statuto non lo menziona. Ha una funzione di coinvolgimento e di visibilità della comunità.

$FDX è separato dall'architettura descritta in questo capitolo. Non attribuisce la qualità di membro, non conferisce diritti di voto né peso nella governance, non dà diritti sul patrimonio o sulla riserva dell'associazione e non dà accesso a meccanismi di protezione. Detenerlo o scambiarlo non comporta alcun rapporto con l'associazione e nessuna aspettativa nei suoi confronti. Come ogni strumento di questo tipo, può perdere interamente il proprio valore.

Due punti di contatto esistono e sono dichiarati. Il Consiglio può accettare $FDX, come ogni altro attivo, per i versamenti dei membri, registrandone l'importo nominale e il valore al momento del versamento. Le somme che la piattaforma di emissione riconosce in relazione agli scambi del token affluiscono a un wallet dell'associazione: quando vi entrano diventano patrimonio sociale, sono registrate come proventi collegati al protocollo e sono destinate al compartimento di riserva. A questi proventi non è collegata alcuna attribuzione a favore di chi detiene o scambia $FDX.

## 4.7 Quadro di sintesi

| Elemento | Funzione | Stato alla data del documento | Che cosa non attribuisce |
|---|---|---|---|
| Pass | Attesta la partecipazione e collega il wallet al registro | Iscrizione nel registro; credenziale non trasferibile dopo la verifica del contratto | Qualità di membro in sé, diritti economici |
| $FXS | Peso nella governance e documentazione della partecipazione | Registrazione virtuale non trasferibile; incide sull'elezione del Board di controllo | Quote del patrimonio, rendimento, protezione |
| $FXS trasferibile e legame con la tesoreria | Moduli futuri | Non attivi; attivabili solo alle condizioni dello statuto | Alcuna aspettativa prima dell'attivazione |
| $FDX | Coinvolgimento della comunità | Esterno all'associazione, emesso da terzi | Qualità di membro, voto, diritti sul patrimonio, protezione |

---

# 5. Patrimonio, compartimenti e fondi di terzi

*La materia è disciplinata dagli artt. 4, 27, 29, 33 e 35–36 dello statuto e dal Regolamento di governance, che prevalgono su questo capitolo.*

## 5.1 Un patrimonio vincolato allo scopo

Il patrimonio di FIÐEX appartiene all'associazione ed è destinato esclusivamente al suo scopo. Non è ripartito in quote, non produce utili da distribuire e non è rappresentato da alcuno strumento digitale. Dei debiti dell'associazione risponde soltanto il patrimonio sociale: i membri non ne rispondono personalmente e non hanno obblighi di versamento oltre la quota di adesione.

Le fonti del patrimonio sono cinque: le quote di adesione; i contributi volontari dei membri al fondo comune; le donazioni e i lasciti; i proventi delle attività strumentali, compresi i corrispettivi dei servizi, insieme ai contributi di enti pubblici o privati; i proventi collegati al protocollo, cioè le somme generate da attività di terzi che affluiscono ai wallet dell'associazione e ne diventano proprietà.

La trasparenza che il progetto si propone non consiste nel dichiarare queste regole, ma nel renderne verificabile l'applicazione. I paragrafi che seguono descrivono come i fondi sono classificati all'ingresso, come sono ripartiti, chi può disporne e come chiunque può controllarlo.

## 5.2 Il titolo di ogni versamento

Ogni versamento è registrato secondo il suo titolo, che il protocollo indica prima che il versamento sia eseguito. I titoli sono quattro.

La **quota di adesione** è il versamento che accompagna l'ingresso nell'associazione e coincide con il Livello I. Il **contributo volontario** è il versamento ulteriore al fondo comune: è definitivo, salvi i casi di ripartizione previsti dallo statuto e descritti nel capitolo 6, e può dare luogo alle registrazioni di partecipazione. La **donazione** è un versamento al quale non è collegata alcuna attribuzione al donatore. Il **provento collegato al protocollo** è la somma proveniente da attività di terzi, destinata al compartimento indicato dal Regolamento e priva di qualunque attribuzione.

Un versamento privo di titolo è trattato come contributo volontario. Di ogni versamento si registrano l'importo nominale nell'attivo ricevuto e il suo valore al momento della ricezione, così che la contabilità resti leggibile anche quando gli attivi versati sono diversi tra loro e variano di valore nel tempo.

## 5.3 I quattro compartimenti

Il Consiglio tiene i fondi in quattro compartimenti distinti, ciascuno con wallet e conti propri.

| Compartimento | Funzione | Stato |
|---|---|---|
| Raccolta | Accoglie i versamenti ancora soggetti al diritto di recesso e, fino alla soglia minima, la parte vincolata dei contributi volontari | Attivo |
| Operativo | Finanzia sviluppo, verifiche del codice, consulenza legale, gestione e compensi | Attivo |
| Riserva | Costituisce la base patrimoniale dei futuri meccanismi di protezione | Attivo come accantonamento; nessun utilizzo per protezione prima dell'attivazione del relativo modulo |
| Richieste future | Destinato all'esame e alla liquidazione delle richieste | Non attivo |

Il Regolamento iniziale fissa le regole di alimentazione. Fino al raggiungimento della soglia minima di raccolta, pari al controvalore di 600.000 USDT di contributi volontari, almeno l'80% di tali contributi resta nel compartimento di raccolta: la parte che può essere spesa nella fase di avvio è quindi limitata a un quinto e segue il preventivo pubblicato. Dopo il raggiungimento della soglia, almeno il 40% dei contributi volontari è destinato alla riserva, e questa quota cresce per scaglioni fino al 70% al raggiungimento del tetto di raccolta. I proventi collegati al protocollo sono destinati per intero alla riserva.

I passaggi di fondi tra compartimenti seguono il preventivo approvato dall'assemblea e sono pubblicati nel protocollo.

È necessaria una precisazione sulla natura di questa ripartizione. I compartimenti sono una separazione contabile e operativa interna: rendono leggibile la destinazione dei fondi e ne vincolano l'uso per gli organi dell'associazione. Non creano patrimoni giuridicamente separati verso i terzi. Un creditore dell'associazione può rivalersi sull'intero patrimonio sociale, a prescindere dal compartimento.

## 5.4 Custodia, firme e chiavi

I fondi sono custoditi in wallet a firma multipla. I firmatari sono membri del Consiglio o persone da esso designate per nome; nessuno detiene più di una chiave e nessuno può disporre dei fondi da solo. Ogni disposizione esegue una decisione del Consiglio messa a verbale, e il verbale indica chi ha deciso e da dove.

Le chiavi che consentono di amministrare e aggiornare il protocollo sono tenute in un wallet a firma multipla distinto da quello dei fondi. Il promotore dell'associazione e chi sviluppa il protocollo non ne sono firmatari e non controllano da soli i rilasci: chi scrive il codice non può modificarlo in produzione senza una decisione del Consiglio. Una chiave persa, compromessa o appartenente a un firmatario cessato è sostituita entro un termine definito.

In caso di attacco, di chiave compromessa o di grave vulnerabilità, il Consiglio può sospendere per un periodo limitato funzioni del protocollo, nuove adesioni e disposizioni di fondi. Durante la sospensione i fondi possono essere spostati soltanto verso altri wallet dell'associazione soggetti alle stesse regole. Il Consiglio ne pubblica i motivi, informa il Board di controllo e riferisce all'assemblea; la proroga oltre il termine richiede il parere favorevole del Board o una delibera dell'assemblea.

## 5.5 Impiego dei fondi

I fondi dei compartimenti possono essere impiegati soltanto in strumenti liquidi e a basso rischio, secondo una politica di impiego approvata dall'assemblea. La liquidità è un requisito, non una preferenza: fondi immobilizzati non potrebbero servire né alle spese dell'associazione né, in futuro, alle funzioni cui la riserva è destinata.

Il risultato dell'impiego, positivo o negativo, resta al patrimonio sociale. Non è attribuito ai membri e non è collegato a strumenti di governance. L'associazione non indica obiettivi di rendimento; rende pubblica la composizione dei fondi e il loro andamento effettivo, a consuntivo.

## 5.6 Fondi di terzi

Dai fondi dell'associazione vanno tenuti distinti i fondi che essa potrebbe detenere per conto di altri, in particolare come deposito vincolato a garanzia dell'esecuzione di un accordo tra due parti, nell'ambito dei servizi descritti nel capitolo 9.

Questi fondi non fanno parte del patrimonio sociale e non sono mezzi dell'associazione, che non ne può disporre. Lo statuto ne fissa il regime. Sono detenuti soltanto in base a un contratto scritto con le parti. Sono tenuti in wallet e conti distinti, con un identificativo per ogni pratica. Non possono essere impiegati, dati in garanzia, compensati con crediti dell'associazione né compresi in alcuna ripartizione; in caso di scioglimento sono rilasciati o restituiti secondo il contratto. Le condizioni di rilascio, chi le accerta e i rimedi sono stabiliti dal contratto, e nessun organo dell'associazione può mutarli dopo il deposito: l'assemblea non decide sulle singole pratiche. Chi accerta le condizioni di rilascio non è firmatario della stessa pratica. Un registro pubblico riporta, per ogni pratica, identificativo, attivo, importo e stato, senza dati identificativi delle parti.

Sono mezzi dell'associazione soltanto i corrispettivi dei servizi resi in relazione a tali depositi.

La custodia di attivi per conto di terzi è un modulo non attivo. Può essere attivata solo con delibera dei soci e dopo il rilascio delle autorizzazioni che la legge richiede. Fa eccezione il deposito vincolato nel quale l'associazione non ha alcun potere di disporre dei fondi, eseguito da un contratto automatico che li rilascia soltanto alle condizioni concordate: può essere offerto prima, se il Consiglio ha accertato per iscritto che non costituisce custodia secondo la legge applicabile. Alla data di questo documento nessun deposito di terzi è accettato.

## 5.7 Contabilità, controllo e pubblicità

Il Consiglio tiene la contabilità secondo la legge e cura gli adempimenti fiscali; l'esercizio coincide con l'anno civile. Il conto annuale è pubblicato nel protocollo insieme ai saldi dei wallet per compartimento. La contabilità è sottoposta a revisione ordinaria quando la legge lo impone; negli altri casi l'assemblea elegge un revisore abilitato e indipendente per una revisione limitata.

Il Board di controllo ha accesso ai verbali del Consiglio, alla contabilità e ai movimenti dei wallet, ed esprime un parere pubblico sul preventivo e sul conto annuale. I compensi sono pagati soltanto dal compartimento operativo, per prestazioni effettive, e sono pubblicati nel conto annuale.

A questi presìdi periodici si aggiunge la verificabilità continua. Gli indirizzi dei wallet di ciascun compartimento sono pubblici, i saldi sono leggibili in ogni momento dalle registrazioni delle reti su cui i fondi si trovano, e il Genesis Observatory li presenta in forma ordinata insieme ai contributi registrati. Chiunque può confrontare ciò che l'associazione dichiara con ciò che le reti registrano, senza dover fare affidamento sul sito dell'associazione.

## 5.8 Limiti

L'architettura descritta riduce alcuni rischi e non ne elimina altri. Rende difficile disporre dei fondi in modo arbitrario o occulto; non protegge il patrimonio dalle variazioni di valore degli attivi in cui è detenuto, dai difetti dei contratti e delle reti su cui è custodito, né dalle pretese dei creditori dell'associazione. I fondi accantonati nella riserva non costituiscono una garanzia per i membri e non attribuiscono loro alcun diritto. Il capitolo 13 espone i rischi nel loro insieme.

---

# 6. Raccolta, livelli e incentivi

*La materia è disciplinata dagli artt. 11 e 36–39 dello statuto e dai §§ 1, 9, 10 e 12 del Regolamento di governance, che prevalgono su questo capitolo.*

## 6.1 Natura della raccolta

La costruzione dell'infrastruttura è finanziata dai membri. Chi ha aderito può versare al fondo comune contributi volontari, in aggiunta alla quota di adesione. La raccolta è dunque una campagna di finanziamento interna all'associazione: si rivolge a chi ne ha accettato lo statuto, e i fondi entrano in un patrimonio vincolato allo scopo.

Il contributo volontario è definitivo. Non è un prestito, non è un deposito e non è il prezzo di una prestazione futura. Chi contribuisce sostiene lo sviluppo del protocollo, la struttura giuridica, le verifiche indipendenti del codice e la formazione di una riserva. In cambio non acquisisce un credito verso l'associazione, ma una registrazione che documenta la sua partecipazione e, per i soci verificati, un peso nella governance.

Il fatto che la raccolta avvenga tra membri non la sottrae alle norme sulle offerte al pubblico. Lo statuto ne tiene conto con i limiti descritti al paragrafo 6.6.

## 6.2 Soglia minima e tetto

La raccolta ha due riferimenti quantitativi. La **soglia minima** è fissata dal Regolamento iniziale nel controvalore di 600.000 USDT di contributi volontari. Il **tetto** è il livello al quale la raccolta si chiude.

La soglia minima non è un obiettivo commerciale: è la condizione al di sotto della quale l'associazione ritiene di non poter svolgere il proprio programma. Per questo lo statuto vi collega più effetti. Fino al suo raggiungimento la maggior parte dei contributi resta vincolata; nessun modulo futuro può essere attivato; non può essere costituito alcun ente operativo. Se non è raggiunta entro il termine previsto, si applica la ripartizione descritta al paragrafo 6.7.

## 6.3 Destinazione dei contributi

Fino alla soglia minima almeno l'80% dei contributi volontari resta nel compartimento di raccolta. La parte restante può finanziare le spese di avvio previste dal preventivo pubblicato: sviluppo, consulenza legale, verifiche del codice, gestione.

Raggiunta la soglia, i contributi sono ripartiti tra il compartimento operativo e la riserva secondo il preventivo approvato dall'assemblea. Alla riserva è destinato almeno il 40% dei contributi volontari, e questa quota cresce per scaglioni fino al 70% al raggiungimento del tetto. La logica è che il costo di costruzione dell'infrastruttura è in larga parte fisso: superata la fase di avvio, ogni contributo ulteriore deve rafforzare in misura crescente la base patrimoniale dei futuri meccanismi di protezione.

Chi contribuisce deve quindi sapere che il suo versamento finanzia due cose distinte: la costruzione dell'infrastruttura, che è una spesa, e la riserva, che è un accantonamento. Le proporzioni sono pubbliche prima del versamento e verificabili dopo.

## 6.4 I livelli di contributo

I tre livelli sono stati descritti nel capitolo 3. Il Livello I coincide con la quota di adesione, fissata nel controvalore di 5 dollari. I Livelli II e III partono dal controvalore di 1.000 e di 10.000 dollari. Il livello si determina sulla somma dei versamenti del membro, al valore registrato al momento di ciascuno, e incide soltanto sul peso del voto ponderato del socio verificato.

## 6.5 Il coefficiente di fase

Chi aderisce quando l'infrastruttura è meno matura sopporta un'incertezza maggiore di chi aderisce più tardi: la soglia minima potrebbe non essere raggiunta e il programma potrebbe non realizzarsi. Il Regolamento prevede uno strumento per tenerne conto, il coefficiente di fase, che può applicarsi ai Livelli II e III.

Il coefficiente riduce il contributo richiesto per raggiungere un livello, in funzione dell'avanzamento della raccolta. È massimo all'avvio, decresce in modo lineare fino alla soglia minima, prosegue con una pendenza minore tra la soglia e il tetto e si annulla al tetto. Non dipende dal calendario ma dal totale raccolto, che è verificabile nel protocollo, e si applica per scaglioni pari a un decimo dell'intervallo, così che il valore vigente sia sempre noto prima del versamento.

Quattro regole ne delimitano la portata. Il contributo richiesto non supera mai il valore nominale del livello: dopo il tetto resta stabile e non esiste una progressione ulteriore. Il livello, il peso del voto e le registrazioni di $FXS sono quelli del valore nominale, per tutti: chi aderisce prima ottiene la stessa posizione con un contributo minore, non una posizione maggiore. Il costo complessivo del coefficiente è imputato a un capitolo del budget degli incentivi e non può superarne il tetto. Le registrazioni non sono trasferibili: la riduzione non può essere convertita in un guadagno cedendo la posizione.

Il coefficiente si applica soltanto dalla pubblicazione nel protocollo della tabella degli scaglioni, decisa dal Consiglio. Alla data di questo documento i parametri non sono fissati e la tabella non è pubblicata.

## 6.6 Registrazioni e budget degli incentivi

A chi versa contributi volontari è attribuita una registrazione di $FXS in forma virtuale, secondo una tabella pubblicata nel protocollo prima del versamento. La natura e i limiti di queste registrazioni sono descritti nel capitolo 4: non sono trasferibili e non danno diritti sul patrimonio, né diritto a rendimento o a protezione.

Gli incentivi della fase iniziale sono raccolti in un unico budget, il PSRP, soggetto a un tetto complessivo. Il budget si articola in quattro capitoli: il riconoscimento della fase Genesis, rivolto ai primi membri; l'assegnazione di verifica, pari al controvalore del Livello I, per il socio che completa la verifica con World ID; il coefficiente di fase; il riconoscimento della partecipazione documentata. Criteri e tetti di ciascun capitolo sono fissati nel documento PSRP, pubblicato nel protocollo.

La scelta di un budget unico ha una ragione di trasparenza. Ogni incentivo, comunque denominato, riduce le risorse disponibili per gli altri impieghi o amplia il numero delle registrazioni. Riunirli sotto un solo tetto, dichiarato in anticipo, permette a chi contribuisce di conoscerne il peso complessivo.

Nessuna registrazione è attribuita gratuitamente a chi lavora per l'associazione. Il gruppo di lavoro è compensato soltanto dal compartimento operativo, per prestazioni effettive.

## 6.7 Limiti della raccolta

Lo statuto pone tre limiti a tutela dei membri e del rispetto della legge.

Il Consiglio tiene e pubblica due contatori: il totale raccolto negli ultimi dodici mesi e il numero di persone raggiunte in ciascuno Stato dell'Unione europea. Al raggiungimento delle soglie indicate dallo statuto sospende le nuove attribuzioni di registrazioni, finché non siano adempiuti gli obblighi che la legge collega al superamento di quelle soglie.

L'associazione non annuncia e non chiede l'ammissione delle registrazioni a una piattaforma di negoziazione.

Il membro che aderisce come consumatore può recedere entro quattordici giorni; fino alla scadenza del termine i suoi versamenti restano nel compartimento di raccolta.

## 6.8 Se la soglia minima non è raggiunta

Il Consiglio pubblica la data di apertura delle adesioni. Se entro dodici mesi da quella data la soglia minima non è raggiunta, lo statuto prevede che il Consiglio ripartisca i contributi volontari tra i membri che li hanno versati, senza bisogno di una delibera.

La ripartizione avviene pro quota, in proporzione agli importi nominali versati, su quanto resta dei contributi volontari dopo il pagamento dei debiti e delle spese sostenute secondo il preventivo pubblicato. Nessun membro riceve più di quanto ha versato. Le quote di adesione e le donazioni non sono ripartite. Conclusa la ripartizione, i soci decidono se proseguire l'attività o sciogliere l'associazione.

Questa regola va letta per ciò che è. Non è una garanzia di restituzione e non attribuisce al membro un credito di importo determinato. Poiché una parte dei contributi può essere spesa nella fase di avvio, e poiché il valore degli attivi versati può variare, quanto ripartito può essere inferiore a quanto versato. La regola stabilisce un criterio di ripartizione di ciò che resta, uguale per tutti, nel caso in cui il programma non possa partire.

## 6.9 Ripartizione deliberata

Fuori da questo caso, l'assemblea può deliberare, su proposta del Consiglio e con le maggioranze qualificate, la ripartizione ai membri di una parte dei contributi volontari. La delibera deve rispettare quattro condizioni: la ripartizione avviene pro quota tra tutti i membri che hanno versato contributi volontari; nessuno riceve più di quanto ha versato; l'importo resta entro il patrimonio netto dell'ultimo conto annuale, dedotti debiti e spese previste; l'ufficio di revisione attesta che non pregiudica i creditori né lo scopo.

Nessun membro ha diritto a che la ripartizione sia deliberata.

## 6.10 Quadro dei parametri

| Parametro | Valore | Stato |
|---|---|---|
| Quota di adesione (Livello I) | Controvalore di 5 USD | Fissato nel Regolamento iniziale |
| Livello II / Livello III | Da 1.000 USD / da 10.000 USD | Fissati nel Regolamento iniziale |
| Soglia minima di raccolta | 600.000 USDT di contributi volontari | Fissata nel Regolamento iniziale |
| Quota vincolata fino alla soglia | Almeno 80% dei contributi volontari | Fissata |
| Quota destinata alla riserva dopo la soglia | Dal 40% al 70%, per scaglioni | Fissata; scaglioni da pubblicare |
| Termine per il raggiungimento della soglia | Dodici mesi dall'apertura delle adesioni | Previsto dallo statuto |
| Tetto di raccolta | — | Da fissare |
| Tetto del budget degli incentivi (PSRP) | — | Da fissare |
| Parametri del coefficiente di fase | — | Da fissare; tabella non pubblicata |
| Tabella delle registrazioni $FXS | — | Da pubblicare prima dell'apertura |

Il Regolamento può essere modificato dall'assemblea con le maggioranze previste; le disposizioni sulla soglia minima sono modificate dai soli soci. Ogni modifica vale dalla finestra di voto successiva ed è pubblicata con la propria impronta.

---

# 7. Soglie operative

*La materia è disciplinata dagli artt. 37, 40–42 e 50 dello statuto e dal Regolamento di governance, che prevalgono su questo capitolo. Il paragrafo 7.5 espone ipotesi di lavoro che non sono regole dell'associazione.*

## 7.1 Condizioni, non date

Un progetto in costruzione può descrivere il proprio futuro in due modi. Può indicare date, e allora chi legge deve fidarsi della capacità di rispettarle. Oppure può indicare condizioni, e allora chi legge può verificare da sé se si sono realizzate. FIÐEX adotta il secondo modo.

Nessuna funzione dell'associazione si attiva al trascorrere del tempo. Ogni funzione si attiva quando ricorrono condizioni dichiarate in anticipo, accertabili dalle registrazioni pubbliche e, per le più rilevanti, approvate dai soci con maggioranza qualificata. Questo capitolo raccoglie tali condizioni in un unico quadro, perché sia chiaro in ogni momento che cosa è attivo, che cosa non lo è e che cosa dovrebbe accadere perché lo diventi.

## 7.2 Che cosa è attivo dall'avvio

L'associazione comincia a operare, e ad accettare adesioni e versamenti, soltanto dopo l'insediamento del Consiglio: quando tutti i suoi membri hanno accettato la carica per iscritto e i wallet a firma multipla sono operativi.

Da quel momento sono attive le funzioni che non richiedono autorizzazioni e non comportano l'assunzione di rischi altrui: l'adesione e il registro dei membri; il Genesis Observatory con la pubblicazione dei fondi per compartimento; la raccolta dei contributi volontari con le relative registrazioni; l'assemblea, le proposte e il voto. I servizi documentali descritti nel capitolo 9 possono essere avviati dal Consiglio come attività strumentale, nei limiti dello statuto.

Non è attivo alcun meccanismo di protezione, non esiste $FXS come strumento trasferibile e l'associazione non custodisce attivi per conto di terzi.

## 7.3 Le soglie che modificano il funzionamento

Lo statuto e il Regolamento collegano alcuni effetti al raggiungimento di soglie determinate.

| Soglia | Effetto |
|---|---|
| Insediamento del Consiglio | Inizio dell'attività; apertura di adesioni e versamenti |
| Cento soci verificati, e comunque entro sei mesi dall'apertura delle adesioni | Elezione del primo Board di controllo; fino ad allora l'ufficio di revisione riferisce direttamente all'assemblea |
| Soglia minima di raccolta (600.000 USDT di contributi volontari) | Cessa il vincolo dell'80% sul compartimento di raccolta; si applica la quota minima destinata alla riserva; diventa possibile deliberare l'attivazione dei moduli e la costituzione di un ente operativo |
| Mancato raggiungimento della soglia minima entro dodici mesi | Ripartizione dei contributi volontari residui e decisione dei soci sulla prosecuzione |
| Contatori di raccolta e di persone raggiunte per Stato dell'Unione europea | Sospensione delle nuove attribuzioni di registrazioni fino all'adempimento degli obblighi di legge |
| Tetto di raccolta | Chiusura della raccolta; quota destinata alla riserva al livello massimo; coefficiente di fase pari a zero |
| Attivazione di $FXS come strumento trasferibile | Il voto ponderato si calcola su $FXS; cessa la verifica per garanzia |

Alcune di queste soglie producono effetti automatici, altre aprono soltanto una possibilità. Il raggiungimento della soglia minima di raccolta appartiene alla seconda specie: rende ammissibile una delibera, non la sostituisce.

## 7.4 I moduli non attivi

Lo statuto individua quattro funzioni come moduli non attivi. Finché un modulo non è attivo, la funzione non può essere offerta né annunciata come disponibile, e l'associazione non assume rischi altrui verso corrispettivo.

Per ciascun modulo l'attivazione richiede che ricorrano insieme tre condizioni comuni: una delibera dei soci adottata con i due terzi dei votanti e la maggioranza ponderata; il raggiungimento della soglia minima di raccolta; il rilascio delle autorizzazioni e il compimento degli adempimenti che la legge richiede per quella funzione. Per i meccanismi di protezione si aggiunge una quarta condizione: una capacità di riserva documentata.

| Modulo | Autorizzazioni e adempimenti indicati dallo statuto, nella misura in cui la legge li richiede |
|---|---|
| Emissione di $FXS come strumento trasferibile | Notifica e pubblicazione del documento informativo previsto dal regolamento europeo sui mercati delle cripto-attività, oppure prospetto se $FXS è qualificato come strumento finanziario; in Svizzera, affiliazione a un organismo di autodisciplina se è qualificato come mezzo di pagamento |
| Meccanismi di protezione mutualistica ed esame delle richieste | Autorizzazione dell'autorità svizzera di vigilanza sui mercati finanziari secondo la legge sulla sorveglianza degli assicuratori; per l'attività rivolta a residenti in Italia, il titolo previsto dal Codice delle assicurazioni private |
| Legame tra strumenti di governance e valori della tesoreria | Gli adempimenti del primo modulo, secondo la qualificazione che ne deriva |
| Custodia di attivi per conto di terzi | Autorizzazione come prestatore di servizi per le cripto-attività secondo il regolamento europeo; in Svizzera, affiliazione a un organismo di autodisciplina |

Lo statuto indica le autorizzazioni con precisione perché la condizione sia verificabile. Non afferma che esse saranno ottenute, né che la loro richiesta sia già stata presentata. Se un'autorizzazione necessaria non è rilasciata, il modulo non si attiva.

## 7.5 La capacità di riserva: ipotesi di lavoro

Lo statuto richiede, per i meccanismi di protezione, una capacità di riserva documentata, senza fissarne la misura. La misura dovrà risultare da un modello di capitale, cioè da una stima fondata sui dati della frequenza e della gravità degli eventi, e dovrà essere approvata dai soci insieme alla delibera di attivazione.

Il progetto ha però adottato alcuni criteri di orientamento, che derivano dall'esperienza delle strutture mutualistiche già operanti nel settore. La più duratura tra esse ha subordinato l'avvio delle proprie attività di protezione al raggiungimento di un capitale minimo, ha limitato l'esposizione su ciascun singolo rischio a una frazione di quel capitale e ha ampliato il rapporto tra impegni e capitale soltanto con la maturità. I criteri di FIÐEX seguono la stessa progressione.

| Fase | Riserva dedicata | Criteri di orientamento |
|---|---|---|
| Nessuna protezione | Inferiore a 1 milione di dollari | Nessun meccanismo attivabile, a prescindere dalle altre condizioni |
| Avvio sperimentale | Almeno 1 milione | Impegni complessivi non superiori alla riserva; limite per singolo rischio pari a un decimo della riserva; limite per singola richiesta; poche categorie di rischio |
| Capacità estesa | Almeno 3 milioni | Rapporto tra impegni e riserva moderatamente superiore a uno; nuove categorie solo con delibera |
| Regime | Almeno 7 milioni | Parametri fissati da un modello di capitale documentato, con parere tecnico indipendente |

Questi valori sono ipotesi di lavoro. Non sono contenuti nello statuto né nel Regolamento, potranno essere modificati dal modello di capitale e non costituiscono un impegno. Indicano una sola cosa con certezza: l'ordine di grandezza. Con le regole di destinazione descritte nel capitolo 6, il raggiungimento della soglia minima di raccolta non porta la riserva al livello dell'avvio sperimentale. Chi contribuisce nella fase iniziale finanzia la costruzione dell'infrastruttura e l'inizio di un accantonamento, non l'apertura di un servizio di protezione.

## 7.6 Come avviene un'attivazione

L'attivazione di un modulo segue un percorso che lascia traccia pubblica in ogni passaggio. La proposta è presentata nel protocollo con la documentazione che dimostra il ricorrere delle condizioni: il saldo della riserva, leggibile dai wallet; gli atti di autorizzazione; i regolamenti che disciplinano la nuova funzione. I soci votano nella finestra successiva con le maggioranze qualificate. Il risultato è accertato con il conteggio pubblico e riproducibile ed è reso noto con la sua impronta. La delibera indica la data dalla quale la funzione è attiva.

Nessun organo può attivare un modulo in altro modo. Il Consiglio non può farlo con una propria decisione; l'assemblea non può farlo in assenza delle autorizzazioni; il superamento di una soglia di raccolta non lo fa da solo.

## 7.7 Ciò che una soglia non comporta

Il raggiungimento di una soglia non obbliga l'associazione ad attivare alcunché, e nessun membro ha diritto a che una funzione sia attivata. I soci possono ritenere che, pur ricorrendo le condizioni, l'attivazione non sia opportuna, o che lo sia in forma più limitata.

Non dipendono invece da alcuna soglia gli obblighi di trasparenza. La pubblicazione dei fondi per compartimento, del registro, dei verbali e del conto annuale è dovuta dal primo giorno di attività, a prescindere dall'importo raccolto e dal numero dei membri.

---

# 8. Protezione futura e processo di esame delle richieste

*La materia è disciplinata dagli artt. 3, 35 e 40 dello statuto, che prevalgono su questo capitolo. I paragrafi 8.3–8.6 espongono orientamenti di progetto, non regole adottate.*

## 8.1 Stato alla data del documento

FIÐEX non offre protezione. Nessun meccanismo di protezione mutualistica è attivo, nessuna richiesta può essere presentata e nessun membro ha titolo a un intervento dell'associazione in caso di perdita. Lo statuto qualifica i meccanismi di protezione come un obiettivo futuro, li colloca tra i moduli non attivi e vieta di offrirli o annunciarli come disponibili fino alla loro attivazione. Fino ad allora l'associazione non assume rischi altrui verso corrispettivo.

Questo capitolo descrive dunque un progetto, non un servizio. Ha lo scopo di rendere noto in quale direzione l'associazione intende muoversi e quali vincoli si è data, così che i membri possano valutarla e, a suo tempo, decidere.

## 8.2 Perché la protezione viene per ultima

L'ordine dei passi è una scelta di metodo. Una protezione credibile presuppone quattro elementi che non si improvvisano: una riserva proporzionata agli impegni; regole scritte su ciò che è protetto e ciò che non lo è; persone e procedure capaci di esaminare un caso con imparzialità; il titolo giuridico per svolgere l'attività. Promettere protezione prima di disporne significa trasferire sui partecipanti un rischio che non conoscono.

Il capitolo 1 ha mostrato che il rischio in questo settore è concentrato in pochi eventi di grande entità e si distribuisce in famiglie di cause molto diverse. Una struttura che se ne facesse carico senza una riserva adeguata e senza distinguere tra quelle cause potrebbe essere esaurita da un solo evento. Per questo l'associazione costruisce prima ciò che rende il rischio leggibile, cioè registri, governo dei fondi e capacità di analisi dei casi, e rimanda la protezione al momento in cui i presupposti saranno verificabili.

## 8.3 Principi di progetto

Sei principi orientano il disegno dei futuri meccanismi.

**Mutualità.** La protezione è concepita come sostegno reciproco tra membri che condividono un rischio, alimentato da risorse comuni, e non come prodotto offerto al pubblico.

**Capacità limitata e dichiarata.** Gli impegni complessivi non possono eccedere quanto la riserva consente, secondo limiti resi pubblici in anticipo: un limite totale, un limite per ciascun rischio, un limite per ciascuna richiesta. Nessuna protezione è illimitata.

**Categorie definite.** È protetto soltanto ciò che rientra in categorie di evento descritte prima che l'evento si verifichi, con le relative esclusioni. Le diverse famiglie di rischio non sono riunite in una protezione indistinta, perché differiscono per frequenza, gravità e possibilità di accertamento.

**Nessun automatismo.** Nessun intervento è eseguito senza l'esame del caso. Un contratto automatico può eseguire una decisione; non può sostituirla quando occorre accertare fatti e interpretare regole.

**Separazione dei ruoli.** Chi fissa le regole non decide i singoli casi; chi esamina un caso non dispone dei fondi; chi dispone dei fondi esegue una decisione che non ha preso.

**Pubblicità.** Regole, limiti, capacità disponibile ed esiti delle richieste sono pubblici, questi ultimi in forma che non identifichi le persone.

## 8.4 Le categorie di evento

La definizione delle categorie protette appartiene al regolamento che i soci dovranno approvare insieme all'attivazione del modulo. L'orientamento di progetto è partire da un numero ridotto di categorie, scelte tra quelle in cui l'evento è accertabile da registrazioni pubbliche e da analisi tecniche indipendenti, ed estenderle soltanto con delibera, sulla base dell'esperienza maturata.

Per ogni categoria il regolamento dovrà indicare che cosa costituisce l'evento, quali prove sono richieste, quali circostanze escludono l'intervento e quale limite si applica. La chiarezza delle esclusioni ha lo stesso peso della descrizione di ciò che è protetto: un membro deve poter sapere prima, e non dopo, se una determinata perdita rientra nel perimetro.

## 8.5 Il processo di esame

Il compartimento denominato «richieste future» è destinato a questa funzione ed è inattivo. Il processo che lo utilizzerà dovrà essere stabilito dal regolamento della protezione. L'orientamento di progetto prevede cinque passaggi.

Il primo è la presentazione della richiesta, accompagnata da una ricostruzione documentata: transazioni, comunicazioni, relazioni tecniche e ogni altro elemento utile, con la dimostrazione che il richiedente è la persona colpita.

Il secondo è un periodo destinato alla raccolta delle evidenze, durante il quale possono essere acquisiti chiarimenti e analisi ulteriori.

Il terzo è l'esame, affidato a persone qualificate, designate secondo criteri pubblici, prive di interesse nel caso e tenute a dichiarare ogni possibile conflitto. Il loro compenso non dipende dall'esito.

Il quarto è la decisione, sempre motivata e comunicata al richiedente, con la possibilità di chiederne il riesame. Il riesame può comprendere una verifica affidata a un terzo indipendente, anche attraverso sistemi di arbitrato decentralizzato quando le parti lo abbiano convenuto. Tale verifica riguarda il rispetto delle regole e della procedura: se accerta una violazione, il caso è esaminato di nuovo; non sostituisce la decisione e non dispone alcun pagamento.

Il quinto è l'esecuzione, compiuta dai firmatari dei wallet in base alla decisione, e la pubblicazione dell'esito.

## 8.6 Il ruolo dei membri

La protezione mutualistica è governata dai membri, ma su un piano preciso. Ai soci spetta decidere se attivare il modulo e approvarne il regolamento: categorie, criteri, limiti, requisiti di chi esamina, procedura. Spetta loro modificarli, sulla base dei risultati. Spetta loro eleggere e revocare gli organi che ne rispondono.

Non spetta all'assemblea decidere la singola richiesta. Lo statuto riserva al Consiglio gli atti di gestione e di tesoreria e non consente all'assemblea di sostituirsi a esso; un voto collettivo sul caso individuale esporrebbe inoltre la decisione a maggioranze occasionali, a conflitti di interesse e alla diffusione di dati personali. La garanzia per il membro non consiste nel poter votare sul proprio caso, ma nel sapere che il caso sarà esaminato secondo regole che i membri hanno approvato, da persone che non hanno interesse nell'esito.

## 8.7 Natura giuridica e autorizzazioni

L'attività di assumere, verso corrispettivo, il rischio economico di eventi incerti è in molti ordinamenti riservata a soggetti autorizzati. Lo statuto ne tiene conto: tra le condizioni di attivazione del modulo indica l'autorizzazione dell'autorità svizzera di vigilanza secondo la legge sulla sorveglianza degli assicuratori e, per l'attività rivolta a residenti in Italia, il titolo previsto dalla normativa italiana, nella misura in cui la legge li richiede.

La forma giuridica dei futuri meccanismi non è ancora determinata. Dipenderà dall'esito delle verifiche di legge e potrà richiedere che l'attività sia svolta da un ente distinto dall'associazione, dotato dei requisiti patrimoniali e organizzativi necessari. Da essa dipenderà anche la posizione del membro: se e in quali limiti l'intervento costituirà una prestazione dovuta oppure una decisione rimessa all'esame del caso. Questo documento non anticipa la risposta e non descrive come acquisito ciò che dovrà essere accertato.

## 8.8 Che cosa il membro non deve attendersi

L'adesione, il livello di contributo e le registrazioni di $FXS non danno diritto a protezione, né oggi né per effetto dell'eventuale attivazione del modulo: le condizioni di accesso saranno stabilite dal regolamento della protezione e potranno comprendere requisiti e contributi specifici. I fondi accantonati nella riserva non sono vincolati a favore di singoli membri. L'attivazione non è certa, non ha una data e richiede condizioni che potrebbero non realizzarsi.

Chi partecipa a FIÐEX deve continuare a considerare interamente a proprio carico i rischi delle proprie operazioni nei mercati crypto.

## 8.9 Ciò che può precedere la protezione

Tra l'assenza di protezione e la sua attivazione esiste un'attività che non richiede di assumere rischi altrui: aiutare chi ha subito un evento dannoso a ricostruirlo, documentarlo e indirizzarlo. La valutazione documentale di un caso è distinta dalla promessa di un intervento economico e può essere svolta come servizio dell'associazione. È descritta nel capitolo 9, e costituisce anche il modo in cui l'associazione intende formare, prima di ogni protezione, l'esperienza e le competenze che l'esame delle richieste richiederà.

---

# 9. Servizi: FIÐEX Resolve

*La materia è disciplinata dagli artt. 3, 35bis, 40 e 42 dello statuto, che prevalgono su questo capitolo. Il capitolo descrive un programma: alla data del documento nessuno dei servizi è attivo.*

## 9.1 Tra il trasferimento e l'accordo

Una blockchain esegue i trasferimenti in modo automatico e ne conserva una traccia che nessuno può alterare. Non decide però se un trasferimento era dovuto. Il consenso delle parti, l'esatta esecuzione di una prestazione, la responsabilità per un inadempimento e i rimedi disponibili restano questioni che il codice non risolve. Il capitolo 1 ha indicato in questo spazio una fonte di danno distinta dagli attacchi informatici.

FIÐEX Resolve è il programma con cui l'associazione intende presidiare questo spazio. Il principio è semplice: il contratto definisce le obbligazioni, la procedura accerta le condizioni, la blockchain esegue le conseguenze che sono state validamente autorizzate. Resolve non sostituisce il giudice, le autorità o i professionisti abilitati. Trasforma un accordo in una procedura verificabile e una controversia in un fascicolo ordinato, così che chi deve decidere, e chi deve farsi valere, disponga di fatti ricostruiti.

## 9.2 Le quattro aree

**Valutazione documentale degli eventi dannosi.** Chi ha subito una perdita è assistito nel ricostruirla: transazioni, comunicazioni, cronologia, eventuale denuncia. Il risultato è un fascicolo coerente e verificabile, utilizzabile davanti a una piattaforma, a un professionista o a un'autorità. La valutazione di un caso è un'attività documentale e non va confusa con la promessa di un intervento economico, che appartiene ai meccanismi di protezione descritti nel capitolo 8 e non è attiva.

**Assistenza al recupero.** È un supporto organizzativo: individuare l'interlocutore corretto, predisporre la documentazione, seguire le comunicazioni, indirizzare verso professionisti abilitati o autorità competenti. Non comporta alcuna promessa di recupero, alcun potere coercitivo e alcun controllo delle chiavi dell'interessato. La rappresentanza e gli atti riservati dalla legge restano ai professionisti.

**Composizione e verifica dei rapporti.** Comprende la negoziazione documentata tra le parti, la ricerca di una composizione amichevole e la verifica di fatti tecnici da parte di specialisti indipendenti. Tre piani restano distinti. La mediazione è consensuale e, dove la legge la disciplina, è riservata agli organismi e ai mediatori abilitati. La determinazione tecnica di un terzo vale nei limiti del mandato che le parti gli hanno conferito. L'arbitrato richiede una convenzione valida e garanzie proprie. Le decisioni operative dell'associazione non sono presentate come arbitrato.

**Deposito vincolato.** Un valore è vincolato e rilasciato soltanto al verificarsi di condizioni stabilite in anticipo dalle parti. Il deposito è anzitutto un rapporto contrattuale e un processo di controllo; il contratto automatico ne è l'esecutore, non la disciplina. I fondi depositati non appartengono all'associazione e non possono essere impiegati: il loro regime è descritto nel capitolo 5.

## 9.3 Un esempio

Un committente incarica uno sviluppatore di realizzare un'applicazione per un corrispettivo di 12.000 USDC. Le parti formano l'accordo con l'aiuto di modelli procedurali: definiscono le fasi del lavoro, i criteri con cui ciascuna si considera completata, chi li accerta ed entro quale termine. Il corrispettivo è depositato e vincolato a quelle condizioni. Al termine di ogni fase la verifica avviene in contraddittorio, con un termine per le contestazioni. L'esito può essere il rilascio allo sviluppatore, la restituzione al committente o una composizione concordata.

L'utilità del percorso non consiste nell'aver bloccato una somma. Consiste nell'aver reso esplicito e verificabile, prima che sorga un disaccordo, il passaggio dall'obbligazione alla sua liberazione.

## 9.4 Chi svolge che cosa

Lo statuto ripartisce i servizi secondo la loro natura.

I servizi documentali e organizzativi sono un'attività strumentale dell'associazione: apertura e tenuta dei fascicoli, raccolta e ordinamento delle prove, assistenza nei rapporti con piattaforme e controparti, indirizzamento. Lo statuto ne esclude espressamente le prestazioni riservate per legge a professionisti abilitati, le decisioni vincolanti per le parti e le promesse di recupero o di compensazione.

I servizi professionali, la mediazione disciplinata dalla legge, le verifiche tecniche con effetti per le parti e la rappresentanza non sono svolti dall'associazione. Potranno essere affidati a un ente operativo distinto, che i soci possono costituire con maggioranza qualificata dopo il raggiungimento della soglia minima di raccolta.

Per il deposito vincolato vale una distinzione ulteriore. Il deposito nel quale l'associazione non ha alcun potere di disporre dei fondi, eseguito da un contratto automatico alle sole condizioni concordate, può essere offerto quando il Consiglio abbia accertato per iscritto che non costituisce custodia secondo la legge applicabile. Il deposito nel quale l'associazione dispone dei fondi è custodia per conto di terzi: è un modulo non attivo, attivabile soltanto con delibera dei soci e con le autorizzazioni di legge.

## 9.5 Il Resolution Desk

Lo strumento operativo è il Resolution Desk, un ambiente unico per la gestione dei fascicoli. Ogni fascicolo ha un identificativo e riporta soggetti, oggetto, termini, documenti, cronologia, responsabili, decisioni ed eventi registrati su blockchain.

L'accesso a un fascicolo dipende dal ruolo e dal mandato ricevuto su quella pratica, mai dalla sola appartenenza all'associazione: il Pass non consente di consultare pratiche altrui né di impartire istruzioni sui fondi. La documentazione di merito è conservata fuori dalla blockchain; su di essa sono registrate soltanto impronte e marche temporali, così che l'integrità dei documenti sia verificabile senza esporne il contenuto. I fascicoli possono contenere dati personali delicati, compresi dati relativi a reati: il loro trattamento richiede basi giuridiche, minimizzazione e regole di conservazione proprie.

## 9.6 La rete di competenze

I servizi si fondano su una rete interna di competenze, che non è un albo né un organismo abilitato. Vi operano figure con ruoli distinti: membri della comunità, ricercatori, assistenti alle pratiche, ricercatori giuridici, analisti di blockchain, esperti tecnici, professionisti legali abilitati, mediatori e revisori indipendenti.

Quattro posizioni restano separate nella documentazione e nel software: la qualità di membro, il Pass, la qualificazione professionale e l'incarico su una pratica. L'anzianità, i contributi versati o le registrazioni di $FXS non conferiscono titoli professionali né poteri sui fondi vincolati. È previsto un percorso per neolaureati in ambito giuridico, limitato ad attività preparatorie svolte sotto supervisione, che non possono essere presentate come esercizio della professione; il percorso non può fondarsi su lavoro gratuito strutturale.

## 9.7 Regole e pratiche

L'organizzazione distingue due circuiti. Nel circuito associativo i membri, attraverso gli organi dell'associazione, definiscono gli standard, le regole generali, i requisiti e la formazione. Nel circuito professionale le singole pratiche sono trattate da chi ne ha ricevuto l'incarico, secondo regole di nomina, incompatibilità, ricusazione, contraddittorio e riesame.

I due circuiti non si sovrappongono. La governance non vota sui depositi individuali, non modifica retroattivamente le condizioni di un accordo e non si sostituisce al terzo nominato dalle parti. I compensi di chi opera sulle pratiche non dipendono dall'esito né dall'importo rilasciato.

L'appartenenza all'associazione è il criterio di accesso ai servizi. I diritti di difesa e di contraddittorio sono però riconosciuti anche a chi, senza essere membro, è coinvolto in una pratica come controparte.

## 9.8 Sostenibilità economica

I servizi possono generare corrispettivi: istruttoria documentale, gestione delle pratiche, verifiche tecniche, configurazione degli accordi, commissioni dichiarate sui depositi vincolati. Sono proventi di attività strumentali e restano distinti dalle quote di adesione, dai contributi volontari, dai compensi dei professionisti e, soprattutto, dalle somme depositate: il deposito di un terzo non è una risorsa del progetto.

I servizi saranno segmentati per complessità e soggetti a soglie economiche, perché una controversia di valore minimo non sostiene il costo di una procedura completa. I risultati saranno misurati con indicatori di qualità, quali la correttezza delle istruttorie, i tempi, gli accordi raggiunti, i costi medi e la soddisfazione delle parti, e non con il volume dei depositi.

## 9.9 Condizioni di legittimità

Sei condizioni delimitano ciò che potrà essere offerto. La promessa predeterminata di una compensazione rientra nella disciplina assicurativa, quale che sia il nome dato al servizio. La custodia e l'amministrazione di cripto-attività per conto di terzi sono servizi regolati, e conta la sostanza dell'attività più della sua qualificazione come decentralizzata. La consulenza, l'assistenza e la rappresentanza legale sono riservate ai professionisti abilitati. Mediazione e arbitrato hanno presupposti e garanzie propri. Il trattamento dei dati dei fascicoli è soggetto alle norme sulla protezione dei dati. Lo scopo non economico dell'associazione limita le attività che essa può svolgere direttamente.

Nessuna di queste condizioni è superata dal fatto che gli utenti siano membri dell'associazione.

## 9.10 Sequenza di realizzazione

Il programma procede per fasi, ciascuna subordinata al completamento della precedente e alle verifiche che la riguardano.

| Fase | Contenuto | Condizione principale |
|---|---|---|
| Fondazione | Regole, ruoli, nucleo iniziale della rete, esercitazione su casi simulati | Insediamento degli organi |
| Desk documentale | Apertura dei fascicoli e servizi documentali, senza promesse e senza custodia | Regolamento dei servizi e regole sul trattamento dei dati |
| Accordi e composizione | Modelli procedurali e composizione su casi senza custodia, con professionisti coinvolti nel disegno | Accertamento del perimetro delle attività riservate |
| Deposito vincolato sperimentale | Contratto circoscritto, sottoposto a verifica indipendente del codice, con importi limitati | Qualificazione giuridica del deposito; per la custodia, attivazione del modulo |
| Protezione e procedure avanzate | Collegamento con i meccanismi del capitolo 8 | Attivazione del relativo modulo |

L'ultima fase non discende automaticamente dalle precedenti. Nessun servizio sarà annunciato come disponibile prima che ne ricorrano le condizioni.

---

# 10. Governance

*La materia è disciplinata dagli artt. 17–34, 41 e 44 dello statuto e dal Regolamento di governance, che prevalgono su questo capitolo. I valori numerici indicati sono quelli del Regolamento iniziale e possono essere modificati dall'assemblea.*

## 10.1 Il problema che la governance deve risolvere

Il capitolo 1 ha indicato nella governance una superficie di rischio: nelle organizzazioni decentralizzate il voto tende a concentrarsi in poche mani, la partecipazione è ridotta e i diritti di voto, quando sono liberamente trasferibili, possono essere acquisiti per il tempo di una sola decisione. Un sistema fondato soltanto sul peso economico consegna le decisioni a chi ha contribuito di più. Un sistema fondato soltanto sul numero delle persone, senza verificarne l'unicità, le consegna a chi è in grado di moltiplicare le proprie identità.

La governance di FIÐEX è costruita per non dipendere da nessuna delle due misure presa da sola. Le decisioni richiedono insieme il consenso delle persone e il consenso del contributo. Chi amministra è identificato, risponde a un organo di controllo e può essere revocato. Ogni voto e ogni conteggio sono verificabili da chiunque.

## 10.2 Gli organi

Gli organi dell'associazione sono quattro.

L'**assemblea** è l'organo supremo. Riunisce i membri e delibera in forma elettronica tramite il protocollo, con voti espressi mediante firma crittografica.

Il **Consiglio** amministra e rappresenta l'associazione. È composto da almeno tre persone fisiche identificate per nome, che svolgono la funzione dalla Svizzera; almeno due vi sono domiciliate. Gli spettano le decisioni di gestione e di tesoreria, l'ammissione dei membri, la tenuta del registro e della contabilità. Opera entro gli indirizzi e il preventivo approvati dall'assemblea, decide a maggioranza e mette a verbale chi ha deciso e da dove. Il primo Consiglio è nominato nell'atto costitutivo; i successivi sono eletti dall'assemblea.

Il **Board di controllo** vigila sul rispetto dello statuto, del Regolamento e delle delibere da parte del Consiglio. È composto da soci verificati che non fanno parte del Consiglio e non hanno incarichi retribuiti dall'associazione. Ha accesso ai verbali, alla contabilità e ai movimenti dei wallet, esprime un parere pubblico sul preventivo e sul conto annuale, pubblica almeno una relazione all'anno, può chiedere la convocazione dell'assemblea e proporre la revoca del Consiglio. Non amministra e non dispone dei fondi; i suoi pareri non vincolano il Consiglio, che deve però motivare per iscritto quando se ne discosta.

L'**ufficio di revisione** verifica la contabilità nei casi e nelle forme previsti dalla legge e dallo statuto.

## 10.3 Chi vota e con quale peso

Il diritto di voto dipende dalla categoria del membro e dalla materia.

Nelle materie riservate votano soltanto i soci, cioè i membri che hanno completato la verifica di unicità. Nelle materie ordinarie votano tutti i membri, ciascuno con un voto.

Accanto al voto per persona esiste il voto ponderato, che spetta ai soci verificati con World ID o identificati presso il Consiglio. Il peso di ciascuno è la radice quadrata del rapporto tra i suoi versamenti e la quota del Livello I. La radice quadrata fa crescere il peso molto meno del contributo: chi ha versato cento volte la quota pesa dieci volte, non cento.

| Versamenti del socio verificato | Rapporto con il Livello I | Peso ponderato |
|---|---|---|
| 5 USD (Livello I) | 1 | 1 |
| 1.000 USD (soglia del Livello II) | 200 | circa 14 |
| 10.000 USD (soglia del Livello III) | 2.000 | circa 45 |

Il Regolamento iniziale pone un tetto: il peso di un singolo socio non supera il 5% dei pesi complessivi. I versamenti provenienti da più wallet della stessa persona si sommano, così che il tetto non possa essere aggirato dividendo il contributo.

Un membro non vota sugli affari e sulle liti tra l'associazione e lui stesso, il coniuge o un parente in linea retta.

## 10.4 La doppia maggioranza

Una delibera è adottata soltanto se ottiene due maggioranze distinte: quella delle persone che votano e quella dei voti ponderati espressi. Nessuna delle due può prevalere sull'altra. Un gruppo numeroso di membri con contributi minimi non può imporre una decisione contro chi ha sostenuto in misura maggiore l'associazione; un gruppo ristretto di grandi contributori non può imporla contro la maggioranza delle persone.

Per le decisioni di maggiore rilievo la maggioranza per persone è elevata ai due terzi dei soci votanti. Lo statuto qualifica espressamente la ponderazione come una deroga alla parità di voto prevista in via generale dalla legge svizzera sulle associazioni.

## 10.5 Le materie

| Materia | Chi vota | Maggioranza |
|---|---|---|
| Modifica dello statuto e dello scopo; scioglimento, fusione, trasformazione, trasferimento della sede all'estero | Soci | Due terzi dei votanti e maggioranza ponderata |
| Attivazione dei moduli; ripartizione deliberata; costituzione di un altro ente; cessione dei diritti sul protocollo | Soci | Due terzi dei votanti e maggioranza ponderata |
| Elezione del Consiglio e dell'ufficio di revisione; esclusione dei membri; disposizioni del Regolamento su verifica, peso, quorum riservati e soglia minima | Soci | Maggioranza dei votanti e maggioranza ponderata |
| Conto annuale e discarico; indirizzi generali e preventivo per compartimenti; altre disposizioni del Regolamento; proposte dei membri; riesame degli atti degli organi | Tutti i membri | Maggioranza dei votanti e maggioranza ponderata |

Il Regolamento iniziale richiede, perché la delibera sia valida, la partecipazione di almeno il 20% dei soci nelle materie riservate e di almeno il 10% dei membri nelle materie ordinarie. In caso di parità la proposta è respinta.

L'assemblea indirizza e controlla; non amministra. Non esegue e non decide i singoli atti di gestione e di tesoreria, che spettano al Consiglio.

## 10.6 Finestre di voto e proposte

L'assemblea non si riunisce in una data e in un luogo: delibera per finestre di voto periodiche, il cui calendario e ordine del giorno sono pubblicati in anticipo. Il Regolamento iniziale prevede una finestra al mese, della durata di quattordici giorni, con al massimo cinque proposte: due del Consiglio e tre dei membri, nell'ordine di presentazione.

Ogni membro può presentare proposte nelle materie dell'assemblea e raccomandazioni rivolte al Consiglio. La proposta si presenta nel protocollo con la firma del proponente, il sostegno di altri cinque membri e un versamento pari al controvalore di un dollaro. Il versamento serve soltanto a scoraggiare le proposte prive di serietà ed è registrato come contributo volontario. Il Consiglio verifica entro settantadue ore i soli requisiti formali e la conformità alla legge e allo statuto; il rifiuto è motivato e pubblicato.

Una proposta approvata in una materia dell'assemblea è una delibera. Una raccomandazione approvata vincola il Consiglio a darle seguito entro trenta giorni oppure a pubblicare un rifiuto motivato: il Consiglio può non eseguire, ma non può tacere.

Un quinto dei membri, o il Board di controllo, può chiedere in ogni momento una finestra straordinaria, che il Consiglio deve convocare entro venti giorni. La richiesta non è soggetta a versamento né a controllo di ammissibilità; se il Consiglio non provvede, i richiedenti convocano direttamente tramite il protocollo.

## 10.7 Delega

Un membro può delegare il proprio voto a un altro membro. La delega risulta dal registro pubblico ed è revocabile in ogni momento. Per evitare che la delega ricrei la concentrazione che il sistema vuole impedire, il Regolamento iniziale limita ciò che una persona può ricevere al 2% dei voti per persona e al 5% dei voti ponderati. La delega è esclusa per la revoca per gravi motivi.

## 10.8 Elezione e revoca

Il Consiglio è eletto dall'assemblea ed è rieleggibile. Il Board di controllo è eletto per un anno dai soci verificati, con un voto ponderato secondo le loro registrazioni di $FXS e con il tetto del Regolamento.

La revoca del Consiglio, o di un suo membro, segue due vie. La revoca ordinaria richiede il voto favorevole di almeno il 35% dei soci e la maggioranza ponderata espressa. La revoca per gravi motivi richiede soltanto la maggioranza dei soci votanti, senza quorum, senza ponderazione e senza delega: quando è in gioco la correttezza di chi amministra, decide la maggioranza delle persone. La delibera che revoca l'intero Consiglio elegge i nuovi membri nella stessa finestra. Le stesse regole valgono per il Board.

Se il Consiglio scende sotto tre membri, o sotto due membri domiciliati in Svizzera, i membri rimasti convocano l'assemblea entro venti giorni e le disposizioni di fondi non urgenti sono sospese fino all'elezione.

## 10.9 Verificabilità

Il risultato di ogni voto è accertato da un programma a codice aperto, pubblicato nel repository dell'associazione, che opera sui dati del registro pubblico alla chiusura della finestra. Il risultato e la sua impronta sono ancorati a una blockchain pubblica entro quarantotto ore. Ogni membro può ripetere il conteggio e verificare che coincida.

La stessa logica vale per le regole. Lo statuto, il Regolamento e questo documento hanno ciascuno un numero di versione, una data e un'impronta pubblicati e ancorati; chi aderisce firma l'impronta delle versioni vigenti, e le versioni precedenti restano consultabili. Una modifica del Regolamento vale dalla finestra di voto successiva.

## 10.10 Tutele del singolo membro

La maggioranza non può tutto. La modifica dello scopo non può essere imposta a nessuno: chi non l'ha approvata può uscire con effetto immediato. Lo stesso vale per una modifica dello statuto che aggravi gli obblighi dei membri. Ogni membro può impugnare davanti al giudice, entro un mese, la delibera contraria alla legge o allo statuto alla quale non ha aderito, e può contestare gli atti del Consiglio, del Board e dell'ufficio di revisione che ledono i suoi diritti, chiedendone prima, se lo ritiene, il riesame dell'assemblea.

## 10.11 Dopo l'eventuale attivazione di $FXS

Se i soci attiveranno $FXS come strumento trasferibile, il voto ponderato si calcolerà sul $FXS detenuto dai soci verificati, in luogo del livello di contributo, con lo stesso tetto. La doppia maggioranza resterà ferma: il voto per persona rimane legato alla persona verificata e non allo strumento. Il passaggio è già disciplinato dallo statuto e non richiede una sua ulteriore modifica.

## 10.12 Limiti dichiarati

Tre aspetti di questo disegno meritano di essere indicati apertamente. Il primo Consiglio è scelto dai fondatori e non dai membri, che lo eleggono soltanto alla scadenza o in seguito a revoca. La revoca ordinaria richiede una partecipazione elevata, che nelle organizzazioni di questo tipo è raramente raggiunta: lo strumento effettivo di controllo sugli amministratori è la revoca per gravi motivi. Il Board di controllo è eletto con un voto ponderato, e dunque i contributi maggiori incidono di più sulla scelta di chi vigila. Sono scelte consapevoli, modificabili dall'assemblea con le maggioranze previste.

---

# 11. Struttura giuridica

*La materia è disciplinata dallo statuto, che prevale su questo capitolo. Il capitolo non costituisce un parere legale.*

## 11.1 Perché una struttura giuridica

Molte organizzazioni decentralizzate operano senza una forma giuridica riconosciuta. La conseguenza è che nessuno risponde con chiarezza degli impegni assunti, i fondi comuni non hanno un titolare e chi partecipa può trovarsi esposto, senza saperlo, a una responsabilità personale e illimitata per gli atti del gruppo.

FIÐEX ha scelto la via opposta. Gli strumenti digitali servono a decidere e a verificare; i diritti e le responsabilità discendono da un ente riconosciuto dalla legge, con organi identificati. La struttura si articola su tre livelli: l'atto di adesione, che lega il singolo membro; l'associazione, che è titolare del patrimonio e risponde verso i terzi; un eventuale ente operativo, per le attività che l'associazione non può svolgere direttamente.

## 11.2 L'associazione

FIÐEX è un'associazione ai sensi degli articoli 60 e seguenti del Codice civile svizzero, con sede nel Cantone di Zugo e durata indeterminata. Ha personalità giuridica propria e scopo ideale, non economico. Il Consiglio ne chiede l'iscrizione nel registro di commercio dopo il proprio insediamento.

Tre conseguenze derivano da questa forma. Il patrimonio appartiene all'associazione e non ai membri. Dei debiti dell'associazione risponde soltanto il patrimonio sociale: è esclusa la responsabilità personale dei membri, così come ogni loro obbligo di versamenti ulteriori. L'associazione agisce attraverso organi previsti dalla legge e dallo statuto, i cui componenti sono persone identificate che rispondono, secondo la legge, dei danni causati per colpa nell'esercizio della funzione.

## 11.3 L'atto di adesione e la gerarchia dei documenti

Il rapporto tra il membro e l'associazione nasce da un atto di adesione, composto dalla firma del messaggio di adesione, dal versamento della quota e dalla comunicazione dei propri dati al Consiglio. Il messaggio firmato contiene l'impronta crittografica dei testi ai quali il membro aderisce. In questo modo l'accordo ha un contenuto certo: non rinvia a una pagina che può cambiare, ma a versioni determinate e conservate.

I testi sono ordinati in una gerarchia. Lo **statuto** stabilisce scopo, organi, diritti e limiti, ed è modificato dai soci con maggioranza qualificata. Il **Regolamento di governance** fissa i parametri che lo statuto gli rinvia e non può derogarvi. Questo **documento** è l'Allegato B dello statuto: vincolano l'associazione e i membri soltanto le sue parti marcate come normative, mentre le parti informative descrivono fatti, intenzioni e ipotesi e non attribuiscono diritti né obblighi. In caso di contrasto prevalgono lo statuto e il Regolamento. Fa fede la versione in lingua italiana.

Ogni versione di ciascun testo ha un numero, una data e un'impronta pubblicati nel protocollo e ancorati a una blockchain pubblica. Le versioni precedenti restano consultabili.

## 11.4 Dove si amministra

La sede di un ente non è una formalità. Gli ordinamenti guardano al luogo in cui le persone che dirigono prendono effettivamente le decisioni, non al Paese in cui è registrato un sito o pubblicato un contratto. Una sede priva di amministrazione reale non produrrebbe gli effetti che le si attribuiscono.

Lo statuto contiene perciò regole di sostanza. I membri del Consiglio svolgono la loro funzione dalla Svizzera, e almeno due vi sono domiciliati, con potere di rappresentanza. Il Consiglio si riunisce e decide in Svizzera; ogni verbale indica chi ha deciso e da dove ed è conservato presso la sede, insieme alla parte riservata del registro dei membri. La gestione corrente è affidata, con contratto scritto, a una persona o a un fornitore identificato che opera dalla Svizzera. L'associazione è rappresentata con la firma collettiva di due membri del Consiglio.

Chi sviluppa il protocollo, compreso il promotore dell'associazione, opera in base a un mandato scritto. Non ha potere di firma, non detiene chiavi di amministrazione o di aggiornamento e non controlla da solo i rilasci. Il Consiglio documenta ogni anno dove sono state svolte le attività di gestione e di sviluppo.

## 11.5 Il protocollo come strumento

Lo statuto distingue l'associazione dai suoi strumenti digitali. Il protocollo, cioè l'insieme formato dal Genesis Observatory, dal pannello di adesione, dal registro dei membri e dal sistema di voto, è uno strumento e non un organo. L'indisponibilità di un sito o di un fornitore non incide sulla validità degli atti: ogni membro può riprodurre l'interfaccia e verificare gli atti dalle registrazioni pubbliche.

Il codice è pubblicato con licenza aperta e i diritti sul protocollo spettano all'associazione, che non può cederli senza una delibera dei soci. Il Consiglio può portare il protocollo su un'altra rete o su nuovi contratti, con preavviso, purché le registrazioni dei membri e la verificabilità degli atti restino integre.

## 11.6 Diritto applicabile, foro e impugnazioni

L'associazione e i suoi rapporti con i membri sono retti dal diritto svizzero. Per le controversie tra l'associazione e i membri è competente il giudice della sede; per quelle sulla validità dell'associazione e delle delibere dei suoi organi questo foro è esclusivo. Per le altre controversie con un membro consumatore restano fermi i fori e le norme imperative di tutela del suo luogo di residenza.

Ogni membro può impugnare davanti al giudice, entro un mese da quando ne ha avuto conoscenza, la delibera dell'assemblea contraria alla legge o allo statuto alla quale non ha aderito. Lo stesso diritto vale contro le decisioni del Consiglio e gli atti del Board di controllo e dell'ufficio di revisione che siano contrari alla legge o allo statuto o che ledano i diritti del membro. Contro questi ultimi il membro può chiedere prima il riesame dell'assemblea, che può annullarli ma non sostituirsi al Consiglio nelle scelte di gestione. Il riesame non sospende l'esecuzione e non esclude il ricorso al giudice.

## 11.7 Arbitrato

Il protocollo può prevedere, accanto al riesame, l'esame delle controversie tramite un sistema di arbitrato decentralizzato. Questo strumento è facoltativo e non sospende né sostituisce i termini per l'impugnazione davanti al giudice. Una controversia è decisa da arbitri soltanto se le parti lo hanno convenuto con un accordo separato. L'accordo arbitrale non vincola il membro consumatore, salvo che egli lo abbia approvato in forma specifica o dopo l'insorgere della controversia.

L'arbitrato decentralizzato è dunque un presidio aggiuntivo, a disposizione di chi lo sceglie, e non una rinuncia alla tutela giudiziaria.

## 11.8 Tutele di chi aderisce

Alcune clausole incidono in modo particolare sulla posizione del membro: il preavviso per l'uscita, l'esclusione, l'assenza di diritti sul patrimonio, il foro e l'arbitrato. Il pannello di adesione le presenta separatamente, per un'approvazione distinta. Il membro consumatore la esprime con una firma elettronica avanzata o qualificata, o con un'identità digitale pubblica; in mancanza, le clausole sul foro e sull'arbitrato non gli sono opposte, salvo che per le controversie sulla validità dell'associazione e delle delibere.

Il membro consumatore riceve prima della firma le informazioni previste dalla legge della sua residenza e può recedere entro quattordici giorni. I dati dei membri sono trattati secondo la legge svizzera sulla protezione dei dati e, per chi vi è soggetto, secondo il regolamento generale europeo; nessun dato identificativo è scritto su una blockchain.

## 11.9 Quadro regolatorio

Le attività descritte in questo documento toccano discipline diverse, e l'associazione si rivolge a persone residenti in più Paesi: alle norme svizzere si aggiungono le norme imperative degli ordinamenti in cui i membri risiedono. Lo stato delle verifiche è il seguente.

| Ambito | Stato |
|---|---|
| Adesione e quota | Rapporto associativo; verso i consumatori si applicano informazione precontrattuale e recesso |
| Raccolta dei contributi e registrazioni | Soggetta alle norme sulle offerte al pubblico; lo statuto prevede due contatori e la sospensione delle attribuzioni al raggiungimento delle soglie |
| Qualificazione di $FXS | Non ancora accertata; da essa dipendono gli adempimenti per l'eventuale emissione come strumento trasferibile |
| Meccanismi di protezione | Non attivi; attivabili soltanto con le autorizzazioni indicate dallo statuto |
| Custodia per conto di terzi | Non attiva; attivabile soltanto con le autorizzazioni indicate dallo statuto |
| Prevenzione del riciclaggio | Adempimenti da determinare in base alla qualificazione delle singole attività |

Alla data di questo documento l'associazione non ha ottenuto né richiesto alcuna delle autorizzazioni indicate. Le qualificazioni giuridiche esposte sono oggetto di verifica con professionisti abilitati e possono cambiare; un loro esito diverso da quello atteso può comportare la modifica o l'abbandono di funzioni previste.

## 11.10 L'ente operativo

Lo scopo ideale limita ciò che l'associazione può svolgere direttamente. Per le attività operative coerenti con lo scopo, tra cui i servizi professionali, la mediazione disciplinata dalla legge, le verifiche tecniche con effetti per le parti e la rappresentanza, lo statuto prevede che i soci possano deliberare, con maggioranza qualificata e dopo il raggiungimento della soglia minima di raccolta, la costituzione di un altro ente o la partecipazione a esso.

La forma e l'ordinamento di tale ente non sono decisi. Tra le ipotesi allo studio vi sono forme societarie che vincolano il patrimonio a una finalità di interesse collettivo. In ogni caso restano fermi lo scopo dell'associazione, i limiti posti al Pass, ai livelli di contributo e alle registrazioni, e il diritto di uscita dei membri.

## 11.11 Modifiche, trasformazione e scioglimento

Lo statuto è modificato dai soci con i due terzi dei votanti e la maggioranza ponderata. La fusione, la trasformazione in un altro tipo di ente e il trasferimento della sede all'estero richiedono le stesse maggioranze e quelle più elevate eventualmente imposte dalla legge.

L'associazione si scioglie per delibera dei soci e nei casi previsti dalla legge. Pagati i debiti, l'assemblea può deliberare la ripartizione dei contributi volontari nei limiti descritti nel capitolo 6. Il residuo è devoluto a un ente con scopo analogo, designato dall'assemblea: è esclusa ogni altra attribuzione ai membri. I fondi di terzi non rientrano nella liquidazione e sono rilasciati o restituiti secondo i rispettivi contratti.

---

# 12. Gruppo di lavoro e responsabilità

*La materia è disciplinata dagli artt. 25–28, 33 e 34 dello statuto, che prevalgono su questo capitolo.*

## 12.1 Persone identificate, ruoli separati

Un'infrastruttura che chiede fiducia deve dire chi ne risponde. In FIÐEX le funzioni che comportano poteri sull'associazione e sui suoi fondi sono affidate a persone fisiche identificate per nome, e sono distribuite in modo che nessuna persona ne riunisca più di una tra quelle che devono controllarsi a vicenda.

La distribuzione segue una regola semplice. Chi scrive il codice non lo mette in produzione da solo. Chi decide una spesa non la esegue da solo. Chi amministra non vigila su se stesso. Chi vigila non amministra e non è retribuito dall'associazione.

## 12.2 I ruoli

| Ruolo | Funzione | Limiti |
|---|---|---|
| Consiglio | Amministra e rappresenta l'associazione; decide gestione e tesoreria | Almeno tre persone, che operano dalla Svizzera; firma collettiva a due; opera entro indirizzi e preventivo dell'assemblea |
| Firmatari dei wallet | Eseguono le disposizioni di fondi decise dal Consiglio | Designati per nome; una sola chiave ciascuno; nessuno dispone da solo |
| Gestione corrente | Pagamenti, contratti, rapporti con fornitori e membri | Persona o fornitore identificato, con contratto scritto, che opera dalla Svizzera |
| Promotore e sviluppatori | Progettano e sviluppano il protocollo | Mandato scritto; nessun potere di firma; nessuna chiave di amministrazione o di aggiornamento |
| Board di controllo | Vigila sul rispetto di statuto, Regolamento e delibere | Soci verificati; non fanno parte del Consiglio; nessun incarico retribuito; non dispongono dei fondi |
| Ufficio di revisione | Verifica la contabilità | Abilitato e indipendente |

I nomi dei membri del Consiglio sono indicati nell'atto costitutivo. Le cariche in corso, con la data di nomina, sono pubblicate nel protocollo e aggiornate a ogni variazione.

## 12.3 Il promotore

Il progetto è stato ideato e avviato da un promotore, che ne ha curato il disegno, la documentazione e lo sviluppo iniziale. Lo statuto ne regola la posizione in modo esplicito, perché l'esperienza del settore mostra che il rischio maggiore per i partecipanti deriva spesso dal controllo che i fondatori conservano su fondi e codice.

Il promotore opera in base a un mandato scritto conferito dal Consiglio. Non ha potere di firma per l'associazione, non è firmatario del wallet che custodisce le chiavi di amministrazione e di aggiornamento del protocollo e non controlla da solo i rilasci. Se è membro dell'associazione, lo è alle stesse condizioni di ogni altro: stessa quota, stessi livelli, stesse regole di voto.

Un elemento va dichiarato. Il promotore ha promosso il token $FDX, descritto nel capitolo 4, e ne detiene una quantità acquistata all'emissione. L'associazione riceve i proventi collegati agli scambi di quel token. Il promotore si trova dunque in una posizione di interesse rispetto a un attivo che l'associazione può accettare e da cui trae proventi: nelle decisioni che lo riguardano si applicano le regole sul conflitto di interessi.

## 12.4 Compensi e incentivi

Il lavoro per l'associazione è retribuito in un solo modo: con compensi pagati dal compartimento operativo, per prestazioni effettive, pubblicati nel conto annuale.

Al gruppo di lavoro non sono attribuiti gratuitamente strumenti di governance, e nessuna registrazione di $FXS è assegnata a titolo gratuito a chi lavora per l'associazione. Questa scelta distingue FIÐEX dalla prassi più diffusa nel settore, nella quale ai fondatori è riservata una quota degli strumenti emessi. Ha due ragioni. Evita che chi amministra abbia un interesse proprio alla circolazione o al valore di uno strumento. Evita che il peso nella governance sia acquisito senza un contributo, a scapito di chi ha contribuito.

Chi lavora per l'associazione può contribuire come ogni altro membro, alle medesime condizioni. I contributi delle persone che ricoprono una carica o un incarico sono indicati come tali nel registro pubblico.

## 12.5 Conflitto di interessi

Il membro del Consiglio che si trova in conflitto di interessi lo dichiara e si astiene dalla decisione. In assemblea nessun membro vota sugli affari e sulle liti tra l'associazione e lui stesso, il coniuge o un parente in linea retta: la regola si applica, tra l'altro, alle delibere sui compensi di chi ne è destinatario. L'esclusione dal voto risulta dal registro pubblico.

## 12.6 Responsabilità

I membri degli organi rispondono secondo la legge dei danni causati per colpa nell'esercizio della funzione. Prima di accettare la carica, ogni membro del Consiglio dichiara per iscritto di conoscere i rischi giuridici dell'attività dell'associazione, come descritti nel registro dei rischi, e la propria responsabilità personale; la dichiarazione richiama espressamente i rischi classificati come elevati.

L'approvazione del conto annuale da parte dell'assemblea libera il Consiglio soltanto per i fatti resi noti nel conto e nelle relazioni: ciò che non è stato dichiarato non è coperto dal discarico. L'associazione può tenere indenni i membri degli organi per gli atti compiuti in buona fede nel suo interesse, nei limiti della legge.

## 12.7 Continuità

L'associazione è costruita per non dipendere da una persona. Una chiave persa, compromessa o appartenente a un firmatario cessato è sostituita entro un termine definito. Un seggio vacante del Consiglio può essere coperto in via provvisoria fino alla finestra di voto successiva; se il Consiglio scende sotto il numero minimo, l'assemblea è convocata e le disposizioni di fondi non urgenti sono sospese. Il codice è pubblico, i registri sono verificabili senza il sito dell'associazione e ogni membro può riprodurne l'interfaccia.

Il venir meno del promotore, di uno sviluppatore o di un fornitore può rallentare lo sviluppo. Non priva l'associazione dei suoi fondi, dei suoi registri né della capacità di decidere.

---

# 13. Rischi e limiti


## 13.1 Come leggere questo capitolo

Un progetto che si propone di rendere il rischio visibile deve cominciare dal proprio. Questo capitolo raccoglie i rischi che una persona assume aderendo a FIÐEX e contribuendo alla sua costruzione. Non è un elenco di formule di cautela: ogni rischio indicato deriva da una caratteristica del progetto descritta nei capitoli precedenti.

L'elenco non è esaustivo. Alcuni rischi possono verificarsi insieme e aggravarsi a vicenda, e altri possono emergere in futuro. Chi valuta di contribuire dovrebbe poter sopportare la perdita integrale di quanto versa.

## 13.2 Rischi di realizzazione

FIÐEX è un progetto in fase iniziale. Alla data di questo documento parte dell'infrastruttura è in costruzione, i contratti digitali non sono stati sottoposti a verifica indipendente del codice e gli organi elettivi non sono ancora stati formati dai membri.

La soglia minima di raccolta potrebbe non essere raggiunta; in tal caso il programma non parte e si applica la ripartizione descritta nel capitolo 6. Anche raggiunta la soglia, lo sviluppo può subire ritardi, costare più del previsto o non conseguire i risultati attesi.

I moduli futuri potrebbero non essere mai attivati. In particolare i meccanismi di protezione richiedono una riserva molto superiore a quella che la soglia minima consente di accantonare, autorizzazioni che potrebbero non essere rilasciate e una delibera dei soci che potrebbe non essere adottata. Nessuno dovrebbe aderire nell'aspettativa di ricevere protezione.

Il progetto dipende, nella fase di avvio, da un numero ridotto di persone. La loro indisponibilità non priva l'associazione di fondi e registri, ma può rallentare o arrestare lo sviluppo.

## 13.3 Rischi relativi ai contributi

Il contributo volontario è definitivo. Non costituisce un credito verso l'associazione e non può essere richiesto indietro, salvo il recesso del consumatore entro quattordici giorni e i casi di ripartizione previsti dallo statuto. La ripartizione per mancato raggiungimento della soglia riguarda soltanto ciò che resta dopo debiti e spese e può essere inferiore a quanto versato; la quota di adesione e le donazioni non sono ripartite. La ripartizione deliberata dall'assemblea non è un diritto.

Chi esce o è escluso dall'associazione non ha diritti sul patrimonio.

Le registrazioni di $FXS non sono trasferibili e non esiste un mercato sul quale cederle. Non rappresentano quote del patrimonio e non danno diritto a rendimento. Potrebbero non essere mai convertite in uno strumento trasferibile. Il loro peso relativo nella governance diminuisce al crescere del numero dei membri e delle registrazioni, comprese quelle attribuite con gli incentivi della fase iniziale.

## 13.4 Rischi patrimoniali

I fondi dell'associazione sono detenuti in attivi digitali, il cui valore può variare in modo ampio e rapido. Anche gli attivi concepiti per mantenere un valore stabile possono perderlo. L'importo registrato al momento del versamento non rappresenta il valore che quei fondi avranno in seguito.

La custodia con firma multipla riduce il rischio di disposizioni arbitrarie, non lo elimina. Le chiavi possono essere perse, sottratte o usate in accordo tra più firmatari. I contratti e le reti su cui i fondi si trovano possono presentare difetti. La presenza di fondi su più reti aumenta il numero dei punti esposti.

L'impiego dei fondi in strumenti liquidi e a basso rischio può comunque produrre perdite. La separazione in compartimenti è interna: i creditori dell'associazione possono rivalersi sull'intero patrimonio, compresa la riserva.

## 13.5 Rischi tecnici e di dipendenza

Il protocollo può contenere errori, anche dopo una verifica indipendente del codice. Il capitolo 1 ha mostrato che una parte rilevante delle perdite nel settore non deriva dal codice ma da procedure, interfacce e fornitori: FIÐEX è esposta agli stessi rischi.

Il funzionamento dipende da servizi di terzi che l'associazione non controlla: il sistema di verifica dell'unicità della persona, le reti su cui sono ancorati registri e risultati, gli strumenti di voto, la piattaforma che ospita l'applicazione di partecipazione, i fornitori dell'infrastruttura. Ciascuno può modificare le proprie condizioni, sospendere il servizio, subire un incidente o cessare. Alcune delle reti utilizzate affidano l'ordinamento delle transazioni a un solo operatore. La possibilità per ogni membro di riprodurre l'interfaccia attenua questi rischi senza annullarli.

## 13.6 Rischi di governance

La partecipazione al voto nelle organizzazioni di questo tipo è di norma bassa. Una partecipazione insufficiente può impedire il raggiungimento dei quorum e bloccare le decisioni, oppure lasciarle a una minoranza attiva.

Il voto ponderato attribuisce un peso maggiore a chi ha contribuito di più; il tetto per membro e la doppia maggioranza limitano questa influenza ma non la escludono, in particolare quando i soci verificati sono pochi. Il Board di controllo è eletto con voto ponderato. Il primo Consiglio è nominato dai fondatori. La revoca ordinaria del Consiglio richiede una partecipazione che potrebbe non essere raggiunta.

La verifica dell'unicità della persona non è infallibile. La verifica per garanzia, ammessa in via transitoria, è più debole delle altre. Una persona potrebbe riuscire a ottenere più di una posizione.

Le regole possono cambiare. Lo statuto e il Regolamento sono modificabili con le maggioranze previste, e un membro può trovarsi in minoranza rispetto a una modifica che non condivide; in alcuni casi la sua tutela consiste nel diritto di uscire, senza diritti sul patrimonio.

## 13.7 Rischi giuridici e regolatori

La qualificazione giuridica di più elementi del progetto non è accertata. Un'autorità o un giudice potrebbe ritenere che le registrazioni di $FXS, o lo strumento in cui potrebbero essere convertite, costituiscano strumenti finanziari o altre attività regolate; che la raccolta dei contributi sia un'offerta al pubblico soggetta a obblighi non adempiuti; che attività dell'associazione rientrino nella disciplina assicurativa, in quella dei servizi sulle cripto-attività, in quella della raccolta del risparmio o in quella delle professioni riservate.

L'associazione si rivolge a persone residenti in più Paesi, i cui ordinamenti possono applicare regole diverse e più restrittive di quelle svizzere, a prescindere da quanto lo statuto prevede. In alcuni Paesi la partecipazione potrebbe essere limitata o vietata.

Le conseguenze possibili comprendono l'ordine di sospendere o cessare un'attività, sanzioni, l'obbligo di restituire quanto raccolto, la modifica o l'abbandono di funzioni previste e, nei casi più gravi, lo scioglimento dell'associazione. Ciascuna di esse può ridurre o azzerare il patrimonio.

La forma di associazione svizzera produce i suoi effetti, compresa la limitazione della responsabilità al patrimonio sociale, a condizione che l'associazione sia effettivamente amministrata come lo statuto prevede. Se così non fosse, potrebbero applicarsi le norme di un altro ordinamento, con conseguenze sul regime fiscale e sulla responsabilità personale di chi agisce per l'associazione.

Le norme applicabili sono in evoluzione e possono cambiare in senso sfavorevole. Il trattamento fiscale dei versamenti e delle eventuali ripartizioni dipende dalla situazione di ciascun membro, che è tenuto a valutarlo.

## 13.8 Rischi connessi a $FDX

$FDX è un token emesso da terzi, privo di diritti e soggetto a variazioni di valore estreme; può perdere l'intero valore. L'associazione può accettarlo come attivo e riceve proventi collegati ai suoi scambi: ne deriva un'esposizione alla volatilità di quell'attivo, alle condizioni della piattaforma che lo emette e alle valutazioni che un'autorità potrebbe dare del rapporto tra l'associazione e quel token. Il promotore del progetto detiene $FDX e si trova rispetto a esso in una posizione di interesse.

Chi acquista o scambia $FDX non acquisisce alcun rapporto con l'associazione e alcuna aspettativa nei suoi confronti.

## 13.9 Rischi dei servizi

I servizi descritti nel capitolo 9 non sono attivi. Una volta avviati, comporterebbero rischi propri: errori nella ricostruzione di un caso; la possibilità che un'attività sia ritenuta riservata a professionisti abilitati; la responsabilità connessa alla detenzione di fondi altrui; il trattamento di dati personali delicati. Nessun servizio comporta una promessa di recupero delle perdite.

## 13.10 Riservatezza

Il membro è identificato verso l'associazione, che conserva il suo nome, il suo indirizzo e il legame con il suo wallet. Questi dati possono essere oggetto di accesso illecito o di richieste delle autorità. Le operazioni compiute dal wallet sono pubbliche e permanenti; chi conosce il legame tra una persona e un wallet può ricostruirne l'attività.

## 13.11 Limiti di questo documento

Questo documento descrive il progetto alla data della sua versione. Le sue parti informative non attribuiscono diritti e possono essere modificate. Contiene descrizioni di funzioni future e di ipotesi di lavoro, che potrebbero non realizzarsi o realizzarsi in forma diversa. I dati sul settore provengono da fonti di terzi e non sono stati verificati in modo indipendente dall'associazione.

Nulla di quanto esposto costituisce consulenza finanziaria, legale o fiscale, né un invito a contribuire. In caso di contrasto tra questo documento e lo statuto prevale lo statuto.

---

# 14. Percorso di sviluppo

*Il percorso descritto è un programma di lavoro e non un impegno: non attribuisce diritti e può essere modificato.*

## 14.1 Criterio

Il percorso di sviluppo di FIÐEX non è scandito da date. È ordinato per fasi, ciascuna delle quali si apre quando la precedente ha prodotto un risultato verificabile e si chiude con un risultato a sua volta verificabile. Il capitolo 7 ha esposto le condizioni che modificano il funzionamento dell'associazione; questo capitolo le dispone nell'ordine in cui il lavoro intende affrontarle.

La scelta ha una conseguenza che va accettata in anticipo: non è possibile dire quando una fase sarà completata. È possibile dire, in ogni momento, a che punto si trova il lavoro e che cosa manca.

## 14.2 Stato alla data del documento

Una parte dell'infrastruttura esiste. Sono stati realizzati il sito, il flusso di adesione con verifica dell'unicità della persona e collegamento di una sola persona a un solo wallet, la conferma dei versamenti sulle registrazioni delle reti, il registro pubblico dei contributi e le viste che presentano la posizione del partecipante e lo stato dei fondi.

Una parte è scritta ma non operativa. I contratti del Pass e di $FXS esistono in forma di bozza sottoposta a prove interne; non sono stati verificati da un soggetto indipendente e non sono stati pubblicati su alcuna rete. Lo statuto, il Regolamento iniziale e questo documento sono redatti e attendono l'adozione da parte dell'assemblea costitutiva.

Una parte è progettata e non ancora realizzata: il programma pubblico di conteggio dei voti, il Genesis Observatory nella sua forma completa, l'applicazione all'interno di World App, il Resolution Desk.

Nessun meccanismo di protezione, nessuno strumento trasferibile e nessun servizio a terzi è in funzione.

## 14.3 Le fasi

**Prima fase: costituzione.** L'assemblea costitutiva adotta lo statuto, il Regolamento iniziale e questo documento. I membri del Consiglio accettano la carica e rendono la dichiarazione prevista. Sono attivati i wallet a firma multipla dei fondi e quello, distinto, delle chiavi di amministrazione, e ne sono pubblicati gli indirizzi. Il Consiglio chiede l'iscrizione nel registro di commercio e affida la gestione corrente. La fase si chiude con l'insediamento del Consiglio: da quel momento l'associazione può operare.

**Seconda fase: apertura delle adesioni.** Il pannello di adesione è completato con le informazioni per i consumatori e con le clausole soggette ad approvazione specifica. Sono resi operativi il registro dei membri nelle sue due parti, i contatori di raccolta e il programma di conteggio. Sono pubblicati la tabella delle registrazioni e il documento che disciplina il budget degli incentivi. Il Consiglio pubblica la data di apertura, dalla quale decorre il termine per il raggiungimento della soglia minima. Si tengono le prime finestre di voto. L'applicazione in World App è presentata alla piattaforma che la ospita, la cui approvazione non dipende dall'associazione.

**Terza fase: raccolta verso la soglia minima.** La maggior parte dei contributi resta vincolata e lo sviluppo procede entro il limite di spesa che ne deriva. Le priorità sono la verifica indipendente del codice del Pass, il completamento del Genesis Observatory, l'adozione da parte dell'assemblea della politica di impiego dei fondi e del primo preventivo per compartimenti, e l'elezione del primo Board di controllo. Il Consiglio può avviare i servizi documentali, dopo l'adozione del relativo regolamento e delle regole sul trattamento dei dati. In parallelo proseguono le verifiche sulla qualificazione giuridica delle attività.

**Quarta fase: dopo la soglia minima.** Cessa il vincolo sul compartimento di raccolta e comincia l'accantonamento alla riserva nelle proporzioni previste. Il Pass è emesso come credenziale non trasferibile. I soci possono deliberare la costituzione di un ente operativo per i servizi che l'associazione non svolge direttamente. I servizi possono estendersi alla formazione assistita degli accordi e alla composizione delle controversie, e a un deposito vincolato sperimentale di importo limitato nella forma che non comporta custodia, se ne ricorrono le condizioni. Viene elaborato il modello di capitale necessario a determinare la capacità di riserva.

**Quinta fase: moduli.** I soci decidono, uno per volta e soltanto quando ne ricorrono le condizioni, sull'attivazione dei moduli: l'emissione di $FXS come strumento trasferibile, il legame tra strumenti di governance e tesoreria, la custodia per conto di terzi, i meccanismi di protezione. Per ciascuno l'attivazione richiede la delibera con maggioranza qualificata e le autorizzazioni di legge; per la protezione richiede inoltre una riserva che il capitolo 7 colloca, come ipotesi di lavoro, a un livello che la sola soglia minima di raccolta non consente di raggiungere. Questa fase non ha un termine e può non compiersi, in tutto o in parte.

## 14.4 Quadro di sintesi

| Fase | Si apre con | Risultato che la chiude |
|---|---|---|
| Costituzione | Adozione dei testi | Insediamento del Consiglio e wallet operativi |
| Apertura delle adesioni | Insediamento del Consiglio | Pannello, registro, contatori e conteggio in funzione; data di apertura pubblicata |
| Raccolta verso la soglia | Data di apertura | Raggiungimento della soglia minima entro dodici mesi |
| Dopo la soglia | Soglia minima raggiunta | Pass emesso; riserva in formazione; modello di capitale; eventuale ente operativo |
| Moduli | Condizioni di ciascun modulo | Delibera dei soci e autorizzazioni, modulo per modulo |

## 14.5 Che cosa può interrompere il percorso

Il percorso può arrestarsi in più punti. Se la soglia minima non è raggiunta entro dodici mesi dall'apertura, i contributi volontari residui sono ripartiti e i soci decidono se proseguire o sciogliere l'associazione. Se una verifica giuridica dà un esito diverso da quello atteso, una funzione può essere modificata o abbandonata. Se un'autorizzazione non è rilasciata, il modulo corrispondente non si attiva. Se una piattaforma di terzi non accoglie l'applicazione o ne muta le condizioni, quel canale viene meno e resta il sito. Il capitolo 13 espone questi rischi.

## 14.6 Come seguire l'avanzamento

Lo stato del percorso non è affidato a comunicati. Il Genesis Observatory indica per ogni fase ciò che è stato completato e ciò che manca, distinguendo le funzioni attive da quelle future. I saldi dei compartimenti sono leggibili dalle registrazioni delle reti. Le delibere dell'assemblea, con il loro esito e il loro seguito, sono pubbliche. Il Board di controllo pubblica almeno una relazione all'anno e il Consiglio il conto annuale.

Il percorso può essere modificato. L'assemblea approva gli indirizzi generali e il preventivo, e può rivedere priorità e ordine delle attività. Ogni modifica di questo documento dà luogo a una nuova versione, con la propria data e la propria impronta; le versioni precedenti restano consultabili, così che chiunque possa confrontare ciò che era stato programmato con ciò che è stato fatto.

---

# 15. Documentazione e avvertenze


## 15.1 I documenti dell'associazione

Questo documento non è l'unica fonte e non è la più importante. Le regole dell'associazione stanno nello statuto e nel Regolamento; altri documenti ne disciplinano singoli aspetti. Il quadro che segue indica quali documenti esistono, chi li adotta e in quale momento.

| Documento | Contenuto | Chi lo adotta | Momento |
|---|---|---|---|
| Statuto | Scopo, membri, organi, patrimonio, moduli, controversie | Assemblea costitutiva; poi i soci, con maggioranza qualificata | Alla costituzione |
| Regolamento di governance (Allegato A) | Quota e livelli, verifica, peso del voto, finestre, quorum, proposte, delega, conteggio, compartimenti, incentivi | Assemblea costitutiva; poi l'assemblea | Alla costituzione |
| Questo documento (Allegato B) | Descrizione del progetto, delle fasi e delle condizioni | Assemblea | Alla costituzione |
| Registro dei rischi | Rischi giuridici dell'attività, che ogni membro del Consiglio dichiara di conoscere | Consiglio | Prima dell'insediamento |
| Tabella delle registrazioni e documento PSRP | Criteri di attribuzione delle registrazioni; capitoli e tetti del budget degli incentivi | Consiglio, nei limiti del Regolamento | Prima dell'apertura delle adesioni |
| Informazioni per i consumatori e clausole ad approvazione specifica | Testi presentati nel pannello di adesione | Consiglio | Prima dell'apertura delle adesioni |
| Preventivo per compartimenti e politica di impiego dei fondi | Destinazione delle risorse; strumenti ammessi e limiti | Assemblea | Prima finestra di voto utile |
| Tabella degli scaglioni del coefficiente di fase | Valori del coefficiente per ciascuno scaglione di raccolta | Consiglio, nei limiti del Regolamento | Prima della sua applicazione |
| Regolamento dei servizi e regole sul trattamento dei dati dei fascicoli | Ruoli, incarichi, incompatibilità, accessi, conservazione | Assemblea | Prima dell'avvio dei servizi |
| Regolamento della protezione | Categorie, criteri, limiti, processo di esame | Soci, con maggioranza qualificata | Con l'eventuale attivazione del modulo |
| Conto annuale, relazioni del Board di controllo, verbali | Rendicontazione e controllo | Consiglio, Board, assemblea | Ogni anno e a ogni decisione |

Alla data di questo documento sono redatti lo statuto, il Regolamento iniziale e il presente testo. Gli altri documenti sono da predisporre nei momenti indicati. Nessuna funzione che dipende da un documento non ancora adottato può considerarsi operante.

## 15.2 Versioni e impronte

Ogni documento dell'associazione ha un numero di versione, una data e un'impronta crittografica. L'impronta è una sequenza di caratteri calcolata dal contenuto del file: se il contenuto cambia, anche di un solo carattere, l'impronta cambia. Le impronte sono pubblicate nel protocollo e ancorate a una blockchain pubblica, dove restano con la data in cui vi sono state scritte.

Chiunque può verificare un documento in tre passaggi: ottenere il file, calcolarne l'impronta con uno strumento standard, confrontarla con quella ancorata. Se coincidono, il documento è quello che l'associazione ha pubblicato in quella data. Le versioni precedenti restano consultabili, così che ogni modifica sia riconoscibile.

Una versione dello statuto entra in vigore con la pubblicazione della sua impronta. Chi aderisce firma l'impronta delle versioni vigenti dello statuto, del Regolamento e di questo documento: la sua adesione è riferita a quei testi e a nessun altro.

## 15.3 Natura di questo documento

Lo statuto distingue, all'interno di questo documento, le parti normative, che vincolano l'associazione e i membri, dalle parti informative, che descrivono fatti, intenzioni e ipotesi e non attribuiscono diritti né obblighi.

Questa versione non contiene parti normative. Ogni capitolo è marcato come informativo e rinvia, per le regole, agli articoli dello statuto e ai paragrafi del Regolamento che disciplinano la materia. Chi vuole conoscere i propri diritti e i propri obblighi deve leggere quei testi. In caso di contrasto prevalgono lo statuto e il Regolamento.

## 15.4 Termini principali

| Termine | Significato |
|---|---|
| Membro | Chi ha aderito all'associazione ed è iscritto nel registro. È socio o aderente |
| Socio | Membro che ha completato la verifica di unicità della persona |
| Aderente | Membro che non ha completato la verifica |
| Pass | Credenziale digitale non trasferibile che attesta la partecipazione |
| Quota di adesione | Versamento dovuto una sola volta all'ingresso; coincide con il Livello I |
| Livello di contributo | Fascia determinata dai versamenti del membro; incide soltanto sul peso del voto ponderato |
| Contributo volontario | Versamento ulteriore e definitivo al fondo comune |
| Registrazione | Annotazione nel registro che documenta la partecipazione e il peso nella governance; non trasferibile |
| $FXS | Strumento della governance. Oggi esiste soltanto come registrazione virtuale |
| Modulo non attivo | Funzione prevista dallo statuto che non può essere offerta né annunciata fino all'attivazione |
| Compartimento | Ripartizione interna dei fondi dell'associazione per destinazione |
| Riserva | Compartimento che accantona la base patrimoniale dei futuri meccanismi di protezione |
| Fondi di terzi | Fondi detenuti per conto di altri, estranei al patrimonio dell'associazione |
| Soglia minima | Importo di contributi volontari al di sotto del quale il programma non parte |
| Coefficiente di fase | Riduzione del contributo richiesto per i Livelli II e III in funzione dell'avanzamento della raccolta |
| PSRP | Budget unico degli incentivi della fase iniziale |
| Doppia maggioranza | Regola per cui una delibera richiede la maggioranza delle persone e quella dei voti ponderati |
| Finestra di voto | Periodo, annunciato in anticipo, nel quale l'assemblea delibera |
| Protocollo | Insieme degli strumenti digitali dell'associazione; è uno strumento, non un organo |
| Genesis Observatory | Spazio del protocollo in cui lo stato dell'associazione è reso leggibile |
| Impronta | Sequenza calcolata dal contenuto di un documento, che ne permette la verifica |

## 15.5 Lingua e comunicazioni

Fa fede la versione in lingua italiana dello statuto e dei suoi allegati. Le traduzioni hanno valore informativo.

L'associazione comunica con i membri mediante pubblicazione nel protocollo; ogni membro può indicare un recapito al quale ricevere avviso delle pubblicazioni. I membri comunicano con l'associazione con un messaggio firmato nel protocollo o per iscritto alla sede.

## 15.6 Avvertenze

FIÐEX è un'infrastruttura in costruzione. Non è un'impresa di assicurazione, non è un intermediario finanziario e non offre prodotti di investimento. Non promette rendimento, rimborso o protezione.

Questo documento ha finalità informativa. Non costituisce un'offerta al pubblico di strumenti finanziari, una sollecitazione all'investimento, una consulenza finanziaria, legale o fiscale. Chi valuta di aderire o di contribuire è tenuto a esaminare lo statuto e il Regolamento, a considerare i rischi esposti nel capitolo 13 e, se lo ritiene, a rivolgersi a un professionista di propria fiducia.

Le funzioni descritte come future sono subordinate allo sviluppo tecnico, alla capacità della riserva, alle delibere dei membri e alle autorizzazioni di legge. Possono non essere realizzate, o esserlo in forma diversa. Le affermazioni che riguardano il futuro esprimono intenzioni alla data del documento e non costituiscono impegni.

La partecipazione può essere limitata o vietata dalla legge del Paese in cui una persona risiede. È responsabilità di ciascuno verificare che la propria adesione sia consentita e valutarne le conseguenze, anche fiscali.

FIÐEX è un progetto indipendente. I nomi di reti, applicazioni e organizzazioni di terzi citati in questo documento appartengono ai rispettivi titolari e sono usati a solo scopo descrittivo; la loro menzione non indica affiliazione, approvazione o collaborazione.

La versione, la data e l'impronta di questo documento sono indicate nel frontespizio e pubblicate nel protocollo.
