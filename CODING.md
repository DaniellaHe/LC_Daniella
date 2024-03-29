# CODING

## 数据传输

### 网络：数据结构

数据结构与算法的本质，是抽象视角下的数据传输。

​	数据结构研究的是数据传输所依赖的网络结构。

​	算法研究的是如何在这个数据传输网络上传输，以及如何加速数据的传输。



数据传输的3要素：

1. 点：状态。点分为已知点和未知点。已知点存储着原始的数据值，未知点是我们想要计算或者传递值的目标位置。
2. 边：递推。代表了从已知点到未知点的递推公式，即函数关系f(x)。定义了如何根据已知点的值计算出未知点的值。
3. 序：顺序。描述了值传递的方向。从已知点到未知点，为先序；从未知点反推出可能的已知点，是后序。



值传递关注有向边：

> 出度：一个节点向外的边的数量，反映了这个节点对其他节点的影响。
>
> 入度：一个节点向内的边的数量，反映了这个节点受到其他节点的影响。

集：出度和入度都是0

线：每个点的出度和入度都不超过1

树：根节点的入度是0，其他节点的入度是1

图：出度和入度无限制

* 无环图：
  * 有向无环图（DAG）：
* 有环图：存在环路或者循环路径，容易死锁

四大数据结构统一于有向无环图



### 方式：拓扑排序



### 效率：时间复杂度