# Subcommand: [csms](../csms.md) [group](./group.md) view

## Description

Get information of a CSMS group, join or leave a group.

## Syntax

```
/csms group view <group id>
```

## Arguments

###### group id

- Type: Integer
- Optional: `false`
- Default: *`None`*
- Min: 1
- Max: 1000000

## Cooldown

Can be used 1 time per 20 seconds, per user.

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

- `/csms group view group_id: 1`

## Subcommands

*`None`*
