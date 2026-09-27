# Xiaohongshu Creator Workflow

把真实经历、笔记和资料整理成适合小红书阅读的图文，并协助准备草稿；只有用户明确要求时才发布。

## 安装

Codex 用户可以把本仓库克隆到个人 skills 目录：

```bash
mkdir -p ~/.codex/skills
git clone https://github.com/Rouen007/xiaohongshu-creator-workflow.git \
  ~/.codex/skills/xiaohongshu-creator-workflow
```

如果使用自定义的 `CODEX_HOME`，请将仓库放到 `$CODEX_HOME/skills/xiaohongshu-creator-workflow`。安装后重新加载或重启 Codex，使其发现新 skill。

## 使用

可以在 Codex 中显式调用：

```text
$xiaohongshu-creator-workflow 帮我把这些经历整理成一篇小红书图文，先准备草稿让我审核。
```

也可以直接用自然语言提出需求，例如“把这份活动记录写成小红书笔记，做一张封面和几张流程图”。Skill 会根据任务协助梳理来源事实、撰写标题正文和话题、制作或整理配图，并在有可用的创作页面时协助上传。

## 工作流程与发布边界

- 先区分已确认事实、个人感受和建议；重要日期、费用或流程要求以原始资料为准，不为增强故事性编造细节。
- 先明确帖子范围，再按时间线整理；长内容拆成便于手机阅读的段落。
- 上传前核对图片顺序、文字、可见范围和隐私信息；默认不公开证件号、申请号、条码、私人邮箱、地址或未遮挡的通知截图。
- 上传草稿不等于发布。只有用户明确要求发布，且发布内容与确认稿一致时才进行发布；若创作界面无法安全操作，就停下并说明如何由用户完成。
- 个人经历不是官方规则。签证、旅行等流程信息应注明以当事人收到的最新通知和现场要求为准。

## 文件

- [`SKILL.md`](SKILL.md)：完整的技能说明和执行边界。
- [`agents/openai.yaml`](agents/openai.yaml)：Codex 界面展示名称和简介。

本仓库不需要额外运行时依赖。
