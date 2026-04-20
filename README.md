# AI Creative Academy LP

AI Creative Academy のランディングページ。

## デプロイ（GitHub Pages）

1. このリポジトリを GitHub に push
2. `Settings` → `Pages` → `Source: Deploy from a branch` → `main / (root)` → Save
3. 数十秒後、`https://<username>.github.io/<repo>/` で公開されます

## ファイル構成

- `index.html` — LP本体（単一ファイル・自己完結）
- `assets/` — 画像・動画
  - `hero.mp4` — ヒーロー動画
  - `owner.png` — 代表プロフィール画像

## ローカルで確認

`index.html` をブラウザで開くだけで動作します。  
動画の自動再生を確認したい場合は、簡易サーバ経由推奨：

```bash
python3 -m http.server 8000
# → http://localhost:8000
```
