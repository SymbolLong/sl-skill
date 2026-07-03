# sl-skill

我自用 & 供大家娱乐使用的 [Claude Code / Agent Skills](https://agentskills.io) 合集。持续更新，一个仓库放多个 skill。

## Skill 列表

| Skill | 说明 |
|-------|------|
| [motivation-mode](skills/motivation-mode/) | 激励模式：手动开启后，每条回复开头自动来一句中文激励语（治愈 / 毒鸡汤 / 热血，可选可随机），用户随时开关。 |
| [nonsense-literature](skills/nonsense-literature/) | 废话文学模式：手动开启后，每条回复末尾追加 3–5 句与正文无关的废话文学（同义反复 / 正确的废话 / 循环因果），现场新造、点到为止，用户随时开关。 |

## 安装

每个 skill 就是 `skills/` 下的一个文件夹。把想用的拷到你的个人 skills 目录即可：

```bash
# Claude Code（用户级 skill 目录）
git clone https://github.com/SymbolLong/sl-skill.git
cp -r sl-skill/skills/motivation-mode ~/.claude/skills/
```

装好后重启 / 新开对话，Claude 就能识别到这个 skill。

## 用法示例

以 `motivation-mode` 为例：

```
你：开启激励模式
Claude：✅ 激励模式已开启（随机风格）……

你：帮我看下这段代码
Claude：💪 这点 bug 算什么，冲！

      好的，这段代码……

你：关闭激励模式
Claude：激励模式已关闭，恢复正常 👌
```

## License

MIT，随便用，图一乐。
