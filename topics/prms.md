# PRMS

> Personal Role Management System saves your time by implementing automation in your server, no one will ask you to edit their personal roles anymore!

## About

Personal Role Management System (PRMS) is similar to PCMS, it helps you to make your current personal role system more organised. Role owners can customise and share their role with their friends without requesting an admin.

## Quick Setup

The configurations of this system is similar to PCMS, system will be fully functional after setting the role requirements with `/prms set requirements`. If you want to allow them to share the role with their friends, setup the role thresholds by running `/prms set thresholds`. Role thresholds represent the limitation of role sharing. For example, if you have done something like this:

```py
2 VIP
5 Staff
4 Good Members
```

Members with all these roles are allowed to share their personal role with 11 friends. The colour of their personal role may not show up due to role hierarchy, you need to drag it up. You don't need to do this if you have setup `/prms set position`:

```py
Admin
Personal Roles < position role
               < new personal role
Booster
```

Newly created personal roles will be dragged up automatically below the position role.

## Manage personal roles in your server

The admin tools of PRMS are similar to PCMS, you can manage a huge amount of personal roles by just clicking a few buttons, amazing! Check the status of any personal role by running `/prms admin roles` or take action against ineligible role owners by using `/prms admin enforce`. Bloony is always the best friend of server management.

## Obtain and customise your personal role

The `set` and `admin` categories are locked for normal members, you only need to know how to use the commands in `user` category. It's quite straight forward since you can just create a role by running `/prms user create_personal_role` or customise your role with `/prms user myrole`. Don't forget to click the sync button after editing your role. If you have a personal role already and it's not managed by the system, simply submit a request with `/prms user obtain_role` and wait for an admin response patiently.

## Relevant Commands

- [prms](/slash-commands/administration/prms/prms.md)
