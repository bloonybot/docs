# Main Command: channels

## Description

Server channels diagnosis. Available channel types: text, voice, stage, category, news and thread.

## Syntax

```
[p]channels [channel | channel type]
```

## Arguments

###### channel | channel type

- Type: [ChannelResolvable](/typedefs/ChannelResolvable.md) | Option<text|voice|stage|category|news|thread>
- Optional: `true`
- Default: *`None`*

## Aliases

*`None`*

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

- `,channels`
- `,channels 748114061966835772`
- `,channels <#748114061966835772>`
- `,channels text`

## Subcommands

*`None`*
