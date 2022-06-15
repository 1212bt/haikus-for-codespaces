
# Haikus for Codespaces

This is a quick node project template for demoing Codespaces. It is based off of the [Azure node sample](https://github.com/Azure-Samples/nodejs-docs-hello-world). It's great!!!
#define  _CRT_SECURE_NO_WARNINGS
#include<stdio.h>
int main()
{
	printf("%d\n", sizeof(char));//字符          1     8bit  最多存储2*8-1（2的8次方减1个数）
	printf("%d\n", sizeof(short));//短整形        2    16 （2*16-1）
	printf("%d\n", sizeof(int));//整形             4   32
	printf("%d\n", sizeof(long));//长整形           4  32
	printf("%d\n", sizeof(long long));//长长整形    8  64
	printf("%d\n", sizeof(float));//浮点型（小数）  4  32
	printf("%d\n", sizeof(double));//双精度浮点     8  64
}
#define  _CRT_SECURE_NO_WARNINGS
#include<stdio.h>
int main()
{
	short age = 20;
	float tizhong=95.6f;//95.6系统默认double类型，95.6f为单精度类型
}
#define  _CRT_SECURE_NO_WARNINGS
#include<stdio.h>
int num1 = 10;//全局变量
int main()
{
	int num2 = 20;//局部变量
	
}//局部变量与全局变量名字建议不要相同，容易产生BUG
  //	局部变量和全局变量相同时，局部变量比较优先。
全局变量的作用域是整个工程
局部变量的作用域是变量所在的局部范围。
#define  _CRT_SECURE_NO_WARNINGS
#include<stdio.h>
