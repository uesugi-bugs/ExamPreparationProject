# Unix
- 配点:10
- 出題範囲:joytas.netの記事
  - [Unixコマンド超入門](https://joytas.net/programming/unix%e3%82%b3%e3%83%9e%e3%83%b3%e3%83%89)
### 予想問題
1. 現在いる場所をフルパスで表示するコマンドは何か  
1. 今いる場所にあるファイルやフォルダの一覧を表示するコマンドは何か  
1. ディレクトリの移動に使うコマンドは何か  
1. ファイルに書き込みするコマンドは何か  
1. ファイルの中身を確認するコマンドは何か  
1. ファイルの移動やファイル名の変更に使うコマンドは何か  
1. file1.txtのコピーをfile2.txtという名前で作成する時のコマンドを記述  
1. sampleという名前のフォルダを削除する際のコマンドを記述  
***
# Vi
- 配点:10
- 出題範囲:Vimtutor
### 予想問題
1. 挿入モードへの移行コマンド  
1. 置換モードへの移行コマンド  
1. 行末で挿入モードを始めるコマンド  
1. 保存せず終了するコマンド  
1. 別のファイル名で保存するコマンド  
1. カーソル下の単語を消して挿入モードに移行するコマンド  
1. 行末まで削除するコマンド  
1. 特定の行まで移動するコマンド  
1. 削除またはヤンクしたものを貼り付けるコマンド  
1. 特定の単語を検索するコマンド  
***
# Git
- 配点:10
- 出題範囲:joytas.netの記事
  - [Git(基本操作)](https://joytas.net/programming/git/basic)
  - [Git(基本操作2)](https://joytas.net/programming/git/basic2)
  - [GitHubとの連携1](https://joytas.net/programming/git/github1)
  - [GitHubとの連携2](https://joytas.net/programming/git/github2)
### 予想問題
1. gitで管理するために初めに実行するコマンド  
1. ファイルをステージングエリアに上げるコマンド  
1. コミットする際のコマンド  
1. 特定のコミット地点まで戻るコマンド  
1. ブランチを確認したり作成したりするコマンド  
1. 別のブランチへ移動するコマンド  
1. 別のブランチでの変更を取り込むコマンド  
1. リモート上のリポジトリのクローンをローカル上に作るコマンド  
1. ローカル上の変更をリモート上に送るコマンド  
1. リモート上の状態をローカル上に取り込むコマンド  
***
# Html&css
- 配点:20
- 出題範囲:過去2回の課題+joytas.netの記事
  - [htmlLesson(週末課題1)](https://joytas.net/202010/htmllesson/)
  - [cssLesson(週末課題2)](https://joytas.net/202010/csslesson/)
  - [Webサイト制作(basic960site)](https://joytas.net/programming/website/webbasic)
### 予想問題
1. 文書宣言のタグとして正しいのはどれか？  
1. CSSファイルを読み込むタグとして正しいのはどれか？  
1. 空白の実体参照はどれか？  
1. 表を表現するためのタグの組み合わせとして正しいのはどれか？  
1. 複数の選択肢をいくつでも選べるように表示させるタグはどれか？  
1. 文字色を指定するためのプロパティはどれか？  
1. ボックスモデルに関する次の記述で正しいものはどれか？  
1. padding: 10px 20px 30px;と指定されたとき、左側のpaddingはどれか？  
1. displayプロパティについて正しいのはどれか？  
1. 「その要素にカーソルがのったとき」にスタイルを適用できる擬似クラスはどれか？  
1. 次のようなファイル構成だったときに、要素の背景にimgフォルダの中のbg.pngを指定したい。cssフォルダ内のstyles.cssにはなんと記述するべきか？  
1. img要素が次のように3つ並んでいたときに、a.pngとb.pngの間、b.pngとc.pngの間に10pxの余白を作りたい。どの宣言を使えばよいか？  
1. 背景に画像を使う際はどのように記述すべきか？
1. redを表現する際はどのように記述すべきか？
1. 「&copy;」を表示するにはどのように記述すべきか？
***
# Java
- 配点:50
- 出題範囲:教科書（配列まで）+joytas.netの記事
1. 下記のコードがコンパイルエラーになる原因は何か
```java:Hoge.java
public class Hoge{
  public static void main(String[]args){
    System.out.println("Hello World);
  }
}
```
2. 1文字を格納する時に宣言する変数の型名は何か
3. 以下のコードを実行した際に表示される値は何か
```java:Hoge.java
public class Hoge{
  public static void main(String[]args){
    int x=5;
    int y=2;
    System.out.println(x/y);
  }
}
```
4. 私は30歳ですと出力させたい場合、以下のコードのprintln後の()内をどのように記述すべきか
```java:Hoge.java
public class Hoge{
  public static void main(String[]args){
    int age=30;
    System.out.println("私はage歳です");
  }
}
```
5. int rand =new java.util.Random().nextInt(99);と記載されている場合、乱数の値はいくつからいくつまでか
6. 変数aと変数bを比較して大きい方の値を変数cに代入したい場合、下記コードのc=と(a,b)の間に何と記述すべきか
```java:Hoge.java
public class Hoge{
  public static void main(String[]args){
    int a=13;
    int b=34;
    int c=      (a,b);
  }
}
```
7. int型の配列numsを要素数5で作成する際のコードを記述せよ
### 予想問題
***
