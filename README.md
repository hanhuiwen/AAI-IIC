# From Stored-Program to Intent-Conditioned Computation (IIC)
## Rethinking the Paradigm for AI-Driven Systems

**Author:** HUIWEN HAN, Lenovo China, China

---

### Abstract / 摘要

#### English Version
For nearly a century, computing systems have been governed by the **stored-program paradigm**, in which explicit programs operate deterministically over data [8]. This assumption underpins core software engineering practices such as debugging, testing, and verification. However, modern AI-driven systems built on foundation models increasingly violate these assumptions: system behavior emerges from interactions among **latent model capabilities**, **runtime intentions**, **retrieved knowledge**, and **contextual signals** rather than static code alone [3].

This article introduces **Intent-Conditioned Computation (IIC)**, a conceptual computation paradigm in which execution is governed by dynamically injected semantic intentions that condition latent computational capabilities. We argue that prompts, policies, and control signals act as **first-class execution parameters**, fundamentally altering the meaning of “program,” “input,” and “correctness.”

We present a high-level architectural decomposition of IIC into five functional roles:
1. **Model Capabilities**
2. **Control Intentions**
3. **Externalized Knowledge**
4. **Deterministic Code**
5. **Data**

This abstraction explains why behavior can change without code modification, why execution is probabilistic yet purposeful, and why classical debugging metaphors no longer suffice. This work is part of the broader **AAI (Architectures of Autonomous Intelligence)** research program and aims to provide a shared conceptual foundation for reasoning about AI-native software systems in research and practice.

**Key Words:** Intent-Conditioned Computation, Foundation Models, Human-AI Interaction, Alignment, AI Safety

---

#### 中文版本
近一个世纪以来，计算系统一直遵循**存储程序范式 (Stored-Program Paradigm)**，即显式程序在数据上进行确定性运行 [8]。这一假设构成了调试、测试和验证等核心软件工程实践的基础。然而，基于基座模型构建的现代 AI 驱动系统日益违背这些假设：系统的行为不再仅仅源于静态代码，而是由**潜能模型能力**、**运行时意图**、**检索到的知识**以及**上下文信号**之间的相互作用涌现而成的 [3]。

本文提出了**意图条件计算 (Intent-Conditioned Computation, IIC)**。这是一种概念性的计算范式，其执行过程由动态注入的语义意图所主导，这些意图对潜能计算能力进行约束和调节。我们认为，提示词 (Prompts)、策略 (Policies) 和控制信号已成为**一等执行参数 (First-class execution parameters)**，从根本上改变了“程序”、“输入”和“正确性”的定义。

我们将 IIC 的高层架构分解为五个功能角色：
1. **模型能力 (Model Capabilities)**
2. **控制意图 (Control Intentions)**
3. **外部化知识 (Externalized Knowledge)**
4. **确定性代码 (Deterministic Code)**
5. **数据 (Data)**

这一抽象解释了为何在不修改代码的情况下行为会发生变化，为何执行过程是概率性但具有目的性的，以及为何经典的调试隐喻不再适用。本研究是更广泛的 **AAI (自主智能架构)** 研究计划的一部分，旨在为研究和实践中推演 AI 原生软件系统提供共同的概念基础。

**关键词：** 意图条件计算、基座模型、人机交互、对齐、AI 安全
