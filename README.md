# justin-skills

Justin 收藏与整理的 Agent Skills（可直接丢进 Claude Code / Cursor 等支持 `SKILL.md` 的工具）。

首页只列已收录的 skill；正文尽量保持来源原样。

## Skills

| Skill | 说明 |
|-------|------|
| [project-architecture-map](skills/project-architecture-map/SKILL.md) | 用一段提示词，让模型根据真实代码画出可交互的「项目架构与运行流程地图」（偏可视化，不是纯文档 wiki）。 |

### 1. project-architecture-map（本仓第一个）

- **路径：** `skills/project-architecture-map/SKILL.md`
- **来源 Gist（原样）：** https://gist.github.com/linearuncle/f9e22e01477c44c328f8e34103ec5fd2
- **介绍贴：** [@LinearUncle](https://x.com/LinearUncle/status/2105506429788422409) — 把通用版提示词放进 Gist；实测 Opus 画架构地图，和 Devin deepwiki 相比更偏可视化。
- **灵感原帖：** [@robinebers](https://x.com/robinebers/status/2105309987983745060) — 功能迭代太快、架构跟不上时，让 Claude Opus 通读项目并做架构梳理。

用法：把该目录装进你的 skills 目录，或把 `SKILL.md` 正文当作提示词直接粘贴给模型。

## 许可与归属

各 skill 正文归属原作者；本仓仅作收藏与 `SKILL.md` 封装。若原作者要求调整，开 issue 或联系 Justin。
