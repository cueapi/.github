<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./cueapi-logo-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="./cueapi-logo-light.svg">
  <img alt="CueAPI" src="./cueapi-logo-light.svg" width="360">
</picture>

<br /><br />

**Coordination infrastructure for AI agent systems.**

A surface for the choreography your agents already run. Every handoff becomes a cue. Every fire is an execution. Every outcome carries structured evidence. Agents, tools, environments, and humans stay in sync, in real time, with a permanent record of what actually happened.

[cueapi.ai](https://cueapi.ai) · [Docs](https://docs.cueapi.ai) · [MCP](https://github.com/cueapi/cueapi-mcp) · [Pricing](https://cueapi.ai/pricing) · [Status](https://status.cueapi.ai)

</div>

---

## Why CueAPI

Agents don't finish in one call. They coordinate across time, tools, environments, agents, and humans. CueAPI is the infrastructure for that choreography. We see a world where agents coordinate at scale with Cue.

## 5-minute quickstart

```bash
pip install cueapi
cueapi login
cueapi quickstart
```

The `quickstart` command walks you through your first cue end-to-end. Schedule a job, run it, report the outcome, see it in the dashboard.

[Full docs →](https://docs.cueapi.ai)

## Open source

| Repo | Description | |
|------|-------------|---|
| [cueapi/cueapi-core](https://github.com/cueapi/cueapi-core) | The open source server. Self-host with Docker. | ![stars](https://img.shields.io/github/stars/cueapi/cueapi-core?style=flat&label=stars) |
| [cueapi/cueapi-python](https://github.com/cueapi/cueapi-python) | Official Python SDK. `pip install cueapi-sdk` | ![pypi](https://img.shields.io/pypi/v/cueapi-sdk?label=pypi) |
| [cueapi/cueapi-cli](https://github.com/cueapi/cueapi-cli) | Official CLI. `pip install cueapi` (or `brew install cueapi/tap/cueapi` on Mac) | ![pypi](https://img.shields.io/pypi/v/cueapi?label=pypi) |
| [cueapi/cuechain](https://github.com/cueapi/cuechain) | TypeScript primitive for verifying contracts between LLM pipeline steps. | ![stars](https://img.shields.io/github/stars/cueapi/cuechain?style=flat&label=stars) |
| [cueapi/cueapi-action](https://github.com/cueapi/cueapi-action) | GitHub Action to coordinate and verify agent jobs from your CI. `uses: cueapi/cueapi-action@v1` | ![stars](https://img.shields.io/github/stars/cueapi/cueapi-action?style=flat&label=stars) |
| [cueapi/cueapi-mcp](https://github.com/cueapi/cueapi-mcp) | Official MCP server. Give any MCP host (Claude Desktop, Cursor, Zed) coordinated agent work with verified handoffs. `npx @cueapi/mcp` | ![stars](https://img.shields.io/github/stars/cueapi/cueapi-mcp?style=flat&label=stars) |

## Built with CueAPI

| Project | Description | |
|---------|-------------|---|
| [Agent CI/CD](https://github.com/govindkavaturi-art/agent-cicd) | GitHub template for AI agent CI/CD pipelines with verified handoffs. | template |

## Get started

- **Hosted:** [cueapi.ai](https://cueapi.ai). Free tier, no setup.
- **Self-hosted:** [cueapi-core](https://github.com/cueapi/cueapi-core). Docker compose, full features, no crippled OSS tier.
- **Docs:** [docs.cueapi.ai](https://docs.cueapi.ai)
- **Status:** [status.cueapi.ai](https://status.cueapi.ai)

---

*Made by [Vector Apps](https://cueapi.ai).*
