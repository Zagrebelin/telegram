# telegram

a minimal [telegram api](https://core.telegram.org/bots/api) wrapper

## installation
```
pip install git+https://github.com/banteg/telegram.git
```

## usage
```python
from telegram import TelegramApi

t = TelegramApi('your bot token')
t.send_message(chat_id=123, text='hi')  # note snake_case
```