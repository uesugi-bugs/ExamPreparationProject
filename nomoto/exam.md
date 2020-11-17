# テスト問題
### Unix問題
### 問題01
今いる場所の隠しファイルを表示するコマンドはどれか？
1. ls 
1. ls-li
1. ls-la
1. ls-lt
### 問題02
一つ前にいた場所に戻るコマンドはどれか？
1. cd ..
1. cd -
1. cd
1. cd ~
### 問題03
今いる場所にlessonというフォルダを作成するコマンドはどれか？
1. mv lesson
1. rm lesson
1. mkdir lesson
1. cp lesson
### 問題04
今いる場所にあるfile1.txtをfile2.txtという名前に変更するコマンドはどれか？
1. rm file1.txt file2.txt
1. rm file2.txt file1.txt
1. mv file2.txt file1.txt 
1. mv file1.txt file2.txt
### 問題05
今いる場所にあるfile1.txtの中身を確認するコマンドはどれか？
1. echo file.txt
1. cat file.txt
1. cat "file.txt"
1. echo "file.txt"
### vimtutor問題
### 問題06
カーソルを一つ左に移動するコマンドはどれか？
1. j
1. h
1. k
1. l
### 問題07
保存して終了するコマンドはどれか？
1. p!
1. pw
1. :p!
1. :wq
### 問題08
カーソルの位置から二つの単語を削除するコマンドはどれか？
1. 2x
1. 2d
1. 2dw
1. 2e
### 問題09
カーソルの位置から行末まで削除し挿入するコマンドはどれか？
1. d$
1. c$
1. A$
1. A
### 問題10
10行目までカーソルを移動するコマンドはどれか？
1. 10dd
1. 10yy
1. 10G
1. 10D
### git問題
### 問題11
gitの管理下に置くコマンドはどれか？
1. git push
1. git pull
1. git clone
1. git init
### 問題12
最初のコミットと現在の作業フォルダの差分を表示するコマンドはどれか？
1. git status
1. git diff
1. git log
1. git graph
### 問題13
test.txtをステージングエリアにあげるコマンドはどれか？
1. git commit -m"test.txt"
1. git Status 
1. git add test.txt
1. git add
### 問題14
devというブランチの修正をmasterブランチに取り込むコマンドはどれか？
1. git checkout master
1. git branch dev
1. git merge dev
1. git branch -b master
### 問題15
リモートリポジトリのパスを確認するコマンドはどれか？
1. git remote -v
1. git pull origin master
1. git push
1. git push -u origin master
### html問題
### 問題16
連番リストを作るタグの組み合わせとして正しいのはどれか？
1. li, ul
1. dl, li
1. li, ol
1. dl, dd
### 問題17
リンク先をブラウザの別タブで開くためにaタグにつける属性はどれか？
1. tab
1. target
1. src
1. origin
### 問題18
サイト内のナビゲーションメニューを示すのに適切なタグはどれか？
1. navigation
1. navigator
1. nav
1. navi
### 問題19
文書のメインコンテンツとあまり関係のない箇所を示すためのタグはどれか？
1. sidebar
1. side 
1. aside
1. dsub
### css問題
### 問題20
要素の下に線を引くことができるプロパティはどれか？
1. border-line
1. border-down
1. border-bottom
1. border-below
### 問題21
要素を非表示にするための宣言は次のどれか？
1. display: hidden;
1. display: none;
1. display: opacity;
1. display: transparent;
### 問題22
box-sizing: border-box;について正しい記述はどれか？
1. widthにpaddingは含まれるがborderは含まれない。
1. widthにpaddingもborderも含まれない。
1. widthにpaddingもborderも含まれる。
1. widthにborderは含まれるがpaddingは含まれない。
### 問題23
リンクの下線を消すためのプロパティは何か？
1. link
1. text-decoration
1. text-align
1. underline
### 問題24
文字の間隔を指定するためのプロパティはどれか？
1. letter-space
1. letter-spacing
1. letter-lead
1. letter-leading
### 問題25
box-shadow:1px 2px 3px 4px #888;の4pxの値はどの値か？
1. 左の向き
1. 右の向き
1. 広がり
1. ぼかし
### java問題
### 問題26
-128から127の整数を格納するのに適した型はどれか？
1. short
1. int
1. float
1. byte
### 問題27
少しあいまいでもよい小数点を格納するのに適した型はどれか？
1. byte
1. boolean
1. double
1. float
### 問題28
javaでプログラムを開発するために必要なソフトはどれか？
1. バイトコードとソースコード
1. コンパイラとソースコード
1. コンパイラとインタプリタ
1. インタプリタとバイトコード
### 問題29
次のソースコードで間違っているものはどれか？
1. int a = 3;
1. int a; 
1. int = a;
1. a = 3;
### 問題30
'真'を格納するのに適した型はどれか？
1. String
1. boolean
1. char
1. true
### 問題31
yが15になる演算はどれか？
1. x==3; y=x*(2+3);
1. x=3;  y=x*2+3;
1. x=3;  y=x*(2+3);
1. x=3;  x+=3; y=x*2+2; 
### 問題32
次の演算で間違っているものはどれか？
double d = 8.5/2;
int i = 8.5/2;
long l = 8 + 2L;
int j = 8 + 2;
### 問題33
改行して文字を表示する命令文はどれか？
1. System.out.print("改行");
1. System.out.printf("改行%d");
1. System.out.println("改行");
1. System.out.print("改行%n");
### 問題34
5と10の数字を比較して大きい方の数値をint numに代入する命令文はどれか？
1. int num = 5&lt;10;
1. int num = Math.max(5, 10);
1. int num = math.max(5, 10);
1. int num = 5&lt;
乱数をint rumに代入する命令文はどれか？
1. int rum = new java.util.Scanner(System.in).nextInt();
1. int rum = new java.util.Arrays.toString();
1. int rum = new java Random().nextInt();
1. int rum = new java Random().nextLine();
### 問題36
次の中で文法として間違っているものはどれか？
1. double d = 2.0F;
1. String s = 2+"人目";
1. double d = true;
1. short s = (byte)2;
### 問題37
「xが5より小さく、かつ2より大きい」条件式はどれか？
1. x&lt;5 || 2<x
1. x&lt;5 && 2<x
1. 2<x , x<5
1. x==2<5
### 問題38
次の式のうち、条件式として適切なものはどれか？
1. age !=30
1. true
1. b+5&lt;20
1. isNumeric =true
### 問題39
switch文の条件式として正しいものはどれか？
1. switch(fortune == 1)
1. switch(fortune)
1. switch(fortune = 1)
1. switch(fortune &lt;= 1)
### 問題40
swich文で処理を中断してswich文を抜けさせるときの指示は？
1. else;
1. stop;
1. break;
1. case;
### 問題41
実行してから条件式を評価する制御構文はどれか？
1. do-while構文
1. if else構文
1. switch文
1. while構文
### 問題42
for文の条件式として正しものはどれか？
1. for(int i=0 ; i<10 ;i++)
1. for(int i==0)
1. for(i==0)
1. for(i)
### 問題43
for文やwhile文を用いた繰り返しの途中で、今回の周だけを中断し次の周へ進む中断方法の文は？
1. break 
1. continue
1. else
1. do
### 問題44
scores配列の要素数を表示方法として正しいものは？
1. Arrays.toString(scores)
1. scores.length
1. scores[]
1. int[]scores
### 問題45
scores配列の3番目の要素を表示する方法として正しいものは？
1. System.out.print(scores[3]);
1. System.out.print(scores[2]);
1. System.out.print(scores{3});
1. System.out.print(scores{2});
### 問題46

1.
1.
1.
1.
### 問題47
1.
1.
1.
1.
### 問題48
1.
1.
1.
1.
### 問題49
1.
1.
1.
1.
### 問題50
1.
1.
1.
1.

