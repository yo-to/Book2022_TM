# 第5章の Column関連の補足
## Teachable Machine とデバイスを連携させる
書籍の P186 で、Teachable Machine とデバイスを連携させる際に活用できる API や通信の仕組みなどについて記載しました。  
書籍内ではキーワードに触れたのみだったため、一部のものについて情報を補足します。

### ブラウザで利用可能なデバイス系の API
対応ブラウザが限定される API になりますが（※ 基本的に Chrome系のブラウザとなる）、書籍内でも書いていた以下の API を利用することで、Bluetooth による無線接続や有線でのシリアル通信を用いて、外部デバイスとの連携を実現できます。

- Web Bluetooth API
- Web Serial API

それらに関する日本語の記事を探す場合は、Google検索で「"web bluetooth api"」や「"web serial api"」を検索キーワードにして、「検索オプションの、言語指定を日本語に設定」ということをやると、日本語で書かれた記事を探すことができます。

#### 著者の書いた記事
著者自身が日本語で書いた記事もあり、基本的に　Qiita に書いているので、雑多な感じになりますが以下の検索結果のリンクからご覧いただけます。

- [Qiita で「web bluetooth api」で検索（著者指定：youtoy）](https://qiita.com/search?sort=&q=web+bluetooth+api+user%3Ayoutoy)
- [Qiita で「web serial api」で検索（著者指定：youtoy）](https://qiita.com/search?q=web+serial+api+user%3Ayoutoy)
## TensorFlow.js を使った仕組みの中のオススメの 1つ：「MediaPipe」
書籍の P187 で、TensorFlow.js が活用されている仕組みという点が Teachable Machine と共通である、Google さんが提供している「MediaPipe」について記載しました。  
書籍内では非常に簡単な説明を記載していただけだったため、情報を補足します。

### 公式ページ関連の URL
以下の公式ページは英語ページのみですが、「トップページ」・「Getting Started ＞ MediaPipe in JavaScript からリンクされている体験用ページ」は、英語の記載はあまり気にせずに、アニメーション画像を見ていただいたりリンク先で動作を試したりということができるものです。

- [MediaPipe の公式ページ：トップ](https://google.github.io/mediapipe/)
   - 「ML solutions in MediaPipe」という部分を見ると、アニメーション画像で MediaPipe で処理できる内容を見ることができます。なお、JavaScript版が対応しているのは、そこで掲載されているもののうちの一部になります。
- [MediaPipe の公式ページ： Getting Started ＞ MediaPipe in JavaScript](https://google.github.io/mediapipe/getting_started/javascript.html)
   - 「Ready-to-use JavaScript Solutions」という部分を見ると、表形式で情報が記載されています。その表の中の「Example」の下にあるリンクは、自身のブラウザ上で JavaScript版MediaPipe を実際に試せるページを開くことができます。
- [MediaPipe の公式ページ： Getting Started](https://google.github.io/mediapipe/getting_started/getting_started.html)
   - JavaScript版を含め、Android・iOS・Python・C++ といった環境・言語で利用する場合に参照するページなどが集まっています。

### 非公式の情報：日本語の情報
日本語の情報でまとまったものはなさそうなのですが、Google検索で「"mediapipe" "javascript"」をキーワードにして、「検索オプションの、言語指定を日本語に設定」ということをやると、日本語で書かれた記事を探すことができます。

#### 著者の書いた記事
なお、著者自身が日本語で書いた記事もあり、そのいくつかを掲載します。

- [【Processing 2021】 #p5js で #MediaPipe （JavaScript版）を使った高精度な認識を利用する - Qiita](
　)https://qiita.com/youtoy/items/70571c7066d41729c2bd)
- [某アニメの悪役が使う「とっておきの手品」っぽい呪文が使えた気になる（かもしれない）Webアプリを作った話【技術概要】](https://zenn.dev/youtoy/articles/8900adadd996caf643a5)
