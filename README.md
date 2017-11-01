## このシステムについて

このシステムは[株式会社メディアコンテンツファクトリー](http://www.media-cf.co.jp/)と、[おおくぼ総合内科クリニック](https://ohkubo-med.jp/)　大久保辰雄院長による共同開発サービスです。

## システム概要

+ このシステムは医療機関において患者からの問診を聴取するためのシステムです。
+ 当システムは全てクラウドサービスです。システムを利用するためにインターネット環境が必要です。
+ 当システムでは、患者が問診を入力する機能、医療機関側で患者の問診内容を確認するための機能、その他設定機能よりなっています。

## 問診結果による推論について

当システムでは、患者の問診回答内容に応じて、自動的に質門が遷移し、問診結果に応じて可能性の高い疾患の推論を行っています。
推論のアルゴリズムは下記より成り立っています。

#### 疾患マスタ
+ 当システムでは、内科及び小児科の診療所／クリニックで遭遇する可能性のある疾患を中心に約600疾患（2017年11月現在）をマスタデータとして格納しています。
+ 疾患マスタでは、各疾患の症状や症状の関連度、年代や性別ごとの発生割合などのデータを保持しています。

#### 症状マスタ
+ 約症状をマスタデータ化しています。
+ 各症状は、

#### 基礎点数

#### 影響要素

#### 
