# pi-extensions

HackXIt umbrella repository for owned Pi packages.

## Packages

This repository tracks the owned Pi packages under `packages/` as git submodules:

- `pi-grill-session`
- `pi-kanban` (private)
- `pi-ready-notification`
- `pi-session-autonamer`
- `pi-session-handover`
- `pi-local-browser-automation` (private)
- `pi-ssh-tools`

`pi-continuity` is intentionally excluded from this initial umbrella repository.

## Install

Install the individual package repositories directly with Pi. Do not install this umbrella repository as a meta-package: Pi's native git package install does not initialize submodules.

Examples:

```bash
pi install git:https://github.com/HackXIt/pi-ssh-tools
pi install git:https://github.com/HackXIt/pi-ready-notification
pi install git:https://github.com/HackXIt/pi-session-autonamer
pi install git:https://github.com/HackXIt/pi-session-handover
pi install git:https://github.com/HackXIt/pi-grill-session
```

Private packages require GitHub access and SSH/HTTPS credentials:

```bash
pi install git:git@github.com:HackXIt/pi-kanban.git
pi install git:git@github.com:HackXIt/pi-local-browser-automation.git
```
