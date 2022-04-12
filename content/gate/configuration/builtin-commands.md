---
pcx-content-type: configuration
title: Built-In Commands
weight: 25
---

# Built-In Commands

Gate includes a few generally useful built-in commands by default.

If you want to add your own commands refer to [extensions](../../extensions).


## Commands
{{<table-wrap>}}

| Built-In Command | Permission            | Description                                                                             |
|------------------|-----------------------|-----------------------------------------------------------------------------------------|
| `/server`        | `gate.command.server` | Players can use the command to view and switch to another server.                       |
| `/glist`         | `gate.command.glist`  | View the number of players on the Gate instance. `/glist all` lists players per server. |

{{</table-wrap>}}

## Permission

By default, the built-in commands don't require the listed permission.
You can change this behaviour by setting `requireBuiltinCommandPermissions: true` in the config.

It is useful if you only want to allow players with certain permissions to use the commands.

## Disable built-in commands

By default, built-in command are registered on startup.
You can change this behaviour by setting `builtinCommands: false` in the config.

