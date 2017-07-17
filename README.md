# [LocalNames](http://databasediv.com/ns/domain/local/)

* このレポジトリでは [LocalNames](http://databasediv.com/ns/domain/local/) の概要情報を整理しています。
* なお、 [LocalNames](http://databasediv.com/ns/domain/local/) の技術情報については [Wiki] に集約しています。

## Background
世界中の地名に対して URI を付与する基盤である [GeoNames.org](http://www.geonames.org/) は、LOD Cloud の中でも重要な地位を占めています(2014年時点で DBPedia に次ぐ第二位)。日本国内では GeoNames.jp が重要な地位を占めています。
地方名や支庁名や地域名のURI基盤を

## Solution
地方名や支庁名や地域名のURI基盤 Localnames を立ち上げました。

## Application
以下のような分野への応用を期待しています。

* 統計分野：[e-Stat API](http://www.e-stat.go.jp/api/) から[Data Cube](http://www.w3.org/TR/vocab-data-cube/) を作成する際のエリア識別子として
* 機械学習：テキストマイニングによって抽出された地名に付与する識別子として
* 公共分野：[IMI 共通語彙](http://goikiban.ipa.go.jp/) における、地理識別子の選択肢のひとつとして

## ToDo
* DBPedia 等の外部データセットと連携するためのリンクセットの充実
