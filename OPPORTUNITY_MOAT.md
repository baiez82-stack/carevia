# Carevia — Opportunity, Unicita e Moat

## Tesi

Carevia non deve essere:
- un catalogo di bonus;
- un CAF digitale generalista;
- un ecosistema caregiver generico;
- un motore di ricerca di servizi;
- una raccolta di guide.

Carevia deve essere il **navigatore operativo delle pratiche e dei servizi di caregiving**.

La promessa da difendere e:

> Dalla situazione reale della famiglia all'azione amministrativa o assistenziale corretta, nel territorio corretto, con il minor numero possibile di passaggi manuali.

## Cosa esiste gia

### BonusX
Punti forti:
- discovery di bonus e agevolazioni;
- pratiche gestite da operatori;
- upload documenti e firme;
- stato pratica;
- servizi CAF/patronato e fiscali.

Implicazione:
Carevia non deve competere come "portale bonus + pratica gestita".

Fonti:
- https://bonusx.it/
- https://bonusx.it/operatori/

### InsiemePiu
Punti forti:
- posizionamento specifico caregiver;
- burocrazia, cura, organizzazione, supporto psicologico e professionisti;
- AI e strumenti per documenti.

Implicazione:
Carevia non deve competere come "ecosistema completo del caregiving".

Fonti:
- https://www.insiemepiu.com/
- https://www.insiemepiu.com/servizi/

## Spazio competitivo da occupare

Carevia deve vincere su 5 dimensioni congiunte:

1. **Case orchestration**
   Non una pratica isolata: una sequenza di dipendenze.
   Esempio: certificato medico -> accertamento -> verbale -> 104 -> permessi/congedo -> misure regionali.

2. **Territorial resolution**
   Comune -> ASL/Azienda sanitaria -> Ambito Sociale -> Regione -> servizio specifico.

3. **Action-first handoff**
   Ogni pratica termina in:
   - PDF ufficiale;
   - domanda online diretta;
   - telefono/email/PEC/sportello esatto.

4. **Official-form assistance**
   Quando esiste un modulo ufficiale:
   - trovare la versione corretta;
   - spiegare i campi;
   - precompilare quando tecnicamente possibile;
   - indicare firma, allegati e destinazione.

5. **Continuous follow-up**
   Dopo il primo contatto:
   - invio;
   - protocollo;
   - integrazione;
   - appuntamento/valutazione;
   - esito;
   - rinnovo.

## Regola di unicita

Una funzione e strategica solo se riduce almeno uno di questi costi per l'utente:
- ricerca;
- interpretazione;
- compilazione;
- reperimento documenti;
- scelta dell'ente;
- invio;
- follow-up.

Se aggiunge informazioni senza ridurre un costo, non e moat.

## Anti-feature

Carevia NON deve:
- aprire home page generiche;
- mostrare 20 misure con pari peso;
- far ricompilare dati che l'utente dovra inserire identici su un portale esterno;
- ricostruire PDF non ufficiali;
- dichiarare copertura locale senza fonte;
- sostituire CAF, patronati, medici o enti quando serve un professionista abilitato;
- competere su community, psicologia, marketplace o agenda sanitaria prima di aver dominato la burocrazia operativa.

## North Star metric

**Percentuale di percorsi in cui l'utente raggiunge un'azione ufficiale verificata senza dover cercare autonomamente dove andare o cosa compilare.**

Metriche secondarie:
- tempo dalla profilazione alla prima azione utile;
- percentuale di CTA che puntano a modulo/servizio/contatto esatto;
- percentuale pratiche con documenti recuperabili tramite link preciso;
- percentuale pratiche con follow-up registrato;
- percentuale link ufficiali verificati e attivi;
- numero medio di passaggi eliminati rispetto al percorso manuale.

## Criteri di accettazione di una pratica

Una pratica non e "completa" finche non ha:

1. eligibility / motivo per cui compare;
2. action class: PDF / online / contatto;
3. CTA esatta;
4. lista documenti;
5. dove recuperare i documenti, quando possibile;
6. cosa verra chiesto nel modulo/portale;
7. fonte ufficiale e data verifica;
8. ente competente;
9. cosa succede dopo l'invio;
10. stato finale / rinnovo.

## Kill criteria

La tesi Carevia va ridimensionata se, dopo verifica competitiva:
- un concorrente nazionale caregiver offre gia Comune->ente->modulo ufficiale->precompilazione->follow-up su larga scala;
- non e possibile mantenere aggiornati i moduli e i percorsi territoriali con un costo sostenibile;
- la maggior parte delle pratiche richiede comunque un intermediario abilitato e Carevia non riduce materialmente il lavoro dell'utente;
- il tempo medio per mantenere una pratica verificata supera il valore generato;
- gli utenti preferiscono delegare completamente a CAF/patronato invece di usare un copilota operativo.

## Priorita di sviluppo

### P0
- pratiche Tier 1 con action class corretta;
- link diretti;
- document recovery;
- tracking invio/esito;
- verifiche automatiche dei link.

### P1
- registry dei PDF ufficiali;
- parser dei moduli PDF;
- prefill client-side;
- firma/istruzioni di firma;
- generazione del pacchetto pratica.

### P2
- backend account;
- storico;
- notifiche;
- collaborazione familiare;
- revisione umana opzionale.

### P3
- espansioni non core solo dopo prova del moat.

## Posizionamento

**Carevia e il navigatore operativo del caregiving. Capisce il caso, risolve il territorio e ti porta direttamente al modulo, alla domanda o al contatto giusto, seguendo la pratica fino all'esito.**

Payoff:
**Carevia. Dal problema al prossimo passo.**

Comportamento di prodotto:
**dal prossimo passo all'azione concreta, senza ricerche da rifare.**
