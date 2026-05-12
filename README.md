# 第1回 RECORE 関西コミュニティ LP 引継ぎ資料

## 概要

RECOREユーザー向けオフラインイベント「第1回 関西コミュニティ」の参加者募集LPです。  
`index.html` 1ファイルのみで構成されており、GitHub Pages で公開します。

---

## ファイル構成

```
recore-kansai-community/
├── index.html   ← LP本体（これ1つだけでOK）
└── README.md    ← この引継ぎ資料
```

---

## GitHub Pages 公開手順

1. [github.com](https://github.com) にログイン
2. 右上「＋」→「New repository」
3. Repository name: `recore-kansai-community`、Public を選択 → 「Create repository」
4. 「uploading an existing file」から `index.html` をアップロード → 「Commit changes」
5. Settings → Pages → Branch: `main` / `/ (root)` → Save
6. 数分後に公開される（URL: `https://{ユーザー名}.github.io/recore-kansai-community/`）

---

## 公開後にやること（必須）

### 申し込みフォームURLの差し替え

`index.html` 内の `YOUR_FORM_URL` を実際のURLに変更する（2か所あります）。

**GitHubのWeb上で編集する方法：**
1. GitHubのリポジトリページで `index.html` をクリック
2. 右上の鉛筆アイコン（Edit）をクリック
3. `YOUR_FORM_URL` を検索して実際のフォームURLに書き換える
4. 「Commit changes」をクリック → 数分で反映

---

## ポータルサイトのボタンとの連携

`https://recorecom-fk8gj3na.manus.space/` の「参加を申し込む」ボタンのリンク先を  
GitHub Pages の公開URLに変更してもらう（ポータルサイトの管理者に依頼）。

---

## イベント基本情報

| 項目 | 内容 |
|------|------|
| 開催日時 | 2025年6月5日（金）17:00〜19:00 |
| 開催場所 | NEXT51 三国ヶ丘店（〒590-0024 大阪府堺市堺区向陵中町４丁４−４） |
| 参加定員 | 5〜10名程度 |
| 参加費 | 無料（懇親会は別途） |
| 主催者 | 上田陸駆（株式会社RECORE カスタマーサクセス） |

---

## デザイン仕様（修正時の参考）

| 要素 | 値 |
|------|----|
| メインカラー（深緑） | `#1E3A14` |
| アクセント（黄緑ゴールド） | `#C4D44A` |
| 本文テキスト | `#2C2C2C` |
| フォント（見出し） | Noto Serif JP |
| フォント（本文） | Noto Sans JP |
| ボタン形状 | 角丸なし |
