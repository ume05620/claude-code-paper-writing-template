# HLA class I スコアリング基準: 出典調査記録

**この資料の目的**: 自験(および引用元のTakehara 2023)が用いているHLA class Iの5段階スコアリング基準(0%, 1–9%, 10–49%, 50–79%, >80%)について、その妥当性の論拠となる一次文献を特定するために行った調査の記録。結論として、完全に一致する単一の「元祖」文献は見つからなかった。

---

## 1. 自験(Takehara 2023踏襲)が使用している基準

`interim_report/膵癌_20250214_..._Claude.pptx`スライド11(英文Methods)より:

> The expression of HLA class Ⅰ-ABC was scored based on the percentage of positively stained tumor cells using the following scoring system: **0, 0%; 1, 1%–9%; 2, 10%–49%; 3, 50%–79%; and 4, >80% [10]。**

この文言はTakehara et al. 2023(PMID 37772585, Anticancer Research)の記載と一言一句同一。

---

## 2. Takehara論文自身の引用[10]を検証 → 破綻していることが判明

Takehara 2023の参考文献リストで[10]を確認したところ:

> 10. **Hodi FS, O'Day SJ, McDermott DF, Weber RW, Sosman JA, ... : Improved survival with ipilimumab in patients with metastatic melanoma.** N Engl J Med 363(8): 711-723, 2010.

これは**悪性黒色腫におけるイピリムマブの生存率改善試験**であり、HLA class Iの染色スコアリングとは一切無関係。**Takehara論文側の誤引用(あるいは編集過程での参照番号のズレ)がそのまま自験の草案に継承されている**と考えられる。この基準の真の出典はTakehara論文からは辿れない。

---

## 3. 候補文献の調査結果

真の出典を探すため、関連するHLA class I IHCスコアリング論文を複数確認したが、いずれも完全には一致しなかった。

| 文献 | スコア区分 | 一致度 |
|---|---|---|
| **自験/Takehara 2023** | 0%, 1–9%, 10–49%, 50–79%, >80% | (基準) |
| Hiraoka et al. 2020(PMID 32495519, 精読済み)膵癌 | +++(≥90%)/++(50–90%)/+(10–50%かつ弱陽性)/−(≤10%) の4段階定性表現。Methods 2.5節に独自定義として記載、出典引用なし | ❌ カットオフ不一致(90% vs 80%等)、段階数も異なる(4段階 vs 5段階) |
| de Kruijf et al. 2010(Clin Cancer Res, 乳癌×Treg研究)Hiraoka論文が引用 | International HLA and Immunogenetics Workshop基準: 0–5%, 5–25%, 25–50%, 50–75%, 75–100% | ❌ 区分の考え方(5%刻み起点)が異なる |
| Sinn et al. 2019(Breast Cancer Research, doi: 10.1186/s13058-019-1231-z、精読済み)乳癌 | 0%, 1–9%, 10–50%, 51–80%, 81–100%(割合)× 染色強度4段階(0–3) = IRS 0–12点 | △ 割合の区切りは近似するが、**染色強度を掛け合わせたIRS(0–12点)が最終指標であり、割合カテゴリのみを最終スコアとする自験とは評価法の構造自体が異なる**。区切り値自体も出典引用なしの自己流。**→ ユーザー判断により本研究では引用しないことを決定(2026-08-12)** |

---

## 4. 結論

- 「0%, 1–9%, 10–49%, 50–79%, >80%」という自験の基準と完全一致する、単一の権威ある一次文献は特定できなかった。
- HLA class IのIHCスコアリングは、Hiraoka・de Kruijf・Sinnなど各グループがそれぞれ微妙に異なるカットオフを無出典(または誤出典)で定義しており、分野内で単一の標準が確立されているわけではない可能性が高い。
- Takehara 2023の[10]=Hodi 2010は明白な誤引用であり、この孫引きは行うべきではない。

## 5. 推奨する論文への記載方針

- 外部文献に無理に紐付けず、Methods記載は「本研究グループの先行研究(Takehara et al. 2023)に準拠した評価基準を用いた」に留める。
- Takehara論文の[10](Hodi 2010)への孫引きは行わない。
- Sinn et al. 2019は、乳癌におけるHLA class I高発現と予後不良(DFS短縮)の関連を報告しており、Hiraoka 2020(膵癌でHLA-I高発現が予後不良)と方向性が一致するため、Discussionでの補強文献としては将来的に検討の余地がある(スコアリング基準の論拠としては不採用)。現時点では`references/refs.yaml`には未登録。
