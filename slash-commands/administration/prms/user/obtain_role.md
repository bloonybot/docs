# Subcommand: [prms](../prms.md) [user](./user.md) obtain_role

## Description

Submit a request to obtain a role.

## Syntax

```
/prms user obtain_role <role>
```

## Arguments

###### role

- Type: [RoleResolvable](/typedefs/RoleResolvable.md)
- Optional: `false`
- Default: *`None`*

## Cooldown

Can be used 1 time per 15 seconds, per user.

## Channel Permissions

Permissions required in a channel, channel permission overwrites are included, `Administrator` and Server Owner override this requirement.

- Bot: *`None`*
- User: *`None`*

> `View Channel`, `Read Message History` and `Embed Links` are required for bot by default, `Send Messages` (Text Channel) or `Send Messages In Threads` (Thread) or `Send Messages` and `Connect` (Voice Channel) are required for both bot and user by default.

## Default Permissions

Permissions required in role settings, `Administrator` and Server Owner override this requirement.

- Bot: *`None`*
- User: *`None`*

## Examples

- `/prms user obtain_role role: 827910959871164486`

## Subcommands

*`None`*
