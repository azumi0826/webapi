# ①課題番号-プロダクト名
旅行計画

## ②課題内容（どんな作品か）
- 地名で検索し、周辺の観光スポットを取得→自動で移動時間と距離を算出


## ③DEMO
(https://yellow31.sakura.ne.jp/webapi/travel_map.html)


## ⑤工夫した点・こだわった点
- 実際に旅行する際の計画立ての順序を考えて作成できた
- スポットの並べ替えができるようにした
- Geocoding API,Maps JavaScript API,Places API,Distance Matrix APIを用いた

## ⑥難しかった点・次回トライしたいこと(又は機能)
<難しかった>
 - スポットの個別削除や、評価による自動選別ができるようにしたい
 - 作成した旅程を共有や保存できる仕組みを作りたい
 - AIと連携させ、旅程表の提案ができるようにしてみたい
 - 移動手段（徒歩、電車、車etc）mo選択できるように（一律で車になってしまっている）
 

## ⑦質問・疑問・感想、シェアしたいこと等なんでも

- [質問]
- [感想]
- マップが表示されず、エラーの解消に時間がかかったが、マップを表示する要素のサイズがCSSで設定できていないだけだった。
- <解決> デプロイ後CSSファイルが読み込まれないエラーとなった。CSSファイルのパスの記載で"."が不足していた。※ローカルでは問題なく動いてしまったので気が付けなった。
 
- [参考記事]
  - 1. Google Maps API [https://qiita.com/Haruka-Ogawa/items/997401a2edcd20e61037]
  - 2. APIエラー[https://qiita.com/yoshiwo/items/0b4a84d2413a87218139]
  - 3. GoogleMapsPlatform[https://developers.google.com/maps/documentation/javascript/local-context/start?hl=ja]
  - 4. [https://plantprogramer.com/travel_brochure/#google_vignette] 
  - 5. [https://qiita.com/murakamixi/items/4c427972ca54ffa19bd5]

