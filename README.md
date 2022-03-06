# Afk-Bot
> Afk Bot akan membuatkan Aternos Server anda always Online/24 Jam
* > Part 1 : Buat Bot
```
// Coding Bot

const mineflayer = require('mineflayer')

const Bot = mineflayer.createBot({
  host: "Aternos ip",
  port: Server Port,
  username: "Nama Bot"
})
```
* > Code untuk Replit always Run walaupun [Repl.it](https://replit.com) ditutup

```
// 24 Jam Code
const express = require('express')
const app = express()

app.get('/', function (req, res) {
  res.send('Bot Joined')
})
app.listen(3000)
```

* > Bot Chat/ Set TimeOut (Pastikan Bot ada Operator Permission)
```
// Chat Code & Set Timeout
Bot.on('spawn', () => {
  Bot.chat("Hello") // Normal Chat
  Bot.chat("/kill @s") // Kill untuk set TimeOut
  Bot.chat("/setidletimeout 30") // TimeOut Code
})
```
Creator - [NiXE xD](https://www.youtube.com/channel/UCK9F2ptByYjY4UOqMn4UXNQ?sub_confirmation=1)
