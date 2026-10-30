# Discord Hub (iPhone向け)

## 機能
- 最大3件のDiscordアカウント表示情報を登録
- 表示名・ユーザー名の端末内保存（localStorage）
- 一覧表示、選択、削除
- Discord公式ログインページを開く
- PWA対応（HTTPSで公開するとホーム画面に追加可能）

## iPhoneへの追加
1. このフォルダの中身をGitHubの新しいリポジトリへアップロード
2. GitHubの Settings → Pages → Deploy from a branch → main / root を選択
3. 公開されたHTTPS URLをiPhoneのSafariで開く
4. 共有ボタン →「ホーム画面に追加」

## 大切な制限
Discord Hubはアカウント情報の整理用ランチャーです。Discord公式アプリのログイン状態を切り替えたり、複数セッションを保持したりはできません。パスワード・トークン・認証コードは保存しません。
