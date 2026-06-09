# 株式会社C-WORK 現場スケジュール

GitHub Pages 公開用の静的サイトです。

## ファイル構成

- `index.html` アプリ本体
- `.nojekyll` GitHub Pagesでそのまま配信するための設定ファイル

## GitHub Pagesで公開する手順

1. GitHubで新しいリポジトリを作成します。
   - 例: `c-work-schedule`
   - Publicリポジトリにすると無料でGitHub Pages公開できます。

2. このフォルダ内のファイルをGitHubへアップロードします。
   - `index.html`
   - `.nojekyll`
   - `README.md`

3. GitHubのリポジトリ画面で `Settings` を開きます。

4. 左メニューの `Pages` を開きます。

5. `Build and deployment` の設定を変更します。
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/ (root)`

6. `Save` を押します。

7. 数分待つと公開URLが表示されます。
   - 例: `https://ユーザー名.github.io/c-work-schedule/`

## 注意

この版は、予定データを各端末のブラウザ内に保存します。
そのため、URLは全員が開けますが、全員で同じ予定を共有編集する仕組みではありません。

全員で同じ予定を編集したい場合は、Firebaseなどの共有データベース対応が必要です。
