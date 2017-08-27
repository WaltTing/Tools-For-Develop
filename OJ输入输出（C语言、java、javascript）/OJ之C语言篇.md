# OJ系统
OJ系统是ACM竞赛、在线笔试必须了解的内容，而输入输出是其中的重中之中。比如题目要求：
## 1.输入单行

输入单行的时候比较简单。

	#include<stdio.h>

    int main(){
    	int a,b;
    	scanf("%d %d",&a,&b)；   
    	printf("%d\n",a+b);
    	return 0;
    }


## 2.输入多对数据，组数不确定
> 求a+b的值。

输入多行如：

> 2 3  
> 4 5  
> 5 6 

输出：

> 5  
> 9  
> 11  

C语言的输入输出方式为：

    #include <stdio.h>
    
    int main(){
    	int a,b;
    	while(scanf("%d %d",&a,&b)!=EOF)   
    		printf("%d\n",a+b);
    	return 0;
    }

事实上我们看到的结果是这样的：

    2 3   
    5  
    4 5   
    9  
    5 6  
    11

即按下Enter键的时候文件输入结束(End Of File)。

## 3.多组数据，组数由第一个数据决定

比如：要求输入两组数，分别求a+b的值。

输入：

> 2   
> 2 3  
> 4 5 

输出：
> 5  
> 9

我们就用一个变量来接收组数N，然后循环输入输出即可。

    #include<stdio.h>
    
    int main(){
    	int a,b;
    	scanf("%d",&n); //n表示组数
    	for(int i=0;i<n;i++){
    		scanf("%d %d",&a,&b);
    		printf("%d\n",a+b);
    	}
    
    	return 0;
    }


参考：[http://blog.csdn.net/sxhelijian/article/details/8978794](http://blog.csdn.net/sxhelijian/article/details/8978794)