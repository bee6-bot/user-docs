---
layout: post
title: "BEE6 Commands"
date: 2023-09-02 16:30:01 +0100
categories: [ "bee6" ]
permalink: /bee6/commands
---

BEE6 has an abundance of commands to help you manage your server. You can view the commands by typing `/` in any text
channel, we've also listed them below!

## Legend

- ⚠️ - Coming soon
- 🚧 - In progress
- ✅ - Implemented

- \[argument\] - Optional argument
- \<argument\> - Required argument

## General Commands

| Command      | Description                                                                   | Arguments    |
|--------------|-------------------------------------------------------------------------------|--------------|
| `/help`      | Shows the help menu.                                                          |              |
| `/bot-stats` | Shows information about BEE6                                                  |              |
| `/invite`    | Shows the invite link for BEE6                                                |              |
| `/support`   | Shows the support server for BEE6                                             |              |
| `/run-code`  | Run JavaScript code using [Piston][piston], with other languages coming soon! | `<language>` |

## Leveling Commands

| Command        | Description                         | Arguments | Status |
|----------------|-------------------------------------|-----------|--------|
| `/level`       | Shows your current level and XP     | `<user>`  | ✅      | 
| `/leaderboard` | Shows the server's leaderboard      |           | ✅      |
| `/synclevels`  | Syncs your levels with [MEE6][mee6] |           | ✅      |
|                | More coming soon!                   |           |        |

## Moderation Commands

| Command  | Description                  | Arguments                   | Status |
|----------|------------------------------|-----------------------------|--------|
| `/ban`   | Bans a user from the server  | `<user> <reason> <confirm>` | ✅      |
| `/kick`  | Kicks a user from the server | `<user> <reason>`           | ✅      |
| `/mute`  | Mutes a user                 | `<user> <reason> <time>`    | ✅      |
| `/warn`  | Warns a user                 | `<user> <reason>`           | ✅      |
| `/purge` | Purges messages              | `<amount>`                  | 🚧     |
|          | More coming soon!            |                             |        |

## Economy Commands

| Command         | Description                         | Arguments         | Status |
|-----------------|-------------------------------------|-------------------|--------|
| `/balance`      | Shows your current balance          | `<user>`          | ✅      |
| `/donate`       | Donate your balance to another user | `<user> <amount>` | ✅      |
| `/deposit`      | Deposit your balance to the bank    | `[amount]`        | ✅      |
| `/withdraw`     | Withdraw your balance from the bank | `[amount]`        | ✅      |
| `/rob`          | Rob another user                    | `<user>`          | ✅      |
| `/work`         | Work for money                      |                   | ✅      |
| `/gamble`       | Gamble your money                   |                   |        |
| `/gamble coin`  | Gamble your money on coinflip       | `<amount> <side>` | ✅      |
| `/gamble dice`  | Gamble your money on dice           | `<amount> <side>` | ✅      |
| `/gamble races` | Gamble your money on a bee race     | `<amount> <bee>`  | ✅      |

## Configuration Commands

| Command  | Description                                    | Arguments | Status |
|----------|------------------------------------------------|-----------|--------|
| `/guild` | Allows you to change the guild's configuration |           | ✅      |
| `/user`  | Allows you to change your configuration        |           | ✅      |
|          | [View all configuration options][configs]      |           |        |

[piston]: https://github.com/engineer-man/piston

[mee6]: https://mee6.xyz 
[configs]: /bee6/configs