# community-buzz

`community-buzz` 帮 Agent 从知乎、B站、什么值得买、V2EX、NGA、贴吧和垂直论坛中寻找有真实内容的产品口碑与实践讨论。

## 筛选方式

- 新采的帖子、回答、视频、评论或回复，只有对象自身原生正向计数不少于 10 才能成为最终证据；帖子和评论分别计算。
- 通过门槛后，只提取具体体验、比较、长期反馈和明确争议。
- 同一内容的转载和重复发布合并，不累加点赞。

每条结果都会解释它在说什么、为什么值得看，并附来源、时间和采集时的正向计数，而不是只发标题。

## 安装

```bash
git clone https://github.com/ruodou233/community-buzz.git ~/.codex/skills/community-buzz
```

也可克隆到 `~/.claude/skills/community-buzz`。

## 使用示例

- “帮我看看社区怎么评价这款耳机。”
- “A 和 B 哪个真实口碑更好？”
- “这个产品论坛里有人长期用过吗？”

## License

MIT
