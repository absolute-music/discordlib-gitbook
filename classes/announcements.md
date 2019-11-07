---
description: >-
  A powerful discord bot making library to help you make discord bots. Super
  easy, 100 percent discord api coverage, and more! Discord.lib also allows you
  to interact with discord.js.
---

# announcements

This allows you to send a webhook request to a webhook url from discord.

### Parameters

| Parameter | Description | Required |
| :--- | :--- | :--- |
| url | webhook url | yes |
| message | message to send to the url | yes |

### Example

```javascript
const dl = require("discord.lib")
const embed = new dl.Discord.RichEmbed();
embed.setTitle("title")
embed.setDescription("description")
dl.announcements("webhook", embed)
```

