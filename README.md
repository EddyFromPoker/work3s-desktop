<p align="center">
  <img src="https://raw.githubusercontent.com/EddyFromPoker/work3s-desktop/main/assets/app-icon-green.svg" alt="Work3s" width="160" />
</p>

<h3 align="center">Agentic Command Center</h3>

<p align="center">
  <strong>Your AI workforce that never sleeps.</strong><br/>
  Work3s listens to your task boards, assigns work to AI agents, and ships code — autonomously.<br/>
  Delegate multiple tasks in parallel. AI handles the heavy lifting.<br/>
  You review, test, and make the final call.
</p>

<p align="center">
  <em>Work3s doesn't cut corners — it removes the work that never needed a human in the first place.<br/>
  Ten tasks running in parallel, each producing production-grade code, each waiting for your sign-off.<br/>
  You're not working harder. You're not sacrificing quality.<br/>
  You're simply not doing the parts that AI does better.</em>
</p>

<p align="center">
  <strong>10x the output. Same quality bar.</strong>
</p>

<p align="center">
  <a href="https://www.work-3s.com/"><img src="https://img.shields.io/github/v/release/EddyFromPoker/work3s-desktop?style=for-the-badge&color=22c55e&label=Download" alt="Download Latest" /></a>
  &nbsp;
  <img src="https://img.shields.io/badge/macOS-13%2B-000?style=for-the-badge&logo=apple&logoColor=white" alt="macOS" />
  &nbsp;
  <img src="https://img.shields.io/github/downloads/EddyFromPoker/work3s-desktop/total?style=for-the-badge&color=6366f1&label=Downloads" alt="Total Downloads" />
</p>

<p align="center">
  <a href="https://www.work-3s.com/">Download for Mac (Apple Silicon)</a> &bull;
  <a href="https://www.work-3s.com/">Download for Mac (Intel)</a>
</p>

---

## The Problem

You have a backlog full of tickets. You have AI coding tools that can write code. But nothing connects the two.

You're still manually reading tickets, switching branches, opening terminals, launching AI assistants, reviewing output, raising PRs, and updating boards. Every task requires a dozen context switches before a single line of code is written.

**Work3s eliminates the donkey work.** AI agents read your tickets, write the code, and raise the PRs. You focus on what only a human can do — review the output, run your tests, and approve the final result. Multiple tasks run in parallel. You step in only at the finish line.

---

## Task Listeners — Autonomous AI Workflows

The core of Work3s. Connect your project management boards and let AI agents pick up work automatically.

### How It Works

1. **Connect your boards** — JIRA, Linear, Trello, GitHub Projects, Asana, Notion, ClickUp, Azure DevOps, or Monday.com
2. **Define your triggers** — Filter by assignment, status, labels, or any combination
   - *"Assigned to me & moved to In Progress"*
   - *"Labeled `bug` & priority High"*
   - *"Sprint active & unassigned"*
3. **Choose your AI agent** — Claude Code, Gemini CLI, GitHub Copilot, Codex, Aider, or any custom command
4. **Let it run** — Work3s watches your boards in real time. When a task matches your trigger:

   > **Read** the ticket and requirements  
   > **Create** an isolated Git worktree for the task  
   > **Launch** the AI agent with full task context  
   > **Implement** the fix or feature autonomously  
   > **Raise** a Pull Request with a summary of changes  
   > **Move** the ticket to Done (or your configured status)

Multiple tasks execute in parallel, each in its own isolated worktree. No conflicts, no interference. You check in when you're ready — review the diffs, run your test suite, and merge with confidence.

### Configure Once, Automate Forever

Each repository gets its own Task Listener configuration:

- **Workflow type** — Trunk-based, Git-flow, or custom branching strategy
- **AI agent** — Select from 10+ supported assistants with optional "yolo mode" for fully autonomous sessions
- **Merge strategy** — Merge, rebase, or squash
- **Sensitive files** — Automatically copy `.env`, config files, and secrets to new worktrees
- **Story point estimation** — Fibonacci, T-shirt sizing, linear, or powers of two
- **Auto-PR** — Automatically raise a pull request when the AI agent completes its work
- **Task templates** — Customize how task context is passed to the AI agent

---

## One-Click PR Review

Review pull requests without leaving Work3s.

