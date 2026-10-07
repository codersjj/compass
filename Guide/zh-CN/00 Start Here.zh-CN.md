# 从这里开始

[中文 README](../../README.zh-CN.md) · [配置与本地化](01%20Configuration%20and%20Localization.zh-CN.md) · [术语表](Terminology.zh-CN.md) · [英文原文](../00%20Start%20Here.md)

Compass 从每日记录开始，逐步加入规划、习惯、任务、写作和可选的 AI 助手。当前仓库是开发候选版，已发布的 1.0.2 压缩包不包含 Life OS 应用；本指南中的应用语言选择适用于本次开发候选版。打包和原生 Obsidian 验收仍是独立要求。

## 第一次打开

1. 将仓库或解压后的目录作为 Obsidian 笔记库打开。需要 Obsidian 1.13.1 或更新版本。
2. 在 **Restricted mode** 提示中选择 **Turn off**。如果已关闭提示，到 **Settings → Community plugins** 关闭受限模式。
3. 用 `Ctrl/Cmd+P` 打开命令面板，执行 **Reload app without saving**。Life OS 自动打开。若需再次打开，用 `Ctrl/Cmd+Shift+L` 或 **Life OS: Open Life OS home**。
4. 在应用顶部选择 **简体中文**。默认语言是 English；选择会保存，未翻译的界面文字显示英文。语言选择不会改写笔记或更改 Obsidian 和第三方插件的语言。
5. 打开 [Setup](../../00%20Dashboards/Setup.md)，查看设置清单。如果看到代码而非清单，先检查社区插件是否已启用和重新加载。

## 今晚先做一件事

用 `Ctrl/Cmd+Shift+D` 创建或打开当天日记，用 `Ctrl/Cmd+Shift+Q` 回答每日问题。每项以 1 到 10 分记录“我是否尽了最大努力”，评价努力程度，避免用成果好坏替代。然后在 `## Journal` 下写一句话。

问题和习惯来自 [Compass Config](../../Meta/Compass%20Config.md)。可以先把问题文字改成中文，保留属性键；步骤见[配置与本地化](01%20Configuration%20and%20Localization.zh-CN.md)。模板的 `Journal`、`Wins` 和 `Gratitude` 等标题需要保持原样，快捷记录和嵌入链接使用这些标题。

## 前 30 天

每天早上打开日记，每晚回答问题。优先建立习惯，不必一次填完所有仪表盘或启用 AI。

- 第 3 天：只调整一个不贴切的问题的 `text`。
- 第 7 天：查看[每日问题仪表盘](../../00%20Dashboards/Daily%20Questions.md)，观察已有记录。
- 真实记录建立后：按 Setup 清单识别并逐项删除 `example` 示例笔记。它们不是你的生活记录。
- 30 天后：稳定记录再增加下一层。英文[构建顺序](../11%20Build%20Order.md)建议先加入 3 到 5 个习惯和每周回顾，然后加入季度个人复盘及规划，之后再加入任务、写作和阅读。

## Life OS 导航

| 模块 | 用途 |
| --- | --- |
| 首页（Home） | 需要关注的任务、快捷记录与规划入口 |
| 今天（Today） | 当天问题、习惯和记录入口 |
| 规划（Plan） | 每日、每周、季度和个人复盘笔记 |
| 专注（Focus） | 按时间状态整理的待办事项 |
| 回顾（Review） | 每日努力、习惯及生活领域的记录趋势 |
| 项目（Projects） | 项目笔记和看板 |
| 人物（People） | 关系笔记和待讨论事项 |
| 创作（Create） | 写作流程和看板 |
| 资料库（Library） | 阅读、书籍和来源笔记 |
| AI | 可选的助手工作流和配置入口 |

界面摘要来自原有 Markdown 文件和属性。图表中的空白表示缺少记录，不能当作零分；示例数据默认排除。详情见[Life OS 英文指南](../21%20Life%20OS%20Application.md)及[数据定义](../22%20Data%20Definitions.md)。

## 后续阅读

中文文档覆盖入门和配置。现有 Markdown 仪表盘、模板、完整英文指南和 AI 提示词仍保留英文；切换应用语言不会翻译它们。其余工作流从[英文入门地图](../00%20Start%20Here.md)进入，插件清单见[插件指南](../02%20Plugins.md)。更新前先备份完整笔记库，并参考[发布清单](../../scripts/RELEASE.md)逐项迁移个人内容和配置。
