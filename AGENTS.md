# FrankX — Agent Operating Contract

Scope: All repositories under the **FrankX-AI** GitHub Organization (https://frankx.ai).
Brand register: `frankx`

## Responsible Agent Team & Governance

| Role | Assigned Owner |
| :--- | :--- |
| **Human Codeowner** | `@frankxai` |
| **Organization Steward** | `steward-frankx` |
| **Executive Seat** | CEO (Founder Office) + CMO (Editorial & Authority) |
| **Universal IS** | Brand IS,Creator IS,Business IS,Code IS |
| **Council Lead** | starlight-prime,starlight-weaver,starlight-social-strategist |
| **Primary Harnesses** | `Claude Code`, `Codex`, `Antigravity`, `Grok` |

## Core Guardrails

1. **Think before coding.** State assumptions and surface tradeoffs. Verify file contents and branch state before writing.
2. **Surgical changes.** Touch only the files required for the active slice. Never overwrite or reset another agent's uncommitted worktree.
3. **Branch and worktree discipline.** Never push directly to `main`. Work on `agent/<harness>/<scope>` in a dedicated worktree and open a **draft** pull request first.
4. **Maker != Checker.** The harness that authors a pull request never approves or merges its own pull request.
5. **CI budget discipline.** Keep pull requests in draft until local verification (`lint`, `typecheck`, `test`, `build`) passes. Mark ready for review once.
6. **Non-waivable safety.**
   - Never commit secrets, API keys, or `.env` files.
   - Preserve repository visibility parity: never copy or mirror private repository contents into a public repository.
   - Money fails closed; no autonomous spend or paid API provisioning without explicit human approval.
   - In health and mind domains, model observations only; never diagnose or make clinical claims.

## Federated Repository Roster (9 repositories)

| Repository | Visibility | Primary Owner | Role |
| :--- | :--- | :--- | :--- |
| `frankx.ai-vercel-website` | `public` | `frankxai` | federated-mirror (SSOT: frankxai/frankx.ai-vercel-website) |
| `FrankX` | `private` | `frankxai` | federated-mirror (SSOT: frankxai/FrankX) |
| `author-os` | `public` | `frankxai` | federated-mirror (SSOT: frankxai/author-os) |
| `publishing-house` | `private` | `frankxai` | federated-mirror (SSOT: frankxai/publishing-house) |
| `prompt-library` | `public` | `frankxai` | federated-mirror (SSOT: frankxai/prompt-library) |
| `claude-skills-library` | `public` | `frankxai` | federated-mirror (SSOT: frankxai/claude-skills-library) |
| `mcp-doctor` | `public` | `frankxai` | federated-mirror (SSOT: frankxai/mcp-doctor) |
| `claude-code-hooks` | `public` | `frankxai` | federated-mirror (SSOT: frankxai/claude-code-hooks) |
| `visual-intelligence` | `public` | `frankxai` | federated-mirror (SSOT: frankxai/visual-intelligence) |

Built on SIP
