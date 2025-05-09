# kbot tg bot proj
# Telegram Bot in Go (Cobra + Telebot)

Telegram bot built using Go, the telebot library, and the Cobra CLI framework.

## 🔗 Bot Link

👉 [t.me/yuriyyuriev_bot](https://t.me/yuriyyuriev_bot)

---

## ⚙️ Installation

> ⚠️ This bot uses an environment variable `TELE_TOKEN` to access the Telegram API.

1. ** Clone repository **

```bash
git clone https://github.com/yuriev-yuriy/kbot.git
cd kbot

2. ** Install dependencies **

go get github.com/spf13/cobra
go get gopkg.in/telebot.v3

3. ** Build the project **

go build -o kbot

4. ** Set the bot token (securely) **

read -s TELE_TOKEN
export TELE_TOKEN=$TELE_TOKEN

5. ** Run the bot **

./kbot start

Once the bot is running, simply send a message to it on Telegram
/start
and
/start hello