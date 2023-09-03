---
layout: post
title: "BEE6 Configs"
date: 2023-09-03 16:00:00 +0100
categories: [ "bee6", "configs" ]
permalink: /bee6/configs
---

BEE6 aims to be as customizable as possible, so we've added a bunch of configs to help you customise BEE6 to your
liking!

## Table of Contents

<!-- TOC -->
  * [Table of Contents](#table-of-contents)
  * [Legend](#legend)
  * [/user](#user)
    * [appearance](#appearance)
    * [moderation](#moderation)
    * [leveling](#leveling)
  * [guild](#guild)
    * [moderation](#moderation-1)
    * [member-events](#member-events)
      * [Customising join/leave messages](#customising-joinleave-messages)
  * [Have a suggestion?](#have-a-suggestion)
  * [Need help?](#need-help)
<!-- TOC -->

## Legend

- ⚠️ - Coming soon
- 🚧 - In progress
- ✅ - Implemented

- \[argument\] - Optional argument
- \<argument\> - Required argument

## /user

### appearance

| Config         | Description                 | Default | Status |
|----------------|-----------------------------|---------|--------|
| `compact-mode` | Whether to use compact mode | `false` | ✅      |

### moderation

| Config             | Description                                                                                    | Default | Status |
|--------------------|------------------------------------------------------------------------------------------------|---------|--------|
| `dm-notifications` | Whether you'd like to receive DM notifications when you're warned, muted, kicked, banned, etc. | `true`  | ✅      |

### leveling

| Config                 | Description                                                       | Default | Status |
|------------------------|-------------------------------------------------------------------|---------|--------|
| `dm-level-up-messages` | Whether you'd like to receive DM notifications when you level up. | `true`  | ✅      |
| `level-up-messages`    | Whether you'd like to receive level up messages.                  | `true`  | ✅      |

## guild

### moderation

| Config               | Description                                          | Default | Arguments                    | Status |
|----------------------|------------------------------------------------------|---------|------------------------------|--------|
| `mod-log-channel`    | Toggle mod logs and set the channel to send them to. |         | `<emable/disable> <channel>` | ✅      |
| `continuous-logging` | Whether to log all messages                          |         | `<enable/disable> <channel>` | ✅      |

### member-events

| Config          | Description                                                | Default | Arguments                              | Status |
|-----------------|------------------------------------------------------------|---------|----------------------------------------|--------|
| `join-message`  | Toggle join messages and set the channel to send them to.  |         | `<emable/disable> <channel> <message>` | ✅      |
| `leave-message` | Toggle leave messages and set the channel to send them to. |         | `<emable/disable> <channel> <message>` | ✅      |

#### Customising join/leave messages

You can customise join/leave messages by using the following variables:

| Variable      | Description                    | Example        |
|---------------|--------------------------------|----------------|
| `user`        | The user who joined/left       | `@BEE6#0001`   |
| `guild`       | The guild the user joined/left | `BEE6 Support` |
| `membercount` | The member count of the guild  | `69,420`       |
|               | More coming soon!              |                |

To use them, you'll need to use the following syntax: `[{variable}]`, for
example:`Welcome [{user}] to [{guild}]! We now have [{membercount}] members!` would
output `Welcome @BEE6 to BEE6 Support! We now have 69,420 members!`.

## Have a suggestion?

If you have a suggestion for a config, feel free to [create a feature request on GitHub]({{ site.bee6_repo }}) or join
our [support server]({{ site.discord_invite }}) and let us know!

## Need help?

If you need help with BEE6, feel free to join our [support server]({{ site.discord_invite }}) and ask in the
`#support` channel!
