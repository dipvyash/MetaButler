# MetaButler

![](images/metabutler.jpeg)

A modular telegram Python bot running on python3 with an sqlalchemy database.

Originally a Kigyo fork - 

Can be found on telegram as [MetaButler](https://t.me/MetaButlerBot).

The Support group can be reached out to at [MetaButler](https://t.me/MetaButler), where you can ask for help setting up your bot, discover/request new features, report bugs, and stay in the loop whenever a new update is available.

<h1 align="center"><b> ⚡ Yuriko Robot ⚡ </b></h1>

<h4 align="center">A Powerful, Smart And Simple Group Manager <br> ... Written with AioGram , Pyrogram and Telethon...</h4>
<p align='center'>
  <a href="https://www.python.org/" alt="made-with-python"> <img src="https://img.shields.io/badge/Made%20with-Python-1f425f.svg?style=flat-square&logo=python&color=blue" /> </a>
  <a href="https://github.com/TeamDeeCode/Yuriko/graphs/commit-activity" alt="Maintenance"> <img src="https://img.shields.io/badge/Maintained%3F-yes-green.svg?style=flat-square" /> </a>
</p>

<p align="center"><a href="https://t.me/YurikoRobot"><img src="(https://telegra.ph/file/e641d3dd2ccdce6a3d934.jpg)" width="400"></a></p>

## Available on Telegram as [@Yuriko](https://t.me/YurikoRobot)

# ❤️ Support
<a href="https://t.me/DeeCodeBots"><img src="https://img.shields.io/badge/Join-Telegram%20Channel-red.svg?logo=Telegram"></a>
<a href="t.me/DeCodeSupport"><img src="https://img.shields.io/badge/Join-Telegram%20Group-blue.svg?logo=telegram"></a>


## ✨ Heroku Deploy ✨
The easiest way to deploy this Bot is via Heroku.

<p align="left"><a href="https://heroku.com/deploy?template=https://github.com/TeamDeeCode/Yuriko"> <img src="https://img.shields.io/badge/Deploy%20To%20Heroku-black?style=for-the-badge&logo=heroku" width="220" height="38.45"/></a></p>

## Setting up the bot (Read this before trying to use!):

# How to setup

- `clone this repository`
- `cd MetaButler`
- `cp sample_config.ini config.ini`
- *Fill in all the vars*
- `pip3 install -U -r requirements.txt`
- *And finally* `python3 -m MetaButler`

*Enjoy!*

# How can I obtain `bot_token`?

Just talk to [BotFather](https://t.me/BotFather)(described [here](https://core.telegram.org/bots#6-botfather))
and follow a few simple steps. Once you've created a bot and received your
authorization token, that's it! that's your `bot_token`.

# How can I obtain a `api_key` and `api_hash`?

In order to obtain an API key and hash you need to do the following:

 - Sign up for Telegram using any application.
 - Login to your Telegram core: [https://my.telegram.org](https://my.telegram.org).
 - Go to '[API Development tools](https://my.telegram.org/apps)' and fill out the form.
 - You will get basic addresses as well as the `api_id` and `api_hash` parameters
   required for Metabutler's configuration file.

# Database

If you wish to use a database-dependent module(eg: locks, notes, userinfo, users, filters, welcomes),
you'll need to have a database installed on your system. I use postgres, so I recommend using it for optimal compatibility.

In the case of postgres, this is how you would set up a the database on a debian/ubuntu system. Other distributions may vary.

- install postgresql:

`sudo apt-get update && sudo apt-get install postgresql`

- change to the postgres user:

`sudo su - postgres`

- create a new database user(change YOUR_USER appropriately):

`createuser -P -s -e YOUR_USER`

This will be followed by you needing to input your password.

- create a new database table:

`createdb -O YOUR_USER YOUR_DB_NAME`

Change YOUR_USER and YOUR_DB_NAME appropriately.

- finally:

`psql YOUR_DB_NAME -h YOUR_HOST YOUR_USER`

This will allow you to connect to your database via your terminal.
By default, YOUR_HOST should be 0.0.0.0:5432.

You should now be able to build your database URI. This will be:

`sqldbtype://username:pw@hostname:port/db_name`

Replace sqldbtype with whichever db youre using(eg postgres, mysql, sqllite, etc)
repeat for your username, password, hostname(localhost?), port(5432?), and db name.

## Credits
The bot is based of on the original work done by
 - [PaulSonOfLars](https://github.com/PaulSonOfLars)
# Thanks to
 - [Dank-del](https://github.com/Dank-del)
 - [SoapDev](https://github.com/SoapDev2018)
 - And many more that we couldn't list it here!
