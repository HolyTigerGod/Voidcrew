## Voidcrew Reborn Codebase

A hobby project, by Jackrip. [/tg/station space station 13 fork](https://tgstation13.org/). Inspired by [shiptest](https://github.com/shiptest-ss13/Shiptest)

| Website             | Link                                                                                                 |
| ------------------- | ---------------------------------------------------------------------------------------------------- |
| Code                | [https://github.com/voidcrew/Voidcrew](https://github.com/voidcrew/Voidcrew)                     |
| Wiki                | [https://wiki.voidcrew-lrp.com](https://wiki.voidcrew-lrp.com.com)                     |                            |
| Voidcrew Reborn Discord | [https://discord.gg/6z9wQTYJmK](https://discord.gg/6z9wQTYJmK) |

This is Voidcrew. A shuttle based Space Station 13 server that allows you to explore the outer edges of space with your crew. Land on planets, asteroids and ruins in search of new treasure. Survey the cosmos while protecting your ship from the dangers that wait. Trade, kill, and team up with other ships in order to survive. The void is unforgiving, and you will die. But you know what say, it's about the friends you made along the way.

All github inquiries (such as moderation actions) may be handled via Jackrip in the discord.

## DOWNLOADING

[Downloading](.github/guides/DOWNLOADING.md)

[Running a server](.github/guides/RUNNING_A_SERVER.md)

[Maps and Away Missions](.github/guides/MAPS_AND_AWAY_MISSIONS.md)

## Compilation

**The quick way**. Find `bin/server.cmd` in this folder and double click it to automatically build and host the server on port 1337.

**The long way**. Find `bin/build.cmd` in this folder, and double click it to initiate the build. It consists of multiple steps and might take around 1-5 minutes to compile. If it closes, it means it has finished its job. You can then [setup the server](.github/guides/RUNNING_A_SERVER.md) normally by opening `tgstation.dmb` in DreamDaemon.

**Building tgstation in DreamMaker directly is deprecated and might produce errors**, such as `'tgui.bundle.js': cannot find file`.

**[How to compile in VSCode and other build options](tools/build/README.md).**

## LICENSE

All code after [commit 333c566b88108de218d882840e61928a9b759d8f on 2014/31/12 at 4:38 PM PST](https://github.com/tgstation/tgstation/commit/333c566b88108de218d882840e61928a9b759d8f) is licensed under [GNU AGPL v3](https://www.gnu.org/licenses/agpl-3.0.html).

All code before [commit 333c566b88108de218d882840e61928a9b759d8f on 2014/31/12 at 4:38 PM PST](https://github.com/tgstation/tgstation/commit/333c566b88108de218d882840e61928a9b759d8f) is licensed under [GNU GPL v3](https://www.gnu.org/licenses/gpl-3.0.html).
(Including tools unless their readme specifies otherwise.)

See LICENSE and GPLv3.txt for more details.

The TGS DMAPI is licensed as a subproject under the MIT license.

See the footer of [code/\_\_DEFINES/tgs.dm](./code/__DEFINES/tgs.dm) and [code/modules/tgs/LICENSE](./code/modules/tgs/LICENSE) for the MIT license.

All assets including icons and sound are under a [Creative Commons 3.0 BY-SA license](https://creativecommons.org/licenses/by-sa/3.0/) unless otherwise indicated.
