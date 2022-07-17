# Main Command: bans

## Description

Obtain a ban in your server.

## Syntax

```
[p]bans <banned user>
```

## Arguments

###### banned user

- Type: [UserResolvable](/typedefs/UserResolvable.md)
- Optional: `false`
- Default: *`None`*

## Aliases

*`None`*

## Cooldown

Can be used 1 time per 15 seconds, per user.

## Channel Permissions

Permissions required in a channel, channel permission overwrites are included, `Administrator` and Server Owner override this requirement.

- Bot: `Ban Members`
- User: `Ban Members`

> `View Channel`, `Read Message History` and `Embed Links` are required for bot by default, `Send Messages` (Text Channel) or `Send Messages In Threads` (Thread) or `Send Messages` and `Connect` (Voice Channel) are required for both bot and user by default.

## Default Permissions

Permissions required in role settings, `Administrator` and Server Owner override this requirement.

- Bot: *`None`*
- User: *`None`*

## Examples

- `,bans 676103178323886085`
- `,bans <@676103178323886085>`

## Subcommands

*`None`*
