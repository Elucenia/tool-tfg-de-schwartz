<!-- ELUCENIA technical documentation · tfg-de-schwartz · ja · no clinical/professional/rights approval -->

# 小児の糸球体濾過量（bedside Schwartz）

[条件・出典・許諾](https://elucenia.org/ja/tools/tfg-de-schwartz)

## 使い方

ポータルでツールを使用するか、ローカルHTTPサーバー経由でindex.htmlを開いてください。言語を選択し、項目を入力して計算してください。

## 入力項目と単位

### 身長

`altura`

cm · 範囲: 40–200

### 血清クレアチニン（酵素法）

`cr`

mg/dL · 範囲: 0.1–15

## 方法の版

CKiD bedside Schwartz 2009：0.413×身長/IDMS Cr、mL/min/1.73m²、CKiD U25とは別

## 記載された計算式

eGFR (mL/min/1.73 m²) = 0.413 × 身長 (cm) ÷ クレアチニン (mg/dL)

Schwartz 2009ベッドサイド式 (bedside) CKiD由来、酵素法で校正したIDMSトレーサブルなクレアチニン。

## 限界・対象集団

これは2009年のbedside Schwartz式です。CKiD研究の慢性腎臓病を有する参加者349人から導出され、募集時の年齢適格条件は1–16歳でした。クレアチニンは酵素法で測定し、IDMSにトレーサブルである必要があります。原研究では、すべての小児のスクリーニングにこの式を使用する前に、腎機能がより高い小児で追加の妥当性検証が必要であるとしています。結果は1.73 m²に補正した推算値であり、実測糸球体濾過量、単独での診断、薬剤の投与量ではありません。CKiD U25を表すものでもありません。

## 参考文献

- [Schwartz GJ et al. New equations to estimate GFR in children with CKD. J Am Soc Nephrol, 2009.](https://doi.org/10.1681/ASN.2008030287)

- [Kidney Disease: Improving Global Outcomes (KDIGO) CKD Work Group. KDIGO 2024 Clinical Practice Guideline for the Evaluation and Management of Chronic Kidney Disease. Kidney Int, 2024.](https://doi.org/10.1016/j.kint.2023.10.018)

- [Original Schwartz2009;JASN20:629–637;DOI10.1681/ASN.2008030287](https://www.infectedbloodinquiry.org.uk/sites/default/files/Batch%204/Batch%204/WITN7142008%20-%20New%20equations%20to%20estimate%20GFR%20in%20children%20with%20CKD%20-%2001%20Jan%202009.pdf)

## 技術テストの再現

このリポジトリのルートディレクトリでnode test.cjsを実行すると、記録された合成ケースを再実行できます。元の入力、期待結果、許容誤差は保持されています。技術テストは臨床的検証を意味しません。

```sh
node test.cjs
```

tool.jsonには出典、版、確認範囲が記録されています。examples.jsonには合成入力と期待結果が保持され、results.jsonには実際に得られた結果が記録されています。

[記録・参考文献](../tool.json) · [JavaScriptコード](../calculator.js) · [参照ケース](../examples.json) · [results.json](../results.json)

## 確認状況と使用条件

独立した臨床レビューは実施されていません。

このインターフェースは独自に作成した翻訳であり、公式版や認証済みの版ではありません。独立した臨床レビュー、専門家による言語レビュー、評価尺度等の権利許諾の確認は実施されていません。

式または分類の結果です。解釈、対応、適用可能性は専門家による評価と選択した出典に依存します。

## ライセンスと帰属表示

Apache-2.0はELUCENIAのコードにのみ適用されます。評価尺度等、出版物、翻訳、データの権利は、それぞれの権利者に帰属します。LICENSEとNOTICEを保持してください。

ELUCENIA · Felipe Guedes · Copyright © 2026
