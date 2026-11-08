# 中英术语对照表

翻译课件时先查这里，保证同一概念在 12 讲里用同一个中文词。遇到新词随时补一条。

## 核心概念

| English | 中文 | 备注 |
|---------|------|------|
| image classification | 图像分类 | |
| linear classifier | 线性分类器 | |
| score function | 打分函数 | 也有人译「评分函数」，本仓库统一用「打分函数」 |
| loss function | 损失函数 | |
| hinge loss | 合页损失 | SVM 用的多类损失 |
| softmax / cross-entropy loss | Softmax / 交叉熵损失 | softmax 一般不译 |
| regularization | 正则化 | |
| L1 / L2 regularization | L1 / L2 正则化 | 也叫 Lasso / Ridge |
| optimization | 优化 | |
| gradient descent | 梯度下降 | |
| stochastic gradient descent (SGD) | 随机梯度下降 | |
| momentum | 动量 | |
| learning rate | 学习率 | |
| learning rate decay | 学习率衰减 | |
| hyperparameter | 超参数 | |
| epoch / batch / iteration | 轮次 / 批 / 迭代 | |
| overfitting / underfitting | 过拟合 / 欠拟合 | |
| generalization | 泛化 | |
| cross-validation | 交叉验证 | |

## 网络与训练

| English | 中文 | 备注 |
|---------|------|------|
| neuron | 神经元 | |
| activation function | 激活函数 | |
| ReLU | ReLU | 不译 |
| backpropagation | 反向传播 | |
| computational graph | 计算图 | |
| chain rule | 链式法则 | |
| fully-connected layer | 全连接层 | |
| convolutional layer | 卷积层 | |
| pooling layer | 池化层 | |
| receptive field | 感受野 | |
| stride / padding | 步长 / 填充 | |
| parameter sharing | 参数共享 | |
| batch normalization | 批归一化 | 常直接写 BatchNorm |
| dropout | Dropout | 不译 |
| data augmentation | 数据增强 | |
| transfer learning | 迁移学习 | |
| fine-tuning | 微调 | |
| vanishing / exploding gradient | 梯度消失 / 梯度爆炸 | |
| weight initialization | 权重初始化 | |

## 架构与任务

| English | 中文 | 备注 |
|---------|------|------|
| convolution | 卷积 | |
| residual connection | 残差连接 | |
| attention | 注意力 | |
| self-attention | 自注意力 | |
| transformer | Transformer | 不译 |
| recurrent neural network (RNN) | 循环神经网络 | |
| LSTM | LSTM | 不译 |
| object detection | 目标检测 | |
| bounding box | 边界框 | |
| semantic segmentation | 语义分割 | |
| instance segmentation | 实例分割 | |
| saliency map | 显著图 | |
| style transfer | 风格迁移 | |
| generative adversarial network (GAN) | 生成对抗网络 | |
| variational autoencoder (VAE) | 变分自编码器 | |
| diffusion model | 扩散模型 | |
| reinforcement learning | 强化学习 | |
| policy gradient | 策略梯度 | |

## 翻译风格约定

- 人名、论文名、模型名、代码标识符**保留英文**：Krizhevsky、ResNet、`np.dot`
- 首次出现的术语写成「中文（English）」，后文只用中文
- 公式里的变量名不改，符号保持原样
- 不确定的译法在 `notes.md` 里记录，不要临时自创
