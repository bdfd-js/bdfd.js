## Table of contents

- [About](#about)
- [Installation](#installation)
- [Example codes](#examples)

## About

bdfd.js is a codinng for discord bots like discord.js

## Installation

`npm i bdfd.js --save`

## Example codes

```
const bdfd = require('bdfd.js');
const bot = new bdfd.Bot();
const set = new bdfd.Settings();

bot.set({
  prefix: '!',
  token: 'token'
});

bot.Commands => {
  "command": "help"
  "description": "see the help of the bot"
  "reply" ["setEmbedResponse("Title", "description", "footer") setEmbedIMage(imageURL)
```image
