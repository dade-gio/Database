Nel progetto Cibora viene realizzata una piattaforma di food delivery che comprende la progettazione e implementazione di un sistema di gestione della base di dati per supportare le operazioni della piattaforma. Ecco una descrizione dettagliata delle componenti principali sviluppate nel progetto:

1. Gestione Utenti
Registrazione e Autenticazione: Gli utenti possono registrarsi inserendo nome, email, password, numero di telefono e indirizzo di recapito. La piattaforma consente inoltre agli utenti di effettuare il login per accedere ai servizi.
Gestione Pagamenti: Gli utenti possono aggiungere metodi di pagamento come carta di credito, PayPal e Satispay, e ricaricare il proprio borsellino elettronico. Il saldo del borsellino viene aggiornato automaticamente ad ogni ordine.
Modalità Premium: Gli utenti possono sottoscrivere un abbonamento premium per avere priorità sugli ordini.
Codici Sconto: Gli utenti possono collezionare e utilizzare codici sconto basati sul numero di ordini effettuati in passato.
2. Gestione Ristoranti
Profilo Ristorante: Ogni ristorante è rappresentato da un nome, descrizione, indirizzo, costo della spedizione, immagine di profilo e rating basato sulle recensioni positive ricevute. I ristoranti possono appartenere a una o più categorie alimentari.
Top Partner: I ristoranti che offrono un servizio eccellente (basato su criteri specifici come il numero di ordini completati e la percentuale di ordini annullati) vengono classificati come Top Partner e ricevono un badge speciale.
Menu: I ristoranti possono gestire il proprio menu aggiungendo piatti con titolo, immagine, ingredienti, allergeni, prezzo e eventuali sconti.
3. Gestione Ordini
Creazione e Annullamento Ordini: Gli utenti possono selezionare piatti dal menu di un ristorante e creare un ordine. Gli ordini possono essere annullati se non sono ancora stati affidati ai riders.
Storico Ordini: Gli utenti possono visualizzare lo storico dei loro ordini e inviare reclami ai ristoranti in caso di problemi.
4. Gestione Riders
Tracciamento in Tempo Reale: La posizione dei riders viene aggiornata in tempo reale tramite GPS. I riders sono classificati in base al mezzo utilizzato (bicicletta normale, bicicletta elettrica, monopattino).
Assegnazione Ordini: Il sistema assegna gli ordini ai riders liberi in base alla distanza minima da percorrere. Per ordini con un tragitto superiore a 10 km, vengono considerati solo i riders con biciclette elettriche.
Monitoraggio delle Prestazioni: Il sistema tiene traccia del numero di consegne effettuate, dei tempi di consegna e delle prestazioni complessive dei riders.
5. Interazioni e Feedback
Chat: Gli utenti possono chattare con i ristoranti e i riders per risolvere problemi relativi agli ordini.
Recensioni e Mance: Dopo la consegna, gli utenti possono recensire il ristorante e il rider, assegnando una valutazione da 1 a 5 stelle e lasciando un commento facoltativo. Gli utenti possono anche dare mance ai riders.
6. Classifiche e Statistiche
Classifiche Mensili: Vengono aggiornate mensilmente le classifiche per i riders più veloci, i cibi più popolari, i ristoranti con più recensioni positive e i clienti che hanno speso di più.
Obiettivi del Progetto
L'obiettivo principale del progetto è creare una base di dati robusta e efficiente per supportare tutte le funzionalità della piattaforma Cibora. Il sistema è progettato per garantire un'esperienza utente fluida e affidabile, favorendo la qualità del servizio e la soddisfazione dei clienti.

Il progetto include la definizione di schemi di database, l'implementazione di logiche di business complesse per la gestione degli ordini e dei pagamenti, e l'integrazione di sistemi di tracciamento in tempo reale per i riders.
