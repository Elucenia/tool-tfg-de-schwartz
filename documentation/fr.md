<!-- ELUCENIA technical documentation · tfg-de-schwartz · fr · no clinical/professional/rights approval -->

# DFG pédiatrique (Schwartz au lit du patient)

[conditions, sources et autorisations](https://elucenia.org/fr/outils/tfg-de-schwartz)

## Mode d’emploi

Utilisez l’outil sur le portail ou ouvrez index.html via un serveur HTTP local. Sélectionnez la langue, remplissez les champs et lancez le calcul.

## Données d’entrée et unités

### Taille

`altura`

cm · intervalle: 40–200

### Créatinine sérique (méthode enzymatique)

`cr`

mg/dL · intervalle: 0,1–15

## Édition de la méthode

CKiD bedside Schwartz 2009:0,413×taille/Cr IDMS; mL/min/1,73m²; pas CKiD U25

## Formule documentée

DFGe (mL/min/1,73 m²) = 0,413 × taille (cm) ÷ créatinine (mg/dL)

Équation au lit du patient Schwartz 2009 (bedside) dérivée CKiD, créatinine enzymatique traçable IDMS.

## Limites et population

Il s’agit de l’équation bedside Schwartz de 2009, élaborée à partir de 349 participants atteints de maladie rénale chronique dans l’étude CKiD, dont l’âge admissible au recrutement était de 1–16 ans. La créatinine doit être mesurée par méthode enzymatique et traçable à l’IDMS. L’étude originale soulignait la nécessité d’une validation supplémentaire chez les enfants ayant une fonction rénale plus élevée avant d’utiliser la formule pour le dépistage chez tous les enfants. Le résultat est une estimation indexée à 1,73 m², et non un DFG mesuré, un diagnostic isolé ou une dose de médicament ; il ne représente pas CKiD U25.

## Références

- [Schwartz GJ et al. New equations to estimate GFR in children with CKD. J Am Soc Nephrol, 2009.](https://doi.org/10.1681/ASN.2008030287)

- [Kidney Disease: Improving Global Outcomes (KDIGO) CKD Work Group. KDIGO 2024 Clinical Practice Guideline for the Evaluation and Management of Chronic Kidney Disease. Kidney Int, 2024.](https://doi.org/10.1016/j.kint.2023.10.018)

- [Original Schwartz2009;JASN20:629–637;DOI10.1681/ASN.2008030287](https://www.infectedbloodinquiry.org.uk/sites/default/files/Batch%204/Batch%204/WITN7142008%20-%20New%20equations%20to%20estimate%20GFR%20in%20children%20with%20CKD%20-%2001%20Jan%202009.pdf)

## Reproduire les tests techniques

Exécutez node test.cjs dans le répertoire racine de ce dépôt pour reproduire les cas synthétiques enregistrés. Les données d’entrée, les résultats attendus et les tolérances d’origine sont conservés. Les tests techniques ne constituent pas une validation clinique.

```sh
node test.cjs
```

tool.json contient les sources, l’édition et le périmètre de la revue. examples.json conserve les données d’entrée et les résultats attendus des cas synthétiques ; results.json consigne les résultats obtenus.

[Fiche et références](../tool.json) · [Code JavaScript](../calculator.js) · [Cas de référence](../examples.json) · [results.json](../results.json)

## Revue et conditions d’utilisation

Aucune révision clinique indépendante n’a été effectuée.

Cette interface est une traduction réalisée par nos soins, et non une édition officielle ou certifiée. La revue clinique indépendante, la révision linguistique professionnelle et l’autorisation des droits sur les instruments n’ont pas été réalisées.

Résultat de la formule ou de la classification. L’interprétation, la conduite et l’applicabilité dépendent de l’évaluation professionnelle et de la source sélectionnée.

## Licence et attribution

Apache-2.0 s’applique uniquement au code d’ELUCENIA. Les droits sur les instruments, publications, traductions et données restent ceux de leurs titulaires respectifs. Conservez LICENSE et NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Résultats documentés

Les informations ci-dessous conservent les sorties de la méthode pour des exemples synthétiques. Elles ne constituent pas une validation clinique indépendante.

### 1

Catégorie G1 : DFG normal ou élevé

La classification en catégories G1 à G5 s’applique à partir de 2 ans ; avant cela, comparer avec les valeurs normales pour l’âge.


### 2

Catégorie G3b : DFG modérément à sévèrement diminué

La classification en catégories G1 à G5 s’applique à partir de 2 ans ; avant cela, comparer avec les valeurs normales pour l’âge.


### 3

Catégorie G4 : DFG sévèrement diminué

La classification en catégories G1 à G5 s’applique à partir de 2 ans ; avant cela, comparer avec les valeurs normales pour l’âge.


### 4

Catégorie G2 : DFG légèrement diminué

La classification en catégories G1 à G5 s’applique à partir de 2 ans ; avant cela, comparer avec les valeurs normales pour l’âge.

