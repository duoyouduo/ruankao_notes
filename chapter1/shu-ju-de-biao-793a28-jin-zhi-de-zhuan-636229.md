# 数据的表示
## 不同进制的转换问题

###为什么十六进制数的后面都要加一个大写的H？

后面加个H，那是给程序的阅读者看的，表示这是一个十六进制。

十六进制（英文名称：**Hexadecimal**），是计算机中数据的一种表示方法。在数学中是一种逢16进1的进位制，一般用数字0到9和字母A到F表示(其中:A~F即10~15)。

为了区别不同数制表示的数，通常用右括另外下标数字或字母表示数制：

* **十进制数用D表示**

* **二进制用B表示**

* **十六进制数用H表示**

* **八进制用O表示**

例如：101B 表示二进制数

###R进制转十进制：按权展开法

**注：0位不用乘权重（都为0）**

![](/imgs/1.2.1-1R进制转十进制.png)

**十进制转二进制：短除法**

![](/imgs/1.2.1-2十进制转二进制.png)

**二进制转八进制、十六进制**

每3个二进制位对应一个八进制位

每4个二进制位对应一个十六进制位

![](/imgs/1.2.1-3二进制转八和十六进制.png)

