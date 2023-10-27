# devroom-trail
## Bot futters :
    1)  Send welcome message when a new member join the server
    2)  Message level system and count memebrs messages
    3)  rock-paper-scissors game
    4)  Sends a message to a specified channel at a specified time every day
    5)  Displays information about a specified hypixel user

       
- Bot commands :
    1. hypixel : Displays information about a specified hypixel user
    2. leaderboard : to Display leaderboard for members' messages
    3. roshambo : To play rock-paper-scissors game
 
       
## How to setup the bot.
- install npm packages  :
  -  You have to install NodeJs first
  -  open terminal in bot dir. and wirght `npm i`
- setup config.ts in src/config.ts :
  - token : you have to put your discord bot token
  - prefix : wright your bot prefix
  - Mongoose : your mongoos data url
  - debugMode : leave it true as defulte
  - joinChannelID : specify welcome channel id
  - hypixelApiKey : hypixel Api Key to get players data
  - reminderTime : specify time in 24h formate to send daily message
  - dailyReminder.guild : specify the guild for the daily reminder
  - dailyReminder.channel : specify the channel for the daily reminder
 
  ##  - Run the bot :
   - open terminal in bot dir. and wirght `npm run start `
