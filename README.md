# 华夏智汇园 UI Library

给 [Google Stitch](https://stitch.withgoogle.com) 和编码代理用的前端设计库。视觉取自当前正在运行的学生工作台（智汇青 / `workbench-teal`），不是另一套皮肤。

## 给 Stitch 用

1. 打开 Stitch，导入这个 GitHub 仓库作为 Library / Design system。
2. 先把本仓库的 `index.html` 设为视觉参考。
3. 每次生成页面时带上根目录 `DESIGN.md`。
4. 只生成内容区，不要重做左侧栏、顶栏、页签。

仓库需要是 **public**，Stitch 才能直接用 URL 拉取。

仓库：https://github.com/zhiweicoding/huaxia-zhihuiyuan-ui

## 里面有什么

| 文件 | 用途 |
| --- | --- |
| `DESIGN.md` | Google `design.md` 规范的设计系统（token + 文案/外壳规则） |
| `tokens.css` | 可直接引用的 CSS 变量 |
| `design_tokens.json` | 机器可读 token |
| `index.html` | 学生工作台外壳 + 组件样例，1440 画布 |

## 不要做的事

- 不要把主色改成 `#1890FF` 或 `#2563EB`
- 不要改成 shadcn / Material 大圆角营销风
- 不要在学生文案里写 Prompt、HTML、AI 产物
