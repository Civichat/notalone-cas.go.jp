
# notalone-cas.go.jp
内閣府官房 孤独・孤立対策担当室が公開した https://notalone-cas.go.jp/ の情報を抽出したもの

## これは何
- 内閣府官房 孤独・孤立対策室が公開したサービス（2021/11/18現在はベータ版とのこと）のチャットボットから得られるデータを収集したものです
- [![Image from Gyazo](https://i.gyazo.com/30be008050e49609bdad717491c36a3c.jpg)](https://gyazo.com/30be008050e49609bdad717491c36a3c)
- こちらのデータに関しては[Spread sheet](https://docs.google.com/spreadsheets/d/19iNsXh2RY38omXCfCN_pbp7XBdeMy5TF07lTrzxiRaY/edit?usp=sharing)にまとめました
	- チャットボットによる「探索」のデータは集め方が難しく、今回のような方法になっています
	- 何かいい方法あれば教えてください

## ファイル構成について
- 基本的にこのリポジトリはデータを抽出しただけです
- その結果はSpread sheetに保存してあります
	- しかし、チャットボットにより推薦されるデータの形をSpread sheetに落とし込むことは難しかったです
	- なので、「公的制度のみ」を抽出したデータを[こちらのSpread sheet](https://docs.google.com/spreadsheets/d/1oC0SS0gzlQYe7yYcw3CUxYeia6sb5LzNWNDDF7oV3Fk/edit#gid=1429606858)においておきます
	- 同様のファイルを`data.csv`とし、[こちら](https://github.com/Civichat/notalone-cas.go.jp/blob/master/data.csv)にもコミットしておきます

```
├── LICENCE
├── README.md
└── data.csv
```

## data.csvの構成について
- このデータのフォーマットは、CPSV-Jという規格と互換性があります
- CPSVの概要については、内閣府官房 政府CIO上席補佐官 平本さんの資料を参照ください
	- https://docs.google.com/presentation/d/1WWESTNDG-Z6NhY6JcZc49uR4YkXv3Bbn/edit?rtpof=true&sd=tru
- 関連: [公共制度の機械可読フォーマットまとめ](https://scrapbox.io/c4j/%E5%85%AC%E5%85%B1%E5%88%B6%E5%BA%A6%E3%81%AE%E6%A9%9F%E6%A2%B0%E5%8F%AF%E8%AA%AD%E3%83%95%E3%82%A9%E3%83%BC%E3%83%9E%E3%83%83%E3%83%88%E3%81%BE%E3%81%A8%E3%82%81)
## こちらの引用について
以下、同サービスの利用規約である [https://notalone-cas.go.jp/terms](https://notalone-cas.go.jp/terms/) から引用

> 当ウェブサイトのコンテンツの利用について
> 当ウェブサイトで公開している情報（以下「コンテンツ」といいます。）は、どなたでも以下の１）～６）に従って、複製、公衆送信、翻訳・変形等の翻案等、自由に利用できます。商用利用も可能です。また、数値データ、簡単な表・グラフ等は著作権の対象ではありませんので、これらについては本利用ルールの適用はなく、自由に利用できます。

> イ．本利用ルールは、平成28年1月27日に定めたものです。本利用ルールは、政府標準利用規約（第 2.0 版）に準拠しています。本利用ルールは、今後変更される可能性があります。既に政府標準利用規約の以前の版にしたがってコンテンツを利用している場合は、引き続きその条件が適用されます。
> ウ．本利用ルールは、クリエイティブ・コモンズ・ライセンスの表示 4.0 国際（ https://creativecommons.org/licenses/by/4.0/legalcode.ja ）に規定される著作権利用許諾条件。以下「CC BY」といいます。）と互換性があり、本利用ルールが適用されるコンテンツはCC BYに従うことでも利用することができます。

これらの記述により、データをSpread sheetにまとめています。`LICENCE`についても[CC BY](https://creativecommons.org/licenses/by/4.0/legalcode.txt)を踏襲してあります

## なぜこれをしたか
- データを公開して欲しかったからです
[![Image from Gyazo](https://i.gyazo.com/d301ac69845a24a64f128a76de397d12.png)](https://gyazo.com/d301ac69845a24a64f128a76de397d12)


## コミットした人間は誰か
- 高木俊輔（Shunsuke Takagi）です
	- [twitter.com/tkgshn](https://twitter.com/tkgshn)
- [株式会社Civichat](https://civichat.jp)という会社を経営しています
- [包摂研究会](https://tkgshn.github.io/projpoverty/)という活動の一環です