- **AI-powered analysis** — Select your preferred AI model to review diffs, identify issues, and suggest improvements
- **Split or unified diffs** — View changes the way you prefer
- **Inline suggestions** — Actionable feedback on every file changed
- **Review history** — Track past reviews and comments

Open a PR, click Review, get results. That simple.

---

## Git Power Shortcuts

Work3s replaces dozens of terminal commands with instant keyboard-driven actions.

| Shortcut | Action |
|---|---|
| `Cmd+K` | **Command Palette** — Search and execute any action |
| `Cmd+P` | **Quick Switch** — Jump between repositories instantly |
| `Cmd+N` | **New Worktree** — Isolated branch in one keystroke |
| `Cmd+O` | **Add Repository** — Bring in a new repo |
| `Cmd+R` | **Refresh** — Sync status across all worktrees |
| `Cmd+B` | **Star Repository** — Pin your most-used repos |
| `Cmd+,` | **Settings** — Configure everything |
| `Cmd+1-9` | **Jump to Repo** — Direct access by position |

### Worktree Management

Every branch gets its own directory. No stashing. No rebuilds. No conflicts with running servers.

- **Create from PR** — One click to check out any Pull Request into an isolated worktree
- **Real-time status** — Color-coded indicators across every worktree: clean, modified, untracked
- **One-click open** — Launch any worktree in your IDE or terminal instantly
- **Multi-repo workspace** — Manage 100+ worktrees across 10+ repositories in a single window
- **File watcher** — Automatic UI updates when Git state changes — no manual refresh needed

---

## Supported Integrations

<table>
<tr>
<td width="33%" valign="top">

**Project Management**
- JIRA
- Linear
- Trello
- GitHub Projects
- Azure DevOps
- Asana
- Notion
- ClickUp
- Monday.com

</td>
<td width="33%" valign="top">

**AI Agents**
- Claude Code
- GitHub Copilot CLI
- Gemini CLI
- Codex
- Cursor AI
- Aider
- Ollama (local)
- OpenAI CLI
- Warp Agent
- llama.cpp
- _Custom commands_

</td>
<td width="33%" valign="top">

**IDEs & Editors**
- VS Code
- Cursor
- Zed
- Sublime Text
- Vim / Neovim
- IntelliJ IDEA
- WebStorm
- PyCharm
- GoLand
- RustRover
- Xcode
- _and 15+ more_

</td>
</tr>
</table>

**Terminals:** Warp, iTerm2, Terminal.app, Kitty, Alacritty, Hyper

---

## Built for Speed

Native Rust backend. No Electron. No web wrapper. Just raw performance.

| | |
|---|---|
| **Startup** | Under 500ms |
| **Memory** | Under 200MB with 100 worktrees |
| **App size** | ~5MB |
| **Worktree creation** | ~200ms |
| **Repository switch** | Under 100ms |

---

## Installation

For download and installation instructions, visit **[work-3s.com](https://www.work-3s.com/)**.

### System Requirements

- macOS 13 (Ventura) or later
- Apple Silicon or Intel Mac
- Git installed (comes pre-installed on macOS)

Auto-updates are built in. Once installed, Work3s keeps itself current.

---

## Frequently Asked Questions

**How do Task Listeners connect to my boards?**
Work3s authenticates directly with your project management platform. Configure your credentials once in Settings, define your trigger rules, and the listener runs continuously in the background.

**Which AI agent should I use?**
Any CLI-based AI coding tool works. Claude Code and Gemini CLI are the most popular choices. Work3s passes full task context to whichever agent you select — including ticket description, acceptance criteria, and repository context.

**What is "yolo mode"?**
Yolo mode runs the AI agent with auto-permission flags, allowing it to make changes without confirmation prompts. Ideal for well-scoped tasks with clear requirements. Can be toggled per repository.

**Does it work with private repositories?**
Yes. Add a GitHub Personal Access Token in Settings and Work3s works with all your private repos.

**Do I need to understand Git worktrees?**
Not at all. Work3s handles all Git complexity behind the scenes. If you can click a button, you can use Work3s.

**What about Windows and Linux?**
macOS is the primary platform today. Windows and Linux support is on the roadmap.

---

<p align="center">
  <strong>The bottleneck was never your ability to write code. It was everything around it.</strong><br/>
  <br/>
  <a href="https://www.work-3s.com/"><strong>Get started at work-3s.com</strong></a>
</p>

---

<p align="center">
  <sub>Built with Rust + Tauri. Designed for developers who ship.</sub>
</p>
