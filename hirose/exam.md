# Unix
1. 現在の場所にどのようなファイルやディレクトリがあるのか確認するコマンドを書け
2. フォルダを作成するときに使うコマンドを書け
3. フォルダ内を移動する際、一つ上の階層に戻るコマンドは次のうちどれか
	1. cd //
	1. cd ..
	1. cd -
4. ファイルの中にテキストを書き込む場合のコマンドは次のうちどれか
	1. echo
	1. write
	1. cat
5. ファイルの名前を書き替えたいときのコマンドとして合っているものは次のうちどれか
	1. rm file1.txt file2.txt
	1. rn file1.txt file2.txt
	1. mv file1.txt file2.txt
	1. rm -r file2.txt
---
# vim
1. vimの操作において、正しいものは次のうちどれか
	1. 左に移動:L　下に移動:K　上に移動:J　右に移動:H
	1. 左に移動:H　下に移動:J　上に移動:K　右に移動:L
	1. 左に移動:L　下に移動:J　上に移動:K　右に移動:H
	1. 左に移動:H　下に移動:J　上に移動:L　右に移動:K
2. 現在の箇所から行末までを削除したいとき使うコマンドは次のうちどれか
	1. dd
	1. dw
	1. de
	1. d$
3. 書かれている数字を３大きくしたいとき使うコマンドは次のうちどれか
	1. 3 ctrl+A
	1. 3 ctrl+X
	1. 3 shift+A
	1. 3 shift+X
4. 15行目の文頭に移動したいとき使うコマンドは次のうちどれか
	1. 15gg
	1. 15g
	1. 15ll
5. 保存せずに終了するとき使うコマンドは次のうちどれか
	1. :wq
	1. :w!
	1. :set nu
	1. :q!
---
# Git
1. Gitをコミットする時のコマンドとして正しいのは次のうちどれか
	1. git commit -m"メッセージを入力"
	1. git add .
	1. git commit m"メッセージを入力"
2. devブランチを作りつmasterブランチから移動したいときのコマンドとして正しいのは次のうちどれか
	1. git branch -b dev
	1. git checkout -b dev
	1. git branch -d dev
	1. git checkout -d dev
3. 現在workブランチにいてGitHubにコミットしたファイルを送りたい時のコマンドとして正しいのは次のうちどれか
	1. git push -u origin master
	1. git add -u origin master
	1. git push -u origin work
	1. git add -u origin work
---
# html&css
1. CSSファイルを読み込むタグとして正しものはどれか？
	1. &lt;link rel="css" href="styles.css"&gt;
	1. &lt;link rel="stylesheet" href="styles.css"&gt;
	1. &lt;link rel="css" location="styles.css"&gt;
	1. &lt;link rel="stylesheet" location="styles.css"&gt;
2. 画像を表示するタグで、ファイル名を指定するための属性はどれか？
	1. file
	1. src
	1. href
	1. scr
3. 連番リストを作るタグの組み合わせとして正しいのはどれか？
	1. li, ul
	1. dl, li
	1. li, ol
	1. dl, dd
4. 説明リストを作るためのタグの組み合わせとして正しいのはどれか？
	1. dm, dl, dt
	1. dh, td, dt
	1. dd, dl, dt
	1. dd, dl, dh
5. 次のUI部品を表示するためのタグはどれか？（画像はChromeでの表示です）
![Q5](https://joytas.net/202010/htmllesson/img/ex37.png)
	1. &lt;input type="text"&gt;
	1. &lt;input type="radio"&gt;
	1. &lt;input type="checkbox"&gt;
	1. &lt;textarea&gt;
6. CSSは何の略か？
	1. Combining Style Sheets
	1. Community Style Sheets
	1. Corporate Style Sheets
	1. Cascading Style Sheets
7. padding: 10px 20px 30px;と指定されたとき、左側のpaddingはどれか？
	1. 10px
	1. 20px
	1. 30px
	1. 上記のどれでもない。
8. ボックスモデルに関する次の記述で正しいものはどれか？
	1. marginの外側にborderがある。
	1. marginとpaddingは同じ意味である。
	1. paddingよりmarginの方が外側にある。
	1. borderの外側にpaddingがある。
9. 次のCSSの色指定において1つだけ異なる色はどれか？
	1. red
	1. #f00
	1. rgb(0, 255, 0)
	1. #ff0000
10. 次のようなファイル構成だったときに、要素の背景にimgフォルダの中のbg.pngを指定したい。cssフォルダ内のstyles.cssにはなんと記述するべきか？
![Q10](https://joytas.net/202010/csslesson/img/ex34.png)
	1. background: url(../img/bg.png)
	1. background: url(../bg.png)
	1. background: url(img/bg.png)
	1. background: url(../css/img/bg.png)
---
# java
1. "Hello World" と出力するプログラムを書け（ファイル名はHelloとする）
2. プログラムで"15" と出力したい時、次のうち間違っているテキストはどれか
	1. System.out.println("15");
	1. System.out.println("%d",45/3);
	1. System.out.print(55%20);
	1. System.out.printf("%d%n",20-5);
3. 次のうち、解が異なる計算式はどれか
	1. 8/2+1
	1. 12%7
	1. 1+4&lowast;3
	1. 18/3-1
4. 次のうち、文法として正しいのはどれか
	1. int x=3+5.0;
	1. String s=2+"人目";
	1. int number="5";
	1. double d=true;
5. 次のプログラムコードをコンパイルした時、エラーになった。どこを直せばよいか述べよ（例：〇〇行目の×××を△△△に直す）
```java:Fortune.java
public class Fortune{
	public static void main(String[] args){
		boolean tenki = true;
		if (tenki=true){
			System.out.println("洗濯にいきます");
			System.out.println("散歩にいきます");
		}else{
			System.out.println("DVDを見ます");
		}
	}
}
```
6. 次のうち、条件式として正しいのはどれか。
	1. 3
	1. isNumeric=true
	1. true
	1. cost=300/15

