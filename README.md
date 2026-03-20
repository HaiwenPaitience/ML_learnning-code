[README .md](https://github.com/user-attachments/files/26132557/README.1.md)
# ML_learnning-code

> 机器学习核心专题学习代码库 · 李海文 · 中国传媒大学 · 2024

本仓库收录本科阶段自主学习机器学习课程的实验代码与练习，涵盖 **CNN 理论基础、文本数据增强、大语言模型应用与评估、统计不确定性量化** 四个核心专题，共 9 个模块。

---

## 📁 目录结构

```
ML_learnning-code/
├── 00-1_python-setup-guide/        # 环境配置与基础工具
├── q10-random-sources/             # 随机数据源与模型泛化
├── q11-conv-size/                  # 卷积核尺寸与感受野分析
├── q12-fc-cnn-equivalence/         # 全连接层与卷积层等价性
├── q15-text-augment/               # 文本数据增强策略
├── q18-using-llms/                 # 大语言模型使用方法
├── q19-evaluation-llms/            # 大语言模型评估框架
├── q25_confidence-intervals/       # 置信区间与统计推断
└── q26_conformal-prediction/       # 保形预测与不确定性量化
```

---

## 🗂 模块说明

### 环境准备
| 模块 | 内容 |
|------|------|
| `00-1_python-setup-guide` | Python 环境配置、依赖安装、Jupyter 使用指南 |

### 专题一：CNN 理论基础
| 模块 | 对应问题 | 核心内容 |
|------|----------|----------|
| `q10-random-sources` | 随机数据源对模型的影响 | 不同数据分布下模型泛化行为分析，参考 Zhang et al. *Rethinking Generalization* (ICLR 2017) |
| `q11-conv-size` | 卷积核尺寸设计 | 3×3 vs 5×5 卷积核的感受野、参数量与计算代价权衡实验 |
| `q12-fc-cnn-equivalence` | FC 层与 CNN 等价性 | 全连接层等价为 1×1 卷积的数学推导与代码验证 |

### 专题二：文本数据增强
| 模块 | 对应问题 | 核心内容 |
|------|----------|----------|
| `q15-text-augment` | 文本增强策略 | 同义词替换（SR）、随机插入（RI）、随机交换（RS）、随机删除（RD），参考 EDA (EMNLP 2019) |

### 专题三：大语言模型
| 模块 | 对应问题 | 核心内容 |
|------|----------|----------|
| `q18-using-llms` | LLM 使用方法 | Prompt 工程、Chain-of-Thought 推理，参考 Wei et al. (NeurIPS 2022) |
| `q19-evaluation-llms` | LLM 评估框架 | 多任务基准测试设计，参考 MMLU (ICLR 2021) |

### 专题四：统计不确定性量化
| 模块 | 对应问题 | 核心内容 |
|------|----------|----------|
| `q25_confidence-intervals` | 置信区间估计 | 贝叶斯推断、MC Dropout、Deep Ensemble 等不确定性量化方法 |
| `q26_conformal-prediction` | 保形预测 | 无分布假设的置信集合构造，覆盖率保证（1−α），参考 Angelopoulos & Bates (2022) |

---

## 🛠 技术栈

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=flat&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat&logo=huggingface&logoColor=black)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)

```
Python       >= 3.10
PyTorch      >= 2.0
transformers >= 4.35
numpy / pandas / matplotlib
scikit-learn
```

---

## 🚀 快速开始

```bash
# 1. 克隆仓库
git clone https://github.com/HaiwenPaitience/ML_learnning-code.git
cd ML_learnning-code

# 2. 安装依赖（建议使用虚拟环境）
pip install torch transformers numpy pandas matplotlib scikit-learn jupyter

# 3. 从环境配置开始
cd 00-1_python-setup-guide
jupyter notebook
```

---

## 📖 配套资料

| 资源 | 链接 |
|------|------|
| 八篇文献精读展示页 | [ml_reading_report.html](https://HaiwenPaitience.github.io/ML/ml_reading_report.html) |
| 图文匹配 Live Demo | [clip_demo_live.html](https://HaiwenPaitience.github.io/ML/clip_demo_live.html) |
| CLIP 官方仓库 | [openai/CLIP](https://github.com/openai/CLIP) |
| HuggingFace Transformers | [huggingface/transformers](https://github.com/huggingface/transformers) |

---

## 👤 作者

**李海文 · Li Haiwen**
中国传媒大学 · 信息与通信工程学院 · 数字媒体技术
研究兴趣：深度学习 · 模型量化 · 多模态 · 不确定性量化

---

*本仓库为研究生复试自主学习材料，持续更新中。*
