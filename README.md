# Tutorial Pinterest API

**Materia:** Social Media Data Analysis  
**Corso di laurea:** LM-43  
**Università:** Università di Catania  
**Anno Accademico:** 2024/2025  

---

## Obiettivo del progetto

Questo progetto nasce come esercitazione pratica dedicata all’utilizzo della **Pinterest API v5** e ha l’obiettivo di guidare passo–passo all’autenticazione, alla richiesta e alla gestione dei dati provenienti dalla piattaforma.

Attraverso esempi in Python, il tutorial mostra come ottenere **token OAuth2**, effettuare chiamate API e interrogare gli endpoint principali, offrendo una base tecnica per future analisi, integrazioni o pipeline di data analysis.

---

## Metodologia

### 1. Autenticazione e Configurazione

La prima parte del progetto illustra come preparare l’ambiente di lavoro e autenticarsi tramite OAuth2:

- **Creazione dell’app Pinterest**
  - Registrazione dell’applicazione
  - Recupero di *client ID* e *client secret*
  - Definizione degli *scope* richiesti

- **Generazione del token OAuth2**
  - Creazione dell’URL di autorizzazione
  - Autorizzazione via browser
  - Recupero del *code* di verifica
  - Scambio del codice per ottenere il **token di accesso**

- **Gestione sicura delle credenziali**
  - Impiego di variabili d’ambiente
  - Esclusione dei file sensibili dal repository

---

### 2. Chiamate API e Gestione dei Dati

Una volta ottenuto il token, il progetto mostra come interagire con vari endpoint delle Pinterest API:

- **Richiesta GET di base**
  - Interrogazione di `user_account` per verificare la connessione
  - Analisi dei metadati restituiti

- **Esplorazione di Board e Pin**
  - Recupero della lista delle board associate all’account
  - Ottenimento dei pin di una board specifica
  - Analisi della struttura del JSON di risposta

- **Gestione degli errori**
  - Interpretazione di status code comuni (200, 400, 401, 403)
  - Suggerimenti per correggere richieste non valide

---

### 3. Esecuzione e Testing del Codice

Il notebook include:

- codice eseguibile con `requests`,  
- spiegazioni passo-passo,  
- esempi commentati,  
- verifiche su header e response,  
- workflow completo pronto da replicare in altri progetti.

Il progetto è pensato per essere immediatamente eseguibile, così da facilitare l’apprendimento e permettere di riutilizzare la struttura per future analisi basate su API REST.

---

## Contatti

Per dubbi, suggerimenti o collaborazioni, sentiti libera/o di contattarmi su **[LinkedIn](https://www.linkedin.com/in/marianatasha-fragalà)**.

---

🙋‍♀ **Developed by Maria Natasha Fragalà**  
© 2025 – Università degli Studi di Catania — For educational purposes.
