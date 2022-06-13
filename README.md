# マイタスクコントロール

## サイト概要
### サイトテーマ
タスクの進捗を管理できるサイトです

### テーマを選んだ理由
プログラミングスクールで課題に取り組んでいる際、同じ課題に取り組む仲間がいる事で
モチベーションを維持して学習を続けることができました。
同時進行している課題やタスクが増えると、カレンダーだけでは管理が困難になりました。
そんな時、簡単にタスクをTODOリストとして管理出来、
スクールの時の様に同じ課題に取り組む人達と共有できたらいいのになと思うようになり
今回のテーマに決めました。

### ターゲットユーザ
- タスク・スケジュール管理が苦手な人
- タスクへのモチベーション維持が苦手な人
- 同じ目標を持った仲間を見つけたい人


### 主な利用シーン
- タスクが増えてリスト化したい時
- タスクの内容を確認したい時
- タスクの進捗を確認したい時
- タスクへのモチベーションが下がった時

## 設計書
- ER図
https://app.diagrams.net/#G1lVOmljxnVcKm8I_Xvr1dtAdRbXwmScr2
- テーブル定義書
https://docs.google.com/spreadsheets/d/1InfBQjmryNwUS11olB_9l6PfwO-YuYUFObsVhKvZ3BM/edit#gid=1373217982

## 開発環境
- OS：Linux(CentOS)
- 言語：HTML,CSS,JavaScript,Ruby,SQL
- フレームワーク：Ruby on Rails
- JSライブラリ：jQuery
- IDE：Cloud9

## 使用素材
トップページ画像
https://o-dan.net/ja/

customers/show
<div id="favorite_btn_<%= task.id %>">
  <%= render "public/favorites/favorite", task: task %>
</div>

tasks/index
<div id="favorite_btn_<%= task.id %>">
  <%= render "public/favorites/favorite", task: task %>
</div>