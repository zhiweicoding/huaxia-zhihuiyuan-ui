---
version: alpha
name: 华夏智汇园
description: 中文智慧学习工作台的当前视觉与产品外壳。面向中学生的专业、克制、可信校园学习产品，而不是娱乐社交或游戏界面。本文件描述 2026-09 工作区里正在运行的学生端，不是下一版未确认稿。
colors:
  primary: "#126D82"
  on-primary: "#FFFFFF"
  primary-hover: "#0B5364"
  primary-active: "#083F4D"
  primary-bright: "#13778B"
  primary-soft: "#E6F2F4"
  primary-soft-strong: "#E8F6F7"
  secondary: "#1C8A9E"
  secondary-deep: "#156A7C"
  on-secondary: "#FFFFFF"
  tertiary: "#278B68"
  on-tertiary: "#FFFFFF"
  sidebar: "#123F4B"
  sidebar-deep: "#0E3440"
  sidebar-text: "#E5F3F5"
  sidebar-muted: "#8FD9E0"
  sidebar-section: "#6B8F96"
  surface: "#FFFFFF"
  surface-subtle: "#F8FAFB"
  background: "#F4F8F9"
  background-alt: "#F6F8FA"
  on-surface: "#263D45"
  on-surface-strong: "#17212B"
  on-surface-variant: "#405965"
  on-surface-muted: "#697784"
  on-surface-faint: "#87979E"
  outline: "#DCE7E9"
  outline-strong: "#D8E1E7"
  outline-input: "#CFD9DF"
  error: "#C45F4C"
  on-error: "#FFFFFF"
  warning: "#AD781D"
  danger-badge: "#EE5572"
  success: "#278B68"
  avatar: "#1B8192"
  brand-glow-a: "#7DD3FC"
  brand-glow-b: "#22D3EE"
  brand-glow-c: "#A78BFA"
  overlay: "#123440"
typography:
  display:
    fontFamily: PingFang SC
    fontSize: 28px
    fontWeight: 700
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: PingFang SC
    fontSize: 22px
    fontWeight: 700
    lineHeight: 30px
  headline-md:
    fontFamily: PingFang SC
    fontSize: 18px
    fontWeight: 700
    lineHeight: 26px
  title-lg:
    fontFamily: PingFang SC
    fontSize: 16px
    fontWeight: 600
    lineHeight: 24px
  body-lg:
    fontFamily: PingFang SC
    fontSize: 14.5px
    fontWeight: 400
    lineHeight: 22px
  body-md:
    fontFamily: PingFang SC
    fontSize: 14px
    fontWeight: 400
    lineHeight: 22px
  label-md:
    fontFamily: PingFang SC
    fontSize: 13px
    fontWeight: 600
    lineHeight: 18px
  label-sm:
    fontFamily: PingFang SC
    fontSize: 12px
    fontWeight: 400
    lineHeight: 16px
  overline:
    fontFamily: PingFang SC
    fontSize: 11px
    fontWeight: 700
    lineHeight: 16px
    letterSpacing: 0.09em
rounded:
  xs: 4px
  sm: 5px
  md: 7px
  lg: 8px
  xl: 13px
  pill: 14px
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 8px
  md: 12px
  lg: 16px
  xl: 20px
  2xl: 24px
  3xl: 32px
  gutter: 20px
  margin: 24px
  sidebar: 234px
  sidebar-collapsed: 72px
  topbar: 58px
  tabsbar: 44px
