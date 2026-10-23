# Carevia — Product Strategy

## North Star

**Dal problema al prossimo passo.**

Carevia non deve diventare una directory di bonus, un portale di link o un marketplace generalista.
Deve essere il **motore decisionale territoriale per caregiver** che trasforma una situazione familiare reale in un piano operativo spiegabile, verificabile e aggiornabile.

## Il vuoto da coprire

Il caregiver italiano incontra informazioni distribuite tra INPS, SSN, Regioni, Province autonome, Comuni, Ambiti territoriali, ASL/ULSS, patronati, associazioni e bandi locali.

Altri soggetti possono:
- pubblicare una prestazione;
- raccogliere servizi;
- trovare professionisti;
- inviare una domanda;
- mostrare strutture vicine.

Carevia deve fare una cosa diversa:

**capire la situazione, eliminare il rumore, collegare gli enti e ordinare le azioni.**

## La promessa di prodotto

Per ogni caso Carevia deve rispondere a queste domande:

1. **Che cosa riguarda questa persona?**
2. **Perché glielo stiamo segnalando?**
3. **Che cosa manca per poterlo verificare davvero?**
4. **Chi è l’ente competente?**
5. **Qual è la fonte ufficiale?**
6. **Quando è stata verificata?**
7. **Qual è il prossimo passo?**
8. **Che cosa NON proponiamo e perché?**

Se una funzione non migliora almeno una di queste risposte, non è prioritaria.

## Moat / vantaggio difendibile

### 1. Caregiver Decision Graph
Relazioni strutturate tra:
- caratteristiche della persona assistita;
- caregiver;
- riconoscimenti;
- lavoro;
- situazione economica;
- condizione prevalente;
- territorio;
- prestazioni;
- servizi;
- documenti;
- requisiti;
- esclusioni;
- enti;
- scadenze;
- fonti.

### 2. Territorial Resolution
Percorso:
**Regione → Provincia → Comune → Ambito → Distretto/ASL → servizio**

Il territorio non è un filtro cosmetico: modifica regole, accessi, bandi e procedure.

### 3. Explainability
Ogni suggerimento deve mostrare:
- perché compare;
- cosa manca;
- stato della misura;
- fonte;
- data ultimo controllo.

### 4. Noise Removal
Carevia deve anche spiegare perché una misura famosa non viene proposta.
Ridurre informazioni inutili è parte del valore.

### 5. Next Best Action
Non mostrare 20 opportunità con pari peso.
Carevia deve individuare **una prossima azione principale**, poi ordinare il resto.

### 6. Continuous Case Management
Evoluzione futura:
- scadenze;
- follow-up;
- cambi normativi;
- bandi territoriali;
- documenti mancanti;
- cambiamento della situazione assistenziale;
- più caregiver per la stessa persona.

Carevia deve diventare un copilota nel tempo, non un questionario usa-e-getta.

## Regole editoriali

- Preferire fonti primarie istituzionali.
- Separare chiaramente:
  - misura vigente;
  - bando aperto;
  - servizio territoriale;
  - sperimentazione;
  - norma in iter;
  - informazione non ancora verificata.
- Ogni fonte deve avere una data di ultimo controllo.
- Non trasformare comunicati o DDL in diritti già disponibili.
- Non promettere idoneità automatica.
- I dati territoriali specifici devono essere pubblicati solo con una fonte identificabile.
- Le sponsorizzazioni non devono modificare il ranking delle misure pubbliche.

## Monetizzazione coerente

Il core decisionale deve restare credibile e indipendente.

Possibili livelli:
- **Free:** orientamento, piano, fonti e PDF.
- **Plus:** continuità, alert, storico, più familiari, condivisione.
- **Assist:** revisione umana tramite professionisti qualificati e processo reale.
- **Business:** welfare aziendale.
- **White label:** enti, associazioni, strutture, welfare provider.
- **Marketplace verificato:** solo come livello successivo, separato dalle fonti pubbliche.

