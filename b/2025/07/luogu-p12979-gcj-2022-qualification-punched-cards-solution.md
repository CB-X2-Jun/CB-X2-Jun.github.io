# 洛谷P12979 [GCJ 2022 Qualification] Punched Cards 题解

## 前言

同步发表于 [洛谷专栏](https://www.luogu.com.cn/article/4uzyid0o)。该专栏文章已经审核通过进入[P12979题解区](https://www.luogu.com.cn/problem/solution/P12979)。

同步发表于 [ESGN](https://etoj.xyz/archives/luogu-p12979-google-code-jam-2022-qualification-punched-cards-solution)。

## 题目

[题目传送门 P12979 [GCJ 2022 Qualification] Punched Cards](https://www.luogu.com.cn/problem/P12979)

## 正文

比较简单的一道题，按照题意模拟即可。

通过观察样例得到，每组数据输出时左上角都是 $4$ 个点：

```plain
..+-+-+-+
..|.|.|.|
+-+-+-+-+
|.|.|.|.|
+-+-+-+-+
|.|.|.|.|
+-+-+-+-+
```
特判一下左上角的位置，再结合其他字符（`|`、`-`、`.`、`+`）在“卡片”中应当存在的位置，用分支结构就可以了。

- `|` 位于偶数行奇数列上；
- `+` 位于奇数行奇数列上；
- `-` 位于奇数行偶数列上；
- `.` 位于偶数行偶数列上，以及左上角有 $4$ 个。

循环应该循环到 $2 \times R + 1$（题目中明确说明的）以及 $2 \times C + 1$（观察可知，比如 $C=4$ 时输出了 $9$ 列）。

注意要输出 `Case #x:`。

## 代码

```cpp
/* By CB_X2_Jun */
#include <iostream>
using namespace std;
int t,r,c,z;
int main()
{
    cin.tie(0);cout.tie(0);ios::sync_with_stdio(false);
    cin >> t;
    z=t;
    while(t--) // 多组数据
    {
        cin >> r >> c;
        cout << "Case #" << z-t << ":\n"; // 别忘了这个
        for(int i=1; i<=2*r+1; i++)
        {
            for(int j=1; j<=2*c+1; j++)
            {
                if(i==1&&j==1||i==1&&j==2||i==2&&j==1||i==2&&j==2)cout << "."; // 特判左上角
                else if(i%2==1&&j%2==1)cout << "+";
                else if(i%2==0&&j%2==1)cout << "|";
                else if(i%2==1&&j%2==0)cout << "-";
                else cout << "."; // 这里都按照位置的奇偶性做判断
            }
            cout << endl;
        }
    }
}
```

***请勿 Copy + Paste，共创和谐洛谷！***

---
### 访客统计
![](https://flagcounter.me/e7K)
