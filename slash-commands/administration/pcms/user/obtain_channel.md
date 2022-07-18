# Subcommand: [pcms](../pcms.md) [user](./user.md) obtain_channel

## Description

Submit a request to obtain a channel.

## Syntax

```
/pcms user obtain_channel <channel>
```

## Arguments

###### channel

- Type: [ChannelResolvable](/typedefs/ChannelResolvable.md)
- Optional: `false`
- Default: *`None`*

## Cooldown

Can be used 1 time per 15 seconds, per user.

## Channel Permissions

Permissions required in a channel, channel permission overwrites are included, `Administrator` and Server Owner override this requirement.

- Bot: *`None`*
- User: *`None`*

> `View Channel`, `Read Message History` and `Embed Links` are required for bot by default, `Send Messages` (Text Channel) or `Send Messages In Threads` (Thread) or `Send Messages` and `Connect` (Voice Channel) are required for both bot and user by default.

## Default Permissions

Permissions required in role settings, `Administrator` and Server Owner override this requirement.

- Bot: *`None`*
- User: *`None`*

## Examples

- `/pcms user obtain_channel channel: 748114061966835772`

## Subcommands

*`None`*
