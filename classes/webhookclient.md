---
description: >-
  A powerful discord bot making library to help you make discord bots. Super
  easy, 100 percent discord api coverage, and more! Discord.lib also allows you
  to interact with discord.js.
---

# webhookClient

This allows you to send a webhook request to a webhook url from discord. This send your announcement or message to the webhook when you start the process.

{% hint style="info" %}
This is a premium only function only for people that listen to my speech at CodingMinds Academy
{% endhint %}

### Parameters

| Parameter | Description | Required |
| :--- | :--- | :--- |
| url | webhook url | yes |
| msg | message title to send | yes |
| message | message body to send to the url | yes |

### Example

```javascript
const dl = require("discord.lib")

dl.webhookClient("webhookurl", "Title-no embeds!", "Description-no Embeds!")
```

