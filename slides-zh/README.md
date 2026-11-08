# 课件翻译（中文）

存放 CS231N 课程 PPT 的中文翻译版本。原文版权归 Stanford University 所有，此处仅为个人学习用途的翻译整理。

## 进度

| # | 课件 | 译文文件 | 状态 |
|---|------|----------|------|
| 01 | Image Classification | `l01-image-classification-zh.pdf` | ⬜ |
| 02 | Linear Classifiers | `l02-linear-classifiers-zh.pdf` | ⬜ |
| 03 | Regularization & Optimization | `l03-regularization-optimization-zh.pdf` | ⬜ |
| 04 | Neural Networks & Backprop | `l04-neural-networks-backprop-zh.pdf` | ⬜ |
| 05 | Convolutional Networks | `l05-convolutional-networks-zh.pdf` | ⬜ |
| 06 | Training Neural Networks I | `l06-training-nn-1-zh.pdf` | ⬜ |
| 07 | Training Neural Networks II | `l07-training-nn-2-zh.pdf` | ⬜ |
| 08 | RNN & Attention | `l08-rnn-and-transformers-zh.pdf` | ⬜ |
| 09 | Detection & Segmentation | `l09-detection-segmentation-zh.pdf` | ⬜ |
| 10 | Visualization & Understanding | `l10-visualization-understanding-zh.pdf` | ⬜ |
| 11 | Generative Models | `l11-generative-models-zh.pdf` | ⬜ |
| 12 | Deep Reinforcement Learning | `l12-deep-rl-zh.pdf` | ⬜ |

状态：⬜ 未开始 / 🟨 翻译中 / ✅ 完成

## 目录约定

每讲一个子文件夹，课件和配套材料放在一起：

```
slides-zh/
├── README.md                 # 本文件：索引与规范
├── glossary.md               # 中英术语对照表（翻译前先查，保证统一）
└── l01-image-classification/
    ├── l01-image-classification-zh.pdf    # 成品：中文译本
    ├── l01-image-classification-en.pdf    # 可选：英文原版对照
    └── notes.md                           # 可选：术语争议、翻不动的句子、补充说明
```

## 命名规范

```
l{两位讲次}-{英文短名}-{语言}.pdf     例：l05-convolutional-networks-zh.pdf
```

- 讲次固定两位数字，保证文件夹按顺序排列
- 语言后缀：`zh` 中文译本、`en` 英文原版、`bi` 双语对照
- 一律用**小写字母 + 连字符**，不用空格、不用中文文件名（避免跨平台乱码）
- 格式优先 PDF（体积小、哪里都能打开）；需要可编辑时再另存 `.pptx`

## 制作方式（推荐工作流）

1. 从 [课程官网](https://cs231n.stanford.edu/) 下载对应讲次的 PDF/PPTX
2. 用 PowerPoint / WPS 在「演讲者备注」或文本框里替换为中文，保留原图
3. 导出 PDF → 按命名规范放进对应文件夹
4. 更新上面这张进度表
5. 遇到新术语先补进 `glossary.md`，再统一全文替换

## 版权与发布提醒

- 课程 PPT 的原文、图片、结构版权属 Stanford University。翻译属于**衍生作品**，严格意义上不能主张版权、也不宜商用。
- 本仓库公开可见，请保持「个人学习 + 注明出处」的定位；若版权方要求，将移除对应文件。
- 已在 [LICENSE](../LICENSE) 中说明：本仓库 CC BY-NC-SA 4.0 仅覆盖自己撰写的笔记文字，**不覆盖**课件原文与其译文。
- 体积建议单文件 < 50 MB；若超过，改用 Git LFS 或改存网盘链接并在 `notes.md` 里留地址。
