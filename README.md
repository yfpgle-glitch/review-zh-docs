<div align="center">

# review-zh-docs

**审阅和改写中文 Markdown 文档，让需求、方案和 README 更具体、可执行、可验收**

![Agents](https://img.shields.io/badge/agents-Codex%20%7C%20Claude%20Code%20%7C%20WorkBuddy-202124?style=flat-square)
![Language](https://img.shields.io/badge/language-%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87-2563EB?style=flat-square)
![Documents](https://img.shields.io/badge/documents-Markdown-16A34A?style=flat-square)

[GitHub 仓库](https://github.com/yfpgle-glitch/review-zh-docs)

</div>

---

## 安装 Skill

### Codex / Claude Code

把这句话发给 Codex 或 Claude Code：

```text
请把这个仓库根目录作为 Skill 安装：
https://github.com/yfpgle-glitch/review-zh-docs
```

安装后，如果没有识别，重新打开一个任务或会话。

该仓库为私有仓库，安装端需要使用有访问权限的 GitHub 账号。

### WorkBuddy

1. [下载 Skill 压缩包](https://github.com/yfpgle-glitch/review-zh-docs/archive/refs/heads/main.zip)。
2. 在 WorkBuddy 中打开“添加技能”，选择“上传技能”。
3. 上传刚刚下载的压缩包。

## 使用

直接告诉当前工具要审阅的文档和期望的处理方式：

- `使用 review-zh-docs 审阅 docs/requirements.md，找出空话、缺失边界和不可验收的要求。`
- `使用 review-zh-docs 修改 README.md，让新人能看懂怎么安装、运行和测试。`
- `使用 review-zh-docs 重写方案中的“实施计划”，保留原意并补出待确认项。`
- `使用 review-zh-docs 检查这份 AI 生成的周报，删除套话，保留事实和下一步。`

## 适用文档

- 需求文档、PRD 和功能说明
- 项目 README、模块说明和交接文档
- 技术方案、架构方案和实施计划
- 验收清单、任务拆解和开发路线图
- 周报、复盘、会议纪要和工作总结
- Codex、Claude、ChatGPT 生成或辅助生成的中文 Markdown 项目草稿

## 默认边界

- “看看、检查、审一下”只给审阅意见，不修改文件。
- “修改、整理、重写”才会编辑文档。
- 没有来源的信息标为 `待确认`，不会自行补成事实。
- 没有核对代码、资料或命令时，会明确说明验证范围。
- AI 式空话和聊天痕迹属于检查项，但不做通用创作或人格化文风改写。
