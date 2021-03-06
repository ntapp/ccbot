# ボットの実績

現在実運用中のZaif取引所用トレンド相場対応ボットの成績を公開します。

## 売買履歴

次の売買履歴は基準ボットの動作結果ですので、他のユーザ様のボットとは若干が異なる場合があります。全てのボットが同時に同じ売買を行うのではなく、各ユーザ様用のボットが起動後から一定間隔でAPIサーバーにアクセスする時刻は異なるためです。

No | 時刻              | タイプ | 1BTC価格  | 通貨ペア | 備考 |
---|------------------|------|--------|---------|---------|
21 | 2017-11-9 23:00  | sell | 824670 | btc_jpy | 通知のみ |
20 | 2017-11-06 06:00 | sell | 865665 | btc_jpy | 通知のみ |
19 | 2017-11-06 04:21 | buy  | 868510 | btc_jpy | |
18 | 2017-11-04 00:02 | sell | 840830 | btc_jpy | |
17 | 2017-11-03 11:10 | buy  | 809645 | btc_jpy | |
16 | 2017-10-31 19:01 | buy  | 691850 | btc_jpy | |
15 | 2017-10-31 02:00 | sell | 674500 | btc_jpy | |
14 | 2017-10-29 19:19 | buy  | 665005 | btc_jpy | |
13 | 2017-10-25 21:40 | buy  | 625160 | btc_jpy | |
12 | 2017-10-22       | sell | 688336 | btc_jpy | |
11 | 2017-10-19       | buy  | 635830 | btc_jpy | |
10 | 2017-10-?? 未記録 | sell | 626285 | btc_jpy | |
 9 | 2017-10-?? 未記録 | buy  | 560779 | btc_jpy | |
 8 | 2017-10-?? 未記録 | sell | 533073 | btc_jpy | |
 7 | 2017-10-?? 未記録 | buy  | 494660 | btc_jpy | |
 6 | 2017-10-?? 未記録 | sell | 487025 | btc_jpy | |
 5 | 2017-10-?? 未記録 | buy  | 483396 | btc_jpy | |
 4 | 2017-10-?? 未記録 | sell | 491926 | btc_jpy | |
 3 | 2017-10-?? 未記録 | buy  | 491886 | btc_jpy | |
 2 | 2017-10-?? 未記録 | sell | 482249 | btc_jpy | |
 1 | 2017-10-?? 未記録 | buy  | 472189 | btc_jpy | |


No.20、21の売りシグナルは、ボットのAPIサーバーへのアクセスタイミングによる価格チェックにより、買った金額よりも安い場合は処理していませんので、BTCを減らしておりません。（ユーザ様用ボット）。

## 2017年11月（集計中）

以下の結果は常に1BTCで取引した場合です。

- (840830 - 691850) / 691850 * 100 = 21.5335694153
- (840830 - 809645) / 809645 * 100 = 3.8516880855

各取引ごとのROI合計  
21.5335694153 + 3.8516880855 = 25.3852575008

各取引ごとの総利益  
(840830 - 691850) + (840830 - 809645) = 180165

## 2017年10月

以下の結果は常に1BTCで取引した場合です。

初回取引開始時のBTC時価総額: 472189

- (482249 - 472189) / 472189 * 100 = 2.130
- (491926 - 491886) / 491886 * 100 = 0.008
- (487025 - 483396) / 483396 * 100 = 0.750
- (533073 - 494660) / 494660 * 100 = 7.765
- (626285 - 560779) / 560779 * 100 = 11.681
- (688336 - 635830) / 635830 * 100 = 8.257
- (674500 - 625160) / 625160 * 100 = 7.892
- (674500 - 665005) / 665005 * 100 = 1.427


各取引ごとのROI合計  
2.1305028283166276 + 0.008131965536730054 + 0.7507302501468774 + 7.765535923664739 + 11.6812505461 + 8.257867669 + 7.8923795508 + 1.4278088135 = 39.9142075471

各取引ごとの総利益  
(482249 - 472189) + (491926 - 491886) + (487025 - 483396) + (533073 - 494660) + (626285 - 560779) + (688336 - 635830) + (674500 - 625160) + (674500 - 665005) = 228989


計算ミス、計算内容にご質問やご意見がある場合は、[Twitter]にてお伝え下さい。

## ボットが見ている相場状況

2017/11/9 23:00時点の相場

![相場](https://www.tradingview.com/x/P1MQjiEX)

2017/11/9 19:30時点の相場

![相場](https://www.tradingview.com/x/hbmcb8w8)

2017/10/22時点の相場

![si1wna4q](https://user-images.githubusercontent.com/29969775/31860169-c8e178f8-b748-11e7-90b1-19280ca6ad38.png)


[Twitter]: https://twitter.com/nkts
