#可靠性分析-串联系统和并联系统的可靠性分析

考查方式：计算方面的问题，给一个串并联交织的模型，能会计算其相应的可靠度。

R1->Rn共n个子系统：

###1. 串联模型

一个子系统出问题，整个系统都不能运行；

可靠性：R = R1×R2×...×Rn 
失效率：λ = λ1+λ2+...+λn（注：此公式是近似简化的算法，是在失效率特别低的情况下用来快速计算失效率的）

###2. 并联模型

所有子系统都失效，整个系统才失效；

可靠性：R = 1-(1-R1)×(1-R2)×...×(1-Rn);

![](/imgs/1.2.15-1系统可靠度.png)

###3. N摸冗余系统与混合系统

这类型计算现在几乎不会考到

模冗余系统：对R1~Rm个子系统进行计算，最终通过表决器来决定整个系统的最终结果，这样可以使得即使某个子系统出错也不会影响到整个系统的结果。

![](/imgs/1.2.15-2n模冗余系统.png)

###4. 常考题型

把串并联综合到一起，求可靠度；

解决思路：从整体看先是串行，分别求并联的可靠度后，再将三个串联的进行求积；

![](/imgs/1.2.15-3常考题型.png)