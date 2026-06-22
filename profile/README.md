# Star Setup

A lightweight CLI to clone, configure, and wire single or multi-repo ecosystems.

## Repositories

| Repo | Description |
| ---- | ----------- |
| [core](https://github.com/star-setup/core) | Rust CLI — the main binary |
| [homebrew-tap](https://github.com/star-setup/homebrew-tap) | Homebrew formula tap |

## Install

```bash
# Homebrew (macOS/Linux)
brew install star-setup/tap/star-setup

# npm
npm install -g @star-setup/star-setup

# Shell (Linux/macOS)
curl --proto '=https' --tlsv1.2 -LsSf https://github.com/star-setup/core/releases/latest/download/star-setup-installer.sh | sh

# PowerShell (Windows)
powershell -ExecutionPolicy Bypass -c "irm https://github.com/star-setup/core/releases/latest/download/star-setup-installer.ps1 | iex"
```

See [star-setup/core](https://github.com/star-setup/core) for full documentation.
