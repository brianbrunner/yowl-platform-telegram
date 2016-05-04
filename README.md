# yowl-platform-facebook

```bash
$ npm install yowl-platform-telegram --save
```

https://core.telegram.org/bots

```js
var telegram = require('yowl-platform-telegram');

bot.platform(facebook({ token: '<token>',
                        host: 'example.com' }));
```

Options:
  `token` (Required) - The token provided to you by telegram
  `host` (Required) - The host for the webhook. Must be secured (i.e. accessible via HTTPS).
  `path` (Optional) - The path for the webook. If not provided, your webhook path will be '/<token>' as suggested by the official telegram docs (https://core.telegram.org/bots/api#setwebhook)
