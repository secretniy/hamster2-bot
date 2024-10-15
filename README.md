# Table of Languages
- [English](#English)
- [Русский](#Русский)
# English
# Hamster 2.0 - Auto Claim Bot

🔗 **Referral Link**: [Hamster 2.0](https://t.me/hamster_kOmbat_bot/start?startapp=kentId948720889)

## 📢 Telegram Group

Join our Telegram group to stay updated and get instructions on how to use this tool:

- [Secretniy Channel](https://t.me/secretniy)
- [Secretniy Chat](https://t.me/+eTYhicQb1KczYTYy)

## 🌟 Features

| Feature        | Status | Description                                |
| -------------- | ------ | ------------------------------------------ |
| Auto Sync  | Default | Claim profit per hour when idle |
| Auto Buy Upgrade   | On/Off | 4 method options                             |
| Auto Buy Skin | On/Off | Selected Highest Skin ID                      |
| Auto Complete Tasks      | On/Off | Complete Tasks             |
| Static UserAgent| Auto ON | Can change         |

## Auto Upgrade metode
Upgrade items with the highest profit

Upgrade items at the lowest price

Upgrade items with a price less than balance

Upgrade item with the highest payback RECOMENDED!

## 🧑‍🔧 How to install in Linux
#Linux
```shell
apt install -y git python3 python3-pip
git clone https://github.com/secretniy/hamster2-bot.git
cd hamster2-bot/
python3 -m pip install -r requirements.txt --break-system-packages
```
Enter you (`query_id=... /user=...`) in file data.txt. Each new token from a new line.

How to find [query_id=... /user=..](https://t.me/secretniy)

To change a file in bash use the command `nano data.txt`

`ctrl+o` `enter` -  save file.

`ctrl+x` -  exit editor.


Modify the config.json file as desired.

**bool** : `true` or `false`

  ```bash
{
    "use_proxy": false,
    "DELAY_UPGRADE": false,
    "MIN_DELAY_UPGRADE": 4,
    "MAX_DELAY_UPGRADE": 6,
    "DELAY_EACH_ACCOUNT": 5,
    "MAXIMUM_PRICE": 2,
    "LOOP_COUNTDOWN": 3800
}
  ````

To change a config file in bash use the command `nano config.json`

## 👩‍🔧 How to install in Windows
#Windows
1. Make sure you computer was installed python and git.
   
   python site : [https://python.org](https://python.org)
   
   git site : [https://git-scm.com/](https://git-scm.com/)

2. Clone this repository
   ```shell
   git clone https://github.com/secretniy/hamster2-bot.git
   ```

3. goto hamster2-bot directory
   ```
   cd hamster2-bot
   ```

4. install the require library
   ```
   python -m pip install -r requirements.txt
   ```
OR
   ```
   pip install requests colorama lxml-html-clean requests-html
   ```
5. Edit `data.txt`, input you data token in `data.txt`, find you token in How to find [query_id=... /user=..](https://t.me/secretniy). One line for one data account, if you want add you second account add in new line!
   **Change config.json exactly as described in the linux instructions**

6. execute the main program 
   ```
   python bot.py
   ```


## 🌎 About Proxy

Register on this site to get free proxy : [Here](https://t.me/secretniy)

The `proxies.txt` file should be in the root directory and contain a list of proxies in the format `username:password@host:port`.

Example:

```yaml
socks5://user1:pass1@ip1:port1
user2:pass2@ip2:port2
```

## 🚀 Run File

| Run                  | 
| -------------------------------- |
| `python3 bot.py`          |

## ⚠️ Note

**Termux** : `pip install requests colorama lxml requests-html`

**Termux** `lxml` issue : try `pip install lxml_html_clean` or `pip install lxml[html_clean]` or `pip install python-lxml`

- **Loading setup via CLI argument:** If the `--setup` argument is provided, the script will load the corresponding `.json` file and run the bot directly without displaying the menu.
- **Menu display:** If no `--setup` argument is provided, the script will display the menu as usual.
- **Setup saving:** The option to save setups has been included in the menu as option `8`.




# Русский
# Hamster 2.0  - Автоматический бот

🔗 **Реферальная ссылка**: [Hamster 2.0](https://t.me/hamster_kOmbat_bot/start?startapp=kentId948720889)

## 📢 Группа в Telegram

Присоединяйтесь к нашей группе в Telegram, чтобы быть в курсе событий и получать инструкции по использованию этого инструмента:

- [Секретный канал](https://t.me/secretniy)
- [Секретный чат](https://t.me/+eTYhicQb1KczYTYy)
