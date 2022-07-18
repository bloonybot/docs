# Subcommand: [csms](../csms.md) [report](./report.md) submit

## Description

Submit a report against users in a CSMS group.

## Syntax

```
/csms report submit <group id> <offenders> <reason>
```

## Arguments

###### group id

- Type: Integer
- Optional: `false`
- Default: *`None`*
- Min: 1
- Max: 999999

###### offenders

- Type: [UserResolvable](/typedefs/UserResolvable.md)...
- Optional: `false`
- Default: *`None`*
- Max: 10 [UserResolvable](/typedefs/UserResolvable.md)s | 230 characters

###### reason

- Type: *`Any`*
- Optional: `false`
- Default: *`None`*
- Max: 2000 characters | 20 lines

## Cooldown

Can be used 2 times per 45 seconds, per user.

## Channel Permissions

Permissions required in a channel, channel permission overwrites are included, `Administrator` and Server Owner override this requirement.

- Bot: `Ban Members`
- User: `Ban Members`

> `View Channel`, `Read Message History` and `Embed Links` are required for bot by default, `Send Messages` (Text Channel) or `Send Messages In Threads` (Thread) or `Send Messages` and `Connect` (Voice Channel) are required for both bot and user by default.

## Default Permissions

Permissions required in role settings, `Administrator` and Server Owner override this requirement.

- Bot: *`None`*
- User: *`None`*

## Examples

- `/csms report submit group_id: 1 offenders: 676103178323886085 reason: too cool`

## Subcommands

*`None`*
