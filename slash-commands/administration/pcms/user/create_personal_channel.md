# Subcommand: [pcms](../pcms.md) [user](./user.md) create_personal_channel

## Description

Creates a new personal channel.

## Syntax

```
/pcms user create_personal_channel <name>
```

## Arguments

###### name

- Type: *`Any`*
- Optional: `false`
- Default: *`None`*
- Max: 75 characters

## Cooldown

Can be used 1 time per 15 seconds, per user.

## Channel Permissions

Permissions required in a channel, channel permission overwrites are included, `Administrator` and Server Owner override this requirement.

- Bot: *`None`*
- User: *`None`*

> `View Channel`, `Read Message History` and `Embed Links` are required for bot by default, `Send Messages` (Text Channel) or `Send Messages In Threads` (Thread) or `Send Messages` and `Connect` (Voice Channel) are required for both bot and user by default.

## Default Permissions

Permissions required in role settings, `Administrator` and Server Owner override this requirement.

- Bot: `Manage Channels`, `Manage Roles`
- User: *`None`*

## Examples

- `/pcms user create_personal_channel name: my channel`

## Subcommands

*`None`*
