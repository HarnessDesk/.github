<div align="center">

### Where your agents work — whoever made them.

A control plane for coding agents, owned by no model vendor.<br/>
Context, policy, history, tools, cost and evidence in one place — whichever agent does the work.

[**Download for macOS**](https://github.com/HarnessDesk/HarnessDesk/releases/latest) &nbsp;·&nbsp;
[Documentation](https://github.com/HarnessDesk/HarnessDesk/blob/main/docs/README.md) &nbsp;·&nbsp;
[harnessdesk.app](https://harnessdesk.app)

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/HarnessDesk/HarnessDesk/main/docs/images/app/turn-dark.gif" />
  <img src="https://raw.githubusercontent.com/HarnessDesk/HarnessDesk/main/docs/images/app/turn-light.gif" width="840" alt="A turn arriving in HarnessDesk: the agent's reasoning appears first, then its tool calls one at a time — reading a file, grepping for a status code, editing it — while the task list in the sidebar ticks over, ending with a summary of what changed." />
</picture>

<sub><em>A turn, as it arrives. Reasoning, then the tool calls, then what changed.</em></sub>

</div>

---

Your machine probably already has several coding agents on it — several histories,
several permission models, several sets of credentials, no shared context, and no
single answer to *what did the agents do in this repository this week*. A model
vendor has little reason to fix that. HarnessDesk is the desk they all report to,
and it makes none of them.

### What's here

**[HarnessDesk](https://github.com/HarnessDesk/HarnessDesk)** — the desk itself. One macOS
window where Codex, Claude Code, Gemini, Cursor and any ACP agent share a history, one
permission policy and one audit log. They run in parallel on their own git worktrees, hand
work to each other mid-conversation, and reach the same 53 built-in plugin tools.

**[dsh-acp](https://github.com/HarnessDesk/dsh-acp)** — an Agent Client Protocol server for
DeepSeek Harness, streaming the reasoning, tool calls, plans and token usage that the
harness's own automation bridge withholds. Works with any ACP client, not just this one.

<br/>

<sub>MIT · local-first · pointed at the agent accounts you already pay for.</sub>
