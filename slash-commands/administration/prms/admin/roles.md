# Subcommand: [prms](../prms.md) [admin](./admin.md) roles

## Description

Shows a list of all managed personal roles, or a specific one.

## Syntax

```
/prms admin roles [role_or_user]
```

## Arguments

###### role_or_user

- Type: [RoleResolvable](/typedefs/RoleResolvable.md) | [UserResolvable](/typedefs/UserResolvable.md)
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

- Bot: `Manage Roles`
- User: *`None`*

## Examples

- `/prms admin roles`
- `/prms admin roles role_or_user: 827910959871164486`

## Subcommands

*`None`*
