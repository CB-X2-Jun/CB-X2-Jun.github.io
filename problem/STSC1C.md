# STSC1C 二叉树 (binary)
洛谷提交链接：[https://www.luogu.com.cn/problem/T506776](https://www.luogu.com.cn/problem/T506776)  
ETOJ 提交链接：[https://etoj.xyz/p/STSC1C](https://etoj.xyz/p/STSC1C)（注意本题在 ETOJ 使用文件 IO，文件名 `binary.in/binary.out`）
## 题目描述

输入一个二叉树的前序与中序遍历，输出其后序遍历。

## 输入格式

输入共两行。

第 $1$ 行：二叉树的前序遍历。

第 $2$ 行：二叉树的中序遍历。

## 输出格式

输出一行，二叉树的后序遍历。

## 样例 #1

### 样例输入 #1

```
ABCD
CBAD
```

### 样例输出 #1

```
CBDA
```

## 提示

对于 $100\%$ 的数据，$1 \le$ 输入的字符串长度 $\le 20$，并且只含大写字母。

数据保证有解。

【样例 #1 解释】

该二叉树形状如下：
```plain
      A
     / \
    B   D
   /
  C
```
