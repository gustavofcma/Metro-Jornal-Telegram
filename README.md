# Metro Jornal Telegram Bot

A bot that send to you the current edition of [Metro newspaper](https://www.metrojornal.com.br/) on Telegram

# Setup

After cloning/downloading the repository, install required dependencies:

`pip install -r requirements.txt`

Create a file `bot.conf` containg:

```
[MetroJornal]
TOKEN =
CITY =
DEST =
```

`TOKEN` - Bot token generated by [BotFather](telegram.me/botfather)

`CITY` - City to be send as message with the file

`DEST` - Here is the ID from user that will receive the file. To find yours, the easier way is to send a message to [userinfobot](telegram.me/userinfobot). To send the file to public groups/channels, you can use the `@username` instead ID

# Run

Today (October, 19. 2017), the journal is available on the following locals:

| Local              | Argument        |
|--------------------|-----------------|
| São Paulo          | `MetroSaoPaulo` |
| Rio de Janeiro     | `MetroSaoPaulo` |
| Belo Horizonte     | `MetroSaoPaulo` |
| Porto Alegre       | `MetroSaoPaulo` |
| Brasília           | `MetroSaoPaulo` |
| Curitiba           | `MetroSaoPaulo` |
| Campinas           | `MetroSaoPaulo` |
| ABC                | `MetroSaoPaulo` |
| Maringá            | `MetroSaoPaulo` |
| Espírito Santo     | `MetroSaoPaulo` |

Choose one local and use the item from Argument column in the following command on the console and see the bot working:

`python routine.py <argument>`