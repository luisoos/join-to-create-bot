# Join to create Discord Bot
Simple JavaScript Discord Bot, that automatically creates a Voice Channel when a user joins the "Create Voice Channel"-Channel.
Source code is simple, written in Discord.js and easy-to-use.

### Requirements
 - [Discord.js](https://discord.js.org/#/)

### Setup

Go setup your bot at https://discord.com/developers/applications!
    (If you don't understand how to create a bot: search on YouTube!)

##### Method 1: (fastest)
    
    git clone https://github.com/luisoos/join-to-create-bot
    cd join-to-create-bot
    npm install
    

##### Method 2: 
    Copy paste all files from the 'src'-folder.


### Configuration

Change the strings in the `config.json` file:
 - `TOKEN`: Your Discord-Bot Token (NEVER PUBLISH YOUR TOKEN!)
 - `JOINTOCREATECHANNEL`: ID of the Voice-Channel you want this to be set up


### Start the Bot
Type `node index.js` to start the bot.
