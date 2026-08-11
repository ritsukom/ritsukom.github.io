# GitHub Pages用 キャリアコンサルタントサイト

## 公開方法
1. このフォルダの中身をGitHubリポジトリのルートへアップロードします。
2. GitHubの Settings → Pages を開きます。
3. Build and deployment で「Deploy from a branch」を選びます。
4. Branch を `main`、Folder を `/(root)` にして保存します。

## 写真の差し替え
現在は写真部分をCSSのプレースホルダーにしています。
`assets/images/` に写真を入れ、`assets/css/style.css` の `.hero-photo` などの background を `url('../images/ファイル名.jpg') center/cover no-repeat;` に変更してください。

## 編集ポイント
- 氏名：`○○○○` を置換
- メール：`contact.html` の `your-email@example.com` を置換
- サービス文章：`index.html` と `services.html`
- プロフィール：`profile.html`

## GitHub Pages上の注意
GitHub PagesはPHPを実行できません。この一式はHTML/CSS/JavaScriptだけで動く静的サイトです。
お問い合わせフォームを設置する場合はGoogleフォーム、Formspree等の外部フォームサービスをご利用ください。
