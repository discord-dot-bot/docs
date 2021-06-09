---
title: Commands
description: 
published: true
date: 2021-06-09T07:55:16.039Z
tags: 
editor: markdown
dateCreated: 2021-06-08T05:57:52.411Z
---

# Discord.Bot commands list
| Command                                                      | Category    | Description                                                  | Permission Requirement | Arguments           | Example usage                     |
| ------------------------------------------------------------ | ----------- | ------------------------------------------------------------ | ---------------------- | ------------------- | --------------------------------- |
| [help](http://documentation.discordbot.cc/en/commands/help)  | Information | Get a link to the documentation and a command list           | None                   | [Command:str]       | .help ping                        |
| [ping](http://documentation.discordbot.cc/en/commands/ping)  | Information | Get the bot's websocket and Discord API ping                 | None                   | n/a                 | .ping                             |
| [uptime](http://documentation.discordbot.cc/en/commands/uptime) | Information | Get the bot's current uptime                                 | None                   | n/a                 | .uptime                           |
| [verify](http://documentation.discordbot.cc/en/commands/verify) | Captcha     | (If the server has a Verified role) Give you a captcha to verify your humanity | None                   | n/a                 | .verify                           |
| [verify-setup](http://documentation.discordbot.cc/en/commands/verify-setup) | Captcha     | Set up verification for the server                           | Admin                  | n/a                 | .verify-setup                     |
| [ipinfo](http://documentation.discordbot.cc/en/commands/ipinfo) | Information | Get information such as ZIP code, longitude, latitude, and more of an ip | None                   | \<ip:str\>          | .ipinfo 8.8.8.8                   |
| [ban](http://documentation.discordbot.cc/en/commands/ban)    | Moderation  | Ban a member                                                 | Ban members            | \<@Member:mention\> | .ban @Neumatic being an idiot     |
| [kick](http://documentation.discordbot.cc/en/commands/kick)  | Moderation  | Kick a member                                                | Kick members           | \<@Member:mention\> | .kick @Neumatic memes             |
| [avatar](http://documentation.discordbot.cc/en/commands/avatar) | Information | Get a member's avatar                                        | Manage messages        | [@Member:mention]   | .avatar @Neumatic                 |
| [mute](http://documentation.discordbot.cc/en/commands/mute)  | Moderation  | [WIP]                                                        | Manage                 | \<@member:mention\> | .mute @Neumatic                   |
| [nuke](http://documentation.discordbot.cc/en/commands/nuke)  | Utility     | Delete a channel, and clone it so all messages are deleted   | Manage channel         | n/a                 | .nuke                             |
| [purge](http://documentation.discordbot.cc/en/commands/purge) | Utility     | Bulk delete messages from a channel                          | Manage messages        | \<count:str\>       | .purge 25                         |
| [whois](http://documentation.discordbot.cc/en/commands/whois) | Information | Get information about a member                               | None                   | \<@Member\>         | .whois @Neumatic                  |
| [eval](http://documentation.discordbot.cc/en/commands/eval)  | Utility     | Evaluate javascript code                                     | Bot group Admin        | \<Code\>            | .eval console.log('Hello, world') |
| [sysinfo](http://documentation.discordbot.cc/en/commands/sysinfo) | Utility     | Get system information, such as RAM usage and CPU            | Bot group Admin        | n/a                 | .sysinfo                          |
| [cat](http://documentation.discordbot.cc/en/commands/cat)    | Images      | Get an image of a cat                                        | None                   | n/a                 | .cat                              |
| [dog](http://documentation.discordbot.cc/en/commands/dog)    | Images      | Get an image of a dog                                        | None                   | n/a                 | .dog                              |
| [bird](http://documentation.discordbot.cc/en/commands/bird)  | Images      | Get an image of a birb                                       | None                   | n/a                 | .bird                             |
| [fox](http://documentation.discordbot.cc/en/commands/fox)    | Images      | Get an image of a fundy                                      | None                   | n/a                 | .fox                              |
| [koala](http://documentation.discordbot.cc/en/commands/koala) | Images      | Get an image of a koala                                      | None                   | n/a                 | .koala                            |
| [foxgirl](http://documentation.discordbot.cc/en/commands/foxgirl) | Images      | Get an image of a foxgirl                                    | None                   | n/a                 | .foxgirl                          |
| [neko](http://documentation.discordbot.cc/en/commands/neko)  | Images      | Get an image of a neko                                       | None                   | n/a                 | .neko                             |
| [lewd](http://documentation.discordbot.cc/en/commands/lewd)  | Images      | Get an image of a lewd neko                                  | None                   | n/a                 | .lewd                             |

