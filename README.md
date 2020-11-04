# README

# アプリ名：Trello風タスク管理アプリ

# 説明（何が出来る物なのか）:様々なタスク、スケジュール管理

#　本番環境(デプロイ先　AWS予定　テストアカウント＆ID：作成中)

# Things you may want to cover:

# 使い方:タスクの作成と移動、編集

# 制作背景(意図):様々なタスクを一括で管理するトレロのような物を作成したいので作成した。チーム開発中に誰がなんのタスクをしているのか、何が残っているのか分かりづらいと思っていたが、トレロがとても管理しやすかったので、同じものを作成したかったので作成しました。

# DEMO:![スクリーンショット 2020-11-01 18.36.02](https://i.gyazo.com/69107fe36d46c36755d6fa56301254c2.png)[画面収録 2020-11-04 21.25.23](https://i.gyazo.com/a47d66e04d385c2120bfe935132c0718.gif)

# 実装予定の内容:タスクの作成、編集、移動、削除

# 使用技術(開発環境):Ruby version:2.5.1 rails version:5.2.3 

# DB設計:usersテーブル:
# Column	Type	Options
# id	integer	null:false,unique:true
# password	string	null:false
# email	string	null:false, unique:true
# first_name	string	null:false
# last_name	string	null:false
# first_name_kana	string	null:false
# last_name_kana	string	null:false
# nickname	string	null:false ,unique:true
# introduction	text	null:false
# birthday	string	null:false
# telephone	string	null:false

# This README would normally document whatever steps are necessary to get the
application up and running.

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
