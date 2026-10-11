# Lecture Core Revision

将大学课件和带时间戳的讲课字幕整理成简洁、可读的复习笔记。

## 特点

- 按原讲课顺序整理，保留页码、时间戳、机制、例子和重要数值。
- 英文解释为主，关键科学术语附中文。
- 区分课件、讲师字幕和 AI 补充解释，注明缺失来源。
- 最后提供 Exam / revision focus。
- 可选 Notion 同步：需要使用者连接 Notion，并提供目标目录。

## 安装到 Codex

下载本仓库 ZIP 并解压，将整个 `lecture-core-revision` 文件夹复制到
`~/.codex/skills/`，然后重启 Codex。

也可以向 Codex 提出：

> 请使用 skill-installer，从 13916947604-maker/git 仓库安装 lecture-core-revision 目录中的 Skill。

## 使用示例

上传匹配的课件和字幕后输入：

> 使用 $lecture-core-revision 整理这节课的核心复习笔记。保留原始页码和时间戳，英文解释为主，关键术语附中文。

如需 Notion 同步，明确提出同步要求，并提供你有写入权限的目录页面。

## 文件

- `lecture-core-revision/SKILL.md`：核心工作指令。
- `lecture-core-revision/agents/openai.yaml`：Codex 界面元数据。

本仓库不包含课程课件、字幕、笔记、登录凭据或私人 Notion 页面地址。
