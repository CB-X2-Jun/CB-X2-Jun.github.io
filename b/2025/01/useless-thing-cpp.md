# useless thing-无用程序箱
洛谷专栏链接：[https://www.luogu.com.cn/article/uzs16qki](https://www.luogu.com.cn/article/uzs16qki)  
洛谷云剪贴板 [同内容链接](https://www.luogu.com.cn/paste/mqwdq59i)

```cpp
#include <iostream>
#include <windows.h>
#include <limits.h>
using namespace std;
int main()
{
	while(1)
	{
		system("cls");
		system("color 0f");
		int x;
		x=-1;
		cout << "无   用   程   序   箱\n输入编号：\n 0：退出\n 1: 切换为cmd（可通过输入exit重新进入无用程序箱）\n 2: 猜数字（5☆级小游戏）\n 3：黑白闪瞎你眼（慎用）\n";
		cin >> x;
		system("cls");
		if(x==0)return 0;
		else if(x==1)
		{
			system("cmd");
		}
		else if(x==2)
		{
			int c,d;
			long long n,k;
			cout << "请选择：\n0.一脸懵逼 ∞条命；\n1.菜鸟瞎搞 50条命；\n2.简单乱弄 25条命；\n3.中等算法 12条命；\n4.困难烧脑  7条命；\n5.极限挑战  5条命；\n6.超神启动  3条命；\n7.刮彩票咯  1条命。\n";
			int i;
			cin >> i;
			if(i==0) n=LLONG_MAX;
			else if(i==1)n=50;
			else if(i==2)n=25;
			else if(i==3)n=12;
			else if(i==4)n=7;
			else if(i==5)n=5;
			else if(i==6)n=3;
			else n=1;
			k=n;
			Sleep(400);
			system("cls");
			cout << "准";
			Sleep(200);
			cout << "备";
			Sleep(200);
			cout << "好";
			Sleep(200);
			cout << "了";
			Sleep(200);
			cout << "吗？\n\n";
			Sleep(555);
			cout << "开";
			Sleep(120);
			cout << "—";
			Sleep(100);
			cout << "—";
			Sleep(260);
			cout << "始！";
			Sleep(1000);
			system("cls");
			int y;
			cout << "请选择颜色哦！(不同电脑的颜色显示不一样，这个描述是Windows 7的。)\n1：5星，深蓝底绿字\n2：2星，灰蓝底灰字\n3：4星：黑底天蓝字\n输入其他为默认颜色。\n";
			cin >> y;
			if(y==1)system("color 1a");
			else if(y==2)system("color 37");
			else if(y==3)system("color 0b");
			Sleep(567);
			system("cls");
			cout << "Loading...";
			Sleep(205);
			for(int l=1; l<=15; l++)
			{
				cout << "..";
				Sleep(205);
			}
			cout << "加载完毕！";
			Sleep(666) ;
			system("cls");
			cout << "找一个人来设置答案吧：\n";
			cin >> d;
			c=-999;
			Sleep(999);
			system("cls");
			cout << "设";
			Sleep(200);
			cout << "置";
			Sleep(300);
			cout << "成";
			Sleep(300);
			cout << "功";
			Sleep(200);
			cout << "！";
			Sleep(900);
			cout << "\n（你朋友得被气死hhh）";
			Sleep(777);
			system("cls");
			while(n>0&&c!=d)
			{
				cout << "猜  数  字\n你的生命数：" << n << "\n猜个数吧：";
				cin >> c;
				if(c>d)
				{
					cout << "大了！2秒后继续。";
					n--;
					Sleep(2000); 
				}
				else if(c<d) 
				{
					cout << "小了！2秒后继续。";
					n--;
					Sleep(2000); 
				}
				else
				{
					system("cls");
					cout << "对了！你的局数：" << k-n+1 << endl;
					system("pause") ;
					break; 
				}
				system("cls");
			}
			if(c==d)continue;
			cout << "你的生命数：" << 0;
			Sleep(1500);
			system("cls");
			cout << "你失败了！正确答案：" << d << endl;
			system("pause");
		}
		else if(x==3)
		{
			int sck;
			cout << "请输入颜色切换的间隔（单位：毫秒），不要小于20否则卡住的概率较大：\n整个过程只会持续5秒。\n";
			cin >> sck;
			for(int i=1; i<=2500.0/sck; i++)
			{
				system("color f0");
				Sleep(sck);
				system("color 0f");
				Sleep(sck);
			}
			system("color 0f");
			system("pause");
		}
	}
}
```

**此为 CB_X2_Jun 个人编写。转载请注明以下内容：**

> 作者：CB_X2_Jun
> 
> 来源（三选一）：
> `https://cb-x2-jun.github.io/b/2025/01/useless-thing-cpp`  
> 或 `https://www.luogu.com.cn/article/uzs16qki`  
> 或 `https://www.luogu.com.cn/paste/mqwdq59i`。

---
### 访客统计
![](https://flagcounter.me/e7K)
