<b>Problema:</b>
In Italia il tasso di disoccupazione è molto alto, ed è difficile trovare un metodo per mettersi in contatto con le aziende.

<b>Soluzione/Obiettivi del sito:</b>
La soluzione è una webapp, che funziona da board dove per affigere il proprio curriculum o offerte di lavoro

<b>Pubblico target:</b>
Persone alla ricerca di un lavoro

<b>Contenuti:</b>
La webapp conterrà il profilo del utente in cerca di lavoro e il suo curriculum, e le diverse offerte di lavoro

<b>Struttura del sito:</b>
L'app sarà composta da poche pagine per rendere la navigazione veloce e facile, per cui conterrà una pagina dove sono contenute tutte le informazioni del utente, e una pagina principale dove sono affisse le diverse offerte di lavoro,
sarà presenta una barra di ricerca e una ricerca a categorie.

<b>Funzionalità e Caratteristiche:</b>

-Diversi tipi di account: potrebbero esserci account per i candidati in cerca di lavoro e account per le aziende che offrono posizioni lavorative.

-Una bacheca per le offerte di lavoro: La webapp dovrebbe avere una bacheca in cui le aziende possono pubblicare le loro offerte di lavoro. 

-Interfaccia semplice e facile da navigare

-Ricerca basata su tag e aziende: Gli utenti dovrebbero poter cercare offerte di lavoro utilizzando parole chiave o tag pertinenti alle loro competenze e interessi. 

-Personalizzazione dell'account: Gli utenti dovrebbero avere la possibilità di personalizzare il proprio account, inserendo informazioni sulle loro competenze, esperienze e preferenze. 

-Protezione della riservatezza dei dati: La webapp dovrebbe consentire agli utenti di controllare quali informazioni sono accessibili pubblicamente e quali rimangono private.

<b>Competizione:</b>indeed.com

<b>WBS</b>
https://miro.com/welcomeonboard/S2h0Y2JOTTVoRHk3RFB3a0NzaTRDVHMyNElUZDFhcGF6ZVZlWDNZbDRMV1pMdm80dVNQYXlQcUVqTDRab3NqdHwzNDU4NzY0NTcxMTEwNzM1MzQ1fDI=?share_link_id=899863130679

<b>Value proposition</b> : Collega i sogni, Unisce le carriere - La Tua porta verso il successo professionale

JobConnect: Semplicità e Velocità nel Tuo Percorso Professionale. Collega Velocemente talenti e opportunità, Rendendo il Tuo Futuro Lavorativo Più Accessibile che Mai.

Semplicità: Il sito facile da navigare, mette a disposizione degli utenti un ampia possibilità di scelta fra tutte le offerte di lavoro.

Velocità: Il sito si distingue per la straordinaria velocità che offriamo nel tuo percorso professionale,  La nostra piattaforma è progettata per collegare rapidamente individui talentuosi con opportunità lavorative

accessibilità: La nostra interfaccia intuitiva e user-friendly permette a chiunque di navigare facilmente.

<b>User stories:</b>

User Story per Candidato in cerca di lavoro:

<b>1) </b>Titolo: Creazione del Profilo Utente
Come un candidato in cerca di lavoro,
Voglio poter creare e modificare il mio profilo,
Così che possa inserire le mie informazioni personali, esperienze professionali e competenze.
Criteri di Accettazione:
Possibilità di inserire dettagli personali, esperienze lavorative e competenze.
Funzionalità per caricare un curriculum vitae.
Possibilità di modificare e aggiornare il profilo in qualsiasi momento.
Stima Temporale: 4 giorni

<b>2) </b>User Story per Aziende:
Titolo: Pubblicazione Offerte di Lavoro

Come un'azienda,
Voglio poter pubblicare offerte di lavoro sulla bacheca,
Così che possa attirare candidati qualificati.
Criteri di Accettazione:
Interfaccia per inserire dettagli dell'offerta di lavoro.
Opzioni per specificare requisiti, location, e tipo di contratto.
Capacità di gestire e modificare le offerte pubblicate.

Stima Temporale: 4

<b>3) </b>User Story per la Ricerca di Lavoro:
Titolo: Ricerca di Offerte di Lavoro

Come un utente in cerca di lavoro,
Voglio poter cercare offerte di lavoro utilizzando filtri e parole chiave,
Così che possa trovare le offerte più adatte alle mie competenze e interessi.
Criteri di Accettazione:
Implementazione di un motore di ricerca con filtri e parole chiave.
Risultati della ricerca pertinenti e ben organizzati.

Stima Temporale: 3 giorni

<b>4) </b>User Story per Personalizzazione dell'Account:
Titolo: Personalizzazione del Profilo

Come un utente,
Voglio poter personalizzare il mio profilo,
Così che possa mettere in evidenza le mie competenze e esperienze uniche.
Criteri di Accettazione:
Possibilità di aggiungere, modificare e rimuovere competenze e esperienze.
Opzioni per personalizzare l'aspetto del profilo.

Stima Temporale: 4 giorni.

<b>5) </b>User Story per l'Interfaccia Utente:
Titolo: Navigazione Semplice e Intuitiva

Come un utente,
Voglio un'interfaccia semplice e intuitiva,
Così che possa navigare facilmente senza confusione.
Criteri di Accettazione:
Design pulito e intuitivo dell'interfaccia utente.
Test con gli utenti per assicurare la facilità di navigazione.

Stima Temporale: 4 giorni



<b>Diagramma UML:</b>

<img src="http://yuml.me/diagram/scruffy/usecase/[Utente]-(registrazione), [Utente]-(login), [Utente]-(modificare le proprie informazioni), (modificare le proprie informazioni)>(login), [Utente]-(navigare la bacheca), (navigare la bacheca) >(login), (login)<(log out), (registrazione)<(login), [organizzazione]-(registrazione), [organizzazione]-(aggiungere nuove offerte di lavoro), (aggiungere nuove offerte di lavoro)>(login), [organizzazione]-(cancellare le offerte di lavoro), (cancellare le offerte di lavoro)<(note: devono essere state pubblicate da quel account), (cancellare le offerte di lavoro)>(login), [amministratore]-(login), [amministratore]-(cancellare utenti), (cancellare utenti)>(login), [amministratore]-(cancellare post), (cancellare post)>login, [amministratore]-(modificare post), [amministratore]-(modificare utenti), [organizzazione]-(modificare post), (modificare post)>(login), (modificare utenti)>(login)">
