# beidou-tzb(北斗添装包)

北斗添装包:给短剧分镜"添"料用的 Claude Code 用户级 skill。目前两件:

| skill | 干什么 |
|---|---|
| [beidou-bq](skills/beidou-bq/) | **夸张表情库**——十族约百条表情写法(震惊惊吓/慌张尴尬/暴怒/悲哭/狂喜/嫌弃/馋爽破防/得意欠揍/恐惧崩溃/无语静默),情绪高点直接取条目抄进分镜。真人写实内夸张、一镜一表情动作、不卡通化,自带防重复三层保险 |
| [beidou-xjc](skills/beidou-xjc/) | **小剧场**——剧情演到触发点(咬下食物/打完一场/误会被拆穿/开箱揭晓……)时切出去,单独演一段 10~30 秒的夸张搞笑小段,演完切回正片。一集可放多个、不限片尾;五形态五十多种玩法,防重复四层保险 |

一对搭档:**表情库是零件,小剧场是用零件搭的一段戏**。通用所有题材:美食、玄幻、萌宝、都市、悬疑、宫斗、职场、乡村都行。

## 安装

把 `skills/` 下的两个文件夹整个复制到 Claude Code 的技能目录:

- Windows:`C:\Users\<你的用户名>\.claude\skills\`
- macOS / Linux:`~/.claude/skills/`

复制完重开 Claude Code 即可。对话里说"来个夸张表情""加个小剧场"这类话就能触发,也可以直接点名 `/beidou-bq`、`/beidou-xjc`。

## 文件结构

```
skills/
  beidou-bq/                     夸张表情库
    SKILL.md                     定位、三条硬规矩、用库四步、自检
    references/biaoqing-ku.md    十族约百条 + 漫画效果→真人写实替代表 + 镜头配合手法
  beidou-xjc/                    小剧场
    SKILL.md                     定位、定死规矩、七步工作流、自检
    references/xjc-shoufa.md     五形态玩法 + 高频触发点轮换表
    references/xjc-fanli.md      成段范例(四个题材)
```
