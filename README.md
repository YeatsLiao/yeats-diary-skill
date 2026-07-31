# 夜知的跑者日记

> Yeats_Liao 的跑步内容创作项目

## 关于

这是"夜知日记"的内容仓库。一个程序员/技术博主，用跑步书籍和个人体验为素材，写跑步笔记。不追热点，不蹭流量，只写跑步教会我的事。

小红书主页：[Yeats_Liao](https://www.xiaohongshu.com/user/profile/65dd96f0000000000d026da8)

语雀知识库：[夜知日记](https://www.yuque.com/yeats_liao/yeats_diary)

## 内容特点

- 程序员/技术人视角解读跑步
- 自然口语化，少引号少emoji，不说教
- 四种创作模式：整本书解读 / 一句话启发 / 思想反常识型 / 跑步体验型
- 七种结构变体：标准体 / 提问体 / 倒叙体 / 书信体 / 清单体 / 极短体 / 日记体
- 每篇提供 8 个备选标题，覆盖悬念/反转/极简/场景/情绪/数据/对话/痛点等风格

## 项目结构

```
yeats-diary-skill/
├── README.md                          # 本文件
├── LICENSE                            # MIT License
├── .gitignore                         # Git 忽略规则
├── SKILL.md                           # 核心 Skill（角色/模式/结构/禁忌/示例）
├── references/                        # 参考资料
│   └── books-database.md              # 跑步书籍数据库
├── templates/                         # 写作模板（3 个案例）
│   ├── template-a-book-review.md      # 整本书解读
│   ├── template-b-one-quote.md        # 一句话启发
│   └── template-c-run-experience.md   # 跑步体验型
└── output/                            # 跑步笔记（本地保存，仅上传 3 篇示例）
    ├── 20250608_夜知日记_当我谈跑步时我谈些什么.md
    ├── ...
    └── 20260723_夜知日记_第五十三篇.md
```

## 笔记统计

- 总计 53 篇笔记（含 2 篇标题库）
- 创作周期：2025.06 - 2026.07
- 涉及书籍：村上春树、大迫杰、Scott Jurek、Meb Keflezighi、三浦紫苑、乔治·希恩 等

## 涉及书籍

| 书名 | 作者 | 篇数 |
|------|------|------|
| 《当我谈跑步时我谈些什么》 | 村上春树 | 3 |
| 《天生就会跑》 | Christopher McDougall | 3 |
| 《强风吹拂》 | 三浦紫苑 | 3 |
| 《大迫杰手记》 | 大迫杰 | 4 |
| 《Eat and Run》 | Scott Jurek | 3 |
| 《26 Marathons》 | Meb Keflezighi | 2 |
| 《跑步圣经》 | 乔治·希恩 | 2 |
| 《Let Your Mind Run》 | Deena Kastor | 2 |
| 《Once a Runner》 | John L. Parker Jr. | 1 |
| 《跑出肯尼亚》 | Adharanand Finn | 1 |
| 《跑步锻造灵魂》 | | 1 |
| 《惊人的超慢跑》 | 梅方久仁子 | 1 |
| 《姿势跑法》 | | 1 |
| 《骨骼跑步法》 | | 1 |
| 无书籍（跑步体验型） | | 20+ |

## 使用 Skill 生成新笔记

本项目包含一个 AI 内容生成 Skill，核心定义在根目录 `SKILL.md`。

使用方法：

1. 读取 `SKILL.md` 了解角色设定、创作模式和写作规范
2. 读取 `references/books-database.md` 获取跑步书籍素材
3. 按照四种模式之一生成笔记，保存到 `output/`（仅本地，不提交）
4. 每篇输出包含正文 + 8 个备选标题 + 互动问题 + 标签

## 许可证

MIT

---

*Created by [Yeats_Liao](https://github.com/YeatsLiao) - CSDN 博主 / AI 从业者 / 跑者*
