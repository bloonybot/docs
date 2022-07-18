# Subcommand: [prms](../prms.md) [admin](./admin.md) assign

## Description

Assigns personal role to a member.

## Syntax

```
/prms admin assign <member> <role>
```

## Arguments

###### member

- Type: [MemberResolvable](/typedefs/MemberResolvable.md)
- Optional: `false`
- Default: *`None`*

###### role

- Type: [RoleResolvable](/typedefs/RoleResolvable.md)
- Optional: `false`
- Default: *`None`*

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

- `/prms admin assign member: 676103178323886085 role: 827910959871164486`

## Subcommands

*`None`*
