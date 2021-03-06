---
layout: post.ja
title: 事例紹介 - ちずコレ
---

## 事例紹介 - ちずコレ

[ちずコレ](http://www.chizu-colle.jp/)というスマートフォン向けのアプリケーションでMroongaを使っているとのことなので紹介します。

ちずコレとは：

> 「ちずコレ」は、マップと中部地域の情報を組み合わせて雑誌感覚で楽しめるスマートフォン向け無料アプリです。さまざまなテーマやストーリーに合わせ、180種類を超えるマップから、自分の欲しいマップをコレクションすることで、あらゆるシーンで活用できます。
>
> 検索画面では、「現在地から検索」と「キーワードで検索」の2つの入口から調べることができ、今すぐ知りたい・行きたいというときや、地名・名称などから探したいときに利用いただけます。
>
> 「ちずコレ」は"場所を探すための地図ではなく、目的を見つけるための地図を"をコンセプトに、地図の新しい楽しみ方を提案します。

Mroongaの使い方：

> スマートフォンアプリで掲載情報を検索する際、サーバサイドでMroongaを使って全文検索しています。（検索処理専用のMroongaエンジンのテーブルを別途準備、掲載情報メンテナンスの際はトリガーで同期）
>
> 検索結果は、スマートフォンの位置（GPSによる）に近い情報順とすることで、より近くにある、ユーザが必要としている情報を提供しています。
>
> 今後の情報量次第で、位置情報の処理もMroongaエンジンに移行することを検討しています。

Mroongaを使ってよかった点：

> スマートフォンの苦手としている高速全文検索処理を簡単に実装できたのでMroongaを使ってよかったです。
>
> MySQLの拡張なのでエンジニアにとってはハードルが低いのですが、ユーザには高いサービス品質（速度、精度）を実現できました。

[利用者ページのちずコレのセクション](/ja/users/#chizu-colle) もご覧ください。使うハードルは低くて高いサービス品質を提供できる、というのはMroongaの特徴ですね。MySQLで全文検索を使いたい方はぜひMroongaを使ってみてください。

中部地域の方は一度ちずコレを試してみてください。

Mroongaを利用している方で紹介してもよいという方はぜひgroonga at groonga.orgまでご連絡ください！
