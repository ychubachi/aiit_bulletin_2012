aiit_bulletin_2012
==================

# はじめに
このファイルはAIITの紀要のフォーマットを実験的に実装しているものです．

- ベースのクラスにjsarticleを利用しています
  - 本文の文字9ptがデフォルトで利用できること
  - \sectionのフォントがサンセリフ体になり、配置も2行の中央に配置され美しい
  - \sectionの番号はjsarticleのデフォルト（ピリオドなし）のままです
  - \captionの番号はjsarticleのデフォルト（コロンなし）のままです
  - 参考文献の標題はjsarticleのデフォルト（センタリングなし）のままです
- aiitbulletinスタイルでやっていること
  - geometryパッケージを用いてマージンなどを設定
  - \maketitleのオーバーライドなど
  
# TODO 
- maketitleについて
  - 英語のtitleのthanksを共有するなど，jpsjスタイルを取り入れたいな
    - そうでなかったら，thanksの番号を1番から参照できるようにしたい
  - と思ったけどめんどくさいので、従来形式でもよいかしら。（\thanksを使わない）
