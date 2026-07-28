# Personal Agent Skills

这个仓库用于集中管理个人创建或整理的 Agent Skills。每个 Skill 均保存在独立目录中，便于安装、更新和继续扩充。

## Skills

- [`align-before-execution`](skills/align-before-execution/)：在高复杂度、高歧义、高成本或高风险任务执行前，按风险等级对齐目标、范围、约束与验收标准。

## 目录约定

```text
skills/
└── <skill-name>/
    ├── SKILL.md
    ├── agents/
    │   └── openai.yaml
    ├── scripts/       # 可选
    ├── references/    # 可选
    └── assets/        # 可选
```

`SKILL.md` 是 Skill 的必需文件。`agents/openai.yaml` 是面向 ChatGPT/Codex 的可选界面元数据；其他目录仅在工作流确有需要时添加。
