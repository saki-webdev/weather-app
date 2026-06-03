# Weather App

JavaScriptを使って天気アプリを作成しました。
都市名を入力すると、OpenWeather APIから天気情報を取得し、現在の天気を表示します。

## URL

https://saki-webdev.github.io/weather-app/

※セキュリティ対策のため、公開版ではAPIキーを除外しています。
そのため現在は天気情報を取得できません。
ローカル環境では天気情報の取得・表示まで正常に動作確認済みです。

## 参考画像

### 通常表示（晴れ）

![Sunny](./images/weather-sunny.jpg)

### 雨天時

![Rain](./images/weather-rain.jpg)

### ダークモード

![Dark mode](./images/weather-dark.jpg)

## 機能

* OpenWeather APIを利用した天気情報の取得
* 都市名検索
* Enterキー検索
* 天気アイコン・気温・天気・湿度・風速の表示
* ローディング表示
* 検索履歴の保存（localStorage）
* ダークモードへの切り替え
* 天候ごとの背景アニメーション
（晴れ / 雨 / 曇り / 雪 / 雷雨）

## 使用技術

* HTML
* CSS
* JavaScript
* OpenWeather API
* localStorage
* GitHub Pages

## 工夫した点

* 天候ごとに背景色やアニメーションを変更し、視覚的にも天気を楽しめるようにしました。
* ローディング表示を実装し、API通信中の状態が分かるようにしました。
* 検索履歴をlocalStorageに保存し、過去に検索した都市を再検索しやすくしました。
* ダークモードを実装し、利用環境に応じて見やすく切り替えられるようにしました。

## 今後追加したい機能

* 5日間天気予報の表示
* 現在地の天気の取得
* レスポンシブデザインの改善
* エラーメッセージの改善
