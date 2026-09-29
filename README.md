# Dev_Skill

这是我的 AI 项目研发工作流 Skill。

## 功能

- 维护项目及各级资料目录的 `README.md` 导航
- 基于本地原始需求、设计图、设计结构化数据、H5 和接口资料进行分析
- 生成需求梳理与范围边界文档
- 通过逐轮确认澄清不确定需求，不自行脑补
- 审查 H5、Bridge 和后端接口契约
- 结合代码库生成技术设计与实施计划
- 按 ITEM → POINT 生成测试用例
- 内置等价类划分、边界值分析和测试用例校验
- 记录实施进展、联调、Bug、测试与验收结果

## 目录

```text
SKILL.md                         Skill 主说明
agents/openai.yaml               Codex 展示信息
references/workflow.md           工作流与需求澄清规则
references/document-templates.md 文档模板
references/test-case-generation.md 测试用例生成规则
scripts/                         测试用例解析、校验和导出脚本
```

## 使用方式

在 Codex 中显式指定：

```text
$ai-project-workflow

分析项目：D:/path/to/project
先读取项目 README 和本地原始材料，不要写代码；不确定内容逐个向我确认。
```

原始材料由用户自行下载并放入项目目录。本 Skill 默认只读取本地材料，不主动联网下载或修改原始文件。
