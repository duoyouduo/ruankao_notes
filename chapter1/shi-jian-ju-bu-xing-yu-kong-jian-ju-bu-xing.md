#局部性原理-时间局部性和空间局部性

**时间局部性：**刚刚访问后的内容要继续访问，短时间内不被替换出cache，以提高效率，比如循环结构中重复执行的语句，应该放到cache当中访问，而不是重复从内存中读取；

**空间局部性：**对内存空间进行顺序访问时，地址空间是相邻的（比如访问一个数组并对其赋值，a[0]...a[n]在内存空间是连续的，访问a[i]之后就要访问a[i+1]，这就体现了空间的局部性）；

![](/imgs/1.2.12-1局部性原理.png)