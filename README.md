<h1 align="center"><b>Unlimited Filter Bot</b></h1>

<h4 align="center">An Advanced Filter Bot with nearly Unlimited Filters!!</h4>

<p align='center'>
  <a href="https://www.python.org/" alt="made-with-python"> <img src="https://img.shields.io/badge/Made%20with-Python-867ae9.svg?style=flat-square&logo=python&logoColor=867ae9&color=867ae9" /> </a>
  <a href="https://github.com/dakshkohli23/Sharingan-Rename-Bot/" alt="Maintenance"> <img src="https://img.shields.io/badge/Maintained%3F-Yes-green.svg?style=flat-square&logo=serverless&logoColor=867ae9&color=867ae9" /> </a>
</p>
<p align="center">
    <a href="https://github.com/dakshkohli23/Unlimited-Filter-Bot"> <img src="https://img.shields.io/codacy/grade/4d58f2a402b54aed8a7d95f7add45a81?color=867ae9&logo=codacy&logoColor=867ae9&style=for-the-badge" alt="Codacy" /></a>
    <a href="https://github.com/dakshkohli23/Unlimited-Filter-Bot"> <img src="https://img.shields.io/github/repo-size/dakshkohli23/Unlimited-Filter-Bot?color=867ae9&logo=github&logoColor=867ae9&style=for-the-badge" /></a>
    <a href="https://github.com/dakshkohli23/Unlimited-Filter-Bot/commits"> <img src="https://img.shields.io/github/last-commit/dakshkohli23/Unlimited-Filter-Bot?color=867ae9&logo=github&logoColor=867ae9&style=for-the-badge" /></a>
    <a href="https://github.com/dakshkohli23/Unlimited-Filter-Bot/issues"> <img src="https://img.shields.io/github/issues/dakshkohli23/Unlimited-Filter-Bot?color=867ae9&logo=github&logoColor=867ae9&style=for-the-badge" /></a>
    <a href="https://github.com/dakshkohli23/Unlimited-Filter-Bot/network/members"> <img src="https://img.shields.io/github/forks/dakshkohli23/Unlimited-Filter-Bot?color=867ae9&logo=github&logoColor=867ae9&style=for-the-badge" /></a>  
    <a href="https://pypi.org/project/Telethon/"> <img src="https://img.shields.io/pypi/v/telethon?color=867ae9&label=telethon&logo=python&logoColor=867ae9&style=for-the-badge" /></a>
</p>

[![Compass_botz](https://img.shields.io/badge/Compass-Bots-867ae9?style=flat&logo=telegram)](https://telegram.dog/compass_botz)  
ㅤㅤㅤㅤㅤㅤㅤ   
[![MIT license](https://img.shields.io/badge/License-MIT-867ae9?style=flat)](https://github.com/dakshkohli23/Unlimited-Filter-Bot/blob/main/LICENSE)  [![Open Source](https://badges.frapsoft.com/os/v2/open-source.svg?v=103)](https://github.com/dakshkohli23/Unlimited-Filter-Bot)


## An advanced Filter Bot with nearly unlimitted filters!


### Features
* Nearly unlimited filters
* Supports all type of filters(Including Alert Button Filter).
* Can save button filters directly (Rose Bot Feature)
* Supports multiple PM connections
* And all other features of a Filter Bot :D


#### Deploy the bot and start adding your filters :)


## How to use the bot
* Add bot to your group with admin rights.

* Add your filters :)


## Bot Commands

(You need to be an admin or Auth User in order to use these commands)

> Filter Commands
* `/add <filtername> <filtercontent>`  -  To add your filter. You can also reply to your content with /add command.

* `/del <filtername>`  -  Delete your filter.

* `/delall`  -  Delete all filters from group. (Group Owner Only!)

* `/viewfilters`  -  List all filters in chat.

> Connection Commands
* `/connect groupid`  -  Connects your group to PM. You can also simply use, `/connect` in groups.

* `/connections`  -  Manage your connections. (only in PM)

> Extras
* `/status`  -  Shows current status of your bot (Auth User Only)

* `/id`  -  Shows ID information

* `/info <userid>`  -  Shows User Information. Also use `/info` as reply to some message for their details!


## You can check the video tutorial on how to deploy

<img src="https://img-premium.flaticon.com/png/512/1383/1383260.png?token=exp=1621339601~hmac=a3050c5f539a9985fe6ac893220e1522" width="50">

[Click here to see tutorial video](https://youtu.be/hkmc3e7U7R4)

Thanks to [InfotelGroup](https://telegram.dog/InFoTelGroup) and [Erich Daniken](https://telegram.dog/ErichDaniken) for the video


## Any bugs or errors or suggestions, report at [Compass Bots](https://telegram.dog/compass_botz)


## Installation

### Deploy to Heroku
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/Oxyver5600/Unlimited-Filter-Bot-1)

### Deploy in your vps
```sh
git clone https://github.com/dakshkohli23/Unlimited-Filter-Bot
cd Unlimited-Filter-Bot
pip3 install -r requirements.txt
# <Create config.py appropriately>
python3 bot.py
```


## Configs

* TG_BOT_TOKEN  - Get bot token from @BotFather

* API_ID        - From my.telegram.org (or @UseTGXBot)

* API_HASH      - From my.telegram.org (or @UseTGXBot)

* AUTH_USERS  - ID of users that can use the bot commands. Get from [MissRose Bot](https://telegram.dog/MissRose_bot) by using /id command

* DATABASE_URI  - Mongo Database URL from https://cloud.mongodb.com/

* DATABASE_NAME  - Your database name from mongoDB. Default will be 'Cluster0'

* SAVE_USER  -  Give yes or no . Usefull for getting userinfo and total user counts. May reduce filter capacity :( .

* HEROKU_API_KEY  -  To check dyno status. Go to https://dashboard.heroku.com/account , scroll down and press Reveal API


### Optional - To set alternate Bot Commmands!
( *Add required field as heroku var and give desired command as value. You can edit it in sample_config.py also!*)

* ADD_FILTER_CMD  -  default will be 'add'

* DELETE_FILTER_CMD  -  default will be 'del'

* DELETE_ALL_CMD  -  default will be 'delall'

* CONNECT_COMMAND  -  default will be 'connect'

* DISCONNECT_COMMAND  -  default will be 'disconnect'

EG;  
![Vars Eg](https://telegra.ph/file/1f956f3491f2f20a9c1ec.jpg)

## Credits

<p align="left">
  <a href="https://github.com/pyrogram/pyrogram">
    <img alt="Pyrogram" src ="https://i.imgur.com/BOgY9ai.png" width="104.75" height="32"/>
  </a>
</p>

<p align="left">
  <a href="https://docs.mongodb.com">
    <img alt="MongoDB" src ="https://img.shields.io/badge/MongoDB-%234ea94b.svg?&style=for-the-badge&logo=mongodb&logoColor=white"/>
  </a>
</p>
