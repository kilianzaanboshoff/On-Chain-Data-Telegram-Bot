# On-Chain-Data-Telegram-Bot
A simple app that sends Telegram notifications when an on-chain event occurs. Optimising this to get updates for staking activity.

# How does it work?
This code is a Telegram bot for Ethereum token transfer notifications. The bot is built using the Flask and Telegram Bot API libraries, and it uses the Alchemy API to receive notifications of token transfers.

The bot uses a Flask endpoint to receive the token transfer notifications from Alchemy, and it sends a message to the user via Telegram with the details of the transfer. The user starts the bot by sending a "/start" command in Telegram, which sets their chat ID as the target for the transfer notifications.

To use the bot, you will need to set the TELEGRAM_API_TOKEN and ALCHEMY_API_KEY environment variables with your Telegram bot API token and Alchemy API key, respectively. 
