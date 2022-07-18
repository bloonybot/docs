# Subcommand: [pcms](../pcms.md) [set](./set.md) perms

## Description

Set the permission overwrites, this rule applies to all personal channels.

## Syntax

```
/pcms set perms [category] [role_overwrite]
```

## Arguments

###### category

- Type: Option<Default|Owner|Friends>
- Optional: `true`
- Default: *`None`*

###### role_overwrite

- Type: [RoleResolvable](/typedefs/RoleResolvable.md)
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

- `/pcms set perms category: Default`
- `/pcms set perms role_overwrite: <@&740194908932931625>`

## Subcommands

*`None`*
