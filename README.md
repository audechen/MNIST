### MNIST

**下载MNIST数据集，并打印一些基本信息：**

```
python download.py
```

**将MNIST数据集保存为图片**

```
python save_pic.py
```

**图像标签的独热表示**


```
python label.py
```

**Softmax 回归分类**

```
python softmax_regression.py
```

**两层卷积网络分类**
```
python convolutional.py
```

#### 可能出现的错误

下载数据集时可能出现网络问题，可以用下面两种方法中的一种解决：
- 使用合适的代理
- 在MNIST的官方网站上下载文件train-images-idx3-ubyte.gz、train-labels-idx1-ubyte.gz、t10k-images-idx3-ubyte.gz、t10k-labels-idx1-ubyte.gz，并将它们存储在MNIST_data/文件夹中。


#### 拓展阅读

- MNIST 数据集经常被用来检验机器学习模型的性能，在它的官网（地址：http://yann.lecun.com/exdb/mnist/ ）中，可以找到多达68 种模型在该数据集上的准确率数据，包括相应的论文出处。这些模型包括线性分类器、K 近邻方法、普通的神经网络、卷积神经网络等。
- 两个MNIST 程序实际上来自于TensorFlow 官方的两个新手教程，地址为https://www.tensorflow.org/get_started/mnist/beginners 和 https://www.tensorflow.org/get_started/mnist/pros 。这两个新手教程的中文版地址为http://www.tensorfly.cn/tfdoc/tutorials/mnist_beginners.html 和http://www.tensorfly.cn/tfdoc/tutorials/mnist_pros.html。
- tf.Tensor 类是TensorFlow的核心类，常用的占位符（tf.placeholder）、变量（tf.Variable）都可以看作特殊的Tensor。可以参阅https://www.tensorflow.org/programmers_guide/tensors 来更深入地学习它的原理。
- 常用tf.Variable 类来存储模型的参数， 可以参阅[https://www.tensorflow.org/programmers_guide/variables](https://www.tensorflow.org/programmers_guide/variables) 详细了解它的运行机制， 文档的中文版地址为http://www.tensorfly.cn/tfdoc/how_tos/ variables.html。
- 只有通过会话（Session）才能计算出tf.Tensor 的值。https://www.tensorflow.org/programmers_guide/graphs 描述了TensorFlow 中 计算图和会话的基本运行原理，对理解TensorFlow 的底层原理有很大帮助。

#### 运行结果

- step 0, training accuracy 0.06
- step 100, training accuracy 0.84
- step 200, training accuracy 0.88
- step 300, training accuracy 0.98
- step 400, training accuracy 0.9
- step 500, training accuracy 0.98
- step 600, training accuracy 0.96
- step 700, training accuracy 0.92
- step 800, training accuracy 0.94
- step 900, training accuracy 0.94
- step 1000, training accuracy 0.96
- step 1100, training accuracy 0.94
- step 1200, training accuracy 0.98
- step 1300, training accuracy 1
- step 1400, training accuracy 0.98
- step 1500, training accuracy 0.9
- step 1600, training accuracy 0.98
- step 1700, training accuracy 0.98
- step 1800, training accuracy 1
- step 1900, training accuracy 0.92
- step 2000, training accuracy 1
- step 2100, training accuracy 1
- step 2200, training accuracy 1
- step 2300, training accuracy 0.98
- step 2400, training accuracy 0.98
- step 2500, training accuracy 0.98
- step 2600, training accuracy 0.98
- step 2700, training accuracy 0.96
- step 2800, training accuracy 1
- step 2900, training accuracy 0.98
- step 3000, training accuracy 0.92
- step 3100, training accuracy 1
- step 3200, training accuracy 1
- step 3300, training accuracy 0.96
- step 3400, training accuracy 1
- step 3500, training accuracy 1
- step 3600, training accuracy 1
- step 3700, training accuracy 0.96
- step 3800, training accuracy 0.98
- step 3900, training accuracy 0.98
- step 4000, training accuracy 1
- step 4100, training accuracy 0.98
- step 4200, training accuracy 1
- step 4300, training accuracy 1
- step 4400, training accuracy 1s
- step 4500, training accuracy 1
- step 4600, training accuracy 0.96
- step 4700, training accuracy 1
- step 4800, training accuracy 1
- step 4900, training accuracy 0.98
- step 5000, training accuracy 1
- step 5100, training accuracy 1
- step 5200, training accuracy 0.98
- step 5300, training accuracy 0.98
- step 5400, training accuracy 0.98
- step 5500, training accuracy 0.98
- step 5600, training accuracy 1
- step 5700, training accuracy 1
- step 5800, training accuracy 0.98
- step 5900, training accuracy 1
- step 6000, training accuracy 0.98
- step 6100, training accuracy 1
- step 6200, training accuracy 0.98
- step 6300, training accuracy 0.98
- step 6400, training accuracy 1
- step 6500, training accuracy 1
- step 6600, training accuracy 1
- step 6700, training accuracy 1
- step 6800, training accuracy 1
- step 6900, training accuracy 0.96
- step 7000, training accuracy 1
- step 7100, training accuracy 1
- step 7200, training accuracy 1
- step 7300, training accuracy 1
- step 7400, training accuracy 1
- step 7500, training accuracy 1
- step 7600, training accuracy 1
- step 7700, training accuracy 0.98
- step 7800, training accuracy 1
- step 7900, training accuracy 1
- step 8000, training accuracy 0.98
- step 8100, training accuracy 1
- step 8200, training accuracy 1
- step 8300, training accuracy 1
- step 8400, training accuracy 1
- step 8500, training accuracy 1
- step 8600, training accuracy 0.98
- step 8700, training accuracy 0.98
- step 8800, training accuracy 1
- step 8900, training accuracy 0.98
- step 9000, training accuracy 1
- step 9100, training accuracy 0.98
- step 9200, training accuracy 1
- step 9300, training accuracy 1
- step 9400, training accuracy 1
- step 9500, training accuracy 1
- step 9600, training accuracy 1
- step 9700, training accuracy 1
- step 9800, training accuracy 1
- step 9900, training accuracy 1
- step 10000, training accuracy 0.98
- step 10100, training accuracy 1
- step 10200, training accuracy 1
- step 10300, training accuracy 1
- step 10400, training accuracy 1
- step 10500, training accuracy 1
- step 10600, training accuracy 1
- step 10700, training accuracy 0.98
- step 10800, training accuracy 1
- step 10900, training accuracy 1
- step 11000, training accuracy 1
- step 11100, training accuracy 1
- step 11200, training accuracy 0.98
- step 11300, training accuracy 1
- step 11400, training accuracy 1
- step 11500, training accuracy 0.98
- step 11600, training accuracy 1
- step 11700, training accuracy 1
- step 11800, training accuracy 1
- step 11900, training accuracy 1
- step 12000, training accuracy 1
- step 12100, training accuracy 1
- step 12200, training accuracy 1
- step 12300, training accuracy 1
- step 12400, training accuracy 0.98
- step 12500, training accuracy 1
- step 12600, training accuracy 1
- step 12700, training accuracy 1
- step 12800, training accuracy 1
- step 12900, training accuracy 1
- step 13000, training accuracy 1
- step 13100, training accuracy 1
- step 13200, training accuracy 1
- step 13300, training accuracy 1
- step 13400, training accuracy 1
- step 13500, training accuracy 1
- step 13600, training accuracy 1
- step 13700, training accuracy 0.98
- step 13800, training accuracy 1
- step 13900, training accuracy 1
- step 14000, training accuracy 1
- step 14100, training accuracy 1
- step 14200, training accuracy 0.98
- step 14300, training accuracy 1
- step 14400, training accuracy 1
- step 14500, training accuracy 1
- step 14600, training accuracy 0.98
- step 14700, training accuracy 1
- step 14800, training accuracy 1
- step 14900, training accuracy 1
- step 15000, training accuracy 1
- step 15100, training accuracy 1
- step 15200, training accuracy 1
- step 15300, training accuracy 1
- step 15400, training accuracy 1
- step 15500, training accuracy 1
- step 15600, training accuracy 1
- step 15700, training accuracy 1
- step 15800, training accuracy 1
- step 15900, training accuracy 1
- step 16000, training accuracy 1
- step 16100, training accuracy 1
- step 16200, training accuracy 1
- step 16300, training accuracy 1
- step 16400, training accuracy 1
- step 16500, training accuracy 1
- step 16600, training accuracy 1
- step 16700, training accuracy 1
- step 16800, training accuracy 1
- step 16900, training accuracy 1
- step 17000, training accuracy 1
- step 17100, training accuracy 1
- step 17200, training accuracy 1
- step 17300, training accuracy 1
- step 17400, training accuracy 1
- step 17500, training accuracy 1
- step 17600, training accuracy 1
- step 17700, training accuracy 0.98
- step 17800, training accuracy 1
- step 17900, training accuracy 1
- step 18000, training accuracy 1
- step 18100, training accuracy 1
- step 18200, training accuracy 1
- step 18300, training accuracy 1
- step 18400, training accuracy 1
- step 18500, training accuracy 1
- step 18600, training accuracy 1
- step 18700, training accuracy 1
- step 18800, training accuracy 1
- step 18900, training accuracy 1
- step 19000, training accuracy 1
- step 19100, training accuracy 1
- step 19200, training accuracy 1
- step 19300, training accuracy 1
- step 19400, training accuracy 1
- step 19500, training accuracy 1
- step 19600, training accuracy 1
- step 19700, training accuracy 1
- step 19800, training accuracy 1
- step 19900, training accuracy 1
- test accuracy 0.9914