Intelligent Twitter Bot
====

製作中

Overview

## Usage

install.shを参考にライブラリを入れたり，コンシュマー，アクセストークンを手に入れる．

env.pyのTWEET_FILTER_WORDSに取得したいツイートが含む単語のリストを入れる．  
(e.g. TWEET_FILTER_WORDS=['あああ','いいい'])

## TODO

- フォローバックできるようにする．
- リムーブされたユーザをリムーブできるようにする．
- SVMでユーザのスコアを計算できるようにする．
- フォローしたユーザがフォローを返すかをデータベースに入れる．
- スコアを元にユーザをフォローできるようにする．
- 連続多腕バンディットでハイパーパラメータチューニングできるようにする．