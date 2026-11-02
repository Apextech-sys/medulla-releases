# Medulla

Installers for Medulla, a personal AI with a memory of its own. Each release has:

| System | File |
|---|---|
| Windows | `Medulla-<version>-win-x64.exe` |
| macOS (Apple silicon) | `Medulla-<version>-mac-arm64.dmg` |
| macOS (Intel) | `Medulla-<version>-mac-x64.dmg` |
| Debian, Ubuntu | `Medulla-<version>-linux-amd64.deb` |
| Fedora | `Medulla-<version>-linux-x86_64.rpm` |
| Arch | `Medulla-<version>-linux-x64.pacman` |
| Any Linux | `Medulla-<version>-linux-x86_64.AppImage` |

The app checks here for new versions and updates itself. This repository holds only the installers:
the code is kept elsewhere, and everything the app remembers stays on the computer it runs on.

It needs [Claude Code](https://claude.com/claude-code) and [Codex](https://developers.openai.com/codex/cli) signed in on the same computer. Everything else comes with it.
