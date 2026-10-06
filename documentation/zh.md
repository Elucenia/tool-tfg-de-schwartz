<!-- ELUCENIA technical documentation · tfg-de-schwartz · zh · no clinical/professional/rights approval -->

# 儿童肾小球滤过率（简化 Schwartz 公式）

[条件、来源与许可](https://elucenia.org/zh/tools/tfg-de-schwartz)

## 使用方法

在门户中使用工具，或通过本地 HTTP 服务器打开 index.html。选择语言，填写各字段，然后计算。

## 输入与单位

### 身高

`altura`

cm · 范围: 40–200

### 血清肌酐（酶法）

`cr`

mg/dL · 范围: 0.1–15

## 方法版本

CKiD床旁Schwartz 2009：0.413×身高/IDMS肌酐；mL/min/1.73m²；非CKiD U25

## 已记录的公式

eGFR (mL/min/1.73 m²) = 0.413 × 身高 (cm) ÷ 肌酐 (mg/dL)

Schwartz 2009床旁式 (bedside) 源自CKiD，酶法肌酐校准可溯源IDMS。

## 限制与适用人群

这是2009年的bedside Schwartz方程，源自CKiD研究中349名慢性肾脏病参与者；该研究的招募年龄资格为1–16岁。肌酐应采用可溯源至IDMS的酶法测定。原始研究强调，在将此方程用于筛查所有儿童之前，须在肾功能较高的儿童中进行进一步验证。结果是按1.73 m²体表面积标准化的估算值，不是实测肾小球滤过率、独立诊断或药物剂量；它不代表CKiD U25。

## 参考文献

- [Schwartz GJ et al. New equations to estimate GFR in children with CKD. J Am Soc Nephrol, 2009.](https://doi.org/10.1681/ASN.2008030287)

- [Kidney Disease: Improving Global Outcomes (KDIGO) CKD Work Group. KDIGO 2024 Clinical Practice Guideline for the Evaluation and Management of Chronic Kidney Disease. Kidney Int, 2024.](https://doi.org/10.1016/j.kint.2023.10.018)

- [Original Schwartz2009;JASN20:629–637;DOI10.1681/ASN.2008030287](https://www.infectedbloodinquiry.org.uk/sites/default/files/Batch%204/Batch%204/WITN7142008%20-%20New%20equations%20to%20estimate%20GFR%20in%20children%20with%20CKD%20-%2001%20Jan%202009.pdf)

## 复现技术测试

在此仓库的根目录中运行 node test.cjs，以重复已记录的合成案例。原始输入、预期结果和容差保持不变。技术测试不构成临床验证。

```sh
node test.cjs
```

tool.json 包含来源、版本和审查范围。examples.json 保留合成输入与预期结果；results.json 记录实际得到的结果。

[记录与参考文献](../tool.json) · [JavaScript代码](../calculator.js) · [参考案例](../examples.json) · [results.json](../results.json)

## 审查与使用条件

尚未开展独立临床审查。

此界面为自主编写的翻译，并非官方或认证版本。尚未完成独立临床审查、专业语言审查或工具权利授权。

公式或分类结果。解释、处理及适用性须结合专业评估和所选来源。

## 许可与署名

Apache-2.0 仅适用于 ELUCENIA 代码。工具、出版物、翻译和数据的权利仍归各自权利人所有。请保留 LICENSE 和 NOTICE。

ELUCENIA · Felipe Guedes · Copyright © 2026

## 已记录的结果

以下信息保留该方法对合成示例的输出，不构成独立的临床验证。

### 1

G1类：GFR正常或偏高

G1 至 G5 分级适用于 2 岁及以上；在此之前，应与相应年龄的正常值比较。


### 2

G3b类：GFR中度至重度降低

G1 至 G5 分级适用于 2 岁及以上；在此之前，应与相应年龄的正常值比较。


### 3

G4类：GFR严重降低

G1 至 G5 分级适用于 2 岁及以上；在此之前，应与相应年龄的正常值比较。


### 4

G2类：GFR轻度降低

G1 至 G5 分级适用于 2 岁及以上；在此之前，应与相应年龄的正常值比较。

