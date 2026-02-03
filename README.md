## Offline Score Board
父が持っていた [**初代 iPad**](https://ja.wikipedia.org/wiki/IPad_(%E7%AC%AC1%E4%B8%96%E4%BB%A3)) でオフライン動作するように開発した Web アプリ。
父に「この iPad になんとかしてスコアボードアプリを入れられないか」と頼まれたのがきっかけ。
Safari 5 で動作するように開発。
CSS grid はもちろん flex すら使えない環境向けに開発するのは自分にとっては新鮮だった。

### 特徴
- モダンな技術がほぼ使えない環境向けに開発。
- どこで引っかかるかわからず不安だったのでビルドツール等は使わず html ファイルにそのまま全てベタ書き。
- オフライン動作に対応させる必要があったが、当時 ServiceWorker は無かったようなので代わりに [HTML5 Application Cache](https://en.wikipedia.org/wiki/Cache_manifest_in_HTML5) という機能を使用。

### 結果
満足してもらえた。
が、流石に iPad が古すぎて電池が全然持たないということでほぼ使われず。ぴえん。
