# Homebrew Tap for Matrix

This is the official Homebrew tap for [Matrix](https://github.com/ojowwalker77/Claude-Matrix) - a persistent memory system for Claude Code.

## Installation

```bash
brew tap ojowwalker77/matrix
brew install matrix
```

## After Installation

Run the setup command:

```bash
matrix init
```

This will:
- Initialize the SQLite database
- Register the MCP server with Claude Code
- Configure your `CLAUDE.md` with Matrix instructions

## Updating

```bash
brew upgrade matrix
```

## Uninstalling

```bash
brew uninstall matrix
brew untap ojowwalker77/matrix
```

## Documentation

See the main repository: https://github.com/ojowwalker77/Claude-Matrix
