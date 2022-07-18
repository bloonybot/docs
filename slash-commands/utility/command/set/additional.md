# Subcommand: [command](../command.md) [set](./set.md) additional

## Description

Set a server rule, it applies to a specific command.

## Syntax

```
/command set additional <options> <action> <category> <command> [object]
```

## Arguments

###### options

- Type: Option<Enable|Disable|Override>
- Optional: `false`
- Default: *`None`*

###### action

- Type: Option<Add|Remove>
- Optional: `false`
- Default: *`None`*

###### category

- Type: Option<Traditional Command|Slash Command>
- Optional: `false`
- Default: *`None`*

###### command

- Type: [CommandResolvable](/typedefs/CommandResolvable.md)
- Optional: `false`
- Default: *`None`*

###### object

- Type: [RoleResolvable](/typedefs/RoleResolvable.md) | [ChannelResolvable](/typedefs/ChannelResolvable.md) | [UserResolvable](/typedefs/UserResolvable.md)
- Optional: `true`
- Default: *`None`*

## Cooldown

Can be used 1 time per 10 seconds, per user.

## Channel Permissions

Permissions required in a channel, channel permission overwrites are included, `Administrator` and Server Owner override this requirement.

- Bot: *`None`*
- User: `Administrator`

> `View Channel`, `Read Message History` and `Embed Links` are required for bot by default, `Send Messages` (Text Channel) or `Send Messages In Threads` (Thread) or `Send Messages` and `Connect` (Voice Channel) are required for both bot and user by default.

## Default Permissions

Permissions required in role settings, `Administrator` and Server Owner override this requirement.

- Bot: *`None`*
- User: *`None`*

## Examples

- `/command set additional options: Disable action: Add category: Traditional Command command_name: ping`
- `/command set additional options: Disable action: Remove category: Traditional Command command_name: help object: 748114061966835772`
- `/command set additional options: Override action: Add category: Slash Command command_name: csms report view object: <@676103178323886085>`

## Subcommands

*`None`*
