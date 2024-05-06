# ①課題番号-プロダクト名

01-じゃんけんアプリ

## ②課題内容（どんな作品か）

①じゃんけんアプリ
- 課題のじゃんけんアプリをUIデザインを変更したものです。
- レスポンシブにも対応するため、ボタンは下に、結果は上に変更しました。
- じゃんけんの手は文字ではなく画像にしました。

②相方マッチングゲーム
- 吉本の漫才師の方をクリックを押すことでボケ担当・ツッコミ担当でシャッフルしてランダム表示します。
- 実際の正しいコンビになったら、①コンビ名を表示　②紙吹雪　③盛り上がっている観客の画像を表示　④歓声の音声が鳴る　ようにしました。
- 吹き出しは実際の漫才のワードです。正しいコンビになったら正しいやり取りになります。（誤ったコンビでも会話は成り立つ場合もあります笑）
- リセットボタンは画面のリロードになります。
- 漫才師さんの画像は吉本興業の宣材写真を利用、他は画像・音声ともにフリー素材を利用しています。

- また、①と②の入口となる画面も用意しました。

## ③DEMO

- [入口のURL](https://chisaxworks.github.io/gs_kadai01_janken/)
- [①じゃんけんアプリのURL](https://chisaxworks.github.io/gs_kadai01_janken/janken.html)
- [②相方マッチングゲームのURL](https://chisaxworks.github.io/gs_kadai01_janken/owarai.html)

## ④作ったアプリケーション用のIDまたはPasswordがある場合

- 今回は無し

## ⑤工夫した点・こだわった点

相方マッチングゲームの工夫点について記載します。
- 今回はアイデアを考えた時点で、写真を出す、セリフを表示する、マッチした時の効果（紙吹雪を出す、音を出す、観客が盛り上がっている）を出したいと考えそれに合う内容にしました。
- 頭の中のイメージに合うように、幸い背景画像はイメージ通りのものがあったのでそれに合うよう、紙吹雪の色や位置の調整などしました。
- ゲームとしてスクロールはさせたくなかったので、1画面に収まるように幅感調整したのは工夫しました。

## ⑥難しかった点・次回トライしたいこと(又は機能)

苦労した点
- 工夫点の1画面に収める調整の点は時間のかかった点でもあります。
- 紙吹雪はライブラリを使っていますが、jQueryではないことと、解説ページが日本語は多少古かったりなどもあったので少し苦労しました。
- マッチした時の動きの記載については、分岐に全部書くと長くなるので、別でfunction名をつけて切り出して、そのfunctionを呼び出す記述にすることで重複記述を減らしました。

トライしたいこと
- 点数表示にしてもいいかなとは思いました

## ⑦質問・疑問・感想、シェアしたいこと等なんでも

- 参考記事
  - 1. [紙吹雪：Canvas Confetti](https://www.kirilv.com/canvas-confetti/)
  - 2. [音声を入れる](https://jp-seemore.com/web/3576/)
  - 3. [タイピング風テキスト](https://coco-factory.jp/ugokuweb/move02/8-10/)
   
- Special Thanks to 吉本興業様
