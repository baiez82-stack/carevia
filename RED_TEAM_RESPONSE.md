# Carevia — Decisione dopo Red Team Gemini

Data: 23 ottobre 2026

## Decisione

**Continuare, ma restringere il prodotto.**

Carevia non compete come portale bonus, CAF digitale o ecosistema caregiver completo.

Il core diventa:

1. **Grafo delle dipendenze burocratiche e socio-sanitarie**
2. **Next Best Action basata sui prerequisiti reali**
3. **Risoluzione territoriale demand-driven**
4. **Action-first handoff**
5. **Registrazione manuale del follow-up finche non esistono API/partnership**

## Implementato subito

- `data/dependency_graph.json`: primo modello di dipendenze.
- UI “Grafo delle dipendenze” nel percorso personale.
- La prossima azione usa il grafo e non piu una priorita statica.
- Copia guidata dei dati gia disponibili per i portali online.
- Campi locali per data invio, protocollo/ricevuta e note/integrazioni.
- Rimosso dalla home il dataset territoriale come elemento di differenziazione.
- Posizionamento: il territorio e infrastruttura necessaria, non moat.

## Cosa NON consideriamo moat

- AI generativa
- eligibility generica
- open data IPA/AgID
- semplice prefill PDF
- template email/PEC
- lista di fonti
- directory di servizi

## Moat da costruire

### 1. Dependency Graph
Il valore e sapere che una determinata azione sblocca piu percorsi e quindi va fatta prima.

### 2. Data maintenance network
Change detection automatica + verifica umana sui nodi territoriali ad alto utilizzo.

### 3. Last-mile partnerships
Patronati, CAF, welfare provider o altri soggetti abilitati solo dove servono realmente invio/protocollazione/revisione.

## Strategia territoriale

Copertura nazionale base:
- Comune -> Azienda sanitaria
- Comune -> Ambito Sociale
- Comune -> contatti istituzionali
- Regione

Approfondimento locale:
- solo sui territori/pratiche con domanda reale;
- Distretto;
- servizio specifico;
- modulo;
- contatto;
- procedura.

## P0

1. Grafo dipendenze per le pratiche core.
2. Action class precisa per ogni pratica.
3. Recupero documenti.
4. Copia guidata per portali SPID/CIE.
5. Tracking manuale di protocollo, integrazioni ed esito.

## P1

1. Registry PDF ufficiali demand-driven.
2. Prefill PDF local-first.
3. Change detection su moduli e contatti.
4. Human-in-the-loop per verifiche locali.
5. Prime partnership di ultimo miglio.

## P2

1. Account/backend privacy-by-design.
2. Collaborazione familiare.
3. Alert/scadenze.
4. B2B welfare.
5. White label / integrazioni.

## Regola di promessa

Carevia puo promettere:
> “Ti portiamo alla prossima azione ufficiale verificata e ti aiutiamo a non perdere il filo.”

Carevia NON puo ancora promettere:
> “Seguiamo automaticamente la pratica dentro l’ente fino all’esito.”

## Metriche

- tempo profilo -> prima azione utile;
- numero di ricerche esterne evitate;
- percentuale di percorsi con CTA esatta;
- percentuale di nodi che sbloccano piu pratiche;
- percentuale di documenti recuperabili con link preciso;
- percentuale di follow-up registrati;
- costo di manutenzione per pratica/territorio attivo.

## Kill criteria

- se il mantenimento locale costa piu del valore prodotto, restringere la copertura profonda;
- se il B2C non converte, passare a B2B/B2B2C;
- se l’ultimo miglio e il valore dominante, integrare partner abilitati invece di replicarli;
- se una piattaforma pubblica unificata risolve davvero socio-sanitario + sociale + invio, rivalutare la tesi.
