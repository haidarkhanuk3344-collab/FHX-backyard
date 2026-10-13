# Page Simplify · 页面精简

一份用于 Codex 的界面审查与精简 Skill。整理冗余文案、重复模块和操作路径，校准视觉对齐、层级与装饰强度，让内容更清楚、页面更协调。

**保留巧思，理清重点。**

An interface review and simplification skill that reduces clutter, aligns visual hierarchy, and preserves design character and functionality.

## 适合什么时候用

- 页面到处都有小字、口号和标签，重点难找。
- 模块重复、容器叠加、操作绕行，需要整理内容与路径。
- 字体、间距、图标、色彩或动效失衡，希望整体更简洁。
- 已有明确风格，希望在保留个性与氛围的前提下精修。

## 如何做取舍

先识别页面的视觉主题和设计巧思，再判断各元素在当前位置的作用。构图、节奏、氛围、品牌记忆和交互隐喻都属于有效的设计价值。

有价值但过于突出的元素，优先调整尺寸、位置、饱和度、阴影或动效强度。确认没有独立作用、移除后不会损害功能和表达的内容，再考虑删除。无法判断的既有设计默认保留。

同时保护必要信息、真实能力、业务功能与无障碍使用，不用缩小文字、隐藏限制或虚构数据制造简洁感。

## 先看案例

[查看前后对照与处理理由](examples/landing-page-before-after.md) · [在线打开原始页面](https://haidarkhanuk3344-collab.github.io/FHX-backyard/skills/page-simplify/examples/before.html) · [在线打开精简后页面](https://haidarkhanuk3344-collab.github.io/FHX-backyard/skills/page-simplify/examples/after.html)

## 安装

1. 下载或克隆 `FHX-backyard` 仓库，找到 `FHX-backyard/skills/page-simplify/`。
2. 将整个 `page-simplify` 文件夹复制到 Codex 用户 skills 目录。默认目录为 `~/.codex/skills/`；自定义了 `CODEX_HOME` 时，使用该目录下的 `skills/`。
3. 确认安装后的结构如下：

```text
skills/
└── page-simplify/
    ├── SKILL.md
    ├── README.md
    ├── LICENSE
    ├── PUBLISHING.md
    ├── references/
    └── examples/
```

重新打开 Codex 或开始新会话，让它加载新 Skill。

## 调用示例

```text
用 $page-simplify 审查这个落地页，先列出值得保留的设计，再给出可定位的精简建议。
```

```text
用 $page-simplify 精简这个页面，保留现有品牌风格与功能，优先减弱抢眼的装饰，并检查窄屏布局。
```

```text
按 $page-simplify 校准这个界面的对齐、字号、间距和动效，让主次更清楚，保留有意的不对称和视觉记忆点。
```

## 示例与可选模板

- [落地页前后对照与处理理由](examples/landing-page-before-after.md)：查看一个完整的精简案例。
- [原始页面](examples/before.html) / [精简后页面](examples/after.html)：下载后用浏览器打开，对照页面表现。
- [审查表与结果汇报模板](references/review-table-template.md)：需要逐项评审或交付表格时使用。

这是一个原创演示案例，用来展示保留、减弱、校准与删除的取舍；单个案例不能证明适用于所有页面的效果。

完整规则保留在 `SKILL.md` 中。示例与模板均为可选材料，只在需要参考或按表格交付时读取，无须每次任务加载。

## 使用边界

这份 Skill 提供判断规则与执行流程。实际审查和修改依赖 Codex 可访问的页面、源码及工具；仅有截图时，无法据此验证交互与业务能力。

审美取舍仍需要人工判断与最终验收。它不检测界面的模型来源，也不保证消除所有人对“AI 风格”的主观感受。

完整规则见 [SKILL.md](SKILL.md)。

本目录的规则、说明、模板与原创示例采用 [MIT License](LICENSE)。

发布前检查与可复用介绍见 [分发说明](PUBLISHING.md)。
