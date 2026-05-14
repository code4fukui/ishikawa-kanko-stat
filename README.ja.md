# ishikawa-kanko-stat

石川県観光アンケートのオープンデータを検索・可視化するWebアプリケーションです。このプロジェクトは[福井県版](https://code4fukui.github.io/fukui-kanko-stat/comment-search.html)をフォークしたものです。

## デモ

- [石川県観光オープンデータ コメント検索](https://code4fukui.github.io/ishikawa-kanko-stat/comment-search.html)

## 機能

コメント検索アプリケーションでは以下のことが可能です：

- **キーワード検索：** アンケートのコメントから特定の語句を検索します。
- **結果のフィルタリング：** 以下の基準でコメントを絞り込みます：
  - エリアおよび施設
  - 訪問者の居住都道府県（例：「県外の方のみ」を表示）
  - センチメント（例：「厳しい意見のみ」を表示）
  - 年代
- **満足度の可視化：** フィルタリングされた結果の満足度をインタラクティブな円グラフで表示します。
- **詳細の閲覧：** 回答日時、満足度スコア、NPS、訪問者の属性など、各コメントのメタデータを確認できます。

## データソース

本アプリケーションは、石川県観光データ分析プラットフォーム「Milli」のオープンデータを利用しています。

- **出典：** [Milli - QRアンケートデータ](https://sites.google.com/view/milli-ishikawa-pref/qr%E3%82%A2%E3%83%B3%E3%82%B1%E3%83%BC%E3%83%88%E3%83%87%E3%83%BC%E3%82%BF)
- **GitHub上の処理済みデータ：** [code4fukui/ishikawa-kanko-survey](https://github.com/code4fukui/ishikawa-kanko-survey)

## ライセンス

MIT License — 詳細は [LICENSE](LICENSE) を参照してください。
