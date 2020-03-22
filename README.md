# Ruby on Rails チュートリアルのサンプルアプリケーション

これは、次の教材で作られたサンプルアプリケーションです。
[*Ruby on Rails チュートリアル*]

## ライセンス

[Ruby on Rails チュートリアル]内にあるソースコードはMITライセンスの元で公開されています。<br>
詳細は[LICENSE.md]をご覧ください。

## 使い方

このアプリケーションを動かす場合は、まずはリポジトリを手元にクローンしてください。その後、次のコマンドで必要となるRubyGemをインストールします。
、、、
$ bundle install --without production
、、、
その後、データベースへのマイグレーションを実行します。
、、、
$ rails db:migrate
、、、
最後に、テストを実行してうまく動いているかどうかの確認をしてください。
、、、
$ rails test
、、、
テストが無事に通ったら、Railsサーバーを立ち上げる準備が整っているはずです。
、、、
$ rails server
、、、

詳しくは、チュートリアルを参考にしてください。


This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
