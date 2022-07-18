# Subcommand: [command](../command.md) [set](./set.md) default

## Description

Set a default server rule, it applies to all commands.

## Syntax

```
/command set default <options> <action> [object]
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

- `/command set default options: Disable action: Add`
- `/command set default options: Disable action: Remove object: 748114061966835772`
- `/command set default options: Override action: Add object: <@676103178323886085>`

## Subcommands

*`None`*
