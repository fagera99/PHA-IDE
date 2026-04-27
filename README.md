# PHA-IDE

> A powerful, AI-native Integrated Development Environment built on top of [VS Code](https://github.com/microsoft/vscode) — extended with a full suite of intelligent agents, multi-model support, and agentic workflows for developers, teams, and enterprises.

---

## What is PHA-IDE?

PHA-IDE is a customized fork of Visual Studio Code that integrates a rich ecosystem of AI-powered extensions directly into the editor. It combines the familiar VS Code experience with advanced agentic capabilities, enabling developers to work alongside AI agents specialized in engineering, design, finance, marketing, and more.

---

## Key Extensions

| Extension | Description |
|---|---|
| `pha-agency` | 150+ specialized AI agents across all domains |
| `pha-models` | Multi-model AI support (local & cloud) |
| `pha-heretic` | Advanced code processing engine |
| `pha-pentagi` | Autonomous task runner & agentic workflows |
| `pha-theme` | Custom PHA dark theme |

---

## Agent Categories

PHA-IDE ships with over **150 specialized agents** covering:

- **Engineering** — Backend, Frontend, DevOps, Security, Mobile, AI/ML
- **Design** — UI/UX, Brand, Visual Storytelling, Image Prompting
- **Finance** — Financial Analysis, FP&A, Tax, Investment Research
- **Marketing** — SEO, Social Media, Content, Paid Media, 20+ platforms
- **Sales** — Outreach, Pipeline, Deal Strategy, Discovery
- **Product** — Product Management, Sprint Planning, User Research
- **Legal** — Document Review, Compliance, Client Intake
- **Game Dev** — Unity, Unreal, Godot, Roblox
- **XR/Spatial** — VisionOS, AR/VR, Spatial Computing

---

## Getting Started

### Prerequisites

- Node.js >= 18
- Git
- Windows / Linux / macOS

### Run

```bash
# Clone the repo
git clone https://github.com/fagera99/PHA-IDE.git
cd PHA-IDE

# Install dependencies
npm install

# Launch
Launch_PHA_IDE.bat   # Windows
```

---

## Architecture

```
PHA-IDE/
├── extensions/
│   ├── pha-agency/       # AI Agents library (150+ agents)
│   ├── pha-models/       # Multi-model provider
│   ├── pha-heretic/      # Code processing engine
│   ├── pha-pentagi/      # Agentic task runner
│   └── pha-theme/        # Custom UI theme
├── src/                  # VS Code core (modified)
└── Launch_PHA_IDE.bat    # Quick launcher
```

---

## Built On

- [Visual Studio Code](https://github.com/microsoft/vscode) — MIT License
- TypeScript
- Node.js

---

## License

MIT — see [LICENSE](LICENSE) for details.

---

---

## Acknowledgements

PHA-IDE stands on the shoulders of amazing open-source projects. Special thanks to:

| Project | Author | Contribution |
|---|---|---|
| [heretic](https://github.com/p-e-w/heretic) | [@p-e-w](https://github.com/p-e-w) | Inspired the `pha-heretic` code processing engine |
| [agency](https://github.com/msitarzewski/agency) | [@msitarzewski](https://github.com/msitarzewski) | Inspired the `pha-agency` AI agents architecture |
| [agency-agents](https://github.com/msitarzewski/agency-agents) | [@msitarzewski](https://github.com/msitarzewski) | Source of inspiration for the 150+ specialized agents library |
| [Visual Studio Code](https://github.com/microsoft/vscode) | Microsoft | Core IDE foundation — MIT License |
| [pentagi](https://github.com/vxcontrol/pentagi) | [@vxcontrol](https://github.com/vxcontrol) | Inspired the `pha-pentagi` autonomous task runner & agentic workflows |

> A huge thank you to all these incredible developers for their open-source contributions that made PHA-IDE possible. ❤️

<p align="center">Built with passion by <a href="https://github.com/fagera99">fagera99</a></p>
