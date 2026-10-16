# Scientific Writing Coach

一个从作者问答出发的科研写作 skill：先澄清研究问题、主张和证据，再整理段落逻辑，最后润色中英文表达。

适用于科研论文和研究计划的反复讨论、逻辑检查与改写。已确定的目标和回答会沿用，不要求每次重新填写问卷。摘要、引言、相关工作、方法、结果和讨论各有独立指南，按当前任务加载。

## 安装与使用

将本仓库中的 `scientific-writing-coach/` 文件夹放入 Codex 的本地 skills 目录（通常为 `~/.codex/skills/`），使入口位于：

```text
~/.codex/skills/scientific-writing-coach/SKILL.md
```

调用示例：

```text
请使用 $scientific-writing-coach 检查这份研究计划。
先指出研究问题、目标和方法之间的逻辑缺口；已有回答请沿用。
按我补充的观点修改段落，以英文为主，并在每段下附中文翻译。
```

## 内容结构

- [SKILL.md](scientific-writing-coach/SKILL.md)：工作流程与章节路由。
- [作者问答](scientific-writing-coach/references/author-dialogue.md)：从稿件中识别需要澄清的问题。
- [段落逻辑](scientific-writing-coach/references/paragraph-logic.md)：逆向提纲、论证衔接与重复检查。
- [语句表达](scientific-writing-coach/references/sentence-style.md)：语言润色、术语和双语一致性。
- `references/`：摘要、引言、相关工作、方法、结果、讨论、结论和研究计划的独立指南。
- `agents/openai.yaml`：Codex 界面名称与调用提示。

## 来源与边界

本技能受北美老刘（Liu）写作课程启发，结合科研编辑实践整理，不是课程官方教材或全部课程的逐字摘要。[来源说明](scientific-writing-coach/references/sources.md)记录了核实范围与材料出处。

技能辅助作者澄清和表达研究判断，不虚构数据、引用或结论，也不将相关性改写为因果性。模板服从作者实际证据、期刊或学校规范及用户要求。
