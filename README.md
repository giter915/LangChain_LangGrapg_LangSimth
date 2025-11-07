##  LangChain × LangGraph × LangSmith 

项目简介

本项目是对 **LangChain、LangGraph 与 LangSmith** 三个核心组件的系统讲解与实战演示。
 旨在帮助学习者理解如何从 **Prompt → Chain → Graph → 调试监控** 构建完整的智能体系统。

### 🏗️ 技术栈

| 模块          | 作用说明                                                     |
| ------------- | ------------------------------------------------------------ |
| **LangChain** | 提供 LLM 调用、文档加载、向量检索、工具集成等基础组件        |
| **LangGraph** | 用于构建带有状态与分支逻辑的智能体流程图（如条件节点、循环、记忆流） |
| **LangSmith** | 可视化调试与性能分析工具，用于追踪链式调用、查看中间结果与执行路径 |

------

### 🧠 内容结构

1. **LangChain **

   - PromptTemplate / Chain / Memory / Tool / Agent 概念
   - 构建最小可运行链（LLM + Prompt）
   - 集成 FAISS / Chroma 等向量数据库实现 RAG

2. **LangGraph **

   - GraphNode / ConditionalEdge / MemoryState
   - 多轮任务分支与异常处理机制
   - 将复杂业务流程用图结构实现可视化与复用

3. **第LangSmith **

   - 跟踪链执行过程
   - 分析 Token 消耗与延迟





视频链接：

<https://www.bilibili.com/video/BV1wUWtzoEpc/?spm_id_from=333.337.search-card.all.click>



