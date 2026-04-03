# ⭐ Kaiyang Zheng的多模态大模型知识库
Multimodal Large Models Knowledge Base

本仓库旨在系统梳理：

- 深度学习与大模型基础理论
- 多模态学习与建模方法
- 多模态大模型体系与工程实践

---

# 📚 知识体系结构

## 🧱 第一部分：基础组件（从最小单元开始）

1. [整体架构](docs/1.%20Architecture%20大模型整体架构.md)
2. [Tokenization / 分词](docs/1.1%20Tokenization%20分词.md)
3. [Embedding / 词嵌入](docs/1.2%20Embedding%20词嵌入.md)
4. [Attention / 注意力](docs/1.3%20Attention%20注意力.md)
5. [FFN、残差、层归一化](docs/1.4%20FFN%20%26%20Add%20%26%20LN%20前馈层、残差、层归一化.md)
6. [Positional Encoding / 位置编码](docs/1.5%20Positional%20Encoding%20位置编码.md)

---

## 🏗️ 第二部分：训练范式（从表示学习到能力对齐）

1. [Pre-training / 预训练](docs/2.%20Pre-training%20预训练.md)
2. [预训练定义](docs/2.1%20预训练定义.md)
3. [预训练数据](docs/2.2%20预训练数据.md)
4. [预训练流程](docs/2.3%20预训练流程.md)
5. [预训练评估](docs/2.4%20预训练评估.md)
6. [Post-training / 后训练](docs/3.%20Post-training%20后训练.md)
7. [SFT 监督微调](docs/3.1%20SFT%20监督微调.md)
8. [RL 强化学习基础](docs/3.2%20RL%20强化学习基础.md)
9. [RLHF](docs/3.3%20RLHF%20基于人类反馈的强化学习.md)
10. [DPO 直接偏好优化](docs/3.4%20DPO%20直接偏好优化.md)
11. [PEFT 参数高效微调](docs/3.5%20PEFT%20参数高效微调.md)
12. [大模型自动评估](docs/3.6%20大模型自动评估.md)

---

## 🤖 第三部分：模型谱系（从经典 LLM 到 MLLM）

1. [Common Models / 常见模型](docs/4.%20Common%20Models%20常见模型.md)
2. BERT 及变体
3. PaLM 系列
4. GPT 系列
5. GLM 系列
6. Qwen 系列
7. DeepSeek 系列
8. MoE 系列
9. 多模态大模型发展脉络
10. 多模态大模型核心能力边界

---

## ⚙️ 第四部分：训练与推理系统（从模型到系统）

1. [训练推理优化](docs/5.%20Training%20%26%20Inferring%20训练推理优化.md)
2. [显存占用分析](docs/5.1%20训练推理显存占用分析.md)
3. [FlashAttention 原理](docs/5.2%20FlashAttention原理.md)
4. [PageAttention 原理](docs/5.3%20PageAttention原理.md)
5. [推理框架](docs/5.5%20推理框架.md)
6. [推理耗时及优化](docs/5.6%20推理耗时及优化.md)
7. [Packing 技巧](docs/5.7%20大模型的packing技巧.md)
8. [训练与推理扩展的转变](docs/训练与推理扩展的转变.md)

---

## 🎥 第五部分：多模态与应用能力（从单模型到任务系统）

1. [Application / 大模型应用](docs/6.%20Application%20大模型应用.md)
2. [Prompt 技术](docs/6.1%20Prompt%20Tech%20提示技术.md)
3. [LLM-based Agent](docs/6.2%20LLM-based%20Agent%20基于大模型的智能体.md)
4. [RAG 检索增强生成](docs/6.3%20RAG%20检索增强生成.md)
5. [RAG 优化工作](docs/6.4%20RAG优化工作推荐.md)
6. [Deep Research](docs/6.5%20Deep%20Research工作梳理及推荐.md)
7. 多模态融合方法
8. 基于知识图谱的多模态数据分析
9. 多模态大模型幻觉
10. 多模态大模型可解释性
11. MLLM 的计算瓶颈

---

## 🗜️ 第六部分：模型压缩与部署（从能力到成本）

1. [Compression / 模型压缩](docs/7.%20Compression%20模型压缩（了解）.md)
2. [Quantization / 模型量化](docs/7.1%20Quantization%20模型量化.md)
3. [Pruning / 模型剪枝](docs/7.2%20Pruning%20模型剪枝.md)
4. [Knowledge Distillation / 知识蒸馏](docs/7.3%20Knowledge%20Distillation%20知识蒸馏.md)
5. [Low-Rank Factorization / 低秩分解](docs/7.4%20Low-Rank%20Factorization%20低秩分解.md)

---

## 📄 第七部分：论文阅读与技术跟踪（从体系到前沿）

1. [论文阅读笔记](docs/8.%20Papers%20论文阅读笔记.md)
2. 技术报告详解
3. o1 技术路线论文
4. Prompt 相关论文
5. LLM-as-Judge
6. 评估体系与 Critical 模型
7. 拓展阅读
8. 工作推荐系列

---

## 🛠️ 第八部分：实践与复现（从理解到落地）

1. [Practice / 大模型实践内容](docs/9.%20Practice%20大模型实践内容.md)
2. nanoGPT：从头训练一个 GPT
3. OpenRLHF 微调教程及代码解析
4. 从零开始训练大模型（预训练篇）
5. 从零开始训练大模型（SFT 篇）
6. 从零开始训练大模型（DPO 篇）
7. 从零开始训练大模型（蒸馏篇）
8. PRM / MCTS / ReFT 等专项实践
9. 数据合成 Agent 框架实现
10. 企业内部工具 Agent 工作流

---

## 🧩 第九部分：附录（面试 / 八股 / 入门导航）

1. [Interview / 大模型面试八股](docs/10.%20Interview%20大模型面试八股.md)
2. Python 相关八股
3. 实习校招面经合集
4. Transformer 量化分析计算
5. 面试手撕专题
6. 机器学习 / 深度学习八股
7. AGENT 专项
8. tool-use 数据合成
9. Agentic 能力优化策略
10. Agentic 入门项目推荐
