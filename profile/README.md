# Star Setup

A lightweight CLI to clone, configure, and wire single or multi-repo ecosystems.

> **Note:** This tool is primarily designed for my own projects and workflows. While it may work for other ecosystems, it is not guaranteed to work with all project structures or build configurations.

[![License](https://img.shields.io/github/license/star-setup/.github)](https://github.com/star-setup/.github/blob/main/LICENSE)

See [star-setup/core](https://github.com/star-setup/core) for full documentation.

## Repositories

| Name/Category | URL(s) | Description |
| ------------- | ------ | ----------- |
| Core | [GitHub](https://github.com/star-setup/core), [npm](https://www.npmjs.com/package/@star-setup/star-setup) | The main rust CLI binary |
| Homebrew Tap | [GitHub](https://github.com/star-setup/homebrew-tap) | Homebrew formula tap |
| Py Wrapper | [GitHub](https://github.com/star-setup/py-wrapper), [pypi](https://pypi.org/project/star-setup/) | PyPI distribution |

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

# pip
pip install star-setup
```
