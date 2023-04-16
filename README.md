# Windows initial setup

Nagitch 自分向け Windows クリーンインストールの手順

## バックアップ

- Choco パッケージのエクスポート（将来的には wget にすると思う）
- 手動インストールしたアプリのインストーラをバックアップ
- Brave Sync に参加してるか確認
  - 今の PC
  - iPhone
- 各アプリの設定をエクスポート
- スタートメニューとタスクバーのピン留めを記録する（スクショ）
- ユーザーの個人設定を記録する（スクショ or 初期化後に思い出す）
  - 壁紙画像の保存
- ホームフォルダのバックアップ
  - git リポジトリは push しておく

## ビルド

### Windows とドライバのインストール

- Windows11 インストール
- ESI Maya 44ex ドライバ(ASIO 含む)インストール
- WSL インストール　管理者権限

### アプリインストール

- choco インストール　管理者権限
- デフォルトブラウザを Brave にする
  - Brave Sync に PC を登録
- Google, ソーシャルログイン, Web サービスのログイン
- choco で入れられないアプリをインストール
  - 必要なものはログイン
  - 設定のインポート

### 個人設定

- いらないもの削除
  - OneDrive
  - Teams
- HHKB 設定 キーボードを英字に設定
- キーボード設定 入力速度最速にする
- 辞書の登録
- スタートメニューのピン止めを全滅させる
  - 必要なものだけ追加
- クイックアクセスのピン止めを全滅させる
  - 必要なものだけ追加
- グラボ
  - リファレンス出力に設定
  - ビデオアップコンバートの設定

### 開発環境のセットアップ

- 業務やプロジェクトに応じて
