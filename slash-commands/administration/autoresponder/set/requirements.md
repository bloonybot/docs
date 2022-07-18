# Subcommand: [autoresponder](../autoresponder.md) [set](./set.md) requirements

## Description

Set the required roles for creating auto response.

## Syntax

```
/autoresponder set requirements <action> <roles> [custom_trigger]
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

###### custom_trigger

- Type: Option<True|False>
- Optional: `true`
- Default: `False`

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

- `/autoresponder set requirements action: Add roles: 827910959871164486`
- `/autoresponder set requirements action: Overwrite roles: 827910959871164486 <@&740194908932931625> custom_trigger: True`

## Subcommands

*`None`*
