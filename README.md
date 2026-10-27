# kirinuki-kun-site

個人用ツール「kirinuki-kun」の公開ページ（ホームページ・プライバシーポリシー・利用規約）を置くリポジトリ。

## 目的

kirinuki-kun は YouTube API を使って自分のチャンネルに動画をアップロードする。
Google Cloud の OAuth 同意画面を「本番環境」にするには、誰でも開けるホームページとプライバシーポリシーの URL が必要なため（利用規約も合わせて置く）、それだけをここで GitHub Pages として公開している。

- ホームページ: https://kaiki323.github.io/kirinuki-kun-site/
- プライバシーポリシー: https://kaiki323.github.io/kirinuki-kun-site/privacy.html
- 利用規約: https://kaiki323.github.io/kirinuki-kun-site/terms.html

ツール本体のコードはこのリポジトリには含まない（非公開リポジトリで管理）。

## 更新するとき

`index.html` / `privacy.html` / `terms.html` を編集して `main` に push すれば、GitHub Pages に反映される。
URL を変えた場合は、Google Cloud の「Google Auth Platform」→「ブランディング」の URL も合わせて変える。
