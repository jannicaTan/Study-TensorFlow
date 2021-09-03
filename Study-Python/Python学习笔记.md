# Python语法学习

基于Python官方文档以及廖雪峰学习笔记

🔗参考链接：

1.https://docs.python.org/zh-cn/3.8/tutorial/index.html

2.https://www.liaoxuefeng.com/wiki/1016959663602400

[TOC]

## 一、Python基础 

交互模式：直接在终端中输入实时显示结果

脚本模式：写好脚本统一运行，结果需要依靠print来进行输出

### 1.数字/字符串/列表

#### 1.1数字

1.加减乘除：

```py
>>> 2 + 2
4
>>> (50 - 5*6) / 4
5.0

```

2.运算：

```python
1.除法运算 (/) 永远返回浮点数类型
>>> 17 / 3  # classic division returns a float
	5.666666666666667
2. //运算符,可以取整；
>>> 17 // 3  # floor division discards the fractional part
	5
3.如果要计算余数，可以使用 %
4.** 运算符：计算乘方
>>> 5 ** 2  # 5 squared
	25
5.在交互模式下，上一次打印出来的表达式被赋值给变量 _
>>> tax = 12.5 / 100
>>> price = 100.50
>>> price * tax
12.5625
>>> price + _
113.0625
```

#### 1.2字符串