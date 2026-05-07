# 要件定義

| 項目 | 内容 |
| --- | --- |
| Rank | 80 |
| Domain | AndroidApp |
| Idea No. | 5 |
| Repository | reading-learning-voice-memo-vault |
| 主な公開先 | Google Play |

## 背景

学習メモや音声メモは入力しやすいが、復習や再利用につながりにくい。

## 目的

読書、記事、動画、語学、暗記カード、音声記録、即時タグ分類をスマホで扱い、要約と復習カードに回す。

## 必須要件

- learning memo を複数件まとめて検証できる。
- required fields: `id`, `title`, `sourceTitle`, `memoText`, `reviewCard`, `owner`。
- warning field: `audioNote`。
- 代表シナリオ、QCDS metrics、docs ZIP、release evidence を再生成できる。
