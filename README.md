# Orchestrate

A local AI agent workspace for knowledge work — a chat-first desktop app over Claude Code (and ChatGPT/Codex), with projects, real files, a terminal, and live preview.

This is the **public distribution** repo: app downloads and the auto-update feed. The application source is private.

## Download

Grab the latest `Orchestrate.app` / DMG from the [Releases](https://github.com/sanisideup/orchestrate/releases) page, open it, and drag Orchestrate to your Applications folder. **Apple Silicon (arm64)** only for now.

Once installed, the app keeps itself up to date automatically.

## Requirements

Orchestrate drives your local `claude` CLI (and optionally `codex`). The app's first-run setup walks you through installing and signing into them. App state lives in `~/.orchestrate/`; your documents stay as real files in each project folder.

## Status

Pre-1.0. Signed + notarized builds and silent auto-update are rolling out — until then a build may need a one-time right-click → **Open** on first launch (Gatekeeper).
