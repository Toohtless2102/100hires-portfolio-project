# 100Hires Portfolio Project

This repository documents my setup process for the 100Hires junior growth marketing specialist application. The first task was to install a development environment, set up AI coding tools, and create this public GitHub repository to demonstrate that I can learn unfamiliar tools and solve problems independently.

## Tools Installed

- **Cursor IDE** — AI-first code editor (a fork of VS Code) downloaded from cursor.com
- **Git for Windows** (v2.54.0) — version control system, downloaded from git-scm.com
- **Claude Code extension** by Anthropic — AI coding agent integrated into Cursor
- **Codex extension** by OpenAI — OpenAI's coding agent for IDEs
- **GitHub account** — for hosting this public repository

## Steps Completed

1. Downloaded and installed Cursor IDE on Windows from cursor.com
2. Created a free GitHub account
3. Created this public repository with an auto-generated README and `main` branch
4. Installed the **Claude Code** extension via Cursor's Extensions Marketplace and signed into my Anthropic account through the browser-based auth flow
5. Installed the **Codex** extension via Cursor's Extensions Marketplace and signed in with my OpenAI/ChatGPT account
6. Installed Git for Windows when I discovered Cursor's clone command wasn't working without it
7. Cloned this repository locally using Cursor's `Git: Clone` command
8. Edited this README to document the entire process
9. Committed and pushed the changes back to GitHub

## Issues I Ran Into & How I Solved Them

**1. Cursor opened to a new "Agent Home" interface, not the traditional editor**
After installing Cursor, the app launched into a chat-style "Agent Home" screen with no visible file explorer or extensions panel. I couldn't figure out where to install extensions. I found a small **"Editor Window ↗"** link in the top-right corner that opens the classic VS Code-style editor view, where the Extensions Marketplace lives.

**2. The Claude Code and Codex extensions didn't show an obvious "Sign In" button after install**
After installing each extension, I expected a clear sign-in popup but didn't see one. I used Cursor's Command Palette (`Ctrl+Shift+P`) and searched the extension name (e.g., "Claude Code", "Codex") to find commands like *"Open Codex Sidebar"*. Running these commands opened the actual extension panel, which then displayed the sign-in flow that opens in the browser.

**3. Both extensions require paid plans for full usage**
Claude Code requires Claude Pro and Codex requires ChatGPT Plus to actually run requests. I installed both extensions and signed in with free accounts to satisfy the setup requirement, but did not subscribe. Claude Code did successfully respond to a test "hello" message; Codex showed a "Get Plus" upsell.

**4. The `Git: Clone` command was missing from Cursor's Command Palette**
When I tried to clone this repo using `Ctrl+Shift+P` → "Git: Clone", the command didn't appear. After typing just "Git" I saw other Git commands but not Clone. I realized Git is not pre-installed on Windows (unlike macOS). I downloaded Git for Windows from git-scm.com, ran the installer with default settings, and **fully closed and reopened Cursor** so it could detect the new install. After that, "Git: Clone" appeared in the Command Palette and the clone worked.

## What I Learned

- **Reading errors carefully matters more than memorizing commands.** Each blocker had a clue — a missing menu item, a hidden button — that pointed at the actual problem.
- **AI coding tools are layered.** "Claude Code" alone doesn't do much; it needs an IDE, an extension, an account, and credits. Understanding that each layer has its own requirements helped me debug faster.
- **Windows has more setup friction than I expected.** Git not being pre-installed was the biggest stumble, and one I'll remember.

## Time Taken

Approximately 1 hours, spread across 2 sessions on 07/05/2026.

---

*Submitted by AadarshPatel for the 100Hires junior growth marketing specialist application.*