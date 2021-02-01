# Auto-Temp-Report

**CAUTION: This repo is only for learning purposes, DO NOT use this repo for real health status reports. The author(s) will not be responsible if anything bad happens.**

**CAUTION: You need to report manually on the website at least once before using this tool.**

**WARNING: Make sure you can access Telegram API if you're using this tool on your local network.**

Extra needs:
1. Contact [BotFather](https://t.me/BotFather) to create an bot, get your bot token.
2. Reply to your bot with any message, then access this link(change ***TOKEN*** to your own):

https://api.telegram.org/bot***TOKEN***/getUpdates

From here you'll see your chat_id. You'll need it later.

### Requirement: Python 3.6+ and some extra packages:

Arch Linux:
```
sudo pacman -S python-beautifulsoup4 python-requests
yay -S python-pytelegrambotapi #From AUR, yay/other AUR tools needed
```

Other system with Python pip installed:
```
pip install requests
pip install beautifulsoup4
pip install lxml
pip install pyTelegramBotAPI
```

One line:
```
python actions.py $ACCOUNT $PASSWORD $TGBOT_TOKEN $CHAT_ID
```

Credits: [zsqw123](https://github.com/zsqw123/Automatic-Health-Card), [JLUZHAnalytica(Original Author)](https://github.com/JLUZHAnalytica/Automatic-Health-Card)

Special Thanks: [F-T-Otaku](https://github.com/F-T-Otaku/Auto-Health-Report)
