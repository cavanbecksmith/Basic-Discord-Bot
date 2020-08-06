# How to Build Your First Discord Bot with Node.js

Link to article on SitePoint: [https://www.sitepoint.com/discord-bot-node-js/](https://www.sitepoint.com/discord-bot-node-js/)

## Requirements

- [Node.js](http://nodejs.org/)
- [Discord](https://discordapp.com/) account

## Installation Steps (if applicable)

1. Clone repo
2. Run `npm install`
3. Add Discord credentials in a `.env` file
3. Run `node index.js`


## Heroku setup

1. When deploying to heroku we need to make sure that we are passing through the enviroment variable **"token"**
2. Visit [https://discord.com/developers/applications](https://discord.com/developers/applications) create an application
3. Navigate to the bot page and create a new bot. This will generate a token which we will use in our **.env** variables
4. Because we are ignoring the **.env** from git we need to load in the enviroment variable from [https://dashboard.heroku.com/apps/**PROJECT_NAME**/settings](https://dashboard.heroku.com/apps/discord-app-2/settings)  
5. Reveal config vars
6. Add discord **token** there
