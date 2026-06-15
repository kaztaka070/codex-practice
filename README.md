# kkresearch

木村和孝（博士（教育学））の研究ホームページです。

## GitHub Pages で公開する方法

このリポジトリは、`index.html` と `style.css` をリポジトリ直下に置いた静的サイトです。GitHub Pages 用のワークフローが公開用ファイルだけを `_site` にまとめてアップロードするため、`main` ブランチへ push すると自動で公開できます。

1. GitHub のリポジトリ画面で **Settings** を開きます。
2. **Pages** を選択します。
3. **Build and deployment** の **Source** で **GitHub Actions** を選択します。
4. `main` ブランチへ変更を push します。
5. Actions の `Deploy static site to GitHub Pages` が成功すると、Pages の URL でサイトを確認できます。

## ローカルで確認する方法

```bash
python3 -m http.server 8000
```

ブラウザで <http://127.0.0.1:8000/> を開いて確認します。
