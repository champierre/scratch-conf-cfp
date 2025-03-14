# アクスタをScratch(とSVG->PDF変換ツール)だけでつくる

### 概要
    - InkscapeはUIがややこしくて使いづらい。Scratchのお絵かきツールは誰でも使えるくらい簡単。
            - アクリルスタンドを作るには、1. レーザーカッターで枠や台のカット、2. UVプリンタで絵柄の印刷が必要。これらの元データはSVGファイルを変換してPDFファイルだが、SVGファイルはScratchから書き出すことができる。
            - 画像の読み込み、サイズの調整や位置決め、カットラインの作成、台を描く工程、を Inkscape でおこなう必要があったが、これらをScratchのお絵かきツールでできることがわかった。
            - 拡張機能やmodを使わず、通常のScratchでできる。 
            - Scratchだと、テンプレートをあらかじめ作っておくことができ、共有やスタジオで管理といったScratchの既存の共創に適した機能を利用できる。
            - SVGファイルからPDFファイルに変換するには、[画像マジック](https://champierre.github.io/gazou-magick/) を利用すればよい。これによって全工程をInkscapeなしで済ますことができる。

### 手順
    - Scratchのお絵かきツールでデザインする。
    - ベクターモード（左下に「ビットマップに変換」と表示されていればOK）で線や図形を描く
    - 線の太さを0.02にすると、ストロークサイズは0.01pxになる。(Helixレーザー加工機は 0.095px 以下でカット線になる)
    - [![Image](https://gyazo.com/2b453dc536ab43956640e5fdc34aedfa/max_size/1000)](https://gyazo.com/2b453dc536ab43956640e5fdc34aedfa)
    - コスチュームをコピーし絵柄の部分を削除すれば枠線だけ残せる。
    - [![Image](https://gyazo.com/810e25cd92dc9d76066e27364f889240/max_size/1000)](https://gyazo.com/810e25cd92dc9d76066e27364f889240)
    - コスチュームの「書き出し」を選ぶとSVGファイルとしてダウンロードできる。
    - [![Image](https://gyazo.com/45bd4edc53187ef5cee4744998072c1e/max_size/1000)](https://gyazo.com/45bd4edc53187ef5cee4744998072c1e)
    - 長さの微調整をしたければ、このSVGファイルをInkscapeで開けば良い。
    - [画像マジック](https://scrapbox.io/tukumanalab/%E7%94%BB%E5%83%8F%E3%83%9E%E3%82%B8%E3%83%83%E3%82%AF) ( [https://champierre.github.io/gazou-magick/](https://champierre.github.io/gazou-magick/) ) を開き、SVGファイルをアップロードし、SVG-">>PDF にチェックを入れ、「ダウンロード」ボタンを押せばPDFファイルに変換できる。
    - [![Image](https://gyazo.com/6c272162837f24cf26081d0bb274f10a/max_size/1000)](https://gyazo.com/6c272162837f24cf26081d0bb274f10a)
    - 出来上がり
    - [![Image](https://gyazo.com/fc97394bb909819920887751e297a139/max_size/1000)](https://gyazo.com/fc97394bb909819920887751e297a139)

### 課題
    - 台に刺さる部分の大きさをアクリルの厚さ(5mm)にあわせる方法
→ あらかじめ用意した5mm厚アクリル板の台座部分のコスチュームをコピーして利用する<br>
アクスタ(5mm) [https://scratch.mit.edu/projects/1143556887/editor](https://scratch.mit.edu/projects/1143556887/editor)<br>

    - 「ぺん」ツールを使うと二重カットになる
→ 二重にカットするだけで問題なし<br>
