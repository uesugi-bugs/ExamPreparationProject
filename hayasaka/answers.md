■Unix問題
1.pwd
2.ls
3.mkdir
4.touch
5.echo "firstLine" > test.txt
6.echo "secondLine" >> test.txt
7.cat
8.cp
9.mv test.txt 移動したいディレクトリのパス
10.rm

■vim問題
1.x
2.dd
3.dw
4.de
5.f + 任意の文字
6.gg
7.u
8.r
9.G
10.:wq

■Git問題
1.git init
2.git add ファイル名 
3.git commit -m"コメント"
4.git graph(git log --graph)
5.git diff
6.git branch ブランチ名
7.git checkout 移動したいブランチ名
8.git merge 取り込みたいブランチ名
9.-u
10.git remote -v

■HTML&CSS問題
1.2
2.2
3.2
4.2
5.1
6.4
7.2
8.3
9.3
10.2
11.2
12.1
13.2
14.2
15.3
16.3
17.4
18.2
19.2
20.3

■Java問題
1.
public class Lesson1{
	public static void main(String[] args){
		System.out.println("Hello World");
	}
}

2.
public class Lesson2{
	public static void main(String[] args){
		int x = 13+17;
		System.out.println(x);
	}
}

3.
public class Lesson3{
	public static void main(String[] args){
		System.out.println(13*17);
	}
}

4.
public class Lesson4{
	public static void main(String[] args){
		int x=5;
		int y=10;
		int temp=x;
		x=y;
		y=temp;
		System.out.println("x=" + x + ",y=" + y);
	}
}

5.
public class Lesson5{
	public static void main(String[] args){
		int x=5;
		for(int i=2; i<=4; i++){
			System.out.println(x*i);
		}
	}
}

6.
public class Lesson6{
	public static void main(String[] args){
		double bmi=21.79930795847751;
		System.out.printf("BMIは%.2fです。",bmi);
	}
}

7.
public class Lesson7{
	public static void main(String[] args){
		int money =10000000;
		System.out.printf("所持金は%,dです。",money);
	}
}

8.
public class Lesson8{
	public static void main(String[] args){
		for(int i=1; i<=9; i++){
			for(int j=1; j<=9; j++){
				System.out.print(i*j + ",");
			}
			System.out.println();
		}
	}
}

9.~20.
import java.util.Arrays;
public class ArrLesson4{
	public static void main(String[] args){
		//9.
		int[] arrA = {4,8,10};
		//10.
		int[] arrB = new int[] {7,1,3};
		//11.
		for(int i=0; i<arr.length; i++){
			System.out.println(arrA[i]);
		}
		//12.
		for(int n : arrB){
			System.out.println(n);
		}
		//13.
		int[] arrC = new int[3];
		//14.
		for(int i=0; i<arrC.length; i++){
			arrC[i] = arrA[i] * 2;
		}
		//15.
		System.out.println(Arrays.toString(arrC));
		//16.
		for(int i=0; i<arrC.length; i++){
			arrC[i] = arrC[i]+arrB[i];
		}
		//17.
		System.out.println(Arrays.toString(arrC));
		//18.
		int sum=0;
		//19.
		for(int n:arrC){
			sum += n;
		}
		//20.
		System.out.println("合計は"+sum+"です。");
	}
}

