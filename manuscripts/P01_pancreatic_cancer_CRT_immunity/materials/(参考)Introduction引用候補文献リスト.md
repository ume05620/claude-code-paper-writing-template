# Introduction 引用候補文献リスト

**この資料の目的**: `manuscript_v1.md`のIntroduction構成メモ(6項目のアウトライン)を裏付けるため、PubMedで検索して選定した引用候補文献をまとめたもの。各文献について書誌情報・入手性・選定理由・対応するアウトライン項目を記録する。

**作成日**: 2026-08-30
**注意**: ここに挙げた文献は、いずれも本資料作成時点で`references/refs.yaml`に**未登録**(Mannucci除く)。実際に引用すると決めた時点で登録する。

---

## 入手方針の切り分け

このプロジェクトのCLAUDE.mdにある「引用データは捏造しない — 数値はすべて実際の論文テキストから取得する」というルールに従い、以下のように切り分けた。

- **全文PDFが必要**: 具体的な数値・試験結果を本文に書くもの → **研究者本人が取得予定(下表の「本人取得」)**
- **抄録で足りる可能性**: 概念・総論として一度触れるだけのもの → ただし多くが無料公開されており取得コストは低い

---

## A. 本人が全文PDF取得予定(6本 — 詳細は別途)

| 文献 | PMID | 対応項目 |
|---|---|---|
| Siegel RL, et al. Cancer statistics, 2025. CA Cancer J Clin. 2025;75(1):10-45. | 39817679 | 項目1 |
| Versteijne E, et al. PREOPANC長期成績. J Clin Oncol. 2022;40(11):1220-1230. | 35084987 | 項目3 |
| Royal RE, et al. Ipilimumab単剤 第2相. J Immunother. 2010;33(8):828-833. | 20842054 | 項目4 |
| O'Reilly EM, et al. Durvalumab±Tremelimumab 第2相. JAMA Oncol. 2019;5(10):1431-1438. | 31318392 | 項目4 |
| Marabelle A, et al. KEYNOTE-158. J Clin Oncol. 2020;38(1):1-10. | 31682550 | 項目4 |
| CheckMate 032(Nivolumab±Ipilimumab±Cobimetinib, 膵癌). | 38316517 | 項目5 |

---

## B. 以下、それ以外の候補文献(詳細)

### 項目1: 有病率・死亡率

#### Bray F, Laversanne M, Sung H, Ferlay J, Siegel RL, Soerjomataram I, et al.
**Global cancer statistics 2022: GLOBOCAN estimates of incidence and mortality worldwide for 36 cancers in 185 countries**
- 雑誌: CA: A Cancer Journal for Clinicians. 2024;74(3):229-263.
- PMID: 38572751 <span style="color:#c0392b;">(検索結果内での明示が弱く、投稿前に要再確認)</span>
- DOI: 10.3322/caac.21834
- URL: https://pubmed.ncbi.nlm.nih.gov/38572751/
- 入手性: CA Cancer J ClinはOpen Access

**選定理由**: 世界規模の癌統計として最も標準的な出典。Siegel(米国統計)と組み合わせて「国際的にも米国でも予後不良」という文脈を作るのが導入部の定型パターン。膵癌の罹患数・死亡数の国際比較が必要な場合に使う。

#### Mannucci A, Goel A.
**Advances in pancreatic cancer early diagnosis, prevention, and treatment: The past, the present, and the future**
- 雑誌: CA: A Cancer Journal for Clinicians. 2026.
- PMID: 40971231
- 登録状況: **`refs.yaml`に登録済み**(tag: Mannucci_40971231, status: candidate)

**選定理由**: 既に収集済みの文献。早期診断・予防・治療を通覧した総説であり、統計(項目1)から標準治療(項目3)への橋渡しに使える。既存登録文献を活用できるという意味で優先度は高い。

---

### 項目2: 一般的な組織型

#### Park W, Chawla A, O'Reilly EM.
**Pancreatic Cancer: A Review**
- 雑誌: JAMA. 2021;326(9):851-862.
- PMID: 34547082 / PMCID: PMC9363152
- DOI: 10.1001/jama.2021.13027
- URL: https://pubmed.ncbi.nlm.nih.gov/34547082/
- 入手性: **PMCで無料公開**
- 正誤表: JAMA. 2021;326(20):2081 に erratum あり(引用時に確認)

**選定理由**: 膵癌の病態・組織型・診断・治療を1本で網羅した高被引用レビュー。診断時病期分布(局所進行30-35%、遠隔転移50-55%)という具体的な数値も含むため、**項目2(組織型)と項目3(ステージごとの治療)の両方を1文献でカバーできる**のが利点。Introductionの冒頭〜中盤を効率よく支えられる。

#### WHO Classification of Tumours: Digestive System Tumours(第5版)
- 種別: **書籍**(`refs.yaml`には登録せず、書誌情報のみで引用)

**選定理由**: 組織型分類の一次情報源として最も権威がある。「膵癌の大半が膵管腺癌(PDAC)である」という記述の根拠として、査読者から出典を求められた場合に最も強い。西川博嘉の教科書と同じく書籍扱いのため、登録簿には載せない運用とする。

---

### 項目3: ステージごとの標準治療(手術・化学療法・放射線治療)

