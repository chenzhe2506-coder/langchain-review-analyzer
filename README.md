## 项目

**目标**：基于 LangChain + RAG 的亚马逊差评语义聚类系统
**开工**：2026-05-10（周日）
**截止**：2026-06-09（30 天）

**简历讲法**：
> 基于 LangChain + RAG 构建电商评论智能分析系统，实现差评语义聚类与历史相似案例检索，辅助卖家选品决策

## 技术栈

- Python + DeepSeek API（兼容 OpenAI SDK）
- LangChain（LCEL 语法）
- ChromaDB（本地向量数据库）
- requests / BeautifulSoup（爬亚马逊评论）

## 4 周路线

- **W0（5/5-5/9）摸鱼时间**：补 Python 工程化最小套件（venv / pip / requirements.txt / 项目目录）
- **W1（5/10-5/16）**：直调 DeepSeek API，写 5 个 prompt 实验（不用 LangChain）
- **W2（5/17-5/23）**：LangChain LCEL 最小闭环（PromptTemplate | ChatModel | StrOutputParser）
- **W3（5/24-5/30）**：RAG（Document Loader → Splitter → Embedding → Chroma → Retriever）
- **W4（5/31-6/6）**：整合到差评项目（prompt 调优 + 输出结构化 + RAG 增强）
- **6/9**：可 demo 版本 + 完整 README

## 注意

- Agent **不在** 30 天范围
- 30 天 KPI：800 行 Python / 10 次 GitHub 提交 / 1 篇技术文章
