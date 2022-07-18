# Subcommand: [csms](../csms.md) [group](./group.md) list

## Description

Global CSMS groups overview, create your own group.

## Syntax

```
/csms group list [group id] [owner id] [name] [guild id] [status] [min cases]
```

## Arguments

###### group id

- Type: Integer
- Optional: `true`
- Default: *`None`*
- Min: 1
- Max: 1000000

###### owner id

- Type: [Snowflake](/typedefs/Snowflake.md)
- Optional: `true`
- Default: *`None`*

###### name

- Type: *`Any`*
- Optional: `true`
- Default: *`None`*
- Min: 3 characters
- Max: 50 characters

###### guild id

- Type: [Snowflake](/typedefs/Snowflake.md)
- Optional: `true`
- Default: *`None`*

###### status

- Type: Option<Open|Require Application|Closed>
- Optional: `true`
- Default: *`None`*

###### min cases

- Type: Integer
- Optional: `true`
- Default: *`None`*
- Min: 1
- Max: 1000000

## Cooldown

Can be used 1 time per 1 minute, per user.

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

- `/csms group list`
- `/csms group list group_id: 1`
- `/csms group list name: meow min_cases: 50`

## Subcommands

*`None`*
