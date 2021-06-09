---
title: Commands
description: 
published: true
date: 2021-06-09T06:59:02.725Z
tags: 
editor: markdown
dateCreated: 2021-06-08T05:57:52.411Z
---

# Discord.Bot commands list
| Command      | Category    | Description                                                  | Permission Requirement | Arguments           | Example usage                     |
| ------------ | ----------- | ------------------------------------------------------------ | ---------------------- | ------------------- | --------------------------------- |
| help         | Information | Get a link to the documentation and a command list           | None                   | [Command:str]       | .help ping                        |
| ping         | Information | Get the bot's websocket and Discord API ping                 | None                   | n/a                 | .ping                             |
| uptime       | Information | Get the bot's current uptime                                 | None                   | n/a                 | .uptime                           |
| verify       | Captcha     | (If the server has a Verified role) Give you a captcha to verify your humanity | None                   | n/a                 | .verify                           |
| verify-setup | Captcha     | Set up verification for the server                           | Admin                  | n/a                 | .verify-setup                     |
| ipinfo       | Information | Get information such as ZIP code, longitude, latitude, and more of an ip | None                   | \<ip:str\>          | .ipinfo 8.8.8.8                   |
| ban          | Moderation  | Ban a member                                                 | Ban members            | \<@Member:mention\> | .ban @Neumatic being an idiot     |
| kick         | Moderation  | Kick a member                                                | Kick members           | \<@Member:mention\> | .kick @Neumatic memes             |
| avatar       | Information | Get a member's avatar                                        | Manage messages        | [@Member:mention]   | .avatar @Neumatic                 |
| mute         | Moderation  | [WIP]                                                        | Manage                 | \<@member:mention\> | .mute @Neumatic                   |
| nuke         | Utility     | Delete a channel, and clone it so all messages are deleted   | Manage channel         | n/a                 | .nuke                             |
| purge        | Utility     | Bulk delete messages from a channel                          | Manage messages        | \<count:str\>       | .purge 25                         |
| whois        | Information | Get information about a member                               | None                   | \<@Member\>         | .whois @Neumatic                  |
| eval         | Utility     | Evaluate javascript code                                     | Bot group Admin        | \<Code\>            | .eval console.log('Hello, world') |
| sysinfo      | Utility     | Get system information, such as RAM usage and CPU            | Bot group Admin        | n/a                 | .sysinfo                          |
| cat          | Images      | Get an image of a cat                                        | None                   | n/a                 | .cat                              |
| dog          | Images      | Get an image of a dog                                        | None                   | n/a                 | .dog                              |
| bird         | Images      | Get an image of a birb                                       | None                   | n/a                 | .bird                             |
| fox          | Images      | Get an image of a fundy                                      | None                   | n/a                 | .fox                              |
| koala        | Images      | Get an image of a koala                                      | None                   | n/a                 | .koala                            |
| foxgirl      | Images      | Get an image of a foxgirl                                    | None                   | n/a                 | .foxgirl                          |
| neko         | Images      | Get an image of a neko                                       | None                   | n/a                 | .neko                             |
| lewd         | Images      | Get an image of a lewd neko                                  | None                   | n/a                 | .lewd                             |

