SublimeText3_settings
=====================

Sublime Text settings for Mac OS X.

以下の手順で適用すれば設定を同期できる

<br>

* **Rictyフォントを生成する**

まだMacにRictyがインストールされていない場合は、以下のコマンドで自動生成する

    $ curl -L 'https://gist.github.com/ysaotome/7286145/raw/installing_ricty_on_MacOSX.sh' | bash

> 参考
> 
> Mac OSXに超カッコイイプログラミング用フォント「Ricty」をセットアップする - blog@sotm.jp
> http://blog.sotm.jp/2014/01/10/Installing-SublimeText3-iTerm2-Ricty-on-MacOSX-109/


<br>

* **Package以下のファイルをclone**

ディレクトリ移動

    $ cd ~/Library/Application Support/Sublime Text 3/Packages

元々配置されているファイルはバックアップをとって削除する

あとはcloneすれば動くはず

    $ git clone https://github.com/tokutoku3/SublimeText3_settings.git Packages

---

Package Controlのインストールも忘れない
http://matome.naver.jp/odai/2138657649717812101

