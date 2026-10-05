<!-- ELUCENIA technical documentation · tfg-de-schwartz · en · no clinical/professional/rights approval -->

# Pediatric GFR (bedside Schwartz)

[conditions, sources and permissions](https://elucenia.org/en/tools/tfg-de-schwartz)

## How to use

Use the tool in the portal or open index.html through a local HTTP server. Select the language, complete the fields and calculate.

## Inputs and units

### Height

`altura`

cm · range: 40–200

### Serum creatinine (enzymatic assay)

`cr`

mg/dL · range: 0.1–15

## Method edition

CKiD bedside Schwartz 2009:0.413×height/IDMS creatinine; mL/min/1.73m²; not CKiD U25

## Documented formula

eGFR (mL/min/1.73 m²) = 0.413 × height (cm) ÷ creatinine (mg/dL)

Schwartz 2009 bedside equation (bedside) derived in CKiD with enzymatically calibrated creatinine traceable to IDMS.

## Limits and population

This is the 2009 bedside Schwartz equation, derived from 349 participants with chronic kidney disease in the CKiD study, whose recruitment eligibility was ages 1–16 years. Creatinine must be measured enzymatically and traceable to IDMS. The original study noted that further validation in children with higher kidney function was needed before using the formula to screen all children. The result is an estimate indexed to 1.73 m², not measured GFR, an isolated diagnosis or a medicine dose; it does not represent CKiD U25.

## References

- [Schwartz GJ et al. New equations to estimate GFR in children with CKD. J Am Soc Nephrol, 2009.](https://doi.org/10.1681/ASN.2008030287)

- [Kidney Disease: Improving Global Outcomes (KDIGO) CKD Work Group. KDIGO 2024 Clinical Practice Guideline for the Evaluation and Management of Chronic Kidney Disease. Kidney Int, 2024.](https://doi.org/10.1016/j.kint.2023.10.018)

- [Original Schwartz2009;JASN20:629–637;DOI10.1681/ASN.2008030287](https://www.infectedbloodinquiry.org.uk/sites/default/files/Batch%204/Batch%204/WITN7142008%20-%20New%20equations%20to%20estimate%20GFR%20in%20children%20with%20CKD%20-%2001%20Jan%202009.pdf)

## Reproduce the technical tests

Run node test.cjs in the root directory of this repository to repeat the recorded synthetic cases. Original inputs, expectations and tolerances are preserved. Technical tests do not constitute clinical validation.

```sh
node test.cjs
```

tool.json contains sources, edition and review scope. examples.json retains synthetic inputs and expectations; results.json records the obtained results.

[Record and references](../tool.json) · [JavaScript code](../calculator.js) · [Reference cases](../examples.json) · [results.json](../results.json)

## Review and conditions of use

Independent clinical review has not been performed.

This interface is an authorial translation, not an official or certified edition. Independent clinical review, professional language review and instrument rights clearance have not been performed.

Formula or classification result. Interpretation, care and applicability depend on professional assessment and the selected source.

## License and attribution

Apache-2.0 applies only to ELUCENIA code. Rights to instruments, publications, translations and data remain with their respective holders. Preserve LICENSE and NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
