# octout.github.io
公開用

### Obs.json
観測地点名およびその緯度経度の定義ファイルです

### index.html
tableauからWDCで接続するページです。
内部で下記のvalues_wdc.jsを実行しています。

### values_wdc.js
APIをtableauに読み込むJavascriptファイルです。
Obs.jsonから位置情報を読み込み、AzureMapsWeatherServiceのAPIへGETメソッドでjsonファイルを取得します。
