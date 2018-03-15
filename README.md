# Graphic Deep Neural Network
在AI学习的漫漫长路上，理解不同文章中的模型与方法是每个人的必经之路，偶尔见到Fjodor van Veen所作的[A mostly complete chart of Neural Networks](http://www.asimovinstitute.org/wp-content/uploads/2016/09/neuralnetworks.png) 和 FeiFei Li AI课程中对模型的[画法](https://github.com/weslynn/graphic-deep-neural-network/blob/master/pic/feifei.png)，大为触动。决定将深度神经网络中的一些模型 进行统一的图示，便于大家对模型的理解。


模型中用到的图标规定如下：
![图标](https://github.com/weslynn/graphic-deep-neural-network/blob/master/pic/cellsreadme.png)



一个具体的问题是否能用人工智能，或者更进一步说用深度学习某个算法解决，首先需要人对问题进行分解，提炼成可以用机器解决的问题，譬如说分类问题，回归问题，聚类问题等。


## 分类问题

深度学习在解决分类问题上非常厉害。让它声名大噪的也是对于图像分类问题的解决。也产生了很多很经典的模型。因此我们首先了解一下它们。

从模型的发展过程中，我们可以看到网络结构不断的进行改进，包括不断增加的网络深度，不断变换的卷积核上，多种多样的网络模块等。

* LeNet [详解 detail](https://github.com/weslynn/graphic-deep-neural-network/blob/master/object%20classification%20%E7%89%A9%E4%BD%93%E5%88%86%E7%B1%BB/LeNet.md)

    <img src="https://github.com/weslynn/graphic-deep-neural-network/blob/master/pic/lenet.png" width="405">


    [1] LeCun, Yann; Léon Bottou; Yoshua Bengio; Patrick Haffner (1998). "Gradient-based learning applied to document recognition" [pdf](http://yann.lecun.com/exdb/publis/pdf/lecun-01a.pdf)

	tf code  https://github.com/tensorflow/models/blob/57014e4c7a8a5cd8bdcb836587a094c082c991fc/research/slim/nets/lenet.py
	pytorch code  https://github.com/pytorch/examples/blob/master/mnist/main.py)  
	caffe code  https://github.com/BVLC/caffe/blob/master/examples/mnist/lenet.prototxt)


* AlexNet



* GoogLeNet

* Inception V3

* VGG

* ResNet







# 贡献力量

如果想做出贡献的话，你可以：

帮忙对没有收录的paper进行模型绘制

帮忙进行模型校对等

提出修改建议


