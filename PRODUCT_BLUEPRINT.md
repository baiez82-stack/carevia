# Carevia — Product Blueprint
## Versione di riferimento

### North Star
**Carevia ti dice quali aiuti e servizi possono riguardare la tua famiglia e ti accompagna, passo dopo passo, fino alla conclusione della pratica.**

Carevia non è:
- un elenco di bonus;
- un portale di link;
- un motore di ricerca;
- un patronato digitale che promette esiti automatici.

Carevia è un **case manager digitale territoriale**.

---

# 1. Principio di prodotto

Ogni utente deve poter capire, in meno di 60 secondi:

1. **Che cosa riguarda la mia situazione?**
2. **Che cosa devo fare per prima cosa?**
3. **Che cosa mi manca?**
4. **Dove devo andare?**
5. **Come capisco quando la pratica è finita?**

Ogni funzione nuova deve migliorare almeno una di queste risposte.

---

# 2. Linguaggio

## Regola
Prima linguaggio umano, poi linguaggio amministrativo.

### Sbagliato
“ICD – UVMD – PUA – FNA”

### Corretto
**Puoi verificare un contributo per continuare l’assistenza a casa.**

Sotto:
> In Veneto questo percorso si chiama Impegnativa di Cura Domiciliare (ICD) e può richiedere una valutazione UVMD.

Gli acronimi devono avere sempre:
- nome esteso;
- significato;
- perché interessa l’utente.

---

# 3. Struttura dell’esperienza

## A. Home
Una sola promessa:

> **Raccontaci la situazione. Ti diciamo cosa può riguardarti e da dove partire.**

CTA primaria:
**Inizia il percorso**

CTA secondaria:
**Riprendi una pratica**

Niente cataloghi di bonus in home.

---

## B. Valutazione iniziale
Massimo 5 passaggi.

### 1. Persona assistita
- età;
- relazione col caregiver;
- situazione prevalente;
- vive sola / con familiari / struttura.

### 2. Territorio
- Regione;
- Provincia;
- Comune;
- geolocalizzazione opzionale.

Carevia risolve:
- ASL/ULSS/ATS sanitaria;
- Ambito Territoriale Sociale;
- Regione;
- servizi locali verificati;
- eventuale livello sub-comunale necessario.

### 3. Riconoscimenti
- invalidità/disabilità;
- Legge 104;
- gravità art. 3 comma 3;
- accompagnamento;
- eventuale verbale/procedura in corso.

### 4. Caregiver / situazione economica
- lavoratore dipendente/autonomo/pensionato/non occupato;
- collegamento a dipendente/pensionato pubblico;
- fascia ISEE sociosanitario;
- disponibilità ISEE.

### 5. Bisogni
- assistenza a domicilio;
- sollievo caregiver;
- pratiche/agevolazioni;
- assistente familiare;
- visite/farmaci;
- ausili/adattamento casa;
- trasporto;
- residenzialità;
- supporto demenze;
- cure palliative.

---

# 4. Motore “A cosa posso avere diritto?”

Carevia non deve mostrare una lista piatta.

Ogni opportunità riceve uno dei seguenti stati:

## ✅ Requisiti compatibili
I principali requisiti noti risultano compatibili.

Copy:
> **I dati inseriti sono compatibili con i requisiti principali.**
> L’ente competente dovrà comunque confermare formalmente l’accesso.

## 🟡 Probabilmente compatibile
Manca un elemento decisivo.

Copy:
> **Potrebbe riguardarti.**
> Per capirlo manca: [documento/requisito/valutazione].

## 🔵 Servizio da attivare
Non è un “diritto economico”, ma un servizio territoriale che può essere richiesto.

Copy:
> **Questo servizio può essere attivato nel tuo territorio.**
> Serve una valutazione del servizio competente.

## ⚫ Non compatibile con i dati inseriti
Copy:
> **Al momento non risulta compatibile.**
> Motivo: [età / ISEE / requisito / categoria].

