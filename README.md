# autonuke

Tool to automatically nuke and restore my workstation on a scheduled basis.

## Why

- Enforce a habit of never relying on hardware.
- Enforce a habit of always having the workstation setup scripted.
- Enforce that the latest software is up to date and that nothing that was unintentionally installed on the OS.
- Enforce that OS secrets are rotated on a scheduled basis.

## Objectives

- It should be able to fully nuke and clean my workstation.
- It should be able to schedule a nuke and visually show it when time is closing in.
- It should be able to restore itself onto the workstation by executing a single script.
- It should be able to restore my workstation from the same restoration script.
- It should be reusable, but my own configuration stored separately and encrypted by a secret.
- It should be able to verify that scripts have not been tampered with.
