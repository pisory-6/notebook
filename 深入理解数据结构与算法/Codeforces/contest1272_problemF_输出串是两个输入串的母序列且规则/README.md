# 输出串是两个输入串的母序列且规则

### 题意

给定两个串A、B，长度分别为L1、L2

要求输出一个串C，满足两个条件

- A、B均是C的子序列
- C是规则的

一个串是规则的，定义如下

- ()是规则的
- 如果一个串S是规则的，则(S)是规则的
- 如果串S、T均是规则的，则ST是规则的

如果有多个解，输出任意一个即可

### 条件范围

L1、L2：[1, 200]

### 样例输入1
```
(())(()
()))()
```

### 样例输出1
```
(())()()
```

### 样例输入2
```
)
((
```

### 样例输出2
```
((()))
```

### 样例输入3
```
())
(()(()(()(
```

### 样例输出3
```
(()()()(()()))
```

### 关联链接

原题：http://codeforces.com/contest/1272/problem/F
