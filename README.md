# NovoAcuity Solutions

Curated engineering solutions from NovoAcuity — reproducible recipes for
working with Claude, MCP, CI/CD, and developer workflows. Each solution
is a self-contained bundle (runbook + supporting scripts) published as a
public GitHub Gist. Tags and short summaries help you find what you need.

Solutions ship when they're battle-tested in a real engineering context
and generalized so a third-party reader on their own machine can apply
them. The bar is "would this help someone outside our environment?"

## Index

| Solution | Summary | Tags | Gist | Updated |
|----------|---------|------|------|---------|
| Use two Claude accounts simultaneously on macOS | Run Claude Code on macOS authenticated as two paid accounts simultaneously, with per-account billing isolation via `CLAUDE_CONFIG_DIR`. Combined weekly capacity, separate `/usage` meters, reproducible setup. | claude-code, macOS, dual-account, billing-isolation | [gist](https://gist.github.com/NovoAcuity/e11d4fbfaf2eb1aa3fe26ed56c7c937d) | 260518 — Phase 29 script hygiene amendments (claude2 v2 with --check + curl-transport-failure handling; setup-acct2 v2 with D-02 preserve-on-reconcile + WR-01 tempfile-leak closure + 999.118 anti-corruption guidance) |

---

Want to suggest a solution or report a problem? Open an issue against this
repo. Solutions are curated; not every issue ships as a published solution,
but we read each one.
