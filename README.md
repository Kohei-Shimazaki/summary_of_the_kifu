# README

# 9・13路盤棋譜まとめサイト

## 概要
囲碁愛好家の9・13路盤研究に役立つサービスです。
サービスが自動で棋譜データを取得するため、棋譜を集める手間が省けます。
ユーザーは手順から棋譜を検索することができ、知りたい定石情報へのアクセスが簡単になります。
また、検討した棋譜を投稿することで、情報をユーザー間で共有することができます。

## バージョン
Ruby 2.6.5 Rails 5.2.4

## 機能一覧
* 優先度：高
  * ログイン機能
  * 棋譜取得機能(カリキュラム外・wheneverを使ったデータ自動取得)
  * 棋譜カテゴリー化
  * 棋譜検討機能
  * 棋譜検索機能
  * お気に入り機能
  * ラベリング機能
  * コメント機能
  * 管理者機能(就業term・devise) 管理者のみ使用可能
* 優先度：中
  * フォロー機能(就業term・友達つながり機能)
  * 勝率表示機能
  * OAuth認証機能(就業term・OAuth)

## カタログ設計
https://docs.google.com/spreadsheets/d/e/2PACX-1vT-pjhkrvAa8ul9AmscvhQyxgofn9JwLSb0M6sZK_8lFtfMiU4hAi538OgRUioCp0jO2TemzIjnv_AD/pubhtml?gid=0&single=true

## テーブル定義
https://docs.google.com/spreadsheets/d/e/2PACX-1vTpcDJHI2hUGfqcY_9WhSZg-YWAQacQ51hbnpeUzwvfzrX_2Pzjlx0Q920hUldhDKsnDcofn5JmRdIq/pubhtml

## ER図
publicフォルダ内のer.jpg

## 画面遷移図
publicフォルダ内のscreen_transition_diagram.png

## 画面ワイヤーフレーム
https://docs.google.com/spreadsheets/d/e/2PACX-1vRvUUIbAI6A2N-wEPWKe5q1XV44lr-b537QZXxS4Kddfq5tRIDsNkZPgqgCT-WvCktaH3n2NcTKlxAY/pubhtml?gid=0&single=true

## 使用予定gem
* nokogiri
* whenever
* devise
* rails_admin
* cancancan
* omniauth
* omniauth-google-oauth2
