# CueAPI

**Make your agents accountable.**

AI agents fail silently. CueAPI makes silent failure impossible.

Schedule agent work, gate every handoff with verification, and refuse to advance until your agent attaches evidence of what it actually did. Once recorded, the outcome is on the record forever — no rewrites, no retroactive edits.

## 5-minute quickstart

```bash
pip install cueapi
cueapi login
cueapi quickstart
```

The `quickstart` command walks you through your first cue end-to-end — schedule a job, run it, report the outcome, see it in the dashboard.

[Full docs →](https://docs.cueapi.ai)

## Why CueAPI

AI agents are unreliable narrators. An agent can return `{"success": true}` after a tool call that silently failed. It can hallucinate a confirmation. It can report sending an email that never sent.

CueAPI is the primitive that makes the agent prove its claims, at the API boundary, at the moment of reporting. No proof, no progress.

## Open source

| Repo | Description | |
|------|-------------|---|
| [cueapi/cueapi-core](https://github.com/cueapi/cueapi-core) | The open source server. Self-host with Docker. | ![stars](https://img.shields.io/github/stars/cueapi/cueapi-core?style=flat&label=stars) |
| [cueapi/cueapi-python](https://github.com/cueapi/cueapi-python) | Official Python SDK. `pip install cueapi-sdk` | ![pypi](https://img.shields.io/pypi/v/cueapi-sdk?label=pypi) |
| [cueapi/cueapi-cli](https://github.com/cueapi/cueapi-cli) | Official CLI. `pip install cueapi` (or `brew install cueapi/tap/cueapi` on Mac) | ![pypi](https://img.shields.io/pypi/v/cueapi?label=pypi) |
| [cueapi/cuechain](https://github.com/cueapi/cuechain) | TypeScript primitive for verifying contracts between LLM pipeline steps. | ![stars](https://img.shields.io/github/stars/cueapi/cuechain?style=flat&label=stars) |

## Built with CueAPI

| Project | Description | |
|---------|-------------|---|
| [Agent CI/CD](https://github.com/govindkavaturi-art/agent-cicd) | GitHub template for AI agent CI/CD pipelines with execution accountability. | template |

## Get started

- **Hosted:** [cueapi.ai](https://cueapi.ai) — free tier, no setup
- **Self-hosted:** [cueapi-core](https://github.com/cueapi/cueapi-core) — Docker compose, full features, no crippled OSS tier
- **Docs:** [docs.cueapi.ai](https://docs.cueapi.ai)
- **Status:** [status.cueapi.ai](https://status.cueapi.ai)

---

*Made by [Vector Apps](https://cueapi.ai).*
