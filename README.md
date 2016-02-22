# Slack Bot with Node.js

This is a mini-project about how to make a web like Slack.
Slackbot is one feature of Slack, it helps team to guide users to create their profiles and explain how slack works. We could build own custom slackbot.

Our NorrisBot will be loaded with guns and jokes about Chuck Norris and it will tell a random one every time that someone says “Chuck Norris” in the chatroom.

Steps:
 Please see in instruction file: Instruction.md
 To run it, provide API key of the bot and doing this below:
 $ set BOT_API_KEY=your_api_key & node bin/bot.js


 issue: show bot's message indefinitely; reason occus in _isFromNorrisBot() that this.user.id and message.user always not equal. Debugging...
