<!-- ELUCENIA technical documentation · tfg-de-schwartz · pt-BR · no clinical/professional/rights approval -->

# TFG pediátrica (Schwartz à beira do leito)

[condições, fontes e permissões](https://elucenia.org/pt-br/ferramentas/tfg-de-schwartz)

## Como usar

Use a ferramenta no portal ou abra index.html em um servidor HTTP local. Selecione o idioma, preencha os campos e calcule.

## Entradas e unidades

### Altura

`altura`

cm · intervalo: 40–200

### Creatinina sérica (enzimática)

`cr`

mg/dL · intervalo: 0,1–15

## Edição do método

CKi DBedside Schwartz 2009:0,413×altura/Cr IDMS; m L/min/1,73 m²; sem CKi DU 25

## Fórmula documentada

TFGe (mL/min/1,73 m²) = 0,413 × altura (cm) ÷ creatinina (mg/dL)

Equação "à beira do leito" (bedside) de Schwartz 2009, derivada no estudo CKiD com creatinina calibrada por método enzimático (rastreável ao IDMS).

## Limites e população

Esta é a equação bedside Schwartz de 2009, derivada de 349 participantes com doença renal crônica no estudo CKiD, cuja elegibilidade de recrutamento foi de 1–16 anos. A creatinina deve ser enzimática e rastreável ao IDMS. O estudo original ressalvou a necessidade de validação adicional em crianças com função renal mais alta antes de usar a fórmula para rastrear todas as crianças. O resultado é uma estimativa indexada a 1,73 m², não TFG medida, diagnóstico isolado ou dose de medicamento; não representa CKiD U25.

## Referências

- [Schwartz GJ et al. New equations to estimate GFR in children with CKD. J Am Soc Nephrol, 2009.](https://doi.org/10.1681/ASN.2008030287)

- [Kidney Disease: Improving Global Outcomes (KDIGO) CKD Work Group. KDIGO 2024 Clinical Practice Guideline for the Evaluation and Management of Chronic Kidney Disease. Kidney Int, 2024.](https://doi.org/10.1016/j.kint.2023.10.018)

- [Original Schwartz2009;JASN20:629–637;DOI10.1681/ASN.2008030287](https://www.infectedbloodinquiry.org.uk/sites/default/files/Batch%204/Batch%204/WITN7142008%20-%20New%20equations%20to%20estimate%20GFR%20in%20children%20with%20CKD%20-%2001%20Jan%202009.pdf)

## Reproduzir os testes técnicos

Execute node test.cjs na pasta raiz deste repositório para repetir os casos sintéticos registrados. As entradas, expectativas e tolerâncias originais são preservadas. Testes técnicos não constituem validação clínica.

```sh
node test.cjs
```

tool.json contém fontes, edição e escopo de revisão. examples.json conserva as entradas e expectativas sintéticas; results.json registra os resultados obtidos.

[Ficha e referências](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referência](../examples.json) · [results.json](../results.json)

## Revisão e condições de uso

Revisão clínica independente não realizada.

Esta interface é uma tradução autoral, não uma edição oficial ou certificada. Revisão clínica independente, revisão linguística profissional e autorização de direitos de instrumentos não foram realizadas.

Resultado da fórmula ou classificação. Interpretação, conduta e aplicabilidade dependem da avaliação profissional e da fonte selecionada.

## Licença e atribuição

Apache-2.0 aplica-se somente ao código da ELUCENIA. Os instrumentos, publicações, traduções e dados mantêm os direitos dos respectivos titulares. Preserve LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Resultados documentados

As informações abaixo preservam as saídas do método para exemplos sintéticos. Não constituem validação clínica independente.

### 1

Categoria G1: TFG normal ou alta

A classificação em categorias G1 a G5 vale a partir dos 2 anos; antes disso, compare com os valores normais para a idade.


### 2

Categoria G3b: TFG moderada a gravemente diminuída

A classificação em categorias G1 a G5 vale a partir dos 2 anos; antes disso, compare com os valores normais para a idade.


### 3

Categoria G4: TFG gravemente diminuída

A classificação em categorias G1 a G5 vale a partir dos 2 anos; antes disso, compare com os valores normais para a idade.


### 4

Categoria G2: TFG levemente diminuída

A classificação em categorias G1 a G5 vale a partir dos 2 anos; antes disso, compare com os valores normais para a idade.

