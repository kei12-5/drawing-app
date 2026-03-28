# お絵かきアプリ

ブラウザで動くシンプルなお絵かきアプリです（HTML / CSS / JavaScript）。

## 使い方

`index.html` をブラウザで開いてください。

## 機能

- ペン・消しゴム・線の太さ・色の変更
- キャンバスのクリア、PNG 保存
- マウス・タッチ対応

## GitHub にプッシュする

[GitHub CLI](https://cli.github.com/)（`gh`）を使う場合:

1. 初回のみログイン（ブラウザで認証）: `gh auth login`
2. このフォルダ（`drawing-app`）で次を実行すると、公開リポジトリを作成して `main` をプッシュします。

```bash
gh repo create drawing-app --public --source=. --remote=origin --push
```

リポジトリ名を変える場合は `drawing-app` を別の名前に置き換えてください。非公開にする場合は `--public` を `--private` にします。
