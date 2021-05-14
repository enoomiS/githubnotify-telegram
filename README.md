# githubnotfy-telegram
Ever wanted to keep track of your repositories the easiest way possibile? This tool bridges Github's webhook notifications to a telegram bot.

## 💎 Advantages
- Productivity: Add to group to tell samll teams keep track of their work.
- Lightweight: Only a single file, runs on cheap hosting plans
- Privacy: Does not store any data. At all.

## ❔ How to usage?
### You can use my already existing bot
1. Go to [GithubAlertsBot](https://t.me/GithubAlertsBot)
2. Start bot and copy webhook url
3. Add webhook url to your repository
4. Get notified!

### Self hosting
1. Create a bot with [BotFather](https://t.me/BotFather)
2. Upload ```bot.php``` to your webspace
3. Update your bot token on line 2 of  ```bot.php``` 
4. Tell Telegram to use your Bot by calling ```bot.php?webhook&token=<yourbottoken>```
5. Start your Bot and copy webhook url
6. Add webhook url to your repository
7. Get notified!

## 🔘 Supported GitHub Events
Currently supports the following types of [HTTP_X_GITHUB_EVENT](https://docs.github.com/en/free-pro-team@latest/developers/webhooks-and-events/webhook-events-and-payloads)
* ```push```
* ```ping```
* ```issues```
* ```member```
* ```deploy_key```
* ```pull_request```
* ```delete```
* ```create```
* ```public```
* ```release```
* ```star```
* ```fork```
