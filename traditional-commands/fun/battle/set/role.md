# Subcommand: [battle](../battle.md) [set](./set.md) role

## Description

Sets the battle game access role.

## Syntax

```
[p]battle set role [role]
```

## Arguments

###### role

- Type: [RoleResolvable](/typedefs/RoleResolvable.md)
- Optional: `true`
- Default: *`None`*

## Aliases

*`None`*

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

- `,battle set role`
- `,battle set role 827910959871164486`
- `,battle set role <@&827910959871164486>`

## Subcommands

*`None`*
