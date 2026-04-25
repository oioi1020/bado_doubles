# バドミントンダブルス記録

GitHub Pages でそのまま公開できる静的 HTML アプリです。

## 公開しても記録が公開されない理由

- 公開されるのは `HTML / CSS / JavaScript` のアプリ本体だけです。
- 記録データは各ユーザーのブラウザの `localStorage` に保存されます。
- 記録データを GitHub Pages に自動送信する処理は入っていません。
- 他人に共有したい場合だけ、JSON のエクスポート機能で手動共有します。

## GitHub Pages で公開する手順

1. このフォルダを GitHub リポジトリに push します。
2. GitHub の `Settings` > `Pages` を開きます。
3. `Build and deployment` の `Source` を `Deploy from a branch` にします。
4. `Branch` は `main`、フォルダは `/ (root)` を選びます。
5. 保存すると、数分後に公開 URL が発行されます。

## 公開 URL

- ルート URL の `index.html` からアプリ本体へ自動で移動します。
- アプリ本体は `app.html` です。

## 注意

- 同じサイトでも、ブラウザや端末が変わると保存データは別になります。
- ブラウザのサイトデータを消すと記録も消える可能性があります。
- 定期的に JSON をエクスポートしてバックアップするのがおすすめです。
