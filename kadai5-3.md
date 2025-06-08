## 外部APIの呼び出しのミニレポート
### Q3-1. 郵便番号APIについて説明せよ。
* エンドポイントと機能
* エンドポイントはhttps://zipcloud.ibsnet.co.jp/api/searchです。
* const zipcode = myForm.zipcode.valueで郵便番号を取得し、const responseでリクエストを送ります。const dataではJSONとして結果を受け取ります。const result情報を取得し画面に表示します。
* リクエストとレスポンスのフォーマット
* リクエスト
* get
* https://zipcloud.ibsnet.co.jp/api/search
* ?zipcode=郵便番号
* レスポンス
* JSON形式で返す

### Q3-2. 各自で調査したAPIについて説明せよ。
* APIの名称と参照URL
* 国立国会図書館サーチ
* https://ndlsearch.ndl.go.jp/help/api/specifications
* エンドポイントと機能
* エンドポイント：https://openlibrary.org/search.json
* 機能：open liblaryに登録されている書籍のデータベースからキーワードを検索して書籍情報をJSON形式で返します。
### Q3-3. 感想
* 今回の課題で苦労したこと
* APIキーを必要なものが多く必要のないものを探すのに少し苦労しました。
* 演習を通して理解できたこと
* Web APIの利便性や課題など
* 最新のデータを取得することができる
* オフラインで使用することができない
* 
