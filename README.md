# mastodon-dqxpresence

Mastodon の表示名に現在の職業とレベルを反映する Python スクリプト

## 設定ファイル .dqxpresence

ホームディレクトリに設置します。

```
{
    "id": 667538238772,
    "namebase": "おるどら",
    "mastodon_client": "<クライアントキー>",
    "mastodon_secret": "<クライアントシークレット>",
    "mastodon_token": "<アクセストークン>",
    "mastodon_instance": "https://foresdon.jp"
}
```

id はマイページのソースを表示して `meta property="og:url"` のところに記述されている数字です。

```
	<meta property="og:url" content="https://hiroba.dqx.jp/sc/character/667538238772/"></meta>
```

また、マイページ全体の公開設定を『制限なしで公開』にしてください。

## ステータスファイル .mpresence

ホームディレクトリに作成されます。
