# Work Until I Die

**Make AI coding agents finish the damn job.**

Work Until I Die, short **WUID**, is a persistence skill for Claude, Codex, Cursor, Windsurf and other AI coding agents.

It forces agents into a stricter long-horizon execution loop:

```text
plan → build → test → fix → verify → checkpoint → continue
```

No more weak “should work now” summaries.
No more half-built features.
No more skipped tests, forgotten context or TODO dumps pretending to be progress.

WUID makes your AI coding agent behave less like optimistic autocomplete and more like a relentless senior engineer.

---

## What problem does this solve?

AI coding agents are powerful, but they often stop too early.

Typical failure pattern:

```text
User: Build the feature.
Agent: I implemented it.
Reality: One file changed, tests skipped, TODOs left, integration broken.
```

WUID changes the agent’s behavior by giving it strict operating rules:

* keep working through multiple iterations
* test after meaningful changes
* inspect failures instead of ignoring them
* fix root causes
* maintain checkpoints
* avoid fake completion
* stop only when the work is actually complete or truly blocked

---

## Free Version

This repository contains the **free WUID agent skill**.

The free version includes:

* maximum persistence execution mode
* long-horizon engineering behavior
* stop conditions
* anti-fake-completion rules
* manual checkpointing structure
* testing and repair loop
* completion report format
* activation phrases for Claude, Codex and other coding agents

Use it when you want your agent to continue beyond the first weak pass and actually push toward completion.

---

## Works With

WUID is designed for agent-based coding workflows such as:

* Claude Code
* Codex
* Cursor
* Windsurf
* OpenClaw
* custom AI coding agents
* repo-based autonomous coding workflows

It is plain Markdown and can be adapted to most AI agent systems that support custom instructions, skills, rules or repository guidance files.

---

## How to Use

Copy the free skill into your agent setup.

Examples:

### Claude / Claude Code

Use it as a Claude skill or include it in your project instructions.

### Codex

Add the rules to your `AGENTS.md` or equivalent project instruction file.

### Cursor

Place the rules inside your Cursor rules / project rules setup.

### Windsurf

Add the rules to your project-level agent instructions.

Then activate it with one of these phrases:

```text
Work until I die
Full send
Don't stop early
Keep going until it's actually done
Finish the whole thing
Overnight mode
Maximum persistence
```

---

## Activation Phrase

When you tell your agent:

```text
Work until I die
```

it should switch into maximum persistence mode and keep working until the task is genuinely complete or a real hard blocker exists.

---

## Upgrade Versions

The free version is intentionally simple.

If you want the full system, there are paid versions available:

### WUID Pro

Full WUID v2.4 persistence skill with stronger execution rules, stricter stop levels, checkpointing, validation behavior, recovery logic and anti-fake-completion structure.

### WUID Max

Complete toolkit with everything in Pro plus Python scripts, durable session state, time tracking, delegation helper, MCP server integration, checkpoint templates and setup guidance.

### WUID Full Setup

Done-for-you setup service. We install and adapt WUID inside your repository for your actual AI coding workflow.

Get Pro, Max or Full Setup here:

https://payhip.com/WUIDAgentTools

---

## Free vs Pro vs Max

| Version    | Best for                    | Includes                                                                             |
| ---------- | --------------------------- | ------------------------------------------------------------------------------------ |
| Free       | Trying the concept          | Basic persistence skill, stop conditions, anti-fake-completion rules                 |
| Pro        | Serious AI coding workflows | Full WUID v2.4 skill, stricter validation, stronger checkpointing, recovery protocol |
| Max        | Long-running agent sessions | Pro + Python tools, durable state, MCP server, delegation helper, templates          |
| Full Setup | Existing repos              | We install and adapt WUID for your project                                           |

---

## Philosophy

WUID is built around one idea:

> AI agents should not stop when the first version exists.
> They should stop when the work is actually done.

The goal is not more talking.
The goal is more completed work.

---

## One-Line Reminder

**Do the work. Keep going. Test, fix, continue. Do not stop at version one.**

---

## License

This free repository is released under the custom WUID Free License.

You may use the free skill for personal and internal project workflows.

You may not resell, repackage, redistribute, clone, commercialize or claim the free or paid WUID materials as your own product.

See [`LICENSE`](./LICENSE) for details.
