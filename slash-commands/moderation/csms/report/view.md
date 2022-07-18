# Subcommand: [csms](../csms.md) [report](./report.md) view

## Description

Query and manage reports in a CSMS group.

## Syntax

```
/csms report view <group id> [case id] [guild id] [mod] [offender]
```

## Arguments

###### group id

- Type: Integer
- Optional: `false`
- Default: *`None`*
- Min: 1
- Max: 1000000

###### case id

- Type: Integer
- Optional: `true`
- Default: *`None`*
- Min: 1
- Max: 1000000

###### guild id

- Type: [Snowflake](/typedefs/Snowflake.md)
- Optional: `true`
- Default: *`None`*

###### mod

- Type: [UserResolvable](/typedefs/UserResolvable.md)
- Optional: `true`
- Default: *`None`*

###### offender

- Type: [UserResolvable](/typedefs/UserResolvable.md)
- Optional: `true`
- Default: *`None`*

## Cooldown

Can be used 1 time per 1 minute, per user.

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

- `/csms report view group_id: 1`
- `/csms report view group_id: 1 case_id: 69`
- `/csms report view group_id: 1 mod: 676103178323886085 offender: 766729393392320554`

## Subcommands

*`None`*
