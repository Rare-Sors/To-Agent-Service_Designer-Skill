# To-Agent 服务设计器

> 为 **AI 代理** 作为主要操作者设计产品 —— 而非人类。

![License](https://img.shields.io/github/license/Rare-Sors/To-Agent-Service_Designer-Skill)
![Stars](https://img.shields.io/github/stars/Rare-Sors/To-Agent-Service_Designer-Skill)
![Skill](https://img.shields.io/badge/skill-ready-brightgreen)
![Agent](https://img.shields.io/badge/agent-native-purple)

## 快速开始

```sh
# 加载技能
opencode skill add toa-service-designer

# 开始设计
# 要求设计任何代理原生服务
```

## 特性

- **代理优先** — 从代理视角设计，而非仪表盘优先
- **技能规范** — 服务与代理之间的结构化文件束契约
- **IM 原生** — 聊天/即时通讯为主要交互界面，而非 Web UI
- **信任与安全** — 内置认证、审批和反滥用模式

## 技能规范结构

| 文件 | 用途 |
|------|------|
| `SKILL.md` | 代理入口点 — 概览、认证、能力 |
| `auth.md` | 完整认证契约 |
| `openapi.json` | 机器可读的 API 表面 |
| `skill.json` | 版本化元数据 |

## 设计流程

```
愿景 → 引导 → 后端 → 技能规范 → 认证 → 任务流 → 信任与安全
```

## 默认技术栈

Next.js · Vercel · Supabase · GitHub

## 贡献

欢迎贡献！

1. Fork 仓库
2. 创建功能分支 (`git checkout -b feature/amazing-feature`)
3. 提交更改 (`git commit -m 'Add amazing feature'`)
4. 推送到分支 (`git push origin feature/amazing-feature`)
5. 发起 Pull Request

## 链接

- **GitHub:** [Rare-Sors/To-Agent-Service_Designer-Skill](https://github.com/Rare-Sors/To-Agent-Service_Designer-Skill)
- **Issues:** [报告问题](https://github.com/Rare-Sors/To-Agent-Service_Designer-Skill/issues)

## 许可证

MIT

---

🌐 [English](README.md)
