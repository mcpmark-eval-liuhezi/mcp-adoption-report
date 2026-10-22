# MCP Adoption Brief

## 1. The Model Context Protocol organization

The Model Context Protocol specification is hosted by the GitHub organization **`modelcontextprotocol`** ([github.com/modelcontextprotocol](https://github.com/modelcontextprotocol)).

Its three most-starred repositories (star counts as of 2026-10-22):

| Repository | Stars |
| --- | --- |
| `modelcontextprotocol/servers` | 91,487 |
| `modelcontextprotocol/python-sdk` | 24,644 |
| `modelcontextprotocol/typescript-sdk` | 13,640 |

The organization publishes 45 public repositories, spanning the specification, official SDKs in Python, TypeScript, Go, C#, Rust, Java and Kotlin, a server registry, and tooling such as the MCP Inspector.

## 2. The specification repository and its most recently updated open pull request

The specification and documentation live in **`modelcontextprotocol/modelcontextprotocol`** (9,511⭐, topics: `docs`, `mcp`, `specification`, `standard`) — not the SDKs or reference servers.

Its most recently updated open pull request is:

- **#3415 — "SEP-3415: Events Extension"**
  https://github.com/modelcontextprotocol/modelcontextprotocol/pull/3415
  - Author: `pja-ant`; draft; last updated 2026-10-22T10:46:42Z.
  - It proposes an Events extension (`io.modelcontextprotocol/events`) letting an MCP client subscribe to upstream system events (Slack messages, repository pushes, PagerDuty incidents) with poll, push and webhook delivery modes, opaque resumption cursors and optional replay.

**Files changed: 1** — exactly one file, listed with its additions and deletions:

| File | Additions | Deletions | Status |
| --- | --- | --- | --- |
| `seps/0000-events-extension.md` | +1225 | −0 | added |

**Total: 1 file changed, 1225 insertions, 0 deletions.**

## 3. Personal bookmark cross-check

Starred repositories for **@HeziLiu**: **6**.

- `OpenBMB/AgentCPM`
- `PaddlePaddle/ERNIE`
- `FudanNLP/fastNLP`
- `maplezzz/NTU_ML2017_Hung-yi-Lee_HW`
- `fighting41love/funNLP`
- `996icu/996.ICU`

**None of the six starred repositories belong to the `modelcontextprotocol` organization.** The bookmark list skews toward NLP frameworks, Chinese NLP corpora, and ML coursework rather than agent/tooling protocols.

## 4. Adoption assessment

- **Momentum:** The `servers` repository alone has 91.5k stars and 11.8k forks, which indicates very broad community engagement with reference implementations. Six official SDKs (Python, TypeScript, Go, C#, Rust, Java) plus a maintained Go SDK in collaboration with Google and a C# SDK with Microsoft signal strong multi-language vendor backing.
- **Spec governance:** Specification changes proceed through SEP (Specification Extension Proposal) PRs such as #3415, reviewed publicly in the `modelcontextprotocol` repository, with working-group design sketches behind them (e.g. the Triggers & Events Working Group). The spec is versioned and dated (the events proposal aligns to the `2026-07-28` protocol).
- **Ecosystem tooling:** A dedicated Inspector for visual testing of MCP servers (11.1k stars) and a community-driven server registry (7.4k stars) reduce the operational risk of adoption.
- **Internal readiness:** No internal stars on any `modelcontextprotocol` repository, so this would be a greenfield adoption; there is no existing bookmarked prior art in the team's own profile to build on.

## 5. Provenance notes

- Repository location: this brief was created in the `mcpmark-eval-liuhezi` organization because GitHub refused to create it in the personal account `HeziLiu` with the current token (403 Resource not accessible by personal access token).
- Tracking issue: #1 — "Adoption brief: MCP".
- Pull request: "Add adoption notes" (this branch, `add-mcp-notes`).
