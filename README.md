#daily exercise 2023.4.7
only to update the exercise of  gramming in my spare time
# include <stdio.h>
int  main()
{
	int a, b, c;
	a = b = c = 0;
	scanf_s("%d%d%d",&a, &b, &c);
	double res;
	res = (a + b + c) / 3;
	printf("%f\n", res);

	return 0;

}
//{
//	int num1 = 0;
//	int num2 = 0;
//	int sum = 0;//这里的话最好就是把所有的定义变量放在开头这里
//	// 先定义变量再使用变量
//
//	// 输入数据-》使用scanf(使用数据输入函数)
//	// 2017的vs是不能用scanf 应该用scanf_s更加安全
//	scanf_s("%d%d", &num1, &num2);// 输入变量需要用& --》 取地址符号
//	sum = num1 + num2;
//	printf("sum = %d\n", sum);
//	return 0;
//}
//int num1 = 100;
//int main()
//{
//	int num2 = 200;
//	printf("%d %d\n", num1,num2);// 区别于输入数据，打印数据是不需要&
//	return 0;
//}
//int main()
//{
//	short age = 20; // 向内存申请两个字节
//	float weight = 95.63f; // 这里的话就是就是如果只是95.63就是表示双精度，用在float里面的话不合适
//	                      // 这个时候呢只需要在数字的后面加上f就可以转换为单精度数字
//	return 1;
//}
//int main()
//{
//	// char 能向内存申请多少空间
//	printf("%d\n", sizeof(char)); // 1
//	printf("%d\n", sizeof(short)); // 2  一个字节就是8个比特位，能容纳大概是2**16-1
//	printf("%d\n", sizeof(int)); // 4
//	printf("%d\n", sizeof(long)); // 4
//	printf("%d\n", sizeof(long long)); // 8
//	printf("%d\n", sizeof(float)); // 4
//	printf("%d\n", sizeof(double)); // 8
//	return 0;
//}
//int main()
//// char -- 字符类型
//{
//	// 需要注意的是变量后面的字符只能用单引号，而pritnf()
//	char ch = 'A'; // ch 就是向内存里面申请了一个空间叫做ch ，也就是一个变量
//	printf("%c\n", ch); // %c -- 打印字符格式的数据
//	int age = 20;
//	printf("%d\n", age); // %d -- 打印整型十进制数据
//	short num1 = 20;
//	printf("%d\n", num1); // %d -- 打印短整型十进制数据
//	long num2 = 20;
//	printf("%d\n", num2); // %d -- 打印长整型十进制数据
//	float f = 5.0;//  单精度浮点数
//	printf("%f\n", f);// 一般都是精确到小数点后6位
//	double d = 5.12;// 双精度浮点数
//	printf("%f\n", d);
//	return 0;
//
//}
//// 包含一个 stdio.h 的文件
//// std ==>> 标准 i => input o => output
////
//# include <stdio.h>
//// int main() 表示的是main函数调用之后要返回一个整型值
//int main() // 主函数 -> 程序的入口
//// main函数有且只能有一个
//{
//	// printf = print function ==>> 打印函数
//	// 这个函数就是别人给你函数，但是你需要去跟他打招呼
//	// 方式：# include
//	printf("Hello World!\n");
//	return 0;// 返回0
//}
//
// //void main()这种写法已经过时了
