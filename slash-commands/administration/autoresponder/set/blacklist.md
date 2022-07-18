# Subcommand: [autoresponder](../autoresponder.md) [set](./set.md) blacklist

## Description

Set the auto responder blacklisted channels.

## Syntax

```
/autoresponder set blacklist <action> <channels>
```

## Arguments

###### action

- Type: Option<Add|Remove|Overwrite>
- Optional: `false`
- Default: *`None`*

###### channels

- Type: [ChannelResolvable](/typedefs/ChannelResolvable.md)...
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

- `/autoresponder set blacklist action: Add channels: 748114061966835772`
- `/autoresponder set blacklist action: Overwrite channels: 748114061966835772 <#740198766707212361>`

## Subcommands

*`None`*