components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.label-md}"
    rounded: "{rounded.sm}"
    height: 40px
    padding: 0 16px
  button-primary-hover:
    backgroundColor: "{colors.primary-hover}"
    textColor: "{colors.on-primary}"
  button-secondary:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.primary-hover}"
    rounded: "{rounded.sm}"
    height: 40px
    padding: 0 16px
  button-ghost:
    backgroundColor: transparent
    textColor: "{colors.primary}"
  input-field:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.on-surface-strong}"
    rounded: "{rounded.sm}"
    height: 40px
    padding: 0 12px
  card-surface:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.on-surface}"
    rounded: "{rounded.md}"
    padding: "{spacing.lg}"
  nav-item:
    backgroundColor: transparent
    textColor: "{colors.sidebar-text}"
    rounded: "{rounded.lg}"
    height: 44px
    padding: 0 14px
  nav-item-active:
    backgroundColor: "{colors.secondary}"
    textColor: "{colors.on-secondary}"
  chip-space:
    backgroundColor: "#F5FAFB"
    textColor: "#59747D"
    rounded: "{rounded.pill}"
    padding: 6px 10px
  tag-primary:
    backgroundColor: "#EDF6F7"
    textColor: "{colors.primary-hover}"
    rounded: "{rounded.xs}"
  page-head:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.on-surface-strong}"
    rounded: "{rounded.md}"
    padding: 15px 18px
  tab-active:
    backgroundColor: "{colors.primary-bright}"
    textColor: "{colors.on-primary}"
    rounded: "{rounded.sm}"
    height: 30px
---

## Brand & Style

华夏智汇园是一套已经在跑的 **PC 学习工作台**，气质是安静的校园管理产品，不是营销站、不是游戏、也不是另一套星空皮肤。

当前正式主题名是 **智汇青 / `workbench-teal`**。主色是青石青绿，侧栏是深青石，内容区是近白灰蓝。界面靠对齐、细边框和克制留白建立层次，不靠大投影、玻璃拟态或每张卡片换一种高饱和色。

生成任何新页面时，必须先套进现有外壳，再画内容区。不要重做 Logo、侧栏、顶栏或页签。

## Colors

调色板以工作台声明色为准，学生壳层里的局部值只允许在极近范围内浮动，不能漂到旧版社区蓝 `#1890FF` 或 Element 默认蓝 `#2563EB`。

- **Primary `#126D82`**：主按钮、激活页签、链接、进度条、选中控件。一屏只保留一个实心主按钮。
- **Primary hover `#0B5364`**：主按钮悬停和按下。
- **Primary soft `#E6F2F4`**：图标底、浅标签、顶栏菜单按钮底。
- **Sidebar `#123F4B → #0E3440`**：左侧导航垂直渐变。文字用 `#E5F3F5`，分组标题用低对比青灰。
- **Nav active**：`linear-gradient(135deg, #1C8A9E, #156A7C)`，白字，轻阴影。不要改成粉蓝青三色大渐变条。
- **Background `#F4F8F9`**：主内容底。工作台全局也可写作 `#F6F8FA`，两者视为同一页底，不要再叠一层浓雾渐变。
- **Surface `#FFFFFF`**：卡片、顶栏、对话框、表格。
- **Text**：标题 `#263D45` / `#17212B`，正文 `#405965`，次要 `#697784`，弱提示 `#87979E`。
- **Success `#278B68`**：完成、成长、采纳。
- **Warning `#AD781D`**：等待、提醒，不要做成亮橙大色块。
- **Danger `#C45F4C`**：删除、错误；通知红点才用 `#EE5572`。
- **亲子紫**：当前学生主工作台不使用紫色主按钮。若未来家长/权限页需要，紫色只表示亲子关系，不得替换主按钮。

品牌名第二段可用很克制的字色渐变 `#7DD3FC → #22D3EE → #A78BFA`，仅限侧栏 Logo 文字，不扩散到卡片和按钮。

## Typography

字体栈：`PingFang SC, Microsoft YaHei, Inter, -apple-system, BlinkMacSystemFont, Segoe UI, sans-serif`。不要用衬线、等宽或展示字体做正文。

- 侧栏品牌名 18.5px / 800。
- 顶栏页面标题 18px / 700，副标题 12px / `#87979E`。
- 内容区大标题最多 28px / 700，区块标题 20–22px，卡片标题 16px / 600。
- 正文 14px，辅助 12px，分组超标题 11px / 700 / 宽字距。
- 按钮文字 13–14px / 600。
- 字距默认 0。不要全大写英文装饰，首页可以保留很小的 `CAMPUS HUB` 眉题，但不作为新页模板。

## Layout & Spacing

