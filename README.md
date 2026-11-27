# gdd-plain — 策划案通读写作

**帮助策划快速落实策划案。**

面向游戏策划的 MiMo / agent skill：按「开发从头读到尾」的结构写需求与细案，并用 B 档大白话降低阅读门槛——词表前置、通用规则只写一遍、主流程完整时间线、拍板数字零漂移。

## 解决什么问题

- 开发反馈：从头读不动、新概念没解释、逻辑要自己拼  
- 策划需要：规范、好懂、可直接进排期评审的正文  
- 约束：只改表达与结构，**不擅自改已拍板规则**

## 文档骨架

```
〇 这是什么（一句话 + 管/不管）
一 词表（人话解释）
二 通用规则（多分支共用，只写一遍）
三/四 主流程（各自完整时间线，从头读到尾）
五 UI
六 资源参考
七 指针与余项
```

## 仓库结构

| 路径 | 说明 |
|------|------|
| `SKILL.md` | 技能主规则与工作流 |
| `references/template.md` | 空白章节模板 |
| `references/checklist.md` | 交付前自检 |
| `references/b-plain-rules.md` | B 档大白话对照 |
| `locales/` | 插件页显示元数据 |

## 安装到 MiMo

将本仓库内容放到全局技能目录：

```text
~/.config/mimocode/skills/gdd-plain/
```

（Windows：`C:\Users\<你>\.config\mimocode\skills\gdd-plain\`）

保证 `SKILL.md` 在该目录下，且目录名与 frontmatter 的 `name: gdd-plain` 一致。

## 使用

在会话中说：

- 「帮我写 XX 玩法细案」  
- 「这案开发看不懂，按通读改」  
- 「大白话一点 / B 档」  
- 「按《需求婚礼》那套结构」  

或直接 `/gdd-plain`。

## License

MIT