#### Versteijne E, et al.
**Preoperative Chemoradiotherapy Versus Immediate Surgery for Resectable and Borderline Resectable Pancreatic Cancer: Results of the Dutch Randomized Phase III PREOPANC Trial(初回報告)**
- 雑誌: J Clin Oncol. 2020;38(16):1763-1773.
- PMID: <span style="color:#c0392b;">未確認</span> / PMCID: PMC8265386
- DOI: 10.1200/JCO.19.02274
- URL: https://ascopubs.org/doi/10.1200/JCO.19.02274
- 入手性: PMCで公開

**選定理由**: 上記A表の長期成績(PMID 35084987)の**初回報告**にあたる。初回報告では全生存に統計的有意差が出ず、長期追跡で有意になったという経緯があるため、「術前化学放射線療法の位置づけは発展途上である」という論調を作る場合、長期成績と対で引用する価値がある。逆に、単に「NACRTは有効」とだけ書くなら長期成績のみで足りるので、その場合は不要。

---

### 項目5: 現在最良のICI併用でもこの治療成績

#### Balachandran VP, Beatty GL, Dougan SK.
**Broadening the Impact of Immunotherapy to Pancreatic Cancer: Challenges and Opportunities**
- 雑誌: Gastroenterology. 2019;156(7):2056-2072.
- PMID: 30660727 / PMCID: PMC6486864
- DOI: <span style="color:#c0392b;">要確認</span>
- URL: https://pubmed.ncbi.nlm.nih.gov/30660727/
- 入手性: **PMCで無料公開**
- 発見経緯: **Hiraoka論文(PMID 32495519)の孫引きとして既に発見済み**(`(参考)文献の所感・引用方針.md`に記録済み)

**選定理由**: 膵癌免疫療法の限界と今後の課題を体系的に論じた総説。**項目5(併用でも成績が限定的)から項目6(だから免疫学的理解が必要)への橋渡し**に最も適している。Hiraoka論文が「PDACへの免疫療法の奏効はまれ」という記述の根拠として引用していた3本のうちの1本でもあり、この分野の標準的な引用先と考えられる。

---

### 項目6: 治療戦略の発展の必要性 / 免疫学的理解の必要性

#### Kabacaoglu D, Ciecielski KJ, Ruess DA, Algül H.
**Immune Checkpoint Inhibition for Pancreatic Ductal Adenocarcinoma: Current Limitations and Future Options**
- 雑誌: Frontiers in Immunology. 2018;9:1878.
- PMID: 30158932 / PMCID: PMC6104627
- DOI: 10.3389/fimmu.2018.01878
- URL: https://pubmed.ncbi.nlm.nih.gov/30158932/
- 入手性: **Frontiers系のためOpen Access**
- 発見経緯: **Hiraoka論文の孫引きとして既に発見済み**

**選定理由**: ICIが膵癌で効かない理由(免疫学的に"cold"な微小環境、desmoplastic stroma によるT細胞浸潤の物理的阻害、免疫抑制細胞の集積)を整理した総説。「PD-1を標的としたアプローチを改善できるかは、免疫学的な明確な理解が必要」という**Introductionの締めの論拠**として直接使える。自験がCD8浸潤・HLA class I・PD-L1という免疫学的パラメータを測定した動機を説明する土台にもなる。

#### Pardoll DM.
**The blockade of immune checkpoints in cancer immunotherapy**
- 雑誌: Nature Reviews Cancer. 2012;12(4):252-264.
- PMID: 22437870 / PMCID: PMC4856023
- DOI: 10.1038/nrc3239
- URL: https://pubmed.ncbi.nlm.nih.gov/22437870/
- 入手性: **PMCで無料公開**
- 発見経緯: **Hiraoka論文の孫引きとして既に発見済み**

**選定理由**: 免疫チェックポイント機構の基礎を確立した超高被引用総説。PD-1/PD-L1軸の説明が必要な箇所(項目4の導入部、あるいは項目6)で、機構の一般的説明の根拠として使える。ただし2012年と古く、あくまで「基礎概念の出典」としての位置づけであり、最新の治療成績の根拠には使えない点に注意。

---

## Introduction執筆時の推奨配列

項目4→5→6の流れは、以下の順で並べると論理が自然につながる。

1. **Royal 2010**(CTLA-4単剤 → 奏効なし)
2. **O'Reilly 2019**(PD-L1単剤/CTLA-4併用 → 閾値未達)
3. **CheckMate 032**(最新世代の併用でも限定的)
4. **Kabacaoglu 2018 / Balachandran 2019**(なぜ効かないのか — 免疫学的機序)
5. → 本研究の位置づけへ

なお **KEYNOTE-158**(MSI-H/dMMR)は、「PDACでICIが承認されているのは極めて限られた集団のみ」という限定条件を示すために、上記1の前後に置くとよい。

---

## 未解決・要確認事項

- [ ] Bray 2024 のPMID(38572751)をPubMedで直接確認する
- [ ] PREOPANC初回報告(2020)のPMIDを確認する
- [ ] Balachandran 2019 のDOIを確認する
- [ ] 各文献を実際に引用すると決めた時点で`references/refs.yaml`に登録する(現時点でMannucci以外すべて未登録)
