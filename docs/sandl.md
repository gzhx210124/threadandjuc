### 导航

| ID | Problem  | Article | 
| --- | ---   | :--- |
| 000 |synchronized和lock 的区别| [解决思路](/docs/sandl.md) |
#### 多线程编程中 synchronize 

多程序编程中有可能出现多个线程同时访问同一个共享变量 可变资源;这种资源可能是：对象，变量，文件等.

**共享：资源可以由多个线程访问**
**可变：资源可以在其生命周期内被修改**

由于线程执行的过程是不可控的，所以需要采用同步机制来协同对对象可变状态的访问