## KPI di prodotto

Non ottimizzare per pagine viste.
Misurare:
- % utenti che arrivano a un prossimo passo concreto;
- tempo necessario per capire da dove partire;
- % suggerimenti con fonte ufficiale verificata;
- copertura territoriale;
- % percorsi in cui Carevia elimina almeno una misura non pertinente;
- ritorno dell’utente per seguire una pratica;
- azioni completate.

## Roadmap prioritaria

1. Motore decisionale spiegabile.
2. Copertura regionale completa.
3. Risoluzione Provincia/Comune/Ambito/ASL.
4. Registro strutturato delle fonti con stato e data.
5. Scadenze e monitoraggio.
6. Account/backend privacy-by-design.
7. Collaborazione familiare.
8. B2B welfare / white label.
9. Marketplace solo dopo aver consolidato indipendenza e fiducia.


## Regola non negoziabile: ACTION FIRST

Carevia non deve chiedere all'utente di ricompilare dentro Carevia una pratica che verra poi compilata di nuovo altrove.

Ogni pratica deve portare immediatamente a uno dei tre esiti operativi verificati:

1. **SCARICA MODULO UFFICIALE** — quando esiste un PDF/modulo ufficiale pertinente e aggiornato. Carevia spiega come compilarlo, quali allegati servono, dove firmare e dove consegnarlo.
2. **APRI DOMANDA ONLINE** — quando la pratica si compila su un portale ufficiale. Carevia apre direttamente il servizio compilabile, non la pagina informativa generica, e prima mostra solo la checklist di dati/documenti da avere pronti.
3. **CONTATTA IL PUNTO ESATTO** — quando non esiste un modulo o una domanda online. Carevia mostra telefono, email, PEC o sportello specifico risolto dal territorio e prepara il testo da usare.

### Vietato
- CTA primarie verso homepage generiche di INPS, ASL, Comune o Regione;
- moduli ricostruiti o inventati;
- compilazioni duplicate senza valore;
- sequenze lunghe di step prima dell'azione principale;
- link esterni che costringono l'utente a ricominciare la ricerca.

### UX obbligatoria della pratica
In alto, sempre:
**Fai questo adesso** → una CTA concreta.

Subito sotto:
- **Prepara queste cose**;
- **Dove recuperarle**;
- **Cosa ti chiederanno / cosa dire**;
- solo dopo, stato e follow-up.

La metrica principale non è “quante informazioni mostriamo”, ma **quanto lavoro burocratico evitiamo all'utente**.


## Decisione dopo il red-team (23 ottobre 2026)

Carevia continua, ma con prodotto ristretto.

### Core difendibile
1. **Grafo delle dipendenze burocratiche e socio-sanitarie**: mostra cosa sblocca cosa e quale prerequisito conviene completare per primo.
2. **Risoluzione territoriale demand-driven**: copertura nazionale base, approfondimento Distretto/modulo/contatto solo sui territori realmente usati e verificati.
3. **Action-first handoff**: modulo ufficiale, servizio online diretto o contatto esatto.
4. **Human-in-the-loop per i dati locali**: prevista come livello successivo per segnalare moduli e contatti cambiati.
5. **Ultimo miglio tramite partnership/API**: non promettere invio/protocollazione automatica finché non esiste una partnership o integrazione reale.

### Cosa non consideriamo moat
- dataset IPA/AgID e altri open data;
- semplice eligibility;
- prefill PDF da solo;
- template email/PEC;
- AI generativa;
- directory di fonti.

### Regola di copertura
Non tentare di mantenere manualmente ogni PDF di ogni Comune. Il livello nazionale serve per risolvere gli enti; la profondità locale viene costruita **dalla domanda reale degli utenti** e sottoposta a verifica.

### Promessa corretta
Carevia accompagna fino all'azione ufficiale verificata e consente di registrare manualmente protocollo, integrazioni ed esito. Non promette tracking automatico dell'ente senza integrazioni.
