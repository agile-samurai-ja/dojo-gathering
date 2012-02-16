============
jekyll
============

jekyllで静的ページを生成するようにしました。
jekyllディレクトリ以下にソースが含まれています。
_layout/default.html がレイアウトファイル
その他のhtmlが各ページのソースです。

ページ生成方法
====================

::

  $ cd jekyll
  $ jekyll ../2012

以上で、2012ディレクトリ以下に静的HTMLが生成されます。

jekyllのインストール
====================

  $ gem install jekyll

以上でインストールできるはず。

動作確認
====================

  $ jekyll --server

以上で簡易HTTPサーバが http://localhost:4000/ あたりに立ち上がります。
手元のブラウザで表示確認ができるはずです。

============
本番用のURL
============

http://agile-samurai-ja.github.com/dojo-gathering


============
確認用のURL
============
http://shintaro.kakutani.com/dojo-gathering/

(認証はかけてないので見えちゃうけど、ソースはprivate repoにあります。作業用。
ちょっとやってみたけど、gh-pages じゃないブランチで作業すれば良いだけかもなあ)

http://shintaro.kakutani.com/dojo-gathering/2012/
フォルダ名01にすべきかもだけど、とりあえず2012で…..


