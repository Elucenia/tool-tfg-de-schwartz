<!-- ELUCENIA technical documentation · tfg-de-schwartz · it · no clinical/professional/rights approval -->

# VFG pediatrica (Schwartz al letto del paziente)

[condizioni, fonti e autorizzazioni](https://elucenia.org/it/strumenti/tfg-de-schwartz)

## Come usare

Usi lo strumento nel portale oppure apra index.html tramite un server HTTP locale. Selezioni la lingua, compili i campi ed esegua il calcolo.

## Dati di ingresso e unità

### Altezza

`altura`

cm · intervallo: 40–200

### Creatinina sierica (metodo enzimatico)

`cr`

mg/dL · intervallo: 0,1–15

## Edizione del metodo

CKiD bedside Schwartz 2009:0,413×altezza/Cr IDMS; mL/min/1,73m²; non CKiD U25

## Formula documentata

eGFR (mL/min/1,73 m²) = 0,413 × altezza (cm) ÷ creatinina (mg/dL)

Equazione al letto Schwartz 2009 (bedside) derivata CKiD con creatinina enzimatica tracciabile IDMS.

## Limiti e popolazione

Questa è l’equazione bedside Schwartz del 2009, derivata da 349 partecipanti con malattia renale cronica nello studio CKiD, la cui età eleggibile per il reclutamento era di 1–16 anni. La creatinina deve essere misurata con metodo enzimatico e tracciabile a IDMS. Lo studio originale ha segnalato la necessità di ulteriore validazione nei bambini con funzione renale più elevata prima di usare la formula per lo screening di tutti i bambini. Il risultato è una stima indicizzata a 1,73 m², non una GFR misurata, una diagnosi isolata o una dose di farmaco; non rappresenta CKiD U25.

## Riferimenti

- [Schwartz GJ et al. New equations to estimate GFR in children with CKD. J Am Soc Nephrol, 2009.](https://doi.org/10.1681/ASN.2008030287)

- [Kidney Disease: Improving Global Outcomes (KDIGO) CKD Work Group. KDIGO 2024 Clinical Practice Guideline for the Evaluation and Management of Chronic Kidney Disease. Kidney Int, 2024.](https://doi.org/10.1016/j.kint.2023.10.018)

- [Original Schwartz2009;JASN20:629–637;DOI10.1681/ASN.2008030287](https://www.infectedbloodinquiry.org.uk/sites/default/files/Batch%204/Batch%204/WITN7142008%20-%20New%20equations%20to%20estimate%20GFR%20in%20children%20with%20CKD%20-%2001%20Jan%202009.pdf)

## Riprodurre i test tecnici

Esegua node test.cjs nella cartella principale di questo repository per ripetere i casi sintetici registrati. Gli input, i risultati attesi e le tolleranze originali sono conservati. I test tecnici non costituiscono validazione clinica.

```sh
node test.cjs
```

tool.json contiene le fonti, l’edizione e l’ambito della revisione. examples.json conserva gli input e i risultati attesi dei casi sintetici; results.json registra i risultati ottenuti.

[Scheda e riferimenti](../tool.json) · [Codice JavaScript](../calculator.js) · [Casi di riferimento](../examples.json) · [results.json](../results.json)

## Revisione e condizioni d’uso

Non è stata effettuata una revisione clinica indipendente.

Questa interfaccia è una traduzione realizzata dagli autori, non un’edizione ufficiale o certificata. Non sono state eseguite la revisione clinica indipendente, la revisione linguistica professionale né la verifica delle autorizzazioni relative ai diritti sugli strumenti.

Risultato della formula o classificazione. Interpretazione, condotta e applicabilità dipendono dalla valutazione professionale e dalla fonte selezionata.

## Licenza e attribuzione

Apache-2.0 si applica solo al codice di ELUCENIA. I diritti su strumenti, pubblicazioni, traduzioni e dati restano ai rispettivi titolari. Conservi LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Risultati documentati

Le informazioni seguenti conservano gli output del metodo per esempi sintetici. Non costituiscono una validazione clinica indipendente.

### 1

Categoria G1: GFR normale o elevata

La classificazione nelle categorie G1 a G5 vale a partire dai 2 anni; prima di allora, confrontare con i valori normali per l’età.


### 2

Categoria G3b: GFR moderatamente o gravemente ridotta

La classificazione nelle categorie G1 a G5 vale a partire dai 2 anni; prima di allora, confrontare con i valori normali per l’età.


### 3

Categoria G4: GFR gravemente ridotta

La classificazione nelle categorie G1 a G5 vale a partire dai 2 anni; prima di allora, confrontare con i valori normali per l’età.


### 4

Categoria G2: GFR lievemente ridotta

La classificazione nelle categorie G1 a G5 vale a partire dai 2 anni; prima di allora, confrontare con i valori normali per l’età.

