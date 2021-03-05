<img src="resources/icon.png" align="right" height="84" />

# Cobalt ![License](https://img.shields.io/github/license/AStainlessSteelSink/cobalt) ![discord.js](https://img.shields.io/badge/discord.js-v12.3.1-blue.svg?logo=npm) ![Issues](https://img.shields.io/github/issues/AStainlessSteelSink/cobalt)

A bot used by the JKR Discord Server, based on the [guidebot framework](https://github.com/AnIdiotsGuide/guidebot) and with code snippets referenced from [woomy](https://github.com/woomyware/woomy).

This bot is currently being worked on and functionality from the old bot is being cleaned up/rewritten and ported over. A rewrite was needed due to how poorly written the first version of Cobalt is (trust me, it's bad, I haven't even shown any of the other JKR developers) and starting from a fairly sturdy framework seems like a helpful nudge to eventually have a much more well-rounded bot.

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
