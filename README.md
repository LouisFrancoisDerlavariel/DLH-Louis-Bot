# MusicBot

**About this branch**

This branch of MusicBot is only compatible with the `rewrite` version of the discord.py library, which can be installed using `python3 -m pip install -U git+https://github.com/Rapptz/discord.py@rewrite#egg=discord.py[voice]`. Since it is a dependency in `requirements.txt`, the library should be automatically installed with running `update.py`.

---

[![GitHub release](https://img.shields.io/github/release/Just-Some-Bots/MusicBot.svg?style=flat-square)](https://just-some-bots.github.io/MusicBot/)
[![Python](https://img.shields.io/badge/python-3.5%2C%203.6-blue.svg?style=flat-square)](https://www.python.org/downloads/)
[![Discord](https://discordapp.com/api/guilds/129489631539494912/widget.png?style=shield)](https://discord.gg/bots)

MusicBot is the original Discord music bot written in [Python](https://www.python.org "Python homepage") 3.5+, using the [discord.py](https://github.com/Rapptz/discord.py) library. It plays requested songs from YouTube and other services into a Discord server (or multiple servers). Besides, if the queue becomes empty MusicBot will play through a list of existing songs with configuration. The bot features a permission system allowing owners to restrict commands to certain people. As well as playing songs, MusicBot is capable of streaming live media into a voice channel (experimental).

![Main](https://i.imgur.com/EZljY52.png)

## Setup
Setting up the MusicBot is relatively painless - just follow one of the [guides](https://just-some-bots.github.io/MusicBot/). After that, configure the bot to ensure its connection to Discord.

The main configuration file is `config/options.ini`, but it is not included by default. Simply make a copy of `example_options.ini` and rename it to `options.ini`. See `example_options.ini` for more information about configurations.

### Commands

There are many commands that can be used with the bot. Most notably, the `play <url>` command (preceded by your command prefix) will download, process, and play a song from YouTube or a similar site. A full list of commands are available [here](https://just-some-bots.github.io/MusicBot/using/commands/ "Commands").

### Further reading

* [Support Discord server](https://discord.gg/bots)
* [Project license](LICENSE)