## ⚪ Dati insufficienti
Copy:
> **Non possiamo ancora valutarlo.**
> Ci manca: [dato].

---

# 5. Scheda opportunità

Ogni scheda deve contenere SEMPRE:

### Titolo umano
“Contributo per continuare l’assistenza a casa”

### Nome amministrativo
“Impegnativa di Cura Domiciliare (ICD)”

### Stato
Probabilmente compatibile

### Perché Carevia lo propone
> Hai indicato: 82 anni, assistenza a domicilio, Veneto, accompagnamento.

### Cosa manca
> Serve verificare la tipologia ICD, ISEE e valutazione del bisogno.

### Cosa ottieni
- contributo;
- servizio;
- agevolazione;
- tutela lavorativa;
- supporto sanitario.

### Chi decide
- INPS;
- Regione;
- Comune;
- ASL/ULSS;
- Ambito;
- altro ente.

### Fonte
URL istituzionale.

### Ultimo controllo
Data.

### CTA
**Apri la pratica**

---

# 6. Il cuore di Carevia: la PRATICA

Una misura selezionata non apre un articolo.
Apre una **pratica guidata**.

## Header pratica
**Assistenza domiciliare — ADI**
Stato: Preparazione documenti

### Progressione
1. Requisiti
2. Documenti
3. Ente
4. Richiesta
5. Attesa
6. Esito

---

# 7. Stati di una pratica

Ogni pratica deve avere uno stato standardizzato:

1. **Da valutare**
2. **Compatibilità verificata**
3. **Documenti da preparare**
4. **Pronta da inviare**
5. **Inviata / richiesta attivata**
6. **In attesa dell’ente**
7. **Integrazione richiesta**
8. **Appuntamento / valutazione**
9. **Approvata / attivata**
10. **Respinta**
11. **Conclusa**
12. **Da rinnovare**

Carevia mostra sempre:
> **Cosa succede adesso**

---

# 8. Next Best Action Engine

Una sola priorità principale per volta.

Esempio:

## Oggi fai questo
**Recupera l’ISEE sociosanitario**

Perché:
> Senza ISEE non possiamo verificare due delle misure più rilevanti per il caso.

CTA:
**Segna come fatto**

Dopo:
> Perfetto. Ora possiamo verificare ICD e Prestazione Universale.

Il motore deve ordinare le azioni secondo:
1. urgenza sanitaria;
2. prerequisiti che sbloccano più pratiche;
3. scadenze;
4. valore/beneficio potenziale;
5. dipendenze burocratiche;
6. semplicità di attivazione.

---

# 9. Dipendenze tra pratiche

Carevia deve sapere che alcune azioni sbloccano altre.

Esempio:

**ISEE sociosanitario**
→ sblocca verifica ICD
→ sblocca Prestazione Universale
→ può influire su compartecipazione SAD

**Verbale 104 art. 3 comma 3**
→ sblocca valutazione permessi 104
→ sblocca congedo straordinario
→ può incidere su altri interventi

**UVMD**
→ può sbloccare ICD
→ servizi domiciliari
→ residenzialità
→ progetto assistenziale.

Questo grafo di dipendenze è parte centrale del moat.

---

# 10. Documenti

I documenti non devono essere una cartella generica.

Ogni documento deve avere:

- nome umano;
- a cosa serve;
- pratiche che lo utilizzano;
- stato;
- data;
- eventuale scadenza;
- chi lo rilascia.

Esempi:
- ISEE sociosanitario;
- verbale invalidità;
- verbale Legge 104;
- accompagnamento;
- documento identità;
- tessera sanitaria;
- certificato medico;
- PAI;
- UVMD;
- delega;
- ricevuta domanda.

## Stati
- non disponibile;
- da richiedere;
- disponibile;
- caricato;
- da aggiornare;
- scaduto.

---

