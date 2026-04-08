# Love Compass - 爱情指南针 Skill

[![Version](https://img.shields.io/badge/version-1.4-blue.svg)]()
[![License](https://img.shields.io/badge/license-MIT-green.svg)]()

一个可自定义的三重身份模式情感陪伴与关系分析 Skill，适用于 OpenClaw 平台。

## ✨ 核心特性

### 🎭 三种工作模式

| 模式 | 状态 | 说明 |
|------|------|------|
| 💬 **会话模式** | 用户自定义 | 100% 自定义角色扮演，沉浸式情感陪伴 |
| 📊 **分析模式** | ✅ 预设完成 | 专业情感分析，结构化输出策略建议 |
| 🛠️ **工程模式** | ✅ 预设完成 | 系统配置，记忆管理，技能操作 |

### 🛡️ 内置安全机制

- 6 条硬边界规则（自我伤害、暴力、不道德行为等）
- 7 条软伦理原则（真诚、忠诚、性别平等等）
- 情感陪伴黄金法则

### 🧠 完整记忆系统

- 分层记忆存储（长期记忆 + 每日记忆）
- 与 amygdala-memory、clawbrain 深度集成
- 自我改进学习能力

### 🎯 首次安装引导

- 首次调用自动弹出初始化引导
- 清晰的角色配置步骤指引
- 配置完成后引导自动消失

## 🚀 快速开始

### 1. 安装到 OpenClaw

```bash
openclaw skills install love-compass
```

### 2. 初始化

首次调用会自动弹出引导，按照指引完成：

1. 打开 `references/identity.md` 填写你的专属角色
2. 打开 `references/soul.md` 修改角色灵魂设定
3. 完成！开始对话

### 3. 使用

| 指令 | 效果 |
|------|------|
| `[你的角色名]` | 进入会话模式 |
| `切换分析模式` / `帮我分析` | 开始情感关系分析 |
| `切换工程模式` | 进入技术操作模式 |

## 📁 项目结构

```
love-compass/
├── SKILL.md                    # 主技能入口 + 首次安装引导
├── README.md                   # 说明文档
└── references/
    ├── identity.md             # 三重身份定义模板
    ├── soul.md                 # 核心灵魂 + 安全边界 + 场景模拟
    └── setup.md                # 安装配置与记忆系统
```

## 📄 License

MIT
