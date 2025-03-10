## Overview
Mail Telegram plugin allows to receive site mail to your telegram account via bot. You can log all email sent on the website or configure this plugin to receive only notification emails for particular administrator(s). See the documentation for configuration details.

## Installation

### Artisan

Using the Laravel’s CLI is the fastest way to get started. Just run the following commands in a project’s root directory:

```bash
php artisan plugin:install vdomah.mailtemplate
```

## Documentation

Full documentation about telegram bots, you can see here: https://core.telegram.org/bots/api

### Get bot token
Create bot by @BotFather. Bot token will look like 123456:ABC-DEF1234ghIkl-zyx57W2v1u123ew11

### Get user chat id
For getting user chat id - write any message to bot or just click Start, and open the following url in your browser:

https://api.telegram.org/bot{{token}}/getUpdates

Don't forget to replace {{token}} with your bot token.

Enter this token and chat id into plugin settings. That is all, have a nice experience with this plugin!

## License

© 2019, [Art Gek](https://github.com/vdomah) under [GNU GPL v3](https://opensource.org/licenses/GPL-3.0).

Developed by [Art Gek](https://github.com/vdomah).

Inspired by [Exception Report to Telegram](https://octobercms.com/plugin/popcornphp-exceptionreport) by [Alexander Shapoval](https://octobercms.com/author/PopcornPHP)