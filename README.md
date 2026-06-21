# pi-extensions

HackXIt Pi extension meta-package and umbrella repository for owned Pi packages.

## Packages

This repository is intended to install the owned Pi packages under `packages/`:

- `pi-grill-session`
- `pi-kanban`
- `pi-ready-notification`
- `pi-session-autonamer`
- `pi-session-handover`
- `pi-local-browser-automation` (pending: no `HackXIt/pi-local-browser-automation` GitHub repository found yet)
- `pi-ssh-tools`

`pi-continuity` is intentionally excluded from this initial meta-package.

## Install

```bash
pi install git:github.com/HackXIt/pi-extensions
```

Implementation note: installability still needs to be proven, especially whether Pi initializes git submodules for git-installed packages. If it does not, this repository needs an explicit install mechanism before being considered installable.
