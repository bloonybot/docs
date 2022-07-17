# Main Command: invites

## Description

Server invites diagnosis.

## Syntax

```
[p]invites [user]
```

## Arguments

###### user

- Type: [UserResolvable](/typedefs/UserResolvable.md)
- Optional: `true`
- Default: *`None`*

## Aliases

*`None`*

## Cooldown

Can be used 1 time per 30 seconds, per user.

## Channel Permissions

Permissions required in a channel, channel permission overwrites are included, `Administrator` and Server Owner override this requirement.

- Bot: `Manage Guild`
- User: *`None`*

> `View Channel`, `Read Message History` and `Embed Links` are required for bot by default, `Send Messages` (Text Channel) or `Send Messages In Threads` (Thread) or `Send Messages` and `Connect` (Voice Channel) are required for both bot and user by default.

## Default Permissions

Permissions required in role settings, `Administrator` and Server Owner override this requirement.

- Bot: *`None`*
- User: *`None`*

## Examples

- `,invites`
- `,invites 676103178323886085`
- `,invites <@676103178323886085>`

## Subcommands

*`None`*
