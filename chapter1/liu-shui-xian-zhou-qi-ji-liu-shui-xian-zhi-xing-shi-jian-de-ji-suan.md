#流水线周期和流水线执行时间的计算

##流水线执行时长的问题


**流水线周期**是**执行时间最长**的那一步操作所用的时间（完成一件事情，要分几个步骤，其中最耗时最长的那一个步骤就是流水线周期）；

流水线的执行过程分为两段：
1.流水线的建立时间：**_第一条指令执行完成使用的时间_**
建立流水线需要有运转（建立）起来的时间，在运转起来之后，就开始按照一定的规律开始在每个周期产出产品（完成指令执行操作）；
2.流水线按规律开始执行的时间：**_（n-1）×流水线周期_**
