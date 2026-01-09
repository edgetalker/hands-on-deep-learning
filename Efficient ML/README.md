### Lab1
+ 剪枝方法介绍
#### 非结构化剪枝
+ magnitude-base pruning
+ pros: 剪枝粒度细，可以自定义prune-ratio
+ cons: 未改变模型结构，无法实现硬件上的加速
#### 结构化剪枝
+ channel pruning + ranking
+ pros: 改变模型结构，可实现加速
+ cons: 对模型的破坏较大，需要微调恢复精度
