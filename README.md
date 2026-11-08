# CS231N 学习笔记

斯坦福 **CS231N: Deep Learning for Computer Vision** 的逐讲学习笔记与作业实现。

用自己的话重写每一讲的要点，记录踩过的坑和代码实现，供自己复习，也希望对同样在学的人有用。

- 课程主页：https://cs231n.stanford.edu/
- 视频与讲义版权归 Stanford 所有，本仓库仅为个人学习整理，引用处均标注来源。

## 进度

| # | 主题 | 笔记 | 状态 |
|---|------|------|------|
| 01 | Image Classification | [notes](notes/01-image-classification.md) | ⬜ |
| 02 | Linear Classifiers: SVM & Softmax | [notes](notes/02-linear-classifiers.md) | ⬜ |
| 03 | Regularization & Optimization | [notes](notes/03-regularization-optimization.md) | ⬜ |
| 04 | Neural Networks & Backpropagation | [notes](notes/04-neural-networks-backprop.md) | ⬜ |
| 05 | Convolutional Networks | [notes](notes/05-convolutional-networks.md) | ⬜ |
| 06 | Training Neural Networks I | [notes](notes/06-training-nn-1.md) | ⬜ |
| 07 | Training Neural Networks II | [notes](notes/07-training-nn-2.md) | ⬜ |
| 08 | RNN & Attention / Transformers | [notes](notes/08-rnn-and-transformers.md) | ⬜ |
| 09 | Detection & Segmentation | [notes](notes/09-detection-segmentation.md) | ⬜ |
| 10 | Visualization & Understanding | [notes](notes/10-visualization-understanding.md) | ⬜ |
| 11 | Generative Models | [notes](notes/11-generative-models.md) | ⬜ |
| 12 | Deep Reinforcement Learning | [notes](notes/12-deep-rl.md) | ⬜ |

> 状态：⬜ 待写 / 🟨 进行中 / ✅ 已完成。章节顺序以官网当学期课表为准。

## 作业

| 作业 | 内容 | 状态 |
|------|------|------|
| Assignment 1 | kNN / SVM / Softmax / 两层网络 | ⬜ |
| Assignment 2 | 全连接网络 / BatchNorm / Dropout / CNN | ⬜ |
| Assignment 3 | RNN / Transformer / GAN / 自监督 | ⬜ |

## 课件翻译

课程 PPT 的中文翻译单独放在 [`slides-zh/`](slides-zh/README.md)，按讲次一个子文件夹，与笔记分开管理。

- 进度表与目录约定：[slides-zh/README.md](slides-zh/README.md)
- 中英术语对照表：[slides-zh/glossary.md](slides-zh/glossary.md)

> 课件原文版权归 Stanford University 所有，译文仅用于个人学习，不作商用。

## 目录结构

```
cs231n-learning/
├── notes/         # 逐讲笔记（Markdown）
├── slides-zh/     # 课程 PPT 中文翻译（按讲次分文件夹）
├── assignments/   # 作业代码实现
├── assets/        # 笔记里引用的图片、曲线
└── README.md
```

## 怎么读

- 每篇笔记结构统一：**本节要点 → 核心公式/推导 → 代码要点 → 待解决问题**。
- 公式用 LaTeX 语法书写（`$...$` 与 `$$...$$`），GitHub 原生支持渲染。
- 图片放在 `assets/`，用相对路径引用，保证 clone 下来能看。

## License

- 笔记文字：CC BY-NC-SA 4.0
- 作业代码：MIT

详见 [LICENSE](LICENSE)。课程原始讲义、幻灯片、作业框架的版权归 Stanford University 所有。
