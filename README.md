# Discord Question Bot
A simple discord bot to manage a channel focused on questions.

**Note** ~ Bot is not currently public and only works on your server

# Current Features 
- Make and modify a question 
- Answer a question 
- Database (mongodb) to keep track of questions and their statuses 

## Future Features 
- Website to view open and closed questions
- Ability to download and backup question db 
- More seamless question management

# Setup 

1. Clone the repo 
```
git clone https://github.com/KaiErikNiermann/QandA-discordBot.git
```

2. Create a `.env` file with the following contents in the bots main directory
```
DB_CONNECT=<your mongodb connect link>
CLIENT_ID=<your bots client ID>
GUILD_ID=<your bots guild ID>
TOKEN=<your bot token>
```
**Note** ~ Read up on how to setup mongodb here https://www.mongodb.com/docs/manual/tutorial/getting-started/

3. Run the bot
```
npm start
```




