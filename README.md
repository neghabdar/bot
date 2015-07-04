# bot
ربات مشکل گشا

```php
require('TelegramBot.php');

$TokenAPI = '116156032:AAELzTNaEvt6q1Kno9SyLn2O_tmiYzhaoGI';
$BotNow = new TelegramBot($TokenAPI);

// Send message to user.
$ChatId = "26038459"; // id Chat
$TextMsg = "Hello world";
$BotNow ->SendMessage($ChatId,$TextMsg); // Success!
```

## Class Function List

* `SendApiBot()`
* `SendQueries()`
* `Status()`
* `GetUpdates()`
* `SendMessage()`
* `GetUserProfilePhoto()`
