# Patholoscope 運用フォルダ(P01 CD8計測)

**作成**: 2026-10-23
**目的**: 第二評価者(T.S.)がPatholoscopeでCD8陽性細胞を計測するための、取扱説明の整理・JPG画像の読み込み条件の最適化・計測処理の自動化の検討。

## フォルダ構成

| フォルダ | 中身 | git管理 |
|---|---|---|
| `manual/` | 三谷商事の取扱説明書(PDF)など | **しない**(メーカーの著作物) |
| `images/` | 計測に使う顕微鏡画像(JPG)。`images/<症例コード>/<症例コード>_CD8_<視野番号>.jpg` | **しない**(研究データ) |
| `results/` | Patholoscopeの計測結果(CSV・スクリーンショット) | **しない**(研究データ) |
| `notes/` | 操作手順メモ、パラメータ設定の記録、検討結果 | する |
| `settings/` | Patholoscopeの設定ファイル(書き出せる場合) | する |

## 前提

- 計測ソフト: Patholoscope ver 1.8.0(MITANI Corporation, Fukui, Japan)。Methodsに記載済み。
- 計測条件(Methods): ホットスポット4視野、×200、CD8陽性細胞数を視野ごとに計測し平均。
- 第二評価者はPython環境なし。自動化はPatholoscope本体の機能か、Windows標準の範囲で検討する。
- Patholoscopeは専用のUSBライセンスキーを差したPCでしか起動しない。このリポジトリのPC(梅宮さんのPC)には入っていない(2026-10-24確認)。そのため、Patholoscopeの操作・パラメータ調整はライセンスキーのあるPCで行い、ここでは手順書・設定の記録・画像の整理を担う。
- 1人目の値・群の情報は第二評価者に見せない(独立評価)。

## 情報源

- 製品ページ: http://www.mitani-visual.jp/en/products/bio_imaging_analysis/patholoscope/
- 取扱説明書(日本語、6.7 MB、ダウンロード時に必要事項の入力あり): https://www.mitani-visual.jp/download/manual/patholoscope-1.php?parts-productsid=Patholoscope
- サポート: https://www.mitani-visual.jp/en/support/
