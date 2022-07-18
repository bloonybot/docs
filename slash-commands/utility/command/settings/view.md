# Subcommand: [command](../command.md) [settings](./settings.md) view

## Description

Views settings of a command.

## Syntax

```
/command settings view [category] [command]
```

## Arguments

###### category

- Type: Option<Traditional Command|Slash Command>
- Optional: `true`
- Default: *`None`*

###### command

- Type: [CommandResolvable](/typedefs/CommandResolvable.md)
- Optional: `true`
- Default: *`None`*

## Cooldown

Can be used 1 time per 15 seconds, per user.

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

- `/command settings view`
- `/command settings view category: Traditional Command command_name: ping`
- `/command settings view category: Slash Command command_name: pcms user mychannel`

## Subcommands

*`None`*
