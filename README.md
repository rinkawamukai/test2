# Study Desk

静的HTML / CSS / JavaScriptだけで動く、勉強用ダッシュボードです。

## 起動方法（推奨）

ブラウザの制約上、同梱の `knowledge` フォルダを自動読込するにはローカルサーバーが必要です。

### Windows
1. ZIPを展開
2. 展開先でターミナルを開く
3. Pythonがある場合: `python -m http.server 8000`
4. ブラウザで `http://localhost:8000` を開く

VS Codeなら Live Server 拡張でも動作します。

## ナレッジを追加する

1. `knowledge` フォルダへ `.txt` を追加
2. `knowledge/manifest.json` の配列にもファイル名を追加
3. 画面の「同梱データ」を押す

または、画面の「フォルダを選択」から任意のフォルダを直接選べます（Chrome / Edge推奨）。この方法なら manifest 編集は不要です。

## 機能
- ラップ付きストップウォッチ
- TXTナレッジ一覧、全文検索、フォルダ選択
- キーボード対応計算機、履歴保存
- ポモドーロ集中タイマー
- 今日のタスク管理
- ダークモード
- LocalStorageによる端末内保存
