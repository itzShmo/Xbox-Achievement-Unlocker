# Xbox Achievement Unlocker
[![GitHub contributors][contributors-badge]][contributors-url]
[![GitHub forks][forks-badge]][forks-url]
[![GitHub stars][stars-badge]][stars-url]
[![GitHub issues][issues-badge]][issues-url]
[![GitHub release][release-badge]][release-url]

[![Discord][discord-id]][discord-invite]

A convenient tool for unlocking achievements on Microsoft/Xbox games, inspired by the functionality of Steam Achievements Manager.

## Table of Contents
- [Xbox Achievement Unlocker](#xbox-achievement-unlocker)
  - [Table of Contents](#table-of-contents)
  - [Why Xbox Achievement Unlocker?](#why-xbox-achievement-unlocker)
  - [How It Works](#how-it-works)
  - [Achievements So Far](#achievements-so-far)
  - [To-Do List](#to-do-list)
  - [Discord Server](#discord-server)

## Why Xbox Achievement Unlocker?
Through my research, I found that there weren't any free achievement unlockers available. Instead, there were numerous paid services offering tools or services to unlock a full game's achievements on your account. This prompted me to create a program that doesn't randomly add gamerscore from arbitrary games or charge you to unlock a game's achievements.

## How It Works
This tool utilizes memory.dll to extract the user's XAuth token from one of the Xbox app processes. The token is then used to make web requests to Xbox servers, pulling information on achievements and informing the server which of these achievements have been unlocked.

## Achievements So Far
1. Can semi-reliably obtain XAuth.
2. Able to query the Xbox server for profile information (XUID, Gamerscore, and Gamertag).
3. Can populate panel with recently played games (non-Xbox titles filtered out).
4. Able to retrieve achievement data after selecting one of these games.
5. Can populate a list on the second form with achievement data.
6. Can unlock achievements on non-event-based games.
7. Able to detect which games are event-based.
8. Can spoof time in unowned games using a supplied Title ID.
9. Experimental stat editor for certain games using title managed stats

## To-Do List
1. Understand event-based achievements and how they are unlocked.
2. Full UI redesign. (possibly WPF? open to ideas and pull requests for this)
3. Integrate game search into main window and spoofer to allow for quick selection.
4. Ability to spoof the platform a game is being played on.

## Discord Server
Join us on our [Discord server][discord-invite] to stay updated and engage with our community.

[contributors-badge]: https://img.shields.io/github/contributors/ItsLogic/Xbox-Achievement-Unlocker?style=for-the-badge
[contributors-url]: https://github.com/ItsLogic/Xbox-Achievement-Unlocker/graphs/contributors
[forks-badge]: https://img.shields.io/github/forks/ItsLogic/Xbox-Achievement-Unlocker?style=for-the-badge
[forks-url]: https://github.com/ItsLogic/Xbox-Achievement-Unlocker/network/members
[stars-badge]: https://img.shields.io/github/stars/ItsLogic/Xbox-Achievement-Unlocker?style=for-the-badge
[stars-url]: https://github.com/ItsLogic/Xbox-Achievement-Unlocker/stargazers
[issues-badge]: https://img.shields.io/github/issues/ItsLogic/Xbox-Achievement-Unlocker?style=for-the-badge
[issues-url]: https://github.com/ItsLogic/Xbox-Achievement-Unlocker/issues
[release-badge]: https://img.shields.io/github/v/release/ItsLogic/Xbox-Achievement-Unlocker?style=for-the-badge
[release-url]: https://github.com/ItsLogic/Xbox-Achievement-Unlocker/releases
[discord-id]: https://img.shields.io/discord/1013602813093359657?logo=discord&style=for-the-badge
[discord-invite]: https://discord.gg/ugDvSw7cns
