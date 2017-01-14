# 何谓机器学习

机器学习，就是把无序的数据，转换成有用的信息。

------

#### 关键术语

在入门机器学习之前，我们先了解一些简单的术语：

- 特征：也称作`属性`
- 训练集：训练机器大脑的样本，包含特征与`目标变量`
- 测试数据：用于测试机器学习算法的效果，测试数据通常不包含`目标变量`，目标变量有机器学习算法得出
- 精确度：比较预测结果与实际结果

#### 如何开发机器学习应用程序

- 收集数据：收集数据的途径很多，爬虫、公开数据源、设备测量数据集等
- 准备输入数据：确保数据符合`机器学习算法`的格式等要求
- 分析输入数据：可能需要人工干预分析以前得到的数据，确保数据中没有垃圾数据
- 训练算法：从数据中抽取知识与信息
- 测试算法：评估算法处理后的`目标变量`
- 使用算法：转换算法为应用程序，执行实际任务

#### 开发环境

这里使用`python`作为开发语言，下边我们来配置环境：

```shell
curl -O https://bootstrap.pypa.io/get-pip.py
```

如果你的版本是2.7：

```shell
python get-pip.py
```

如果是python3：

```shell
python3 get-pip.py
```

#### 基础库

我们使用了`NumPy`作为基础库，这里包含了线性代数等知识。比如说我们如何求一个矩阵的逆：

```python
randMat = mat(random.rand(4, 4)) // 从随机的数组中创建矩阵
invRandMat = randMat.I // invRandMat就是randMat逆矩阵
```

#### 入门知识小结

学习机器学习算法，必须了解数据实例，每个数据实例有多个特征值组成。为了充分的构建和训练机器，我们必须已知大量的训练样本集。