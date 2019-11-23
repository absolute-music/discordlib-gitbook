---
description: >-
  A powerful discord bot making library to help you make discord bots. Super
  easy, 100 percent discord api coverage, and more! Discord.lib also allows you
  to interact with discord.js.
---

# MusicClient Guide

## Make music system works

Importing the packages needed using the following code

```javascript
const { musicClient } = require("discord.lib")
require("node-opus or opusscript")
```

{% hint style="info" %}
 You should probably install ffmpeg since ffmpeg-binaries from npm might cause error
{% endhint %}

## Install ffmpeg

### Windows

Download at [https://ffmpeg.zeranoe.com/builds/](https://ffmpeg.zeranoe.com/builds/)

### Mac

Download at [https://evermeet.cx/ffmpeg/](https://evermeet.cx/ffmpeg/)

### Linux Command Line

```javascript
1. sudo apt update
2. sudo apt install ffmpeg
3. ffmpeg -version
```

## Actual code

```javascript
const { musicClient, login } = require("discord.lib")
musicClient("your prefix", "Youtube api key")
login("token", "game")
```

### Install opusscript or node-opus for it to work

```javascript
npm i node-opus/opusscript
```

## Using discord.lib to play music

### Let's import packages first

```javascript
const { musicClient, login } = require("discord.lib")
require("node-opus or opusscript")
```

### Main code

The main code is one of the function in discord.lib.

```javascript
musicClient("your prefix", "yt-api-key")
login("token")
```

### Resulting code

```javascript
const { musicClient, login } = require("discord.lib")
require("node-opus or opusscript")
musicClient("your prefix", "yt-api-key")
login("token")
```

And you are all set!



