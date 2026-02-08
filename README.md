<p align="center">
  <img src="https://raw.githubusercontent.com/EddyFromPoker/work3s-desktop/main/assets/app-icon-green.svg" alt="Work3s" width="160" />
</p>

<h3 align="center">Agentic Command Center</h3>

<p align="center">
  <strong>Stop juggling branches. Start shipping faster.</strong><br/>
  Work3s is a native desktop app that gives you superpowers for managing Git worktrees, integrating with your favorite tools, and automating your development workflow.
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

<!-- Uncomment and add screenshot paths when available
<p align="center">
  <img src="https://raw.githubusercontent.com/EddyFromPoker/work3s-desktop/main/assets/screenshot-dashboard.png" alt="Work3s Dashboard" width="800" />
</p>
-->

## Why Work3s?

Most developers work on multiple branches, PRs, and tasks throughout the day. Every context switch means stashing changes, switching branches, waiting for rebuilds, and losing your flow.

**Git worktrees** solve this by letting you have multiple branches checked out simultaneously in separate directories. But managing them from the terminal is tedious.

**Work3s makes it effortless.** One click to create a worktree from a PR. One click to open it in your IDE. Real-time status at a glance. AI-powered workflows that handle the rest.

---

## What You Get

### Instant Context Switching
Open any branch in its own directory without stashing, resetting, or waiting. Jump between tasks in seconds, not minutes. Each worktree is isolated — your `node_modules`, build cache, and running servers stay untouched.

### See Everything at a Glance
A beautiful, real-time dashboard shows the status of every worktree across all your repositories. Color-coded indicators tell you instantly which branches are clean, which have changes, and which need attention.

### One-Click IDE & Terminal Launch
Open any worktree directly in your preferred editor or terminal. Work3s supports **25+ IDEs** and **6+ terminals** — from VS Code and Cursor to the full JetBrains suite, Vim, Zed, and more.

### GitHub PR Integration
Create a worktree from any Pull Request in one step. Work3s fetches the PR branch, sets up the worktree, and opens it in your IDE. Review PRs without disrupting your current work.

### AI-Powered Workflows
Launch AI coding assistants like **Claude Code**, **GitHub Copilot CLI**, **Gemini CLI**, **Aider**, and more — directly in the worktree context. Optional "yolo mode" for fully autonomous AI coding sessions.

### Project Management Integration
Connect your task boards from **JIRA**, **Linear**, **GitHub Projects**, **Asana**, **Notion**, **ClickUp**, and more. AI-powered task tracking, story point estimation, and automatic PR creation on task completion.

### Multi-Repository Workspace
Manage all your repositories in a single window. Star favorites, organize into groups, and switch instantly with `Cmd+P`. Handle 100+ worktrees across 10+ repos without breaking a sweat.

### AI Code Review
Get AI-powered code reviews with diff visualization, issue identification, and actionable suggestions — all without leaving the app.

---

## Supported Tools

<table>
<tr>
<td width="33%" valign="top">

**IDEs & Editors**
- VS Code
- Cursor
- Zed
- Sublime Text
- Vim / Neovim
- Emacs
- Nova / Lapce
- IntelliJ IDEA
- WebStorm
- PyCharm
- GoLand
- RustRover
- Xcode
- Android Studio
- _and 10+ more_

</td>
<td width="33%" valign="top">

**AI Assistants**
- Claude Code
- GitHub Copilot CLI
- Gemini CLI
- Cursor AI
- Aider
- Ollama (local)
- OpenAI CLI
- Codex
- Warp Agent
- llama.cpp
- _Custom commands_

</td>
<td width="33%" valign="top">

**Project Management**
- JIRA
- Linear
- GitHub Projects
- Azure DevOps
- Asana
- Notion
- ClickUp
- Monday.com
- Trello

</td>
</tr>
</table>

**Terminals:** Warp, iTerm2, Terminal.app, Kitty, Alacritty, Hyper

---

## Performance

Work3s is built with **Rust** and **Tauri** for native performance. No Electron. No bloat.

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

---

## Keyboard Shortcuts

| Shortcut | Action |
|---|---|
| `Cmd+K` | Command Palette |
| `Cmd+P` | Quick Switch Repository |
| `Cmd+N` | New Worktree |
| `Cmd+O` | Add Repository |
| `Cmd+R` | Refresh |
| `Cmd+B` | Star/Unstar Repository |
| `Cmd+,` | Settings |
| `Cmd+1-9` | Jump to Repository |

---

## Frequently Asked Questions

**Does it work with private repositories?**
Yes. Add a GitHub Personal Access Token in the settings and Work3s will work with all your private repos.

**Do I need to know Git worktrees to use Work3s?**
Not at all. Work3s handles all the Git complexity behind the scenes. If you can click a button, you can use Work3s.

**What about Windows and Linux?**
macOS is the primary platform today. Windows and Linux support is on the roadmap.

**How does auto-update work?**
Work3s checks for updates automatically and notifies you when a new version is available. Updates install in the background with zero downtime.

---

<p align="center">
  <sub>Built with Rust + Tauri for native performance. Designed for developers who ship.</sub>
</p>
