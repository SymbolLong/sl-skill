# sl-skill

我自用 & 供大家娱乐使用的 [Claude Code / Agent Skills](https://agentskills.io) 合集。持续更新，一个仓库放多个 skill。

## Skill 列表

| Skill | 说明 |
|-------|------|
| [motivation-mode](skills/motivation-mode/) | 激励模式：手动开启后，每条回复开头自动来一句中文激励语（治愈 / 毒鸡汤 / 热血，可选可随机），用户随时开关。 |
| [nonsense-literature](skills/nonsense-literature/) | 废话文学模式：手动开启后，每条回复末尾追加 3–5 句与正文无关的废话文学（同义反复 / 正确的废话 / 循环因果），现场新造、点到为止，用户随时开关。 |
| [classic-lines](skills/classic-lines/) | 经典台词模式：手动开启并指定作品（剧/影/动漫/文学/游戏），每条回复末尾附 1 句该作品的真实经典台词原句；严格只引确有其事的原句，不瞎编，用户随时开关。 |
| [saucy-jokes](skills/saucy-jokes/) 🔞 | **18+** 老司机·荤段子点播：按需点播（非持续模式），点一次给一个成人段子，引用块隔离、点完即回归正常、绝不主动开车也不污染正经对话；守未成年/非自愿/歧视/重口等红线。 |
| [innuendo-tales](skills/innuendo-tales/) 🔞 | **18+** 色魔狂人·双关叙事点播：点一段表面正经、通篇强双关的连续叙事（5–10 句），暗示明白好懂（谐音+强指示）却全程不点破、不露骨；同样点播隔离、不污染上下文、守全部红线。 |

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
