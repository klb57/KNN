## k-近邻算法实现手写数字识别系统

### 运行方法
在Python命令提示符中输入python kNN.py即可运行

### 实验数据
```这里构造的系统只能识别数字0到9```
需要识别的数字已经使用图形处理软件，处理成具有相同的色彩和大小 1：宽高是32像素x32像素的黑白图像

k-近邻算法识别手写数字数据集，错误率为1.2%。改变变量k的值、修改函数handwritingClassTest随机选取训练样本、改变训练样本的数目，都会对k近邻算法的错误率产生影响，感兴趣的话可以改变这些变量值，观察错误率的变化。

该数据集合修改自"手写数字数据集的光学识别"一文中的数据集合，该文登载于2010年10月3日的UCI机器学习资料库中http://archive.ics.uci.edu/ml。作者是土耳其伊斯坦布尔海峡大学计算机工程系的E. Alpaydin与C. Kaynak。

### 总结
k-近邻算法是分类数据最简单有效的算法。k-近邻算法是基于实例的学习，使用算法时我们必须有接近实际数据的训练样本数据。k-近邻算法必须保存全部数据集，如果训练数据集很大，必须使用大量的存储空间。此外，由于必须对数据集中的每个数据计算距离值实际使用是可能非常耗时。