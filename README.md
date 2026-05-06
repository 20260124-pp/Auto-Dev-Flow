# Auto-Dev-Flow 🚀

### 简介
这是一个基于 Java 17 和 LangChain4j 构建的多智能体 (Multi-Agent) 开发工作流原型。它旨在通过 AI 协作自动完成从需求分析到代码实现的过程。

### 核心智能体架构
1. **Architect Agent**: 负责根据自然语言描述设计数据库 Schema 和接口定义。
2. **Coder Agent**: 负责编写符合最佳实践的 Java Controller、Service 和 Mapper 代码。
3. **Reviewer Agent**: 负责对代码进行安全性和性能审计，并提出修改建议。

### 技术栈
- **Language**: Java 17
- **Framework**: Spring Boot, LangChain4j
- **IDE**: Trae / Cursor
- **Model**: Gemini-3-Flash / Xiaomi MiMo
