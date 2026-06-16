<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/agenthatch/.github/main/profile/assets/logo-dark.svg">
    <img alt="agenthatch" src="https://raw.githubusercontent.com/agenthatch/.github/main/profile/assets/logo-light.svg" width="480">
  </picture>
</p>

<p align="center">
  <strong>Turn any SKILL.md into a runnable AI Agent.</strong>
</p>

<p align="center">
  <a href="https://github.com/agenthatch/agenthatch"><img src="https://img.shields.io/badge/Core-agenthatch-blue" alt="agenthatch"></a>
  <a href="https://github.com/agenthatch/agenthatch/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-MIT-green" alt="MIT License"></a>
  <a href="https://discord.gg/agenthatch"><img src="https://img.shields.io/badge/Discord-join%20us-5865F2?logo=discord&logoColor=white" alt="Discord"></a>
</p>

---

## What is agenthatch?

agenthatch is an **Agent Factory** that transforms declarative SKILL.md skill files into fully functional, standalone AI agents. Inspired by the Claude Code SKILL.md specification, agenthatch goes further — it analyzes, reasons about, and generates production-ready agents with MCP integration, tool calling, and multi-turn conversation capabilities.

### How it works

```
SKILL.md → Phase 1: Parse → Phase 2: 6-Harness LLM Reasoning → Phase 3: Jinja2 Code Generation → Runnable Agent
```

1. **Phase 1 — Parse**: Deterministic frontmatter + content extraction from SKILL.md
2. **Phase 2 — 6-Harness Reasoning**: Six specialized LLM agents analyze identity, intent, interface, MCP servers, base environment, and cross-validate into AHSSPEC
3. **Phase 3 — Code Generation**: Jinja2 templates produce a standalone Python package with pyproject.toml, agent code, tools, and runtime config

One command from SKILL.md to deployable agent:

```bash
agenthatch hatch my-skill && agenthatch run my-skill
```

## Projects

| Repository | Description |
|---|---|
| [agenthatch](https://github.com/agenthatch/agenthatch) | Core CLI, skill engine, harness pipeline, and agent generation |
| [agenthatch-core](https://github.com/agenthatch/agenthatch) | Universal agent runtime — LLM client, sandbox, conversation loop |

## Get Involved

agenthatch is an open-source project welcoming contributors of all levels.

- **Try it**: `pip install agenthatch && agenthatch init`
- **Report bugs**: [GitHub Issues](https://github.com/agenthatch/agenthatch/issues)
- **Ask questions**: [GitHub Discussions](https://github.com/agenthatch/agenthatch/discussions)
- **Chat with us**: [Discord](https://discord.gg/agenthatch)
- **Contribute**: See [CONTRIBUTING.md](https://github.com/agenthatch/agenthatch/blob/main/CONTRIBUTING.md)

## License

agenthatch is open source under the [MIT License](https://github.com/agenthatch/agenthatch/blob/main/LICENSE).