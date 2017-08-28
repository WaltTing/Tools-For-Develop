# OJ系统
OJ系统是ACM竞赛、在线笔试必须了解的内容，而输入输出是其中的重中之重。比如题目要求：

## 1.输入单行

> 题目描述：输出a+b的值。  

样例输入：

> 2 3

输出：

> 5

java的解决方案是：

    import java.util.Scanner;
    
    public class input {
		public static void main(String[] args){
			Scanner cin = new Scanner(System.in);
			int a = cin.nextInt();
			int b = cin.nextInt();
			System.out.println(a+b);
    	}
    }
    
如上，`int a = cin.nextInt();` 就相当于C语言中的 `scanf("%d",&a);`

## 2.指定输入数据的组数

样例输入：

> 2  
> 2 3        
> 5 6  

输出：
> 5   
> 11

事实上输完 `2 3` 之后即跳出5。

实现：

	public class Input {
	    public static void main(String[] args) {
	        Scanner cin = new Scanner(System.in);
	        int n = cin.nextInt();
	        int a,b;
	        for(int i=0;i<n;i++){
	            a = cin.nextInt();
	            b = cin.nextInt();
	            System.out.println(a + b);
	        }
	
	    }
	}

## 3.输入的组数不确定

样例输入：

> 2 3  
> 3 4  
> 4 5   
> ...

输出：

> 5  
> 7   
> 9  
> ...

	import java.util.Scanner;
	
	public class input {
	    public static void main(String[] args) {
	        Scanner cin = new Scanner(System.in);
	        int a,b;
	        while(cin.hasNext()){
	            a = cin.nextInt();
	            b = cin.nextInt();
	            System.out.println(a + b);
	        }
	
	    }
	}

每输入一组数，都会在下方得出计算结果。


## 4.输入一组字符串

下面的cin.next()相当于从控制台接收字符串的输入。

	import java.util.Arrays;
	import java.util.Scanner;
	
	public class input {
	    public static void main(String[] args) {
	        Scanner cin = new Scanner(System.in);
	        char[] ch = cin.next().toCharArray();  //将输入的字符串转化成字符
	        System.out.println(Arrays.toString(ch));  //将数组以字符串的表现形式输出
	    }
	}

