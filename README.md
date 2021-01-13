#define _CRT_SECURE_NO_WARNINGS 1
#include<stdio.h>

int main()
{
	printf("%d\n", sizeof(char));
	printf("%d\n", sizeof(short));
	printf("%d\n", sizeof(long));
	printf("%d\n", sizeof(long long));
	printf("%d\n", sizeof(float));
	printf("%d\n", sizeof(double));
	return 0;
}
//char-字符类型
//%d--打印整型
//%c--打印字符
//%f--打印浮点数字--打小数
//%p--以地址的形式打印
//%x--打印十六进制
//%0……

//char ch = 'A';//内存
	//printf("%c\n", ch);//%c-打印字符格式的数据
	//short int--短整型
	//int--整型
	//int age = 20;
	//printf("%d\n", age);//%d--打印整型十进制数据
	//long--长整型
	//long num = 100;
	//printf("%d\n", num);
	//float f = 5.0;
	//printf("%f\n", f);
	//double d = 3.14;
	//printf("%lf\n", d);
//包含一个叫stdio.h的文件
//std-标准standard input output
//#include<stdio.h>
//int main()
//主函数-程序的入口-main函数有且仅有一个
//{
	//这里完成任务
	//在屏幕上输出hello world
	//函数-print function-printf-打印函数
	//printf("hello world\n");
	//库函数-C语言本身提供给我们使用的函数
	//别人的东西-打招呼
	//#include
	//return 0;
//}
//int 是整型的意思
//main前面的int表示main函数调用返回一个整型值
//int main()
//{
	//return 0;//返回 0
//}
//void main()//这种写法是过时的写法
//{
//}
