# To-Agent Service Designer

> Design products where **AI agents** are the primary operator — not humans.

![License](https://img.shields.io/github/license/Rare-Sors/To-Agent-Service_Designer-Skill)
![Stars](https://img.shields.io/github/stars/Rare-Sors/To-Agent-Service_Designer-Skill)
![Skill](https://img.shields.io/badge/skill-ready-brightgreen)
![Agent](https://img.shields.io/badge/agent-native-purple)

## Quick Start

```sh
# Load the skill
opencode skill add toa-service-designer

# Start designing
# Ask to design any agent-native service
```

## Features

- **Agent-first** — Design from agent perspective, not dashboard-first
- **Skill Spec** — Structured file bundle contract for services & agents
- **IM-native** — Chat/IM as primary interaction, not web UI
- **Trust & Safety** — Built-in auth, approval, and anti-abuse patterns

## Skill Spec Structure

| File | Purpose |
|------|---------|
| `SKILL.md` | Agent entry point — overview, auth, capabilities |
| `auth.md` | Full authentication contract |
| `openapi.json` | Machine-readable API surface |
| `skill.json` | Versioned metadata |

## Design Flow

```
Vision → Onboarding → Backend → Skill Spec → Auth → Task Flow → Trust & Safety
```

## Default Stack

Next.js · Vercel · Supabase · GitHub

## Contributing

Contributions welcome!

1. Fork the repo
2. Create feature branch (`git checkout -b feature/amazing-feature`)
3. Commit changes (`git commit -m 'Add amazing feature'`)
4. Push to branch (`git push origin feature/amazing-feature`)
5. Open Pull Request

## Links

- **GitHub:** [Rare-Sors/To-Agent-Service_Designer-Skill](https://github.com/Rare-Sors/To-Agent-Service_Designer-Skill)
- **Issues:** [Report a bug](https://github.com/Rare-Sors/To-Agent-Service_Designer-Skill/issues)

## License

MIT

---

🌐 [中文文档](README.zh.md)
