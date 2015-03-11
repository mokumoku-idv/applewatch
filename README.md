# Apple watch kitまとめ

大きく分けて３つの見せ方
WatchKitアプリの通常起動
チラ見（Glance）
お知らせ

## チラ見
見るだけが基本
小さくまとめた情報を見せるだけ
リードオンリー

## Notification
* LocalかRemoteどちらも可能
* 多分この辺りが分かりやすそう
http://blog.haranicle.net/customize_notification/
http://blog.haranicle.net/applewatch_notification/
http://qiita.com/TECHFUND/items/dddaeb8616b053d568be

## Watch kit app
WatchKitアプリはiPhoneアプリと協調して動作
WatchKitアプリはUI部分のみを含み、プログラムはホストとなるiOSアプリが持つ
UIの状態更新はiPhone側から行う

## できないこと
GPS機能がない
プログラムからView関連をaddできない
バックグラウンド処理はサポートしてない

##UIDesign Basics

## WatchKitExtension
Watch kit Appを制御するもの

## WKInterfaceController
Watch kit側の処理をコントロールするもの
watch側では基本表示しか行わないので、実態はiOSの本体で動いてる？




