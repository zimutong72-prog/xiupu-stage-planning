# 秀谱｜舞台策划 Skill

秀谱帮助秀导把口头创意、节目资料和各工口反馈整理成可编辑的导演策划案和七列 Q 表。从创意讨论到排练、彩排和现场改稿，可以在同一对话里带着最新确认版继续做。

## 快速开始

在 Codex 对话里发送下面的安装指令。

```text
请用 $skill-installer 安装这个 Skill：
https://github.com/zimutong72-prog/xiupu-stage-planning/tree/main/xiupu-stage-planning
```

安装后，新开对话，输入 `$xiupu-stage-planning` 并从技能选择器选中它。如果没显示，重启 Codex 后再试。手动安装时，把仓库里的整个 [xiupu-stage-planning 文件夹](xiupu-stage-planning) 复制到 `~/.agents/skills/`，保留 `SKILL.md`、`agents/` 和 `references/`。

## 第一次使用

只调用 Skill，或在启用 Skill 的对话里只提交素材、没有说明任务时，秀谱会先回复：

> 秀谱舞台策划已就绪。现在开始工作吗？回复「开始」，或直接发给我节目需求、参考片段或已有方案。

回复「开始」后，可以用大白话讲想法。已提供明确任务时，秀谱直接开始。启动确认在同一个对话里最多出现一次。

例如，可以直接发送：

```text
用 $xiupu-stage-planning 帮我做一个 60 秒音乐会开场。
8 名舞者，一块主屏，两侧可上场。开头只看见一个人，副歌才看见全队。
请写一段导演策划说明和七列 Q 表草稿。
```

## 工作流程

1. **从想法到概念。** 整理创作者想要的感受、关键画面、已确认条件和待确认项。
2. **从概念到方案。** 按节目时间、音乐、台词、人员与调度、视觉、灯光、道具起草 Q 表，为每条 Cue 记录触发与衔接。音源未定时标注建议触发点。
3. **给方案补参考。** 按段落找实拍、切片或参考图，标明看哪里、借什么、怎么适配。真实链接依赖当前对话的联网能力，无法检索时提供可复制的搜索词。
4. **定稿并持续改稿。** 秀导确认 V1 后，可以带着导演意见、工口反馈或彩排实测时间继续改稿。秀谱先列受影响的 Cue、字段和冲突，确认后再给新版。

试改稿时，可以补一句：「导演说 8 人改成 6 人，保留副歌揭示全队的时机。先给我看哪些 Cue 要改。」

[完整的 60 秒方案和改稿示例](xiupu-stage-planning/references/example.md) · [舞台参考检索规则](xiupu-stage-planning/references/reference-search.md) · [Skill 本体](xiupu-stage-planning/SKILL.md)

## 许可证

本项目采用 [MIT 许可证](LICENSE)。
