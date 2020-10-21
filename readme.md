# Botkit Starter Kit

This is a Botkit starter kit for slack, created with the [Yeoman generator](https://github.com/howdyai/botkit/tree/master/packages/generator-botkit#readme).

To complete the configuration of this bot, make sure to update the included `.env` file with your platform tokens and credentials.

[Botkit Docs](https://botkit.ai/docs/v4)

This bot is powered by [a folder full of modules](https://botkit.ai/docs/v4/core.html#organize-your-bot-code). 
Edit the samples, and add your own in the [features/](features/) folder.

Help with running locally:
https://medium.com/greenroom/the-slack-bot-tutorial-i-wish-existed-d53133f03b13

---

NOTE** Does NOT use RTM, uses EVENTS API instead

---

## Local

Need to install `ngrok` : [https://dashboard.ngrok.com/get-started/setup](https://dashboard.ngrok.com/get-started/setup)

`node bot.js`

## Documentation
- [conversations.list](https://api.slack.com/methods/conversations.list) - Slack Events API
- [OAuth Tokens & Redirct URLs](https://api.slack.com/apps/ASAA2MGRZ/oauth?success=1)
