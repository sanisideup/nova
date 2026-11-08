<div align="center">

# Nova

### Get your agents out of the terminal.

Claude, ChatGPT, and OpenCode in one Mac workspace for non-engineers. Bring your existing agent setup. Free.

[Download for Mac](https://github.com/sanisideup/nova/releases/latest/download/Nova-arm64.dmg)
&nbsp;·&nbsp; [supernova.md](https://supernova.md)

</div>

---

## What it is

Nova is a workspace for working with AI agents on real knowledge work: PRDs, notes, research, decisions, Slack threads. It brings Claude, ChatGPT, and OpenCode into one window you can read and edit.

Built for the people who don't write code all day: product managers, founders, writers, researchers, ops.

- **Projects and chats** in a left panel, chats grouped by folder or status.
- **Your files and a real terminal** a glance away on the right.
- **Markdown, fully rendered and editable in place.** Read and edit like a human does, not a computer. No asterisks, hashtags, or brackets. Autosaves as you type.
- **Live artifacts.** HTML pages render live in a sandboxed preview beside the chat. JSX and TSX files open as editable source.
- **A readable chat.** You and the agent in clear lanes. Tool activity folds into one tidy card. No more walls of terminal output.
- **Side chats.** Start a side chat from a main chat's menu, or type `/side-chat` (short alias `/btw`) to explore a detail while the main chat continues.
- **Your project's local skills in the chat.** Type `/` to discover commands and skills from your agent and local `.claude`, `.agents`, `.codex`, and `.opencode` folders.
- **Claude, ChatGPT, or OpenCode.** Choose your agent in the composer and switch per chat.
- **An in-app web browser.** Browse and act on live web URLs beside your work — no more tabbing out.

Full walkthrough, screenshots, and the capability-by-capability comparison: **[supernova.md](https://supernova.md)**.

## Download

Grab the latest `Nova.app` / DMG from the [**Releases**](https://github.com/sanisideup/nova/releases) page, open it, and drag Nova to your Applications folder. The app keeps itself up to date automatically.

## Private by design

- **We never read your conversations.** We never see, store, or train on them, and don't want to.
- **Requests go straight to your model provider.** Your Mac talks directly to your chosen provider. Nothing routes through our servers.

App state lives in `~/.nova/`; your documents stay as real files in each project folder.

## How it compares

This follows the comparison on [supernova.md](https://supernova.md). A check means the capability is built into the listed surface; a minus means it is not built in there.

| Capability | ChatGPT Work (desktop) | Claude Cowork (desktop) | Claude Code (terminal) | Cursor (code editor) | Obsidian (notes app) | **Nova (Mac)** |
| --- | :---: | :---: | :---: | :---: | :---: | :---: |
| Markdown rendered and editable in place | ✓ | − | − | ✓ | ✓ | **✓** |
| File list in app, including hidden files | ✓ | ✓ | − | ✓ | − | **✓** |
| Readable agent chat | ✓ | ✓ | − | ✓ | − | **✓** |
| Works in your local files | ✓ | ✓ | ✓ | ✓ | ✓ | **✓** |
| Live artifact preview beside agent chat | ✓ | ✓ | − | ✓ | − | **✓** |
| Project local skills in agent chat | ✓ | − | ✓ | ✓ | − | **✓** |
| Uses your Claude subscription | − | ✓ | ✓ | − | − | **✓** |
| Uses your ChatGPT subscription | ✓ | − | − | − | − | **✓** |
| Uses your OpenCode subscription | − | − | − | − | − | **✓** |
| In app web browser | ✓ | ✓ | − | ✓ | − | **✓** |

## Requirements

- **Apple Silicon Mac with macOS 12 or newer.** Windows support is on the roadmap.
- Install at least one supported agent CLI: **Claude**, **Codex** (for ChatGPT), or **OpenCode**. First-run setup walks you through it. OpenCode's free models need no separate provider login.
- **Free** to use. Bring your agent account or configured provider. Claude's Agent SDK uses metered programmatic credit rather than interactive subscription limits.

## Status

Pre-1.0. The application source is private; this repo is the public distribution channel (downloads + the auto-update feed).
