---
description: >-
  A powerful discord bot making library to help you make discord bots. Super
  easy, 100 percent discord api coverage, and more! Discord.lib also allows you
  to interact with discord.js.
---

# bot activities

You could use the dl.login way to set regular games, but you cannot do server count there. The client way is the only way to do that. And this tutorial is to show you how.

{% hint style="info" %}
You need to make sure that only the token is in dl.login function.
{% endhint %}

First, we need to interact with discord.lib client by doing:

```javascript
const dl = require("discord.lib")
dl.client.on("ready", () => {
 dl.client.user.setActivity(`I am serving ${client.users.size}`)
})
```



