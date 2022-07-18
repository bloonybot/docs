# Subcommand: [prms](../prms.md) [set](./set.md) requirements

## Description

Set the required roles for creating personal role.

## Syntax

```
/prms set requirements <action> <roles>
```

## Arguments

###### action

- Type: Option<Add|Remove|Overwrite>
- Optional: `false`
- Default: *`None`*

###### roles

- Type: [RoleResolvable](/typedefs/RoleResolvable.md)...
- Optional: `false`
- Default: *`None`*
- Max: 10 [RoleResolvable](/typedefs/RoleResolvable.md)s | 300 characters

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

- `/prms set requirements action: Add roles: 827910959871164486`
- `/prms set requirements action: Overwrite roles: 827910959871164486 <@&740194908932931625>`

## Subcommands

*`None`*
