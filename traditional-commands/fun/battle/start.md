# Subcommand: [battle](./battle.md) start

## Description

Starts a new battle game.

## Syntax

```
[p]battle start <members...>
```

## Arguments

###### members

- Type: [MemberResolvable](/typedefs/MemberResolvable.md)...
- Optional: `false`
- Default: *`None`*
- Min: 2 [MemberResolvable](/typedefs/MemberResolvable.md)s
- Max: 30 [MemberResolvable](/typedefs/MemberResolvable.md)s

## Aliases

*`None`*

## Cooldown

Can be used 1 time per 20 seconds, per server.

## Channel Permissions

Permissions required in a channel, channel permission overwrites are included, `Administrator` and Server Owner override this requirement.

- Bot: `Manage Channels`
- User: *`None`*

> `View Channel`, `Read Message History` and `Embed Links` are required for bot by default, `Send Messages` (Text Channel) or `SEND_MESSAGES_IN_THREADS` (Thread) or `Send Messages` and `Connect` (Voice Channel) are required for both bot and user by default.

## Default Permissions

Permissions required in role settings, `Administrator` and Server Owner override this requirement.

- Bot: `Manage Roles`
- User: *`None`*

## Examples

- `,battle start 676103178323886085 894884615909670923`
- `,battle start <@676103178323886085> <@894884615909670923>`
- `,battle start <@676103178323886085> 894884615909670923`

## Subcommands

*`None`*
