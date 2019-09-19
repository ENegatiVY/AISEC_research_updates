# 赵璞的学习总结

## 第一周(2019/9/19)

本周主要读了AISec中宇飞师兄推荐的两篇论文：

[Intriguing properties of neural networks](https://arxiv.org/abs/1312.6199) 这是对抗样本的开山之作。

这篇论文主要讲了两个神经网络的特性：

1.在高层单元中，是这些单元的线性组合构成的特征空间包含的语义信息，而非单个单元的特征。

2.深度神经网络可以被样本欺骗，而这种欺骗只需要在原样本上加上很难发觉的很小的扰动即可实现。

[Visualizing and Understanding Convolutional Networks (ECCV '14)](https://cs.nyu.edu/~fergus/papers/zeilerECCV2014.pdf) 这是模型可视化的一篇经典作。

这篇论文主要讲了通过反池化、矫正、反卷积这样的步骤，就可以把高维的特征映射到原始图片上，从而可以寻找到原始图片中，对高维的特征有着主要影响的区域。通过分析这些区域，就可以对神经网络的结构做出针对性的改动，从而提升模型性能。