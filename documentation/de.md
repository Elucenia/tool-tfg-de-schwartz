<!-- ELUCENIA technical documentation · tfg-de-schwartz · de · no clinical/professional/rights approval -->

# Pädiatrische GFR (Bedside-Schwartz)

[Bedingungen, Quellen und Berechtigungen](https://elucenia.org/de/werkzeuge/tfg-de-schwartz)

## Verwendung

Verwenden Sie das Werkzeug im Portal oder öffnen Sie index.html über einen lokalen HTTP-Server. Wählen Sie die Sprache, füllen Sie die Felder aus und berechnen Sie das Ergebnis.

## Eingaben und Einheiten

### Körpergröße

`altura`

cm · Bereich: 40–200

### Serumkreatinin (enzymatische Bestimmung)

`cr`

mg/dL · Bereich: 0,1–15

## Fassung der Methode

CKiD Bedside Schwartz 2009:0,413×Größe/IDMS-Cr; mL/min/1,73m²; kein CKiD U25

## Dokumentierte Formel

eGFR (mL/min/1,73 m²) = 0,413 × Größe (cm) ÷ Kreatinin (mg/dL)

Schwartz 2009-Bedside-Gleichung (bedside) aus CKiD mit enzymatisch kalibriertem, IDMS-rückführbarem Kreatinin.

## Grenzen und Population

Dies ist die bedside-Schwartz-Gleichung von 2009, abgeleitet aus 349 Teilnehmenden mit chronischer Nierenkrankheit in der CKiD-Studie, deren Rekrutierung ein Alter von 1–16 Jahren voraussetzte. Kreatinin muss enzymatisch bestimmt und auf IDMS rückführbar sein. Die Originalstudie wies auf die Notwendigkeit zusätzlicher Validierung bei Kindern mit höherer Nierenfunktion hin, bevor die Formel zum Screening aller Kinder eingesetzt wird. Das Ergebnis ist eine auf 1,73 m² indexierte Schätzung, keine gemessene GFR, isolierte Diagnose oder Arzneimitteldosis; es stellt nicht CKiD U25 dar.

## Referenzen

- [Schwartz GJ et al. New equations to estimate GFR in children with CKD. J Am Soc Nephrol, 2009.](https://doi.org/10.1681/ASN.2008030287)

- [Kidney Disease: Improving Global Outcomes (KDIGO) CKD Work Group. KDIGO 2024 Clinical Practice Guideline for the Evaluation and Management of Chronic Kidney Disease. Kidney Int, 2024.](https://doi.org/10.1016/j.kint.2023.10.018)

- [Original Schwartz2009;JASN20:629–637;DOI10.1681/ASN.2008030287](https://www.infectedbloodinquiry.org.uk/sites/default/files/Batch%204/Batch%204/WITN7142008%20-%20New%20equations%20to%20estimate%20GFR%20in%20children%20with%20CKD%20-%2001%20Jan%202009.pdf)

## Technische Tests reproduzieren

Führen Sie node test.cjs im Stammverzeichnis dieses Repositorys aus, um die dokumentierten synthetischen Fälle zu wiederholen. Ursprüngliche Eingaben, erwartete Ergebnisse und Toleranzen bleiben erhalten. Technische Tests stellen keine klinische Validierung dar.

```sh
node test.cjs
```

tool.json enthält Quellen, Ausgabe und Umfang der Überprüfung. examples.json bewahrt die synthetischen Eingaben und erwarteten Ergebnisse; results.json dokumentiert die tatsächlich erhaltenen Ergebnisse.

[Eintrag und Referenzen](../tool.json) · [JavaScript-Code](../calculator.js) · [Referenzfälle](../examples.json) · [results.json](../results.json)

## Überprüfung und Nutzungsbedingungen

Eine unabhängige klinische Prüfung wurde nicht durchgeführt.

Diese Benutzeroberfläche ist eine selbst erstellte Übersetzung und keine offizielle oder zertifizierte Ausgabe. Eine unabhängige klinische Überprüfung, eine professionelle sprachliche Prüfung und eine Klärung der Rechte an den Instrumenten wurden nicht durchgeführt.

Ergebnis der Formel oder Klassifikation. Interpretation, Vorgehen und Anwendbarkeit hängen von der fachlichen Beurteilung und der ausgewählten Quelle ab.

## Lizenz und Urheberangaben

Apache-2.0 gilt nur für den ELUCENIA-Code. Die Rechte an Instrumenten, Veröffentlichungen, Übersetzungen und Daten verbleiben bei den jeweiligen Rechteinhabern. Bewahren Sie LICENSE und NOTICE auf.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Dokumentierte Ergebnisse

Die folgenden Angaben bewahren die Ausgaben der Methode für synthetische Beispiele. Sie stellen keine unabhängige klinische Validierung dar.

### 1

Kategorie G1: normale oder hohe GFR

Die Einteilung in die Kategorien G1 bis G5 gilt ab dem 2. Lebensjahr; davor mit den altersentsprechenden Normwerten vergleichen.


### 2

Kategorie G3b: mäßig bis stark verminderte GFR

Die Einteilung in die Kategorien G1 bis G5 gilt ab dem 2. Lebensjahr; davor mit den altersentsprechenden Normwerten vergleichen.


### 3

Kategorie G4: stark verminderte GFR

Die Einteilung in die Kategorien G1 bis G5 gilt ab dem 2. Lebensjahr; davor mit den altersentsprechenden Normwerten vergleichen.


### 4

Kategorie G2: leicht verminderte GFR

Die Einteilung in die Kategorien G1 bis G5 gilt ab dem 2. Lebensjahr; davor mit den altersentsprechenden Normwerten vergleichen.

