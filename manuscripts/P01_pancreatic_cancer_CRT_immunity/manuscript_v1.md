# {Oncopathological Study on Radiation-Induced Anti-Tumor Immunity in Pancreatic Cancer 
Treated with Neoadjuvant Chemoradiotherapy}

**Author(s)**: {Kazuma Umemiya }
**Institution**: {Fukushima Medical University}
**Corresponding author**: {責任著者・連絡先}

---

## Abstract

<!-- 構成メモ(Takehara et al. 2023 abstractの構成: Background/Aim → Patients and Methods → Results → Conclusion に準拠。以下は執筆前のメモ書きであり、まだ文章化していない。 -->

**Background**: {メモ: ICIを含む集学的治療への理解を深める必要性を述べる}

**Methods**: {メモ: 後方視的研究 / 症例数(NACRT群24例・対照群62例) / 福島県立医科大学附属病院 / 群分け(NACRT群 vs 手術単独群) / 化学療法の内容(GEM単剤)と放射線の線量分割(50.4 Gy/28 fr) / IHCで評価した分子(CD8, HLA class I, PD-L1)}

**Results**: {略 — 後で記入}

**Conclusions**: {略 — 後で記入}

**Keywords**: {キーワード 5〜8 語}

---

## Introduction

<!-- 構成メモ(執筆前のアウトライン。まだ文章化していない) -->

{メモ:
1. 膵癌の有病率・死亡率
2. 一般的な組織型
3. ステージごとの標準治療(手術・化学療法・放射線療法の位置づけ)
4. ICIの成功例(他癌腫での例は略) → PDACでのICIの成績 → 過去の試験結果 → 標準治療への導入状況
5. 現在最良のICI併用療法でも、その治療成績はこの程度
6. よって治療戦略のさらなる発展が必要。PD-1を標的としたアプローチを改善できるかは、免疫学的な明確な理解が必要
7. 本研究の位置づけ(略 — 後で記入)
}

---

## Methods

### Study design and participants

This retrospective cohort study was conducted at Fukushima Medical University Hospital. We identified patients aged 20 to 79 years who underwent radical surgical resection for pathologically confirmed pancreatic ductal adenocarcinoma between May 2010 and August 2019. Patients who received neoadjuvant chemoradiotherapy (NACRT) with concurrent gemcitabine before radical resection were compared with patients who underwent radical resection alone, without any preoperative chemotherapy or radiotherapy, during the same period. Paraffin-embedded tumor tissue from the resected specimen was required for inclusion; pretreatment biopsy tissue was not required. Patients without available paraffin-embedded sections, those with rare histological subtypes, and those in whom the resected specimen was judged non-neoplastic on pathological review were excluded. After applying these criteria, 24 patients who received NACRT and 62 patients who did not were included in the analysis. This study was approved by the Institutional Review Board of Fukushima Medical University (approval no. {IRB番号未確認}) and was conducted in accordance with the ethical principles of the Declaration of Helsinki.

### Intervention or exposure

Patients in the NACRT group received chemoradiotherapy with single-agent gemcitabine, following the neoadjuvant chemoradiotherapy regimen recommended at the time of treatment. Radiotherapy was delivered concurrently in conventional fractionation to a total dose of 50.4 Gy in 28 fractions, encompassing the primary tumor with a margin and the regional lymph node area. Patients in the comparator group underwent radical resection without any preceding chemotherapy or radiotherapy.

### Outcomes and definitions

#### Immunohistochemical staining

Formalin-fixed, paraffin-embedded surgical specimens were cut into 4-μm-thick sections and deparaffinized according to routine procedures. Antigen retrieval conditions were optimized separately for each marker. For CD8, sections were heated in Target Retrieval Solution (pH 9.0; Agilent Technologies, Santa Clara, CA, USA) at 100°C for 20 min. For HLA class I, sections were autoclaved in citrate buffer (pH 6.0) at 121°C for 10 min and allowed to cool at room temperature for 1 h. For PD-L1, sections were autoclaved in Target Retrieval Solution (pH 9.0; Agilent Technologies) at 120°C for 10 min. After retrieval, sections were rinsed in deionized water and washed in phosphate-buffered saline (PBS). Endogenous peroxidase activity was blocked with 3% hydrogen peroxide for 15 min.

Sections were then incubated overnight at 4°C for 16 h with the following primary antibodies: anti-CD8 (1:600; clone C8/144B; Agilent Technologies), anti-HLA class I-ABC (1:400; clone EMR8-5; Hokudo, Sapporo, Japan), and anti-PD-L1 (1:400; clone E1L3N; Cell Signaling Technology, Danvers, MA, USA). For CD8 and HLA class I, an avidin-biotin-complex-labeled anti-mouse secondary antibody (VECTASTAIN ABC-HRP Kit; Vector Laboratories) was applied for 30 min at room temperature. For PD-L1, a horseradish-peroxidase-conjugated anti-rabbit polymer (Envision+ System-HRP; Agilent Technologies) was applied for 30 min at room temperature. Immunoreactivity was visualized with 3,3′-diaminobenzidine. For PD-L1, sections were counterstained with Mayer's hematoxylin for 1 min at room temperature; sections stained for CD8 and HLA class I were not counterstained, and adjacent serial sections were stained with hematoxylin and eosin (H&E) for histological reference.

#### Evaluation of immunohistochemical staining

For assessment of CD8+ tumor-infiltrating lymphocytes, hotspot areas of tumor-infiltrating lymphocytes were selected in four independent fields within the intratumoral region and the invasive front of each surgically resected specimen at ×200 magnification, and the mean number of CD8+ cells across the four fields was calculated using Patholoscope version 1.8.0 (MITANI Co., Fukui, Japan).

Expression of HLA class I was scored according to the percentage of tumor cells showing positive membranous staining, using the same five-tier scoring system applied in our institution's previous work on the tumor immune microenvironment {Takehara_37772585}: 0, <1%; 1, 1–9%; 2, 10–49%; 3, 50–79%; and 4, ≥80%.

<!-- [方針決定 2026-09-14] Takehara 2023の原文表記(0, 0%; ... 4, >80%)は整数前提で、0〜1%の間とちょうど80%が定義から漏れる。本研究は視野平均(小数)をスコア化しており、平均ちょうど80%の症例が1例実在するため、解析コード(v20250211以降: x<1→0, <10→1, <50→2, <80→3, <100→4)に合わせて「<1%」「≥80%」と表記する。区分自体はTakeharaと同一。 -->

Tumor cells were considered positive for PD-L1 when dark brown membranous staining was observed in ≥1% of tumor cells; samples not meeting this threshold were considered negative.

CD8 and HLA class I staining were each assessed independently by two observers (K.U. and T.S.) <!-- FLAG-INITIALS: イニシャルは仮(K.U.=梅宮和真氏本人、T.S.=今回の評価者)。正式な氏名・イニシャル表記をご確認ください -->, and discrepant results were resolved by joint reassessment and consensus.

### Statistical analysis

Continuous and ordinal variables, including the number of CD8+ cells and the HLA class I expression score, were compared between the NACRT and comparator groups using the Mann-Whitney U test; results are reported as medians with 95% confidence intervals estimated by bootstrap resampling (10,000 iterations). Categorical variables, including patient background characteristics, PD-L1 positivity, and the dichotomized HLA class I expression (score 0–2 versus 3–4), were compared using Fisher's exact test. A two-sided p-value of <0.05 was considered statistically significant. Statistical analyses were performed using Python version 3.9.21 with the pandas (version 2.2.3), SciPy (version 1.13.1), and NumPy (version 1.26.4) libraries.

<!-- [確認済み 2026-09-04] バージョンの根拠: (1) 解析ノートブックのメタデータ language_info.version = 3.9.21、kernelspec.display_name = "analysis"、(2) conda環境 C:\Users\pureb\anaconda3\envs\analysis が現存し、conda-metaのパッケージは2024-12-27のインストール以降更新されていない、(3) 2025年2月前後の全ノートブック(膵癌解析v20250204/v20250211、集計v20250208/v20250215、ForestPlot各版)がすべてPython 3.9.21で一致。なお現在のbase環境(Python 3.12.7 / NumPy 2.5.1 / SciPy 1.18.0)は解析環境とは別物なので混同しないこと。 -->

<!-- [方針決定 2026-09-04] 生存解析(Kaplan-Meier法・log-rank検定など)は本論文のスコープに含めない。研究計画書には予後(生存期間・無再発生存期間・局所制御期間)も観察項目として含まれているが、本論文はCD8・HLA class I・PD-L1の群間比較に絞って報告する。Limitationsで「予後との関連は本研究では検討していない」旨に触れるかは別途判断。 -->

---

## Results

### Participant characteristics

{対象者背景}

### Primary outcomes

{主要アウトカム}

### Secondary outcomes

{副次アウトカム}

---

## Discussion

{考察}

---

## Conclusions

{結論}

---

## References

<!-- refs.yaml のタグを使って引用を管理する -->
<!-- 例: [1] Smith_keyword_12345678 -->
