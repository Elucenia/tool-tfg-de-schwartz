<!-- ELUCENIA technical documentation · tfg-de-schwartz · es · no clinical/professional/rights approval -->

# TFG pediátrica (Schwartz a pie de cama)

[condiciones, fuentes y permisos](https://elucenia.org/es/herramientas/tfg-de-schwartz)

## Cómo usar

Utilice la herramienta en el portal o abra index.html mediante un servidor HTTP local. Seleccione el idioma, complete los campos y calcule.

## Entradas y unidades

### Estatura

`altura`

cm · intervalo: 40–200

### Creatinina sérica (método enzimático)

`cr`

mg/dL · intervalo: 0,1–15

## Edición del método

CKiD bedside Schwartz 2009:0,413×altura/Cr IDMS; mL/min/1,73m²; no CKiD U25

## Fórmula documentada

TFGe (mL/min/1,73 m²) = 0,413 × altura (cm) ÷ creatinina (mg/dL)

Ecuación a pie de cama Schwartz 2009 (bedside) derivada CKiD con creatinina enzimática trazable a IDMS.

## Límites y población

Esta es la ecuación bedside Schwartz de 2009, derivada de 349 participantes con enfermedad renal crónica del estudio CKiD, cuya edad elegible para el reclutamiento fue de 1–16 años. La creatinina debe medirse mediante un método enzimático y ser trazable a IDMS. El estudio original señaló la necesidad de validación adicional en niños con función renal más alta antes de usar la fórmula para cribar a todos los niños. El resultado es una estimación indexada a 1,73 m², no TFG medida, diagnóstico aislado ni dosis de medicamento; no representa CKiD U25.

## Referencias

- [Schwartz GJ et al. New equations to estimate GFR in children with CKD. J Am Soc Nephrol, 2009.](https://doi.org/10.1681/ASN.2008030287)

- [Kidney Disease: Improving Global Outcomes (KDIGO) CKD Work Group. KDIGO 2024 Clinical Practice Guideline for the Evaluation and Management of Chronic Kidney Disease. Kidney Int, 2024.](https://doi.org/10.1016/j.kint.2023.10.018)

- [Original Schwartz2009;JASN20:629–637;DOI10.1681/ASN.2008030287](https://www.infectedbloodinquiry.org.uk/sites/default/files/Batch%204/Batch%204/WITN7142008%20-%20New%20equations%20to%20estimate%20GFR%20in%20children%20with%20CKD%20-%2001%20Jan%202009.pdf)

## Reproducir las pruebas técnicas

Ejecute node test.cjs en el directorio raíz de este repositorio para repetir los casos sintéticos registrados. Se conservan las entradas, los resultados esperados y las tolerancias originales. Las pruebas técnicas no constituyen validación clínica.

```sh
node test.cjs
```

tool.json contiene las fuentes, la edición y el alcance de la revisión. examples.json conserva las entradas y los resultados esperados de los casos sintéticos; results.json registra los resultados obtenidos.

[Ficha y referencias](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referencia](../examples.json) · [results.json](../results.json)

## Revisión y condiciones de uso

No se ha realizado una revisión clínica independiente.

Esta interfaz es una traducción de elaboración propia, no una edición oficial o certificada. No se han realizado la revisión clínica independiente, la revisión lingüística profesional ni la autorización de derechos de los instrumentos.

Resultado de la fórmula o clasificación. La interpretación, la conducta y la aplicabilidad dependen de la evaluación profesional y de la fuente seleccionada.

## Licencia y atribución

Apache-2.0 se aplica únicamente al código de ELUCENIA. Los derechos de los instrumentos, publicaciones, traducciones y datos permanecen en manos de sus respectivos titulares. Conserve LICENSE y NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
