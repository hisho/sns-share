# SNSシェアOGPタグ設定

[https://hishohub.github.io/sns-share/](https://hishohub.github.io/sns-share/ "https://hishohub.github.io/sns-share/")

## Twitter確認
[Card validator](https://cards-dev.twitter.com/validator "Card validator")
## Facebook確認
[シェアデバッカー](https://developers.facebook.com/tools/debug/sharing/?q=https%3A%2F%2Fhishohub.github.io%2Fsns-share%2F "シェアデバッカー")


タイプ指定(自動吐き出し)
```html
<head prefix="og: http://ogp.me/ns# fb: http://ogp.me/ns/fb# website: http://ogp.me/ns/website#">
```
***
タイプ指定(自動吐き出し)
```html
<meta property="og:type" content="website">
```
***
言語設定
```html
<meta property="og:locale" content="ja_JP">
```
***
サイトのURL(自動吐き出し)
```html
<meta property="og:url" content="https://hishohub.github.io/sns-share/">
```
***
サイトの名前
```html
<meta property="og:site_name" content="サイトの名前">
```
***
ページのタイトル(自動吐き出し)
```html
<meta property="og:title" content="タイトル">
```
***
サイズ1200*620px   
[OGP画像シミュレータ](http://ogimage.tsmallfield.com/ "OGP画像シミュレータ")
```html
<meta property="og:image" content="https://hishohub.github.io/sns-share/assets/img/screenshot/screenshot.png">
```
***
サイトの説明(自動吐き出し)
```html
<meta property="og:description" content="説明説明説明説明説明説明説明説明説明説明説明説明説明説明">
```
***
## Twitterの設定
Twitterカードの種類(summaryが多い)
```html
<!--ツイッターカード -->
<meta name="twitter:card" content="summary">
<!-- 大きい画像 -->
<meta name="twitter:card" content="summary_large_image">
```
***
TwitterアカウントのID
```html
<meta name="twitter:site" content="@hisho_official">
```
***
Facebookの設定(やった方が良い)   
[app_idの取得方法](https://pasolack.com/sns/facebook-developer-entry/ "app_idの取得方法")
```html
<meta property="fb:app_id" content="App-ID">
```
***
その他   
あればなおよし
```html
<meta property="og:country-name" content="国名">
<meta property="og:region" content="都道府県">
<meta property="og:locality" content="市区町村">
<meta property="og:street-address" content="住所">
<meta property="og:postal-code" content="郵便番号">
<meta property="og:latitude" content="緯度">
<meta property="og:longitude" content="経度">
<meta property="og:email" content="メールアドレス">
<meta property="og:phone_number" content="電話番号">
<meta property="og:fax_number" content="FAX番号">
```