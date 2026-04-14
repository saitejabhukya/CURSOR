# Cursor IDE Setup Task

## Tools Installed

- **Cursor IDE** - AI-powered code editor downloaded from https://cursor.com
- **Claude Code for VS Code** - Official Anthropic extension installed via Cursor Extensions Marketplace
- **Claude Code CLI** - Installed via npm using `npm install -g @anthropic-ai/claude-code`
- **Codex** - OpenAI Codex extension installed via Cursor Extensions Marketplace

## Steps Completed

1. Downloaded and installed Cursor IDE from cursor.com
2. Opened Extensions panel (`Ctrl+Shift+X`) and searched for "Claude Code"
3. Installed the **Claude Code for VS Code** extension by Anthropic
4. Opened the Terminal in Cursor and ran `claude` to start the CLI
5. Installed Claude Code CLI via `npm install -g @anthropic-ai/claude-code`
6. Ran `claude` again and selected Dark mode theme
7. Logged in using **Claude account with subscription** (Option 1)
8. Opened Extensions panel again and searched for "Codex"
9. Installed the **Codex** extension in Cursor
10. Created a public GitHub repository
11. Cloned the repository and opened it in Cursor using `Ctrl+Shift+P` → Git: Clone
12. Created and edited this README.md file
13. Committed and pushed changes to GitHub

## Issues Encountered & How I Solved Them

### Issue 1: "claude" command not recognized in terminal
- **Problem:** Running `claude` in the terminal gave an error:
  `The term 'claude' is not recognized as the name of a cmdlet`
- **Solution:** Installed the Claude Code CLI separately using:
  `npm install -g @anthropic-ai/claude-code`

### Issue 2: No login button visible after installing the extension
- **Problem:** After installing Claude Code for VS Code, there was no visible Sign In button
- **Solution:** Logged in through the terminal by running `claude` and selecting the login option from the CLI prompt