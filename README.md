# quanttide-gallery-of-knowledge-engineering

量潮知识工程工作案例

## 简介

本仓库收录了量潮知识工程团队的实践案例，涵盖知识图谱构建、本体建模、知识抽取与管理等知识工程领域的实际项目示例。

## 层次说明

每个案例按知识加工深度分为四层：

| 层 | 目录 | 说明 | 格式 |
|---|------|------|------|
| **Data** | `data/` | 原始材料，未经处理的源素材 | 任意原始格式 |
| **Information** | `information/` | 从 data 中提取出的信息，已过滤和整理 | Markdown |
| **Knowledge** | `knowledge/` | 结构化知识，包含 domain、ontology、instance 的 JSON | JSON |
| **Wisdom** | `wisdom/` | 将 knowledge 翻译为可编程的代码模型和规则 | Python |

从 data 到 wisdom 的加工依次递进：

```
data → information → knowledge → wisdom
           提取        结构化      代码化
```

## 案例列表

### 代码重构（code/refactor）

| 层 | 文件 | 内容 |
|----|------|------|
| Data | — | Martin Fowler 重构理论相关资料（外部引用） |
| Information | `information/code/refactor.md` | 重构主题整理后的 Markdown 文档 |
| Knowledge | `knowledge/code/refactor.json` | 6 个本体 + 24 个实例（含关系）的 JSON |
| Wisdom | `wisdom/code/refactor.py` | 使用 Pydantic 定义的知识库模型 |

```
information/code/refactor.md  →  knowledge/code/refactor.json  →  wisdom/code/refactor.py
       （信息）                         （知识）                          （智慧）
```

## 许可

本仓库采用 [Creative Commons Attribution 4.0 International (CC BY 4.0)](LICENSE) 许可协议。
