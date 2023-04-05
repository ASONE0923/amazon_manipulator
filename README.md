# Amazon_Manipulator
■ サービス概要
　自分がAmazonで何を買って、いくら使ったかをコマンドライン上にて瞬時に把握できるサービス

■メインのターゲットユーザー
　Amazonを利用する20代〜40代のユーザー

■ユーザーが抱える課題
　Amazonは注文・購入するのはとても簡単だが、毎月の利用額を把握することはできない。

■解決方法
　このアプリからAmazonにログインすることで、注文履歴ページにアクセスして、注文履歴として必要な情報を収集することができる。

■実装予定の機能（以下の例は実際のアプリの機能から一部省略しています）
・注文履歴取得機能
    1.利用顧客は、Amazonの登録情報(Eメールアドレス、パスワード)を用意する。
    2.Amazon_Manipulator(:AM)は利用顧客に登録情報の入力を促す。
    3.利用顧客が登録情報を入力すると、AMは登録情報を使ってAmazonのWebサイトにログインする。
    4.AMはAmazonのWebサイトにログインすると、注文履歴ページを開く。
    5.AMは注文履歴ページが開くと、注文履歴を取得する。
    6.AMは、取得した注文履歴を表示(または保存)する。
    7.AMは、注文履歴が収集できると、AmazonのWebサイトからログアウトする。
　
■なぜこのサービスを作りたいのか？
　便利さからAmazonを利用する人は年々増えており、自分も生活の一部と言っていいほどに活用させていただいている。しかし、そのあまりの便利さ故に毎月の支出の元になっているのもまた事実である。そこで、毎月の利用額を瞬時に把握できるサービスを作成することで、無駄な出費を減らせるのではないかと考えた。

■クラス図

[![Image from Gyazo](https://i.gyazo.com/ac3d09b89e3c823d818ca0125ef2cef3.png)](https://gyazo.com/ac3d09b89e3c823d818ca0125ef2cef3)