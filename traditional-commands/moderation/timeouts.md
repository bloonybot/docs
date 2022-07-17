# Main Command: timeouts

## Description

Obtain all timed out members in your server, or a specific one.

## Syntax

```
[p]timeouts [member]
```

## Arguments

###### member

- Type: [MemberResolvable](/typedefs/MemberResolvable.md)
- Optional: `true`
- Default: *`None`*

## Aliases

*`None`*

## Cooldown

Can be used 1 time per 15 seconds, per user.

## Channel Permissions

Permissions required in a channel, channel permission overwrites are included, `Administrator` and Server Owner override this requirement.

- Bot: `Moderate Members`
- User: `Moderate Members`

> `View Channel`, `Read Message History` and `Embed Links` are required for bot by default, `Send Messages` (Text Channel) or `Send Messages In Threads` (Thread) or `Send Messages` and `Connect` (Voice Channel) are required for both bot and user by default.

## Default Permissions

Permissions required in role settings, `Administrator` and Server Owner override this requirement.

- Bot: *`None`*
- User: *`None`*

## Examples

- `,timeouts`
- `,timeouts 676103178323886085`
- `,timeouts <@676103178323886085>`

## Subcommands

*`None`*
