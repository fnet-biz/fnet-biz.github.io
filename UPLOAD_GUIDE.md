# GitHub Pages 手動アップロード手順

## 設定内容

- GitHubアカウント: `fnet-biz`
- リポジトリ名: `fnet-biz.github.io`
- 公開URL: https://fnet-biz.github.io/
- 問い合わせ受信先: `fnet.businessdomain@gmail.com`

## アップロード

1. GitHubで `fnet-biz/fnet-biz.github.io` リポジトリを開きます。
2. **Add file → Upload files** を選びます。
3. このフォルダの中身をすべてアップロードします。フォルダ自体ではなく、`index.html` がリポジトリ直下に置かれるようにしてください。
4. **Commit changes** を実行します。
5. **Settings → Pages** を開き、公開元が **Deploy from a branch / main / root** になっていることを確認します。
6. 数分後、https://fnet-biz.github.io/ を開いて表示を確認します。

公開後、次のURLにもアクセスできることを確認してください。

- https://fnet-biz.github.io/robots.txt
- https://fnet-biz.github.io/sitemap.xml

## 問い合わせフォームの初回認証

1. 公開ページのお問い合わせフォームからテスト送信します。
2. `fnet.businessdomain@gmail.com` に届くFormSubmitの認証メールを開きます。
3. メール内の認証リンクをクリックします。
4. もう一度テスト送信し、問い合わせメールを受信できることを確認します。

初回認証が完了するまで問い合わせメールは配信されません。認証メールが見当たらない場合は、迷惑メールフォルダも確認してください。

## Google Search Console

`fnet.businessdomain@gmail.com` でGoogle Search Consoleへログインし、次を人手で実施してください。

1. `https://fnet-biz.github.io/` をURLプレフィックスとして登録します。
2. 所有権確認を完了します。
3. `sitemap.xml` を送信します。
4. URL検査でトップページを確認し、インデックス登録をリクエストします。
