# WHOAMI.md

> *Defines an AI agent's identity document — who it is, what it does, and how to verify it*

[![License: CC0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
[![Part of agent-md-specs](https://img.shields.io/badge/part%20of-agent--md--specs-blue)](https://github.com/totalmarkdown/agent-md-specs)
[![Maintained by TotalMarkdown](https://img.shields.io/badge/maintained%20by-TotalMarkdown.ai-8B5CF6)](https://totalmarkdown.ai)

**Maintained by TotalMarkdown.ai**
· License: CC0 1.0 Universal — Public Domain
· Part of [agent-md-specs](https://github.com/totalmarkdown/agent-md-specs)
· [Discussions](https://github.com/totalmarkdown/whoami.md/discussions)

> TotalMarkdown.ai is currently in development. Star this repo to follow progress.

---

## What is WHOAMI.md?

WHOAMI.md is an agent's identity card. It declares the agent's name, role, capabilities, version, and the organization it belongs to. Think of it as a machine-readable profile that other agents and systems can inspect.

Where SOUL.md defines personality, WHOAMI.md defines facts. It answers the questions: What is this agent called? What can it do? Who operates it? How do you verify it's legitimate? This is critical in multi-agent environments where agents need to identify and trust each other.

Create a WHOAMI.md for any agent that will interact with other agents, be discoverable in a registry, or need to prove its identity and capabilities to external systems.

---

## Quick Start

```bash
curl -O https://raw.githubusercontent.com/totalmarkdown/whoami.md/main/WHOAMI.md
```

Add to your project root and customize for your agent.

---

## When to use WHOAMI.md

- Registering an agent in a discovery service so other agents can find and engage it
- Providing identity verification when an agent connects to a new system or API
- Declaring capabilities so orchestrators can route tasks to the right agent

---

## Where it fits

Pairs with SOUL.md (personality) and HIREME.md (engagement terms). Used by SEEKING.md (discovery) and CONTACT.md (how to reach the agent). Referenced by AGENTS.md and CLAUDE.md.

---

## The Full Spec

→ [WHOAMI.md](./WHOAMI.md)

---

## Part of agent-md-specs

One of 178 specs in [agent-md-specs](https://github.com/totalmarkdown/agent-md-specs)
— the open standard library covering every dimension of AI agent configuration.

---

## Contributing

1. Open an issue describing your proposed change
2. Fork and make your edit
3. Open a PR — all contributions must be CC0

---

## License

[CC0 1.0 Universal](./LICENSE) — Public Domain.
Use freely for any purpose, no attribution required.

---

*Maintained by TotalMarkdown.ai*
*Part of [agent-md-specs](https://github.com/totalmarkdown/agent-md-specs)*
