# Google Sheets 雛形（CSV公開用）

## 目的
この雛形は「外部問題データURL」へ貼り付ける **CSV公開URL** を作るためのテンプレートです。  
`term / yomi / emoji / badge / level` の5列を使います。

## 手順
1. Google スプレッドシートで新規作成します。
2. 1行目に以下のヘッダーをそのまま入力します。  
   `term, yomi, emoji, badge, level`
3. 2行目以降に問題を追加します（例は下の表参照）。
4. **ファイル → 共有 → ウェブに公開** を開きます。
5. **リンク**で「形式：CSV」を選び、公開します。
6. 生成された **CSVのURL** をゲームの「問題データURL」欄に貼り付けます。

## 公開済みCSVのURL（今回の指定）
```
https://docs.google.com/spreadsheets/d/e/2PACX-1vRSSGtJfEZXjdJm2FKR46MsxURlOlUZ4tjzZ6nGv7_dAU-K96eI4pAlKOk3k3bgt-DEjisr2kiLDjW-/pub?gid=0&single=true&output=csv
```

## 列の説明
- **term**: 表示される単語（日本語）
- **yomi**: タイピングする読み（ひらがな or ローマ字）
- **emoji**: 表示用絵文字（任意）
- **badge**: 右上バッジ（任意）
- **level**: 難易度（`easy` / `normal` / `hard` / `oni`、または `簡単` / `普通` / `難しい` / `鬼` / `おに`）

## 入力例
| term | yomi | emoji | badge | level |
| --- | --- | --- | --- | --- |
| 腹痛 | ふくつう | 🤢 | 症状 | easy |
| 発熱 | はつねつ | 🔥 | 症状 | normal |
| 胸痛 | きょうつう | 💥 | 症状 | hard |
