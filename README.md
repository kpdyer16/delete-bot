# delete-bot
Discord automatic message cleanup bot using discord.js

### How to get it set up
There are a few necessary steps to make:
Full instructions on setting up a new bot and creating the development environment are on the [discord.js guide](https://discordjs.guide/preparations/), which this guide is based on.


1. Create a new bot in the [Discord Developer Portal](https://discord.com/developers/applications). [[Instructions]](https://discordjs.guide/preparations/setting-up-a-bot-application.html#creating-your-bot)
2. In the root directory of the delete-bot source, create a file named config.json. You will store the following:
   1. The clientId (called the Application ID on the Discord Developer Portal)
   2. The token, found on the bot page in the Discord Developer Portal
   3. The guildID of the server you will be testing your bot on.
3. [Add your bot to the server](https://discordjs.guide/preparations/adding-your-bot-to-servers.html#bot-invite-links)
4. Deploy the commands with deploy-commands.js
5. Run your bot with index.js
