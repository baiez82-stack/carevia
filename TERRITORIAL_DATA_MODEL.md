# Carevia — Territorial Data Model

## Obiettivo

Carevia non considera il territorio un semplice filtro geografico.
Il registro territoriale è parte del motore decisionale e deve consentire di risolvere il percorso:

**Regione → Provincia → Comune → Ambito → Distretto/ASL/ULSS → servizio → modalità di accesso**

## Regola fondamentale

Un nodo territoriale può essere mostrato come **verificato** solo se dispone di:

- ente identificabile;
- fonte istituzionale;
- descrizione del servizio;
- modalità di accesso;
- ambito geografico;
- stato del servizio/misura;
- data dell’ultimo controllo Carevia.

Se manca uno di questi elementi, il nodo deve essere marcato come:
- copertura regionale;
- copertura base;
- fallback da verificare.

Carevia non deve fingere precisione locale.

## Schema minimo di un nodo

- id
- scope: Regione / Comune / ASL-ULSS / Ambito / Distretto
- region
- province
- city
- type
- title
- status
- purpose
- access
- eligibility / target
- source_url
- verified_at
- condition_tags
- age_constraints
- needs_tags
- dependencies
- exclusions

## Livelli di copertura

### Verificata locale
Il Comune/Distretto specifico dispone di più nodi verificati e utilizzabili nel decision engine.

### Verificata regionale
Sono disponibili misure regionali verificate ma non ancora risolti tutti gli enti locali.

### Copertura base
Sono disponibili solo percorsi nazionali e indicazioni generiche.

Il livello deve essere sempre visibile all’utente.

## Pilot Verona / Veneto — 22 ottobre 2026

Nodi iniziali verificati:

1. Regione Veneto — Impegnative di Cura Domiciliare (ICD)
2. Regione Veneto — interventi a favore del caregiver familiare
3. Comune di Verona — Sportello Sì / Centri Sociali Territoriali
4. Comune di Verona — ICD e sostegno caregiver
5. Comune di Verona — Servizio di Assistenza Domiciliare (SAD)
6. Comune di Verona — pasti a domicilio
7. Comune di Verona — telesoccorso / telecontrollo
8. ULSS 9 Scaligera — Distretto 1 Verona Città
9. ULSS 9 Scaligera — ADI / COT Verona Città
10. ULSS 9 Scaligera — UVMD
11. ULSS 9 Scaligera — rete cure palliative
12. Veneto — Sanità km zero Fascicolo / deleghe

## Processo editoriale

1. Ricerca su fonte primaria istituzionale.
2. Verifica data e stato.
3. Classificazione del nodo.
4. Inserimento di requisiti e accesso.
5. Collegamento alle condizioni del Decision Graph.
6. Test con caso reale/dimostrativo.
7. Pubblicazione con data di verifica.
8. Riesame periodico o quando cambia una norma/bando.

## Priorità di espansione

1. Veneto completo:
   - ULSS;
   - capoluoghi;
   - Ambiti Territoriali Sociali;
   - ICD / caregiver / sollievo;
   - ADI / PUA / COT;
   - CDCD;
   - servizi comunali.
2. Lombardia.
3. Emilia-Romagna.
4. Piemonte.
5. Lazio.
6. Toscana.
7. resto d’Italia.

La priorità non indica importanza sociale: serve a costruire progressivamente densità territoriale verificata.

## Metriche territoriali

- % popolazione coperta da registry verificato;
- numero di nodi verificati;
- fonti scadute da riesaminare;
- % percorsi con un ente locale concreto;
- % percorsi che evitano un fallback Google;
- tempo medio tra bisogno e primo punto di accesso concreto.

## Moat

La barriera competitiva non è la quantità di link, ma la relazione strutturata tra:

**caso → requisito → misura → ente → territorio → accesso → documento → prossimo passo**

Ogni nuova fonte deve aumentare questa capacità, non solo la dimensione della biblioteca.
