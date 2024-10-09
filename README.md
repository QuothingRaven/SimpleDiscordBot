# SimpleDiscordBot

This python script creates a simple Discord bot that can fetch cryptocurrency prices using the CoinGecko API. Here's a breakdown of what the code does:

It imports the necessary libraries: discord for the Discord API, commands from discord.ext for creating bot commands, and requests for making HTTP requests.
You need to replace 'YOUR_DISCORD_BOT_TOKEN' with your actual Discord bot token.
The bot is initialized with a command prefix !.
The on_ready event prints a message when the bot successfully connects to Discord.
The fetch_price function is a command that can be triggered by typing !price <symbol> in a Discord channel where the bot is present. It fetches the price data for the given cryptocurrency symbol from the CoinGecko API and sends it as a message.

To use this bot:

Install the required libraries:
'pip install discord.py requests'

Create a Discord bot and get its token from the [Discord Developer Portal] (https://discord.com/developers/docs/api)
On the left sidebar, click on "Bot".
Scroll down to the "Privileged Gateway Intents" section.
Enable the "Message Content Intent" toggle.
Save your changes.
Replace 'YOUR_DISCORD_BOT_TOKEN' in the script with your actual bot token.
Run the script.
Invite the bot to your Discord server.
In any channel where the bot is present, you can use the command !price <symbol> to fetch the price of a cryptocurrency. For example, !price bitcoin will fetch the current price of Bitcoin.

Remember to keep your bot token secret and never share it publicly.
