# Subcommand: [pcms](../pcms.md) [set](./set.md) category

## Description

Set the category to create new personal channels.

## Syntax

```
/pcms set category [channel]
```

## Arguments

###### channel

- Type: [ChannelResolvable](/typedefs/ChannelResolvable.md)
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

- `/pcms set category`
- `/pcms set category channel: 740200942934294619`

## Subcommands

*`None`*
