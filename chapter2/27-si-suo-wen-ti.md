#进程管理-死锁问题

**进程死锁**：系统中有一系列资源，和一系列需要用到这些资源的进程，如果系统在某一时刻发现所有的可用资源都被分配，而当前所有的进程都没有完成自己本身的任务，所以不会去释放自己占有的资源（此时所有的进程都在等待其他进程释放资源，但自己都不会释放自己已经占有的资源），造成系统无法正常完成一系列任务，从而发生死锁（一个进程在等待一件不可能发生的事件，进程就死锁了）；

**系统死锁**：一个或多个进程产生死锁，就会造成系统死锁；

##两类问题：

1. 例题：**需要多少资源进程不会发生死锁**；

2. 死锁的预防和避免：银行家算法；

![](/imgs/1.3.7-1死锁问题.png)