<div align="center">
  <br />
  <p>
    <a href="https://discord.js.org"><img src="https://discord.js.org/static/logo.svg" width="546" alt="discord.js" /></a>
  </p>
</div>

## About

<strong>Welcome to `ssj.js-v13@v1.0`, based on `discord.js@13.17`</strong>

- ssj.js-v13 is a [Node.js](https://nodejs.org) module that allows user accounts to interact with the Discord API v9.


### <strong>I don't take any responsibility for blocked Discord accounts that used this module.</strong>
### <strong>Using this on a user account is prohibited by the [Discord TOS](https://discord.com/terms) and can lead to the account block.</strong>

### <strong>[BASED DOCUMENTATION WEBSITE](https://discordjs-self-v13.netlify.app/)</strong>

## Installation

**Node.js 16.6.0 or newer is required**

> Recommended Node.js version: [18+](https://nodejs.org/en/blog/release/v18.17.0) (LTS)

```sh-session
npm i ssj.js-v13@latest
```

## Example

```js
const { Client } = require('ssj-v13.js'),
client = new Client()

client.on('ready', async () => {
  console.log(`${client.user.tag} is ready!`);
})

client.login("token");
```

## Get Token ?

<strong>Run code (Discord Console - [Ctrl + Shift + I])</strong>

```js
window.webpackChunkdiscord_app.push([
  [Math.random()],
  {},
  req => {
    if (!req.c) return;
    for (const m of Object.keys(req.c)
      .map(x => req.c[x].exports)
      .filter(x => x)) {
      if (m.default && m.default.getToken !== undefined) {
        return copy(m.default.getToken());
      }
      if (m.getToken !== undefined) {
        return copy(m.getToken());
      }
    }
  },
]);
console.log('%cWorked!', 'font-size: 50px');
console.log(`%cYou now have your token in the clipboard!`, 'font-size: 16px');
```

## Credits
- [Discord.js](https://github.com/discordjs/discord.js)
- [Base](https://github.com/aiko-chan-ai/discord.js-selfbot-v13)

## Other Projects

- [Speed](https://github.com/Senju-sh/Speed-Selfbot)