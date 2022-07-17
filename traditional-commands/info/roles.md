# Main Command: roles

## Description

Server roles diagnosis.

## Syntax

```
[p]roles [role]
```

## Arguments

###### role

- Type: [RoleResolvable](/typedefs/RoleResolvable.md)
- Optional: `true`
- Default: *`None`*

## Aliases

*`None`*

## Cooldown

Can be used 1 time per 20 seconds, per user.

## Channel Permissions

Permissions required in a channel, channel permission overwrites are included, `Administrator` and Server Owner override this requirement.

- Bot: *`None`*
- User: *`None`*

> `View Channel`, `Read Message History` and `Embed Links` are required for bot by default, `Send Messages` (Text Channel) or `Send Messages In Threads` (Thread) or `Send Messages` and `Connect` (Voice Channel) are required for both bot and user by default.

## Default Permissions

Permissions required in role settings, `Administrator` and Server Owner override this requirement.

- Bot: *`None`*
- User: `Manage Roles`

## Examples

- `,roles`
- `,roles 827910959871164486`
- `,roles <@&827910959871164486>`

## Subcommands

*`None`*
