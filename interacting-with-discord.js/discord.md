---
description: >-
  A powerful discord bot making library to help you make discord bots. Super
  easy, 100 percent discord api coverage, and more! Discord.lib also allows you
  to interact with discord.js.
---

# Discord

You could use this to do things like creating a rich embed. 

## Examples

### Example of making a rich embed

{% hint style="info" %}
You could view all of the embed variable[ here](https://discord.js.org/#/docs/main/stable/class/RichEmbed?scrollTo=addBlankField)\(It is the same as the library [discord.js](https://npmjs.com/package/discord.js)\)
{% endhint %}

```
const dl = require("discord.lib")
const embed = new dl.Discord.RichEmbed();
embed.setTitle("help")
embed.addField("A_ban", "Ban a member")
```

### Example of sending webhook message

```
const dl = require("discord.lib")
// Create a new webhook
const hook = new dl.Discord.WebhookClient('webhook id', 'webhook token');

// Send a message using the webhook
hook.send('I am now alive!');
```

