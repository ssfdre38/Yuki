This bot has been contributed to by GameW1izard and his HatBot as well as OpenAI.

The bot is under constant development to add new functionality over time. Currently, it can chat with Discord users and generate images using GPT-4 Turbo and DALL-E 3 HD.

To use the bot, create a file called `.env` and inside place the following:
```
AI_TOKEN=<your openai token here>
BOT_TOKEN=<your discord bot token here>
DB_TYPE=mysql | postgres | sqlite | mariadb | mssql | db2 | snowflake | oracle
DB_HOST=localhost or URL/IP:Port of db (unused for sqlite)
DB_NAME=sqlite db filename | db name for all other types
DB_USERNAME=username to access db (unused for sqlite)
DB_PASSWORD=password to access db (unused for sqlite)
```
Then run `npm install` to install the dependencies and `npm start` to start the bot.


Just remember to replace <your openai token here> and <your discord bot token here> with your actual tokens.
