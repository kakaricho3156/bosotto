# README
***アプリケーション名	***
bosotto

***アプリケーション概要***	
チャットルームでテキストや画像だけでなく、音声を用いたコミュニケーションが可能になります。

***URL***
 https://bosotto.herokuapp.com/

***テスト用アカウント***
---------------------------------------	
Basic認証用ユーザー名:admin
Basic認証用パスワード:1111
メールアドレス:apple@gmail.com 
パスワード:111111eeeeee

***利用方法***
---------------------------------------
トップページからユーザーの新規登録を行います。
チャットルーム作成ボタンからチャットルームを作成します。
チャットルームに入室後、入力欄からテキスト、画像、音声データを入力し投稿します。

***アプリケーションを作成した背景***
---------------------------------------
	両親に課題をヒアリングし、「孫はこのご時世だからたまにしか遊びに来れない。もっと、孫を近くで感じられるようなアプリがほしい」という課題が判明した。電話でも良いのではないかと思ったが、電話だとかけている時は良くても通話が終わった後、寂しくなる。かといってLINEやメールなどの文章や写真だけでは孫を身近に感じられるという課題には十分に応えられない。よって、音声を気軽に投稿できるアプリを開発しようと考えました。

***洗い出した要件***
---------------------------------------
https://docs.google.com/spreadsheets/d/1_poq4j2XtnWw-z-qbQd8w53PudogIQ6lgqtkTh_3gcI/edit#gid=982722306

***実装予定の機能***	
---------------------------------------
保存した音声にタイマーをつけて、目覚まし時計やアラームにする機能を実装する予定です

***データベース設計***	
---------------------------------------
![データベース設計](https://user-images.githubusercontent.com/94548036/180713630-96e042b1-1c4f-455b-93ae-bccbda900814.png)

***画面遷移図***	
---------------------------------------

![画面変移図](https://user-images.githubusercontent.com/94548036/180713940-91efaf81-7aee-4521-819d-3ef0bf97651c.png)

***開発環境***
---------------------------------------
フロントエンド
バックエンド
インフラ
テスト
テキストエディタ
タスク管理

***ローカルでの動作方法***
---------------------------------------
% git clone https://github.com/kakaricho3156/bosotto
% cd kakaricho3156/bosotto
% bundle install
% yarn install

***工夫したポイント***
---------------------------------------
※	制作背景・使用技術・開発方法・タスク管理など、企業へＰＲしたい事柄を記載。
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
