<div align="center">

# Nova

### Get your agents out of the terminal.

The same agents you run in the terminal, in a Mac app for non-engineers. Runs on your existing **Claude** or **ChatGPT** subscription. Free.

[**Download for Mac →**](https://github.com/sanisideup/nova/releases/latest/download/Nova-arm64.dmg)
&nbsp;·&nbsp; [supernova.md](https://supernova.md)
&nbsp;·&nbsp; Apple Silicon &nbsp;·&nbsp; signed &amp; notarized

</div>

---

## What it is

Nova is a workspace for working with AI agents on real knowledge work: PRDs, notes, research, decisions, Slack threads. It drives the same Claude (or ChatGPT) you already run in the terminal and gives it a window you can actually read and edit.

Built for the people who don't write code all day: product managers, founders, writers, researchers, ops.

- **Projects and chats** in a left panel, chats grouped by folder or status.
- **Your files and a real terminal** a glance away on the right.
- **Markdown, fully rendered and editable in place.** Read and edit like a human does, not a computer. No asterisks, hashtags, or brackets. Autosaves as you type.
- **Live artifacts.** HTML and JSX render live in a sandboxed preview beside the chat.
- **A readable chat.** You and the agent in clear lanes. Tool activity folds into one tidy card. No more walls of terminal output.
- **Your project's local `/skills` in the chat.** Type `/` and the skills in your project's `.claude` folder autocomplete. No trip to the terminal.
- **Claude or ChatGPT.** Pick your model right in the composer, per chat, on your own subscription.
- **An in-app web browser.** Browse and act on live web URLs beside your work — no more tabbing out.

Full walkthrough, screenshots, and the capability-by-capability comparison: **[supernova.md](https://supernova.md)**.

## Download

Grab the latest `Nova.app` / DMG from the [**Releases**](https://github.com/sanisideup/nova/releases) page, open it, and drag Nova to your Applications folder. **Apple Silicon (arm64) only** for now. The app keeps itself up to date automatically.

## Private by design

- **We never read your conversations.** We never see, store, or train on them, and don't want to.
- **Requests go straight to your model.** Your Mac talks directly to Claude or ChatGPT. Nothing routes through our servers.

App state lives in `~/.nova/`; your documents stay as real files in each project folder.

## How it compares

How Nova stacks up against the tools it borrows from, as I used each in mid-2026:

| Capability | Codex app | Cowork app | Claude Code | Cursor | Obsidian | **Nova** |
| --- | :---: | :---: | :---: | :---: | :---: | :---: |
| Markdown rendered & editable in place | – | – | – | – | ✓ | **✓** |
| Readable agent chat, not a wall of text | ✓ | ✓ | – | ✓ | – | **✓** |
| Works in your local files | ✓ | ✓ | ✓ | ✓ | ✓ | **✓** |
| Live artifact preview beside the agent chat | ✓ | ✓ | – | – | – | **✓** |
| Your project's local `/skills` in the agent chat | – | – | – | – | – | **✓** |
| Runs on your Claude subscription | – | ✓ | ✓ | – | – | **✓** |
| Runs on your ChatGPT subscription | ✓ | – | – | – | – | **✓** |
| In-app web browser | ✓ | – | – | ✓ | – | **✓** |

## Requirements

- **macOS on Apple Silicon** (M-series). Windows support is on the roadmap.
- The **Claude** (and optionally **Codex**) CLI installed and signed in. First-run setup walks you through it.
- **Free** to use. Bring your own Claude or ChatGPT subscription (or an API key). Driving the agent programmatically draws from the metered programmatic credit, not interactive subscription limits.

## Status

Pre-1.0. Builds are signed and notarized, so they open with no Gatekeeper wall, and silent auto-update is rolling out. The application source is private; this repo is the public distribution channel (downloads + the auto-update feed).
