# Subcommand: [pcms](../pcms.md) [admin](./admin.md) channels

## Description

Shows a list of all managed personal channels, or a specific one.

## Syntax

```
/pcms admin channels [channel_or_user]
```

## Arguments

###### channel_or_user

- Type: [ChannelResolvable](/typedefs/ChannelResolvable.md) | [UserResolvable](/typedefs/UserResolvable.md)
- Optional: `true`
- Default: *`None`*

## Cooldown

Can be used 1 time per 20 seconds, per user.

## Channel Permissions

Permissions required in a channel, channel permission overwrites are included, `Administrator` and Server Owner override this requirement.

- Bot: *`None`*
- User: `Administrator`

> `View Channel`, `Read Message History` and `Embed Links` are required for bot by default, `Send Messages` (Text Channel) or `Send Messages In Threads` (Thread) or `Send Messages` and `Connect` (Voice Channel) are required for both bot and user by default.

## Default Permissions

Permissions required in role settings, `Administrator` and Server Owner override this requirement.

- Bot: `Manage Channels`, `Manage Roles`
- User: *`None`*

## Examples

- `/pcms admin channels`
- `/pcms admin channels channel_or_user: 748114061966835772`

## Subcommands

*`None`*
