# Documento dei Requisiti – ProgettoSitoWebLego
## 1. Introduzione
### 1.1 Scopo del documento
Questo documento descrive i requisiti del sito web Lego.

### 1.2 Contesto
Il sistema è un'applicazione web che permette agli utenti di esplorare il mondo Lego, cercare singoli pezzi, leggere l'evoluzione della storia e conoscere invenzioni Lego.

### 1.3 Tema d'esempio
Lettura di come sono cambiati i prodotti Lego nel tempo e visione delle creazioni.

## 2. Obiettivi generali
- Creare un sito web informativo
- Permettere agli utenti di vedere ser e cercare singoli pezzi Lego
- Offrire la visione della storia e di creazioni Lego
- Gestire un catalogo di mattoncini di diverso colore

## 3. Stakeholder e Attori
Attori principali:
- Utente non registrato: può visualizzare la storia dei Lego
- Utente registrato: vede il catologi e i set Lego
- Amministratore: gestisce set LEGO e catalogo

## 4. Requisiti Funzionali
### 4.1 Requisiti principali
- Registrazione utente
- Login utente
- Inserimento nuovi set Lego (admin)
- Eliminazione set LEGO (admin)
- Visualizzazione catalogo pezzi
- Ricerca pezzi specifici
- Visualizzazione storia
- Accesso a invenzioni

### 4.2 User Stories
- Come utente voglio registrarmi per accedere al sito
- Come utente voglio effettuare il login
- Come utente voglio cercare pezzi Lego specifici
- Come amministratore voglio aggiungere nuovi set
- Come amministratore voglio eliminare set esistenti
- Come utente voglio guardare le creazioni Lego
- Come utente voglio conoscere la storia Lego

## 5. Requisiti Non Funzionali
- Prestazioni: caricamento pagine veloce
- Usabilità: interfaccia semplice e intuitiva
- Sicurezza: gestione sicura delle credenziali
- Affidabilità: sistema stabile
- Compatibilità: accessibile da browser moderni
- Manutenibilità: codice organizzato

## 6. Casi d’Uso
### 6.1 Casi d’uso essenziali
- Registrazione
- Login
- Ricerca pezzi
- Gestione set (admin)
- Visualizzazione storia e creazioni

### 6.2 Descrizione semplificata dei casi d’uso
- L’utente accede al sito
- Cerca i pezzi
- Guarda le crezioni
- Legge la storia
- Amministratore festisce i set

### 6.3 Relazioni tra casi d’uso (include / extend)
- Login → include autenticazione utente
- Invenzioni e Storia → extend intrattenimento
- Gestione set → include inserimento e cancellazione

### 6.4 Diagramma dei casi d’uso
Attori (utente, admin) collegati a:
- Login
- Registrazione
- Gestione set
- Visualizzazione creazioni
- Lettura storia

## 7. Glossario dei Termini
- Lego Set: insieme di pezzi e informazioni
- Pezzo: singolo mattoncino Lego
- Catalogo: elenco dei mattoncini di colori diversi
- Invenzioni: creazioni Lego
- Storia: descrizione evoluzione prodotti Lego

## 8. Pianificazione e Milestone
### 8.1 Gantt super semplificato
Fase	           Durata	            Significato
Analisi	        1 settimana	    Capire cosa deve fare il sito
Progettazione	1 settimana	    Decidere come sarà fatto il sito
Sviluppo	    2 settimane	    Costruire il sito
Test	          3 giorni	    Controllare che tutto funzioni
Rilascio	      1 giorno	    Mettere il sito online