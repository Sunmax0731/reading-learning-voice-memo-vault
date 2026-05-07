# 読書・学習・音声メモ保管庫

読書、記事、動画、語学、暗記カード、音声記録、即時タグ分類をスマホで扱い、要約と復習カードに回す。

| 項目 | 内容 |
| --- | --- |
| Rank | 80 |
| Domain | AndroidApp |
| Idea No. | 5 |
| Repository | reading-learning-voice-memo-vault |
| 主な公開先 | Google Play |

## Implementation

- `src/product-profile.mjs`: プロダクト定義。
- `src/core.mjs`: 入力正規化とバッチ評価。
- `src/validators.mjs`: 必須項目と warning 項目の検査。
- `src/review-model.mjs`: UI/レビュー向けモデル。
- `src/report.mjs`: Markdown / HTML レポート生成。
- `src/cli.mjs`: CLI。

## Validation

`npm test` で代表シナリオ、QCDS、docs ZIP、文字化けを検証します。

## Strict QCDS Docs

- [Remote benchmark](docs/qcds-remote-benchmark.md)
- [Strict metrics](docs/qcds-strict-metrics.json)
- [Traceability matrix](docs/traceability-matrix.md)
- [Release evidence](docs/release-evidence.json)
