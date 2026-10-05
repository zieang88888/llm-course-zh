# LLM Course 全量章节索引

> 本索引收录源项目 [mlabonne/llm-course](https://github.com/mlabonne/llm-course) 的全部 **20 个章节**（2026-10-05 按源 README 编号章节标题实测）。章节链接指向源 README 对应锚点，即点即学。

## 🧩 LLM Fundamentals（4 章 · 可选）

| 编号 | 中文译名 | 英文原名 | 一句话要点 |
| --- | --- | --- | --- |
| 1 | 机器学习数学基础 | Mathematics for Machine Learning | 线性代数 / 微积分 / 概率与统计 |
| 2 | Python 机器学习 | Python for Machine Learning | 数据科学库、预处理与 Scikit-learn |
| 3 | 神经网络 | Neural Networks | 反向传播、优化器、防过拟合、MLP |
| 4 | 自然语言处理 | Natural Language Processing (NLP) | 分词、词嵌入、RNN/LSTM/GRU |

## 🧑‍🔬 The LLM Scientist（8 章 · 核心）

| 编号 | 中文译名 | 英文原名 | 一句话要点 |
| --- | --- | --- | --- |
| 1 | LLM 架构 | The LLM Architecture | Transformer、分词、注意力、采样策略 |
| 2 | 预训练模型 | Pre-Training Models | 数据准备、分布式训练、优化与监控 |
| 3 | 后训练数据集 | Post-Training Datasets | 存储格式、合成数据、数据增强与质量过滤 |
| 4 | 监督微调 | Supervised Fine-Tuning | LoRA/QLoRA、训练参数、分布式与监控 |
| 5 | 偏好对齐 | Preference Alignment | 拒绝采样、DPO、GRPO、PPO 与奖励模型 |
| 6 | 模型评估 | Evaluation | 自动化基准、对齐评估与 Goodhart 定律 |
| 7 | 量化 | Quantization | 8-bit / GPTQ / GGUF / EXL2 压缩与推理加速 |
| 8 | 前沿趋势 | New Trends | 模型合并（MergeKit）与新兴训练技术 |

## 👷 The LLM Engineer（8 章 · 核心）

| 编号 | 中文译名 | 英文原名 | 一句话要点 |
| --- | --- | --- | --- |
| 1 | 运行 LLM | Running LLMs | 模型访问与基础提示工程 |
| 2 | 向量存储 | Building a Vector Storage | 文档摄入与嵌入存储 |
| 3 | 检索增强生成 RAG | Retrieval Augmented Generation | 基础检索增强流水线 |
| 4 | 高级 RAG | Advanced RAG | 查询优化、路由与工具调用 |
| 5 | Agent 智能体 | Agents | 自主任务执行、协议与框架 |
| 6 | 推理优化 | Inference optimization | 性能调优与成本控制 |
| 7 | 部署 LLM | Deploying LLMs | 生产环境部署实践 |
| 8 | 安全加固 LLM | Securing LLMs | 提示注入、后门与防御 |

---

## 实战 Notebook（23 个）

源课程配套 **23 个 Colab Notebook**，分组如下（2026-10-05 按源 README 逐条计数）：

| 分组 | 数量 | 代表内容 |
| --- | --- | --- |
| Tools | 8 | LLM AutoEval / LazyMergekit / AutoQuant / ZeroSpace 等自动化工具 |
| Fine-tuning | 6 | Unsloth 微调 Llama 3.1 / ORPO / DPO / QLoRA / Axolotl |
| Quantization | 4 | 8-bit / GPTQ / GGUF+llama.cpp / EXL2 |
| Other | 5 | MergeKit 合并 / MoE / abliteration / 知识图谱 / 解码策略 |

> Notebook 直达链接见源 README「📝 Notebooks」部分：https://github.com/mlabonne/llm-course/blob/main/README.md

## 索引说明

- 章节名与 Notebook 分组取自源 README 全文（经 jsDelivr CDN 抓取原文，2026-10-05）。
- 源 README 直达：https://github.com/mlabonne/llm-course/blob/main/README.md
