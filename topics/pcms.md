# PCMS

> Personal Channel Management System allows your server members to take care of their own channel without annoying your admins, with powerful tools to implement role requirements and thresholds.

## About

Personal Channel Management System (PCMS) is basically an efficient way for you to manage a huge amount of personal channels in your community server. You will no longer be annoyed by those channel owners when they want to edit channel name, add or remove friends in their channels.

## Quick Setup

Nobody is allowed to create personal channel by default, you need to set some role requirements with `/pcms set requirements` first. Members with one of the whitelisted roles will be able to create one personal channel. They won't be able to add friends to their channel without additional role thresholds setup by using `/pcms set thresholds`. Role thresholds represent the maximum amount of friends allowed in a personal channel. For example, if you have done something like this:

```js
2 Booster
3 Double Booster
6 Generous Donator
```

Members with both `Booster` and `Double Booster` roles are allowed to add 5 friends max. We recommend you to set a category for creating personal channel with `/pcms set category`, otherwise, channel will be created in the top of your server.

## Manage personal channels in your server

PCMS offers high-quality tools for you to manage personal channels conveniently and efficiently, that's why Bloony is the best choice. You can get info of a personal channel and take action on it by using `/pcms admin channels` with argument provided or get a list of all current managed personal channels by using `/pcms admin channels` with no argument provided. If your server has reached the maximum channel limit, you may want to delete some inactive personal channels. Some channel owners may no longer be eligible to own a channel anymore, `/pcms admin inactivity` and `/pcms admin enforce` can solve all these problems by clicking a few buttons.

## Obtain and customise your personal channel

The `set` and `admin` categories are locked for normal members, you only need to know how to use the commands in `user` category. It's quite straight forward since you can just create a channel by running `/pcms user create_personal_channel` or customise your channel with `/pcms user mychannel`. Don't forget to click the sync button after editing your channel. If you have a personal channel already and it's not managed by the system, simply submit a request with `/pcms user obtain_channel` and wait for an admin response patiently.

## Relevant Commands

- [pcms](/slash-commands/administration/pcms/pcms.md)
