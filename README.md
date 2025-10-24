# My Claude Code Plugins 🚀

> Personal collection of workflow plugins I've built for Claude Code

Hey! I'm sharing some plugins I've created to make development with Claude Code more systematic and powerful. These are based on advanced context engineering patterns that help with with my daily work.

## 🎯 Featured Plugins

### [Research-Plan-Implement](./plugins/research-plan-implement)

**The ultimate workflow plugin for systematic software development**

A three-phase methodology that helps you:
- 🔍 **Research** - Deep codebase analysis with specialized AI agents
- 📋 **Plan** - Interactive implementation planning driven by real code patterns
- ⚡ **Implement** - Structured execution with automated verification

Based on [Advanced Context Engineering](https://github.com/humanlayer/advanced-context-engineering-for-coding-agents/blob/main/ace-fca.md) by [Dexter Horthy](https://github.com/humanlayer) @ HumanLayer.

**What you get:**
- 4 specialized research agents (codebase analyzer, locator, pattern finder, web researcher)
- 3 workflow commands mapping to Research → Plan → Implement
- Documentation-first philosophy: understand what IS, not what SHOULD BE
- Task organization system with metadata tracking

[→ Learn more](./plugins/research-plan-implement/README.md)

### [Spec-Driven Development](./plugins/spec-driven-development)

**Specification-first development workflow for building projects right the first time**

A four-phase methodology that guides you through:
- 📝 **Clarify Requirements** - Interactive questioning to capture clear, testable requirements
- 🏗️ **Clarify Design** - Technical design and architecture based on requirements
- 📋 **Create Plan** - Detailed task breakdown with verification steps
- ⚡ **Implement Plan** - Systematic implementation with rigorous testing

**What you get:**
- 4 workflow commands mapping to Requirements → Design → Plan → Implement
- Specification documents (requirements.md, design.md, plan.md) that drive development
- Mandatory testing for every task with max 3 attempts before stopping
- Phase-based execution with human review checkpoints
- Documentation-first philosophy: understand WHAT before HOW

[→ Learn more](./plugins/spec-driven-development/README.md)

---

## 🚀 How to Use

To install my plugins, first add this repo as a marketplace in Claude Code:

```bash
/plugin marketplace add kasperjunge/kasperjunge-marketplace
```

Then install whichever plugins you want:
```bash
/plugin install research-plan-implement@kasperjunge-marketplace
/plugin install spec-driven-development@kasperjunge-marketplace
```

## 📦 What's Available

| Plugin | Version | Description |
|--------|---------|-------------|
| [research-plan-implement](./plugins/research-plan-implement) | 1.0.0 | Advanced context engineering workflow for systematic development |
| [spec-driven-development](./plugins/spec-driven-development) | 1.0.0 | Specification-first workflow with requirements, design, planning, and rigorous testing |

## 🛠️ Want to Create Your Own Plugins?

Feel free to fork this and create your own plugin collection! Check out the [Plugin Development Guide](./docs/plugin-marketplaces.md) to learn how Claude Code plugins work.

### Structure
```
marketplace/
├── .claude-plugin/
│   └── marketplace.json          # Marketplace catalog
├── plugins/
│   └── your-plugin/
│       ├── plugin.json           # Plugin manifest
│       ├── README.md             # Plugin docs
│       ├── agents/               # Optional: AI agents
│       ├── commands/             # Optional: slash commands
│       └── scripts/              # Optional: helper scripts
└── docs/
    └── plugin-marketplaces.md    # Detailed documentation
```

## 📚 Resources

- [Plugin Marketplace Documentation](./docs/plugin-marketplaces.md)
- [Claude Code Plugin System](https://docs.anthropic.com/claude-code/plugins)
- [Advanced Context Engineering Framework](https://github.com/humanlayer/advanced-context-engineering-for-coding-agents)
# kasperjunge-marketplace
