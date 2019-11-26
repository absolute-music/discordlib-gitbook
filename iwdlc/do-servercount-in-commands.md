---
description: >-
  A powerful discord bot making library to help you make discord bots. Super
  easy, 100 percent discord api coverage, and more! Discord.lib also allows you
  to interact with discord.js.
---

# Do servercount in commands

You can do servercount in commands by doing something like this:

```javascript
const dl = require("discord.lib")
dl.client.on("message", msg => {
 if(msg.content === "servercount"){
  msg.channel.send(client.guilds.size)
 }
})
```

