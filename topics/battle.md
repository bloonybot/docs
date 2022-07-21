# Battle

> A simple but exciting fun game for you to play with your friends.

## About

Except server management, we also provide a small amount of fun commands. You can set them up in your server to increase diversity of events.

## Quick Setup

Pretty easy, you just need to setup:

- Manager Role (optional): Basically event manager. They can start and clear a game without fulfilling the `Manage Guild` default permission requirement, they can also participate in a game.
- Game Channel (required): People cannot play this game outside of this channel.
- Access Role (required): Participants will be granted this role to access the game channel.

Don't forget to configure permission overwrites in the game channel properly.

```py
              View Channel  Send Messages
Default          true          false
Manager Role     true          true
Access Role      true          true
```

## Start a new game

You can start a game with `[p]battle start` and tell your friends how to play by showing the `[p]battle` embed. Each game cannot have less than 2 participants or have more than 30 participants. Access role will be assigned after starting a new game and channel permission overwrites will also be changed, both will be done automatically.

## Cancel or clear a game

You can cancel a currently active game or clear a previously ended game by running `[p]battle clear`, access role will not be removed automatically if you suddenly cancel a currently active game.

## Relevant Commands

- [battle](/traditional-commands/fun/battle/battle.md)
