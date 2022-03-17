# Afk-Bot
> Afk Bot will make your Aternos Server run 24 Hours
* > Part 1 : Buat Bot
```
// Coding Bot

const mineflayer = require('mineflayer')

const Bot = mineflayer.createBot({
  host: "Aternos IP",
  port: Server Port,
  username: "Bot Name"
})
```
* > Code to make your Project to always Running on [Repl.it](https://replit.com) after the Website Closed and Deploy them on [UptimeRobot](https://uptimerobot.com)
```
// 24 Hours Running Code
const express = require('express')
const app = express()

app.get('/', function (req, res) {
  res.send('Bot Joined')
})
app.listen(3000)
```

* > Bot Chat/ Set TimeOut (Make sure the bot have Operator Permission)
```
// Chat Code & Set Timeout
Bot.on('spawn', () => {
  Bot.chat("Hello") // Normal Chat
  Bot.chat("/kill @s") // Kill to set TimeOut
  Bot.chat("/setidletimeout 30") // TimeOut Code
})
```
Creator - [NiXE xD](https://www.youtube.com/channel/UCK9F2ptByYjY4UOqMn4UXNQ?sub_confirmation=1)
