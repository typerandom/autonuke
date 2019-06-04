# doomsday

Tool to automatically nuke my macOS workstation on a scheduled basis.

<img src="static/avatar.jpg" />

## Why

- Enforce a habit of never relying on hardware.
- Enforce a habit of always having the workstation setup scripted.
- Enforce that the latest software is up to date and that nothing that was unintentionally installed on the OS.

## Objectives

- It should be able to fully nuke and clean my macOS workstation.
- It should be able to schedule a nuke and visually show it when time is closing in.

## How

- https://www.jamf.com/blog/reinstall-a-clean-macos-with-one-button/
- https://grahamrpugh.com/2018/03/26/reinstall-macos-from-system-volume.html

## API

```
$ doomsday [api]
```

#### set [days]

Sets a doom to trigger in [days] (default 30).

### whatsup

Output what's going on.

#### abort

Abort the doom.

#### doom [--yes]

This triggers the system to be wiped and reinstalled.

Note: Unless `--yes` is provided, it will prompt before proceeding.
