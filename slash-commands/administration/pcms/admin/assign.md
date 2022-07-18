# Subcommand: [pcms](../pcms.md) [admin](./admin.md) assign

## Description

Assigns personal channel to a member.

## Syntax

```
/pcms admin assign <member> <channel>
```

## Arguments

###### member

- Type: [MemberResolvable](/typedefs/MemberResolvable.md)
- Optional: `false`
- Default: *`None`*

###### channel

- Type: [ChannelResolvable](/typedefs/ChannelResolvable.md)
- Optional: `false`
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

- `/pcms admin assign member: 676103178323886085 channel: 748114061966835772`

## Subcommands

*`None`*
