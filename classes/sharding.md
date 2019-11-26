---
description: >-
  A powerful discord bot making library to help you make discord bots. Super
  easy, 100 percent discord api coverage, and more! Discord.lib also allows you
  to interact with discord.js.
---

# sharding

## shardManager

This allows you to shard your discord bot.

{% hint style="info" %}
This function requires Premium
{% endhint %}

### Param

| Name | Description | Required |
| :--- | :--- | :--- |
| file | path to your main file | yes |
| amount | shard amount\(Do not put "" around the amount!\) | yes |
| broadcasteval | broad cast eval content | no |

### Example

On a new file, write this file down

```javascript
const dl = require("discord.lib")
dl.shardManager("./path/to/your/file.js", 2, broadcast eval)
```

{% hint style="info" %}
You still put your login function in your main file.
{% endhint %}