# 11. Ente e modalità di accesso

Ogni pratica deve dire chiaramente:

## Devi rivolgerti a
**ULSS 9 Scaligera**

## Servizio
Distretto / ADI / COT

## Come
- online;
- telefono;
- email;
- sportello;
- medico di base;
- patronato;
- altro professionista.

## Cosa dire
Carevia può fornire una frase semplice:
> “Vorrei sapere come avviare la valutazione per assistenza domiciliare per mia madre residente a…”

## Cosa portare
Checklist.

---

# 12. Conclusione pratica

Una pratica è conclusa solo quando Carevia sa l’esito.

### Approvata
Mostrare:
- cosa è stato ottenuto;
- decorrenza;
- eventuale importo;
- prossima scadenza;
- rinnovo.

### Respinta
Chiedere:
- motivo;
- documento ricevuto;
- possibilità di integrazione/riesame/ricorso;
- professionista consigliato quando necessario.

### Servizio attivato
Mostrare:
- data attivazione;
- referente;
- frequenza;
- prossimo controllo.

---

# 13. Dashboard principale

La dashboard NON deve essere piena di card.

Deve contenere:

## 1. Prossima azione
La cosa più importante da fare.

## 2. Le tue pratiche
Massimo 3 stati sintetici:
- 2 da preparare;
- 1 in attesa;
- 1 conclusa.

## 3. Opportunità nuove
Solo se davvero pertinenti.

## 4. Scadenze
ISEE, rinnovi, appuntamenti, integrazioni.

## 5. Territorio
ASL + Ambito già risolti.

---

# 14. Navigazione

Menu definitivo consigliato:

- **Home**
- **Il mio percorso**
- **Pratiche**
- **Documenti**
- **Territorio**
- **Fonti**

Da evitare:
- “Sostegni”
- sezioni duplicate;
- tecnicismi amministrativi.

---

# 15. Modello dati principale

## Person
persona assistita.

## Caregiver
persona che assiste.

## Territory
Regione, Provincia, Comune, ASL, Ambito, Distretto.

## Benefit / Service
misura o servizio.

## EligibilityRule
requisito.

## EligibilityResult
valutazione del singolo caso.

## Case
pratica aperta.

## CaseStep
passaggio della pratica.

## Requirement
requisito mancante/verificato.

## Document
documento.

## Authority
ente.

## Deadline
scadenza.

## Source
fonte ufficiale.

## Dependency
relazione tra pratica/documento/requisito.

## Event
evento storico della pratica.

---

# 16. Regola di trasparenza

Carevia non deve mai dire “hai diritto” quando non può dimostrarlo.

Deve mostrare:

- **compatibile**;
- **probabile**;
- **da attivare**;
- **non compatibile**;
- **non determinabile**.

Per ogni risultato:
- motivo;
- requisito;
- fonte;
- data;
- ente che decide.

---

# 17. Local Decision Engine

Ordine delle regole:

1. norma nazionale;
2. Regione;
3. Provincia / Città Metropolitana;
4. Comune;
5. Ambito Territoriale Sociale;
6. ASL/ULSS/ATS;
7. Distretto;
8. servizio locale;
9. eventuale livello sub-comunale.

Se il livello locale non è risolto:
> **Carevia non ha ancora una fonte locale verificata.**
> Ti mostriamo il livello istituzionale più preciso disponibile.

---

# 18. Tipologie di pratica da implementare per prime

## Tier 1 — massima priorità
1. Invalidità / accertamento disabilità
2. Legge 104
3. Accompagnamento
4. Permessi 104
5. Congedo straordinario
6. ADI
7. SAD
8. Prestazione Universale
9. ICD / assegni di cura regionali
10. Home Care Premium

## Tier 2
11. Disability Card
12. ausili/protesica
13. Dopo di Noi
14. esenzioni ticket
15. CDCD / demenze
16. cure palliative
17. centri diurni
18. telesoccorso
19. pasti a domicilio
20. assistente familiare

