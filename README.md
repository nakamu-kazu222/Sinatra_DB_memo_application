# Sinatra_DB_memo_application
## 概要
Sinatraを利用したメモアプリケーションです
メモを作成、編集、削除、一覧表示ができます

## アプリケーションを立ち上げるための手順
- リポジトリをローカル環境にコピー
```
git clone https://github.com/nakamu-kazu222/Sinatra_DB_memo_application.git
```

- `Sinatra_memo_application`ディレクトリに移動
```
cd Sinatra_DB_memo_application
```

- リモートブランチをフェッチする
```
git fetch origin refs/pull/1/head:db_memo_application
```

- フェッチしたブランチに切り替える
```
git checkout db_memo_application
```

- bundler を使用して Gem をインストール
```
bundle install
```

- サーバーを立ち上げる
```
bundle exec ruby memo_app.rb
```

- http://localhost:4567/memos で WEBページを開く
