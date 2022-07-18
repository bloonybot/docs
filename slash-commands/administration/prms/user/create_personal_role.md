# Subcommand: [prms](../prms.md) [user](./user.md) create_personal_role

## Description

Creates a new personal role.

## Syntax

```
/prms user create_personal_role <name> [colour] [icon]
```

## Arguments

###### name

- Type: *`Any`*
- Optional: `false`
- Default: *`None`*
- Max: 50 characters

###### colour

- Type: [ColourResolvable](/typedefs/ColourResolvable.md)
- Optional: `true`
- Default: *`None`*
- Max: 6 characters

###### icon

- Type: [IconURLResolvable](/typedefs/IconURLResolvable.md)
- Optional: `true`
- Default: *`None`*
- Max: 200 characters

## Cooldown

Can be used 1 time per 15 seconds, per user.

## Channel Permissions

Permissions required in a channel, channel permission overwrites are included, `Administrator` and Server Owner override this requirement.

- Bot: *`None`*
- User: *`None`*

> `View Channel`, `Read Message History` and `Embed Links` are required for bot by default, `Send Messages` (Text Channel) or `Send Messages In Threads` (Thread) or `Send Messages` and `Connect` (Voice Channel) are required for both bot and user by default.

## Default Permissions

Permissions required in role settings, `Administrator` and Server Owner override this requirement.

- Bot: `Manage Roles`
- User: *`None`*

## Examples

- `/prms user create_personal_role name: my role`
- `/prms user create_personal_role name: my role colour: c3ffde icon: https://cdn.discordapp.com/emojis/886415639646994453.png`

## Subcommands

*`None`*