---

# 19. Template pratica

Ogni nuova pratica deve poter essere definita con:

- id
- nome umano
- nome amministrativo
- descrizione
- tipo
- territorio
- requisiti
- criteri di esclusione
- documenti
- ente
- modalità di accesso
- URL modulo
- URL fonte
- passaggi
- dipendenze
- scadenza
- rinnovo
- stato normativo
- data ultimo controllo

Questo deve consentire di aggiungere nuove pratiche senza modificare ogni volta l’interfaccia.

---

# 20. Monetizzazione compatibile con la fiducia

## Free
Deve includere:
- valutazione;
- territorio;
- opportunità;
- pratiche base;
- fonti;
- PDF.

Non mettere dietro paywall il “sapere da dove iniziare”.

## Plus
Può monetizzare:
- account cloud;
- più persone assistite;
- sincronizzazione famiglia;
- notifiche;
- scadenze;
- storico;
- documenti cloud;
- aggiornamenti automatici personalizzati.

## Assist
Solo quando esiste un processo reale:
- revisione professionale;
- appuntamento;
- patronato/professionista;
- supporto pratica.

## Business / White Label
- aziende;
- welfare;
- cooperative;
- associazioni;
- enti;
- strutture.

Le sponsorizzazioni non possono modificare il ranking dei diritti/servizi pubblici.

---

# 21. UX per persone in difficoltà

## Regole
- una sola CTA primaria per schermata;
- frasi brevi;
- niente gergo senza spiegazione;
- progressi visibili;
- sempre “cosa faccio adesso”;
- evitare tabelle complesse su mobile;
- font leggibili;
- contrasto elevato;
- niente colori come unica indicazione di stato;
- pulsanti grandi;
- possibilità di salvare e riprendere;
- stampa/PDF;
- eventuale condivisione con familiare.

---

# 22. Fasi di sviluppo

## Fase A — Decision Engine
- standardizzare EligibilityRule;
- standardizzare stati;
- mostrare motivazione/esclusione;
- ordinare opportunità.

## Fase B — Practice Engine
- oggetto Case;
- CaseStep;
- avanzamento;
- documenti;
- azioni completate.

## Fase C — Local Engine
- collegare ASL/ATS/Regione/Comune;
- servizio specifico;
- contatti;
- moduli;
- modalità di accesso.

## Fase D — Persistence
- backend;
- account;
- storico;
- notifiche;
- documenti;
- condivisione.

## Fase E — Intelligence
- monitoraggio fonti;
- cambi normativi;
- nuove misure;
- ricalcolo automatico delle opportunità.

---

# 23. Criteri di accettazione del prodotto

Carevia è utile solo se un utente può completare questo scenario:

> “Assisto mia madre e non so da dove iniziare.”

Entro pochi minuti Carevia deve:
1. identificare il territorio;
2. individuare 3–5 percorsi realmente pertinenti;
3. eliminare quelli non pertinenti;
4. spiegare il motivo;
5. scegliere una priorità;
6. indicare documenti necessari;
7. indicare ente e modalità di accesso;
8. aprire una pratica;
9. permettere di segnare un passaggio come fatto;
10. accompagnare fino a esito/conclusione.

Se manca uno di questi passaggi, Carevia è ancora un orientatore.
Quando tutti sono presenti, Carevia diventa un **case manager digitale**.

---

# 24. Posizionamento definitivo

## Payoff
**Carevia. Dal problema al prossimo passo.**

## Descrizione breve
**Il case manager digitale che aiuta i caregiver a capire quali aiuti e servizi possono riguardare la propria famiglia e li accompagna, passo dopo passo, fino alla conclusione della pratica.**

## Differenza competitiva
**Non mostra tutto ciò che esiste. Mostra ciò che riguarda te, nel tuo territorio, e ti dice cosa fare dopo.**
