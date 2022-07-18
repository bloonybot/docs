# Subcommand: [autoresponder](../autoresponder.md) [admin](./admin.md) entries

## Description

Shows a list of all auto responses, or a specific one.

## Syntax

```
/autoresponder admin entries [user]
```

## Arguments

###### user

- Type: [UserResolvable](/typedefs/UserResolvable.md)
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

- Bot: *`None`*
- User: *`None`*

## Examples

- `/autoresponder admin entries`
- `/autoresponder admin entries user: 676103178323886085`

## Subcommands

*`None`*
