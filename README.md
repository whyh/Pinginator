# Pinginator
The bot is your nightmare. It is your neighbor. It pings all collected users from group.

The main problem is that telegram bot API doesn't provide opportunity to get users from group.
So bot collects them from wrote messages, joined and left user.

## Requirements
```
mongodb
pymongo
PyTelegramBotApi

You have to set environment variables BOT_TOKEN, BOT_LOGIN, BOT_NAME.
```

## Commands

```
/help, /start - print usage

/ping - pings all collected users

@pinginator - responses to you
```
## Have fun
