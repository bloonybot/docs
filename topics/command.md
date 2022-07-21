# Command

> Advanced Command Accessibility Control System allows you to disable a command, or even more?

## About

`/command` is the main command of Command Accessibility Control System, you may ask: I can just disable your commands in server settings, why I need to use this system? Good question, now I will explain it.

## Command Structure Diagnosis

```py
<prefix><main command> <subcommand group> <subcommand>
```

Since it is the most complicated system that I have ever made, a command is classified into 4 parts.

- prefix
- main command
- subcommand group
- subcommand

A valid command must have a prefix and main command, subcommand group and subcommand are optional. The prefix of a slash command is obviously `/`. Since it is so difficult to explain, we have given a name to each category:

Common command

```py
<prefix><main command>
```

Medium size command

```py
<prefix><main command> <subcommand>
```
Complex command

```py
<prefix><main command> <subcommand group> <subcommand>
```

You can set command override on any of them, big brain moment.

## Command Override Hierarchy

Enabled categories override disabled categories, it is the base rule. If you set an override on a main command, its subcommand groups and subcommands will be affected. We will show you an example.

`/pcms user mychannel`

- Disable `pcms` by default: the whole command will be unavailable.
- Disable `pcms` for by default and enable `pcms user mychannel` for a role: members with the role can run `pcms user mychannel`, nobody can run other subcommands.
- Enable `pcms` by default and disable `pcms user`: members can run any subcommands.
- Disable `pcms` for a channel, enable `pcms user` for a role: members with the role can run all subcommands under subcommand group `user` in any channels, other people cannot run any subcommands in that channel. For other subcommands like `pcms set category`, nobody can run them in that channel, including members with that role.

If you still don't understand it, don't touch this and mess up anything. Go to support server and ask for help.

## Command Permission Override

**DANGER**! This function allows members to bypass command default permission requirements, do not touch this without fully understanding the system. You may want to allow a specific group of members to use a command, which is locked behind dangerous permission requirement by default. For example, you want to allow trial moderator role to handle reports in `/csms report view`, but that role does not have ban members permission. In this case, you can enable permission override for that role on that command.

## Relevant Commands

- [command](/slash-commands/utility/command/command.md)
