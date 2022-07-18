# Subcommand: [pcms](../pcms.md) [set](./set.md) thresholds

## Description

Set the role thresholds for adding friends, it represents the maximum amount of friends allowed.

## Syntax

```
/pcms set thresholds <action> <role_thresholds>
```

## Arguments

###### action

- Type: Option<Add|Remove|Overwrite>
- Optional: `false`
- Default: *`None`*

###### role_thresholds

- Type: [RoleThresholdResolvable](/typedefs/RoleThresholdResolvable.md)...
- Optional: `false`
- Default: *`None`*
- Max: 15 [RoleThresholdResolvable](/typedefs/RoleThresholdResolvable.md)s | 400 characters

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

- `/pcms set thresholds action: Add role_thresholds: 827910959871164486 1`
- `/pcms set thresholds action: Overwrite role_thresholds: 827910959871164486 1, <@&740194908932931625> 3`

## Subcommands

*`None`*
