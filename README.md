# ClipVault 🔖

> Advanced clipboard manager for power users.

[![PyPI](https://img.shields.io/pypi/v/clipvault)](https://pypi.org/project/clipvault/)
[![License](https://img.shields.io/github/license/HoraceDong31415-bit/clipvault)](LICENSE)

## Why ClipVault?

Because your clipboard history should be smart, not just a dump.

### Features

- 🔍 **Smart Search** - Full-text search across all clips
- 🏷️ **Categories** - Auto-detect: code, URL, command, text
- ⭐ **Favorites** - Star important clips
- 📊 **Statistics** - Track clipboard usage
- 🔒 **Privacy** - All data local
- 📦 **Import/Export** - JSON format

## Quick Start

```bash
# Install
pip install clipvault

# Save current clipboard
cv save

# Save with tag
cv save --tag work

# List recent
cv list

# Search
cv search "python"

# Paste from history
cv paste 5
```

## Commands

| Command | Description |
|---------|-------------|
| `cv save [text]` | Save to history |
| `cv list` | Show history |
| `cv search <query>` | Full-text search |
| `cv paste <idx>` | Paste from history |
| `cv favorite <idx>` | Toggle favorite |
| `cv stats` | Usage statistics |

## Installation

```bash
pip install clipvault
```

## Requirements

- Python 3.8+
- macOS / Linux / Windows
