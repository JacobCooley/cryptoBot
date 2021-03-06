# CryptoBot for Slack
A bot that posts crypto prices/charts to a specified channel in your teams slack.
### Setup
1. Fork cryptoBot from `https://github.com/JacobCooley/cryptoBot`
2. Navigate to the folder and run `npm i`
3. Create a [Slack OAuth Token](https://api.slack.com/custom-integrations/legacy-tokens)
4. Create A [Slackbot](https://ideasbynature.slack.com/apps/A0F7YS25R-bots?next_id=0) in your Teams Slack (only follow step 1)
5. Add 3 Environment Variables
    - slackBotCCOauth - Your Oauth token you created in Step 3
    - slackBotCCToken - Your Slackbot token from step 4
    - slackBotChannel - The name of your channel 
    
    **It is recommended to set different environment variables for the channel name on your local machine and your cloud platform if you want to change the code and test**

### Running

Once you have your repo environment variables on your cloud platform, simply run `npm run start

### Images

You can have the bot post images by adding the `png` format image into `/bot/images` folder.  Once the image is there, add the name of the image (without the file extension) into `/config/constants.js` under the memes array

### Help

Once the app is integrated, go to the channel and type `cc help` to see a list of commands
