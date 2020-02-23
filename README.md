# tensor_code :tada:

## 记录 :memo:

### 机器学习

#### 机器学习是什么？

- 机器学习是对能通过`经验`自动改进对计算机算法对研究
- 机器学习是用`数据`或以往的`经验`，以此优化计算机程序的性能标准

#### 案例

- 线性回归
- 逻辑回归
- 图片分类
- 语音助手

### 神经网络

#### 什么是神经网络？

- 人工神经网络是一种运算模型（就是输入输出的映射），由大量的节点（或称神经元）之间相互联接构成
- 每个神经元里存储着若干`权重`（weight）、`偏置`（bias）、和一个`激活函数`（activation）
- 输入乘上权重加上偏置，经过激活函数得到输出
- 激活函数用于添加一些非线性变换
- 神经网络通常包含一个输入层、若干隐藏层、一个输出层
- 输入层通常不用于计算神经网络的层数

#### 什么是神经网络的训练？

- 给大量输入和输出，算出神经网络里所有神经元的权重、偏置，然后给定新的输入，可以算出新的输出
- 在机器学习里，输入输出被称为`特征`和`标签`，大量输入输出被称为训练集

#### 如何训练神经网络？

- 初始化：随机生成一些权重和偏置
- 计算损失：给定特征，计算出标签，得到它与真实标签相差多远
- 优化：微调权重和偏置，使损失变小

#### 前向传播与反向传播

- 前向传播： 将训练数据的特征送入网络，得到标签
- 反向传播： 计算损失并优化