「WebMail Notifier( http://dreamcheeky.com/webmail-notifier )」という新着メールを光ってお知らせしてくれる製品を、
好き勝手に点灯させるためのプログラムです。



https://github.com/ashel/webmailwindow
からForkさせていただきました。

どうやら複数バージョン出回っているらしく、
新しい製品ではうまく動かなかったため、動くように改造しました。
(新製品では色の明るさが制御できるようになったため、通信内容が変わっているようです。)

使い方は本家と同じです。

% webmailwindow.exe -c [r|g|b|rg|rb|gb|rgb|none]


■ビルドの仕方

1. 「Windows Driver Kit Version 7.1.0」をダウンロード&インストールします。
https://www.microsoft.com/en-us/download/details.aspx?id=11800

2. スタートメニューを開き、全てのプログラムの中から「Windows Driver Kits - x86 Free Build Environment」を選びます。
　するとコマンドプロンプトが開きます。

3. コマンドプロンプトが開くので、プロジェクトルートディレクトリまで移動します。
　cd {～\webmailwindow}

4. 「build」と打ちます。
　成功すればプロジェクトルート直下に生成された「objfre_wxp_x86」というようなディレクトリの中に「webmailwindow.exe」が出来上がります。

5. あとは「webmailwindow.exe」を好きなところへ持って行き、コマンドプロンプトで実行してください。


■ライセンス
distributed with MIT license.
