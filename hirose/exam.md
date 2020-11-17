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
	1. 15G
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
4. xに12、yに18を代入し"x+y=30"と出力したく以下のプログラムを書いたが、思う通りな結果を得ることはできなかった。どこを直せばよいか述べよ（例：〇〇行目の×××を△△△に直す）
```java:Q4.java
public class Main{
	public static void main(String[] args){
		int x=12;
		int y=18;
		System.out.println("x+y="+x+y);
	}
}
```
5. 次のうち、文法として正しいのはどれか
	1. int x=3+5.0;
	1. String s=2+"人目";
	1. int number="5";
	1. double d=true;
6. 次のプログラムコードをコンパイルした時、エラーになった。どこを直せばよいか述べよ（例：〇〇行目の×××を△△△に直す）
```java:Q6.java
public class Dice{
	public static void main(String[] args){
		int scoreA=new java.util.Random().nextInt(6)+1;
		int scoreB=new java.util.Random().nextInt(6)+1;
		if (scoreA=scoreB){
			System.out.println("あいこ");
		}else if(scoreA>scoreB){
			System.out.println("Aの勝ち");
		}else{
			System.out.println("Bの勝ち");
		}
	}
}
```
7. 次のうち、条件式として正しいのはどれか。
	1. 3
	1. "false"
	1. true
	1. cost=300/15
8. 以下の文を読み、括弧の中に入る数字を答えよ
`int[] nums={10,20,30,40} という配分の要素数は( )であり、10は( )番目の要素に入っている`
9. 以下のようなプログラムが組まれているとき、どのような結果が出力されるか。次のうち正しい組み合わせを答えよ
```java:Q9.java
public class Main{
	public static void main(String[] args){
		int[][] scores={{40,50,60},{80,60,70}};
		System.out.println(scores.length);
		System.out.println(scores[0].length):
	}
}
```
	1. 1行目:2 2行目:3
	1. 1行目:2 2行目:[40,50,60]
	1. 1行目:[[40,50,60],[80,60,70]] 2行目:[40,50,60]
	1. 1行目:[[40,50,60],[80,60,70]] 2行目:3
10. 次のプログラムを実行したときどのような結果が出力されるか述べよ
```java:Q10.java
public class Main{
	publis static void main(String[] args){
		int x=5;
		int y=3;
		for (int i=0;i<8;i++){
			x+=y;
		}
		System.out.println(x);
	}
}
```
11. 次のプログラムを実行したときどのような結果が出力されるか述べよ
```java:Q11.java
public class Main{
	public static void main(String[] args){
		for (int i=0;i<5;i++){
			for (int j=0;j<5;j++){
				if (i+j+1<5){
					System.out.print();
				}else{
					System.out.print("A");
				}
			}
			System.out.println();
		}
	}
}
```
12. 次のプログラムを実行したときどのような結果が出力されるか述べよ
```java:Q12.java
public class Main{
	public static void main(String[] args){
		int[] nums={56,39,3,98,47};
		for (int i=0;i<nums.length;i++){
			for (int j=i+1;j<nums.length;j++){
				if(nums[i]<nums[j]){
					int temp=nums[i];
					nums[i]=nums[j];
					nums[j]=temp;
				}
			}
		}
		System.out.println(Arrays.toString(nums));
	}
}
```
13. 次のプログラムを実行したとき"data&#91;3&#93;&#91;8&#93;"にはどのような数が入っているか答えよ
```java:Q13.java
public class Main{
	public static void main(String[] args){
		int[][] data=new int[9][9];
		for (int i=0;i<data.length;i++){
			for (int j=0;j<data[i].length;j++){
				data[i][j]=(i+1)+(j+1);
			}
		}
	}
}
```
13. 次のようなプログラムを組み、九九の表を出力したが列がズレてしまい失敗例のように出力された。成功例のようにきれいに揃えるにはどこを直せばよいか答えよ（例：〇〇行目の×××を△△△に直す）
```java:Q13.java
import java.util.*;
public class Main{
	public static void main(String[] args){
		int[][] nums=new int[9][9];
		for(int i=0;i<nums.length;i++){
			for(int j=0;j<nums[i].length;j++){
				nums[i][j]=(i+1)*(j+1);
			}
		}
		for(int i=0;i<nums.length;i++){
			for(int j=0;j<nums[i].length;j++){
					System.out.printf("%d",nums[i][j]);
			}
			System.out.println();
		}
	}
}
```
```
失敗例
123456789
24681012141618
369121518212427
4812162024283236
51015202530354045
61218243036424854
71421283542495663
81624324048566472
91827364554637281
```
```
成功例
  1  2  3  4  5  6  7  8  9
  2  4  6  8 10 12 14 16 18
  3  6  9 12 15 18 21 24 27
  4  8 12 16 20 24 28 32 36
  5 10 15 20 25 30 35 40 45
  6 12 18 24 30 36 42 48 54
  7 14 21 28 35 42 49 56 63
  8 16 24 32 40 48 56 64 72
  9 18 27 36 45 54 63 72 81
```