当前学生壳是三层固定骨架，内容画在骨架里面：

1. 左侧栏 **234px**，收起 **72px**。品牌区约 96px。
2. 顶栏 **58px**：折叠、面包屑、搜索、通知、全屏、头像。
3. 页签栏 **44px**：已打开的工作区，激活页签用主色实底。
4. 主内容：白顶栏下方的灰底工作区，内边距 20–24px。

间距走 4/8 体系：4、8、12、16、20、24、32。按钮和输入框高度 40px。侧栏导航项高度 44px、左右边距 10px。

PC 验收宽度：1024、1280、1440、1920。1024 必须能用，不允许页面级横向滚动。画布类页面（仰望星辰、知识图谱）要给中间画布留出至少约 260px，不要只监听 `window.resize`，主导航展开/收起也要重算宽度。

内容区优先两栏或三栏工作台，不要做成营销落地页的大插画和超大标题。列表、筛选、表格、图谱工具条必须对齐。

## Elevation & Depth

层次主要靠 **色面差 + 1px 边框**，不是厚阴影。

- 页底灰、卡片白、顶栏白。
- 卡片默认 `box-shadow: none`，边框 `#DCE7E9` / `#D8E1E7`。
- 侧栏可以用很轻的右侧阴影 `2px 0 10px rgba(13,48,58,.14)`。
- 对话框、下拉、搜索浮层才用阴影：约 `0 16px 40px rgba(29,43,54,.16)` 或 `0 20px 46px rgba(23,57,68,.22)`。
- 页面头卡可加 **4px 主色左边线**，不要大背景图。
- 禁止强发光、玻璃拟态、每张卡片不同彩色投影。

## Shapes

形状语言是 **略圆的工具型直角**：够现代，但不泡。

- 按钮、输入、页签、账号胶囊：5px。
- 卡片、对话框、页面头：7px。
- 侧栏导航项：8px。
- 品牌标：13px。
- 空间/身份小芯片：14px 胶囊。
- 头像：全圆。
- 标签：4px。

同一屏不要混用大圆角营销卡和这些工作台圆角。节点画布里，节点外框可以在方/圆之间切换，但内部内容尺寸不跟着拉伸。

## Components

### App shell

所有学生页都活在 `StudentPrototypeChrome` 里：深青侧栏 + 白顶栏 + 白页签 + 灰内容。新页面只设计 `workspace-page-body` 内部。

侧栏分组必须保持：

- 学习中心：首页、学习题集、思辨解题、仰望星辰、问答、学习助理
- 知识管理：知识转译、知识图谱、记忆清单、知识资产
- 成长与协作：成长雷达、学习社群
- 系统：AI提示词、系统工具

图标用 18px 线性描边，圆端、1.7 描边。不要用 emoji 代替功能图标。

### Buttons

实心主按钮青绿、白字、5px、无阴影、字重 600。次按钮白底青边或浅青底。文字按钮无底。危险按钮才用砖红色。不要在同一操作区摆两颗同等权重的实心主按钮。

### Inputs

白底、`#CFD9DF` 边框、5px、高度 40px。悬停边框略加深，聚焦主色边框 + `0 0 0 2px rgba(18,109,130,.10)`。占位符 `#96A2AB`。

### Cards & page heads

白底、细边框、7px。页面头、策略头、任务总览：左边 4px 主色条。社区和资产页可以更有层次，但必须仍像这个系统的一张工作台，而不是新皮肤。

### Tabs & chips

顶栏页签：未选中浅灰描边，选中主色实底白字。内容区分页签用文字色 + 主色下划线，不要一排巨大胶囊。

### Navigation

侧栏项默认透明，悬停 `rgba(255,255,255,.08)`，激活青绿渐变。收起后只显示图标并居中。

### Empty / loading / error

每个列表都要有骨架、空态、无结果、网络错误、无权限。状态不能只靠颜色，要配合文字或图标。

### Floating assistant

右下角保留圆形「提问」入口。仰望星辰页隐藏该浮层，改走页内图谱对话。完整工作区仍是 `/ai-dialog`。

