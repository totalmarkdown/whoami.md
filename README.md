# WHOAMI.md

> *Declares the verifiable identity of an AI agent*

[![License: CC0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
[![Part of agent-md-specs](https://img.shields.io/badge/part%20of-agent--md--specs-blue)](https://github.com/totalmarkdown/agent-md-specs)
[![Maintained by TotalMarkdown](https://img.shields.io/badge/maintained%20by-TotalMarkdown.ai-8B5CF6)](https://totalmarkdown.ai)

**Maintained by TotalMarkdown.ai**
· License: CC0 1.0 Universal — Public Domain
· Part of [agent-md-specs](https://github.com/totalmarkdown/agent-md-specs)
· [Discussions](https://github.com/totalmarkdown/whoami.md/discussions)

> TotalMarkdown.ai is currently in development. Star this repo to follow progress.

---

> **Canonical Source:** This spec is maintained in the main
> [agent-md-specs](https://github.com/totalmarkdown/agent-md-specs) repository.
> This repo is an auto-synced mirror for easy discovery and download.
> To report issues or submit changes, please open a PR or issue on the
> [main repository](https://github.com/totalmarkdown/agent-md-specs).

## What is WHOAMI.md?

WHOAMI.md is the agent's identity card. It declares who the agent is — name, version, model, capabilities, owner, and organizational affiliation — in a structured, auditable format.

It's the first thing compliance teams review before approving an agent deployment, and the first thing other agents check when deciding whether to trust a peer.

Create a WHOAMI.md for any agent deployed in an enterprise environment, interacting with other agents, or requiring identity verification.

---

## Quick Start

```bash
curl -O https://raw.githubusercontent.com/totalmarkdown/whoami.md/main/WHOAMI.md
```

Add to your project root and customize for your agent.

---

## When to use WHOAMI.md

- Any agent deployed in an enterprise environment
- Agents that need to prove their identity to API gateways or policy engines
- Multi-agent systems where agents need to identify themselves to each other

---

## Where it fits

Works alongside ID.md (permanent UUID), ATTESTATION.md (cryptographic identity proof), SESSION.md (ephemeral runtime identity), OWNER.md (who is liable), and CONTACT.md (reachable endpoints).

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
