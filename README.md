# Cobalt
<a href="https://github.com/AStainlessSteelSink/cobalt/blob/main/LICENSE"> ![License](https://img.shields.io/github/license/AStainlessSteelSink/cobalt) </a>
<a href="https://github.com/discordjs"> ![discord.js](https://img.shields.io/badge/discord.js-v12.3.1-blue.svg?logo=npm) </a>
<a href="https://github.com/AStainlessSteelSink/cobalt/issues"> ![Issues](https://img.shields.io/github/issues/AStainlessSteelSink/cobalt) </a>

A bot used by the JKR Discord Server, based on the [guidebot framework](https://github.com/AnIdiotsGuide/guidebot) and with code snippets referenced from [woomy](https://github.com/woomyware/woomy).

This bot is currently being worked on and is no where near a functional state. It will be added to the main server once it is at a point of being just as functional (or more functional) than the existing Cobalt bot. A rewrite was needed due to how poorly written the first version of Cobalt is (trust me, it's bad, I haven't even shown any of the other JKR developers) and starting from a fairly sturdy framework seems like a helpful nudge to eventually have a much more well-rounded bot.

Also, it's in Discord.js instead of Eris - considering this bot is only intended to be used on one server, the Eris optimizations are not needed and Discord.js has a far more 'detailed' API and online support community.

Feel free to look around. If you find any issues or would like to make improvements to this bot, go ahead! Although this bot isn't *specifically* intended to be used outside of JKR, it's intentionally open source so others can contribute if they'd like.

## Requirements

- `git`
- `node` 12.0.0 or higher
- node-gyp build tools (required for Enmap and many other libraries

## Intents

For info about intents check out the [official Discord.js guide page](https://discordjs.guide/popular-topics/intents.html) and the [official Discord docs page](https://discord.com/developers/docs/topics/gateway#gateway-intents). Certain intents may require extra steps.

## Starting the bot

To start the bot, run `npm start` in your working directory.
