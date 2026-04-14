# CueAPI

Your agents are failing silently. CueAPI tells you when and why.

---

### Open source

| Repo | Description | |
|------|-------------|---|
| [cueapi/cueapi-core](https://github.com/cueapi/cueapi-core) | The open source server. Self-host with Docker in 60 seconds. | ![stars](https://img.shields.io/github/stars/cueapi/cueapi-core?style=flat&label=stars) |
| [cueapi/cueapi-python](https://github.com/cueapi/cueapi-python) | Official Python SDK. `pip install cueapi-sdk` | ![pypi](https://img.shields.io/pypi/v/cueapi-sdk?label=pypi) |
| [cueapi/cueapi-cli](https://github.com/cueapi/cueapi-cli) | Official CLI. `pip install cueapi` (or `brew install cueapi/tap/cueapi` on Mac) | ![pypi](https://img.shields.io/pypi/v/cueapi?label=pypi) |
| [cueapi/cuechain](https://github.com/cueapi/cuechain) | TypeScript primitive for verifying contracts between LLM pipeline steps. | ![stars](https://img.shields.io/github/stars/cueapi/cuechain?style=flat&label=stars) |

---

### What CueAPI does

- Execution proof - every execution tracked with delivery status and outcome separately
- Automatic retries - exponential backoff when delivery fails (1, 5, 15 min)
- Worker transport - no public URL needed, your agent polls for jobs
- Failure alerts - email and webhook when all retries exhaust

---

### Get started
```bash
# Hosted (free tier: 10 cues, 300 executions/month)
pip install cueapi-sdk

# Self-hosted
git clone https://github.com/cueapi/cueapi-core && docker compose up
```

[cueapi.ai](https://cueapi.ai) · [docs.cueapi.ai](https://docs.cueapi.ai) · [x.com/cueapi](https://x.com/cueapi)

---

*This profile is automatically updated by CueAPI.*
