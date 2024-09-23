[![Static Badge](https://img.shields.io/badge/Telegram-Bot%20Link-Link?style=for-the-badge&logo=Telegram&logoColor=white&logoSize=auto&color=blue)](https://t.me/boinker_bot/boinkapp?startapp=boink1197825376)

#  AUTO FARM FOR BOINKERS💩💎

## Recommendation before use

# 🔥🔥 PYTHON version must be 3.10 🔥🔥

> 🇷 🇺 README in russian available [here](README-RU.md)

## Features  
|                      Feature                       | Supported |
|:--------------------------------------------------:|:---------:|
|                   Multithreading                   |     ✔️     |
|              Proxy binding to session              |     ✔️     |
| Auto-register your account with your referral link |     ✔️     |
|                     Auto spins                     |     ✔️     |
|                 Auto claim booster                 |     ✔️     |
|                     Auto tasks                     |     ✔️     |
|                Auto upgrade Boinker                |     ✔️     |
|             Auto spin wheel of fortune             |     ✔️     |
|           Support for pyrogram .session            |     ✔️     |


## [Settings](https://github.com/BlackJkee/BoinkersBot/blob/main/.env-example/)
|          Settings           |                                 Description                                  |
|:---------------------------:|:----------------------------------------------------------------------------:|
|    **API_ID / API_HASH**    |   Platform data from which to run the Telegram session (default - android)   |
|       **PLAY_GAMES**        |              Play games or just start farming (default is True)              |
| **USE_RANDOM_DELAY_IN_RUN** |       Whether to use random delay at startup (True / False)                  |
|   **RANDOM_DELAY_IN_RUN**   |               Random seconds delay (default is [5, 30]                       |
|         **USE_REF**         |         Register accounts with ur referral or not (default - False)          |
|         **REF_ID**          |   Your referral argument (comes after app/startapp? in your referral link)   |
|   **USE_PROXY_FROM_FILE**   | Whether to use a proxy from the `bot/config/proxies.txt` file (True / False) |

## Quick Start 📚

To fast install libraries and run bot - open `run.bat` on **Windows** or `run.sh` on **Linux**

## Prerequisites
Before you begin, make sure you have the following installed:
- [**Python**](https://www.python.org/downloads/release/python-3100/) **version 3.10**

## Obtaining API Keys
1. Go to [**my.telegram.org**](https://my.telegram.org/auth) and log in using your phone number.
2. Select `API development tools` and fill out the form to register a new application.
3. Record the `API_ID` and `API_HASH` provided after registering your application in the `.env` file.

## Installation
You can download the [**repository**](https://github.com/BlackJkee/BoinkersBot) by cloning it to your system and installing the necessary dependencies:
```shell
git clone https://github.com/BlackJkee/BoinkersBot.git
cd BoinkersBot
```

Then you can do automatic installation by typing:

Windows:
```shell
run.bat
```

Linux:
```shell
run.sh
```

# Linux manual installation
```shell
sudo sh install.sh
python3 -m venv venv
source venv/bin/activate
pip3 install -r requirements.txt
cp .env-example .env
nano .env  # Here you must specify your API_ID and API_HASH, the rest is taken by default
python3 main.py
```

You can also use arguments for quick start, for example:
```shell
~/BoinkersBot >>> python3 main.py --action (1/2)
# Or
~/BoinkersBot >>> python3 main.py -a (1/2)

# 1 - Run clicker
# 2 - Creates a session
```

# Windows manual installation
```shell
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
copy .env-example .env
# Here you must specify your API_ID and API_HASH, the rest is taken by default
python main.py
```

You can also use arguments for quick start, for example:
```shell
~/BoinkersBot >>> python main.py --action (1/2)
# Or
~/BoinkersBot >>> python main.py -a (1/2)

# 1 - Run clicker
# 2 - Creates a session
```
