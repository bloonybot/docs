# Subcommand: [autoresponder](../autoresponder.md) [user](./user.md) create_autoresponse

## Description

Creates a new auto response.

## Syntax

```
/autoresponder user create_autoresponse [content] [reactions] [custom_trigger]
```

## Arguments

###### content

- Type: *`Any`*
- Optional: `true`
- Default: *`None`*
- Max: 150 characters | 3 lines

###### reactions

- Type: [EmojiResolvable](/typedefs/EmojiResolvable.md)...
- Optional: `true`
- Default: *`None`*
- Max: 3 [EmojiResolvable](/typedefs/EmojiResolvable.md)s | 150 characters

###### custom_trigger

- Type: *`Any`*
- Optional: `true`
- Default: *`None`*
- Min: 4 characters
- Max: 30 characters

## Cooldown

Can be used 1 time per 15 seconds, per user.

## Channel Permissions

Permissions required in a channel, channel permission overwrites are included, `Administrator` and Server Owner override this requirement.

- Bot: *`None`*
- User: *`None`*

> `View Channel`, `Read Message History` and `Embed Links` are required for bot by default, `Send Messages` (Text Channel) or `Send Messages In Threads` (Thread) or `Send Messages` and `Connect` (Voice Channel) are required for both bot and user by default.

## Default Permissions

Permissions required in role settings, `Administrator` and Server Owner override this requirement.

- Bot: `Add Reactions`
- User: *`None`*

## Examples

- `/autoresponder user create_autoresponse content: I have my own ar!`
- `/autoresponder user create_autoresponse content: I have my own ar! reactions: <:meow:886415639646994453> <a:attack:805519522454306857> 833970997233188884 custom_trigger: meow`

## Subcommands

*`None`*
