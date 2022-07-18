# Subcommand: [prms](../prms.md) [admin](./admin.md) enforce

## Description

Enforces the role requirements or thresholds against all personal role owners.

## Syntax

```
/prms admin enforce <action>
```

## Arguments

###### action

- Type: Option<Role requirements for owning personal role|Role thresholds for sharing personal role>
- Optional: `false`
- Default: *`None`*

## Cooldown

Can be used 1 time per 1 minute and 30 seconds, per server.

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

- `/prms admin enforce action: Role requirements for owning personal role`
- `/prms admin enforce action: Role thresholds for sharing personal role`

## Subcommands

*`None`*
