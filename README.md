# 受発注管理（オオサカポテト）

社内用の受発注・出荷量・シフト・袋詰原価の管理画面。

- 画面：この `index.html`（GitHub Pages で配信）
- データ：Google スプレッドシート（Apps Script の API 経由）
- ログイン：名前＋合言葉（合言葉は Apps Script のスクリプトプロパティで管理。この中には入っていない）

## 更新手順
1. `index.html` を差し替える
2. `git add -A && git commit -m "更新" && git push`
3. 1〜2分で GitHub Pages に反映

API 側（Apps Script）は `~/gas-projects/受発注管理` で `clasp push` → 新バージョンをデプロイ。
