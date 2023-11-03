<b>Problema:</b>
In Italia il tasso di disoccupazione è molto alto, ed è difficile trovare un metodo per mettersi in contatto con le aziende.

Soluzione/Obiettivi del sito:
La soluzione è una webapp, che funziona da board dove per affigere il proprio curriculum o offerte di lavoro

Pubblico target:
Persone alla ricerca di un lavoro

Contenuti:
La webapp conterrà il profilo del utente in cerca di lavoro e il suo curriculum, e le diverse offerte di lavoro

Struttura del sito:
L'app sarà composta da poche pagine per rendere la navigazione veloce e facile, per cui conterrà una pagina dove sono contenute tutte le informazioni del utente, e una pagina principale dove sono affisse le diverse offerte di lavoro,
sarà presenta una barra di ricerca e una ricerca a categorie.

Funzionalità e Caratteristiche:

-Diversi tipi di account: potrebbero esserci account per i candidati in cerca di lavoro e account per le aziende che offrono posizioni lavorative.

-Una bacheca per le offerte di lavoro: La webapp dovrebbe avere una bacheca in cui le aziende possono pubblicare le loro offerte di lavoro. 

-Interfaccia semplice e facile da navigare

-Ricerca basata su tag e aziende: Gli utenti dovrebbero poter cercare offerte di lavoro utilizzando parole chiave o tag pertinenti alle loro competenze e interessi. 

-Personalizzazione dell'account: Gli utenti dovrebbero avere la possibilità di personalizzare il proprio account, inserendo informazioni sulle loro competenze, esperienze e preferenze. 

-Protezione della riservatezza dei dati: La webapp dovrebbe consentire agli utenti di controllare quali informazioni sono accessibili pubblicamente e quali rimangono private.

Competizione:indeed.com

Diagramma UML:

<img src="http://yuml.me/diagram/scruffy/usecase/[Utente]-(registrazione), [Utente]-(login), [Utente]-(modificare le proprie informazioni), (modificare le proprie informazioni)>(login), [Utente]-(navigare la bacheca), (navigare la bacheca) >(login), (login)<(log out), (registrazione)<(login), [organizzazione]-(registrazione), [organizzazione]-(aggiungere nuove offerte di lavoro), (aggiungere nuove offerte di lavoro)>(login), [organizzazione]-(cancellare le offerte di lavoro), (cancellare le offerte di lavoro)<(note: devono essere state pubblicate da quel account), (cancellare le offerte di lavoro)>(login), [amministratore]-(login), [amministratore]-(cancellare utenti), (cancellare utenti)>(login), [amministratore]-(cancellare post), (cancellare post)>login, [amministratore]-(modificare post), [amministratore]-(modificare utenti), [organizzazione]-(modificare post), (modificare post)>(login), (modificare utenti)>(login)">
