# sl-skill

我自用 & 供大家娱乐使用的 [Claude Code / Agent Skills](https://agentskills.io) 合集。持续更新，一个仓库放多个 skill。

## Skill 列表

| Skill | 说明 |
|-------|------|
| [vibe-modes](skills/vibe-modes/) | 回复点缀·氛围模式**总控**（装一次 = 全部持续模式）：7 个可独立开关、可叠加的频道——激励、丧(消极)、废话文学、经典台词、歌词、古诗词、古文；开启后在回复开头/末尾加一句点缀，随时开关。真实类频道（台词/歌词/诗词/古文）严格只引真实原句。 |
| [light-humor](skills/light-humor/) | 轻松一刻·讲个笑话（触发「讲个笑话」）：按需点播，点一次给一个干净、善意、老少咸宜的笑话（谐音梗/冷笑话/生活观察）；点播隔离、不污染对话、不涉黄不冒犯。 |
| [innuendo-tales](skills/innuendo-tales/) 🔞 | **18+** 双关叙事点播（触发「开个车」，本合集唯一成人向）：点一段表面正经、通篇强双关的连续叙事（5–10 句），暗示明白好懂（谐音+强指示）却全程不点破、不露骨；点播隔离、不污染上下文、守全部红线（未成年/非自愿/歧视/重口/真人，均含"别误杀"判据）。 |

## 安装

每个 skill 就是 `skills/` 下的一个文件夹。把想用的拷到你的个人 skills 目录即可：

```bash
# Claude Code（用户级 skill 目录）
git clone https://github.com/SymbolLong/sl-skill.git
cp -r sl-skill/skills/vibe-modes ~/.claude/skills/      # 或拷你想要的那个
```

装好后重启 / 新开对话，Claude 就能识别到这个 skill。

## 用法示例

以 `vibe-modes` 的激励频道为例：

```
你：开启激励模式
Claude：✅ 激励模式已开启（随机风格）……

你：帮我看下这段代码
Claude：💪 这点 bug 算什么，冲！

      好的，这段代码……

你：开启诗词模式        # 频道可叠加
你：关闭激励模式
Claude：激励模式已关闭 👌
```

## License

MIT，随便用，图一乐。