## Iconography

线性图标，风格接近 Element UI / Tabler。侧栏图标 18px，顶栏图标按钮 40×40。品牌标可有极轻的青光呼吸，但不把整页做成发光动画。

## Motion

过渡短而功能化：侧栏 200ms，颜色 160ms，不要弹跳和页面级视差。画布工具必须直接可点，不要先弹一层说明。

## Copywriting

学生和家长看的文案要像学习工具，不暴露实现。

禁用或少用：Prompt、HTML、AI 产物、向量、Token、模型、监控孩子。

推荐：智能助理 / 学习助理、个性化讲解、网页讲解、语音讲解、学习成果、知识地图、学习情况。

当前侧栏仍有「AI提示词」系统入口，那是后台策略页，不是学生内容文案模板。新的学生可见说明不要再写 Prompt。

## Information Architecture

当前 canonical 学生入口：

| 入口 | 路由 | 页面职责 |
| --- | --- | --- |
| 首页 | `/index` | 学习驾驶舱、今日任务、智慧山脉、最近学习 |
| 学习题集 | `/exercise-workspace` | 错题、归类、多解、动画讲解、复盘 |
| 思辨解题 | `/thinking-solution` | 五阶段思考、迁移、图谱分析 |
| 仰望星辰 | `/star-map` | 题目知识关系、页内学习助理、学习链 |
| 问答 | `/qa` | 原题输入与基础/变式/迁移诊断 |
| 学习助理 | `/ai-dialog` | 三栏对话、语音/PPT/动画讲解 |
| 知识转译 | `/knowledge-translation` | 公式/概念/题目双向转译 |
| 知识图谱 | `/board` | 个人无限画布、节点编辑、协作入口 |
| 记忆清单 | `/memory-list` | 主动回忆与复习窗口 |
| 知识资产 | `/knowledge-assets` | 题目/图谱/转译/音视频成果 |
| 成长雷达 | `/growth-radar` | 学习证据与趋势 |
| 学习社群 | `/learning-community` | 推荐、问答、项目组、动态 |
| 系统工具 | `/user/profile` | 账号与资料 |

旧 `/tool/*`、`/learning/*`、`/graph/*` 只做兼容，不在这些地址复制一套新 UI。

## Product Pages

生成页面时按现有信息密度，不要简化成空泛仪表盘。

- **首页**：保留驾驶舱问候和智慧山脉层叠山阶（筑基 / 问道 / 践行 / 传承），下面是今日任务和建议下一步。未确认前不要擅自改成能力卡片栅格。
- **题集 / 思辨 / 问答**：左列表或阶段条 + 右主作答区，答案默认不要一上来就展示。
- **仰望星辰**：左对话 / 中画布 / 右节点图文栏。工具叠在画布上。节点详情是连续文章，不是弹窗。
- **知识图谱**：图谱列表、我的图谱/共同创作、无限画布、复合节点、曲线连线、右侧学习助理。
- **学习助理**：会话列表 + 对话 + 产物卡（语音、网页讲解、PPT 分镜）。
- **学习社群**：沿用现有外壳，内容区可以更有层次；内部建议推荐 / 兴趣社群 / 项目组 / 我的。

## Do's and Don'ts

- Do 把新页面画进现有侧栏+顶栏+页签外壳。
- Do 使用智汇青主色和深青侧栏。
- Do 保持高信息密度、细边框、小圆角。
- Do 为学生文案使用学习语言，不展示技术实现词。
- Do 在 1024 宽度下检查不溢出、不遮挡。
- Don't 把全站改成星空、游戏、玻璃拟态或 Material 3 大圆角。
- Don't 使用 `#1890FF` 或 `#2563EB` 当主色。
- Don't 用紫色做普通主按钮。
- Don't 重做首页智慧山脉，除非任务明确说下一版首页。
- Don't 在学生页写 Prompt、HTML、AI 产物。
- Don't 把实时 IM、音视频上课、图谱以外的协同画进当前默认稿。
- Don't 输出 React/shadcn 视觉当作本产品；对照时以这套青绿工作台为准。
