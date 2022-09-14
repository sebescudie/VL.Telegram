**Important: Remove the netcore folder from the TelegramBot nuget**
**Many of the initial examples are broken**

Known issue: TelegramBot ReceiveAsync does not stop when Cancellation Token is triggered

# VL.Telegram

A VL wrapper of the [Telegram.Bot](https://github.com/TelegramBots/Telegram.Bot) lib.

## What's inside

This one is not as complete as motzi's [beta plugin](https://github.com/mhusinsky/vvvv-Telegram). It was made with installation monitoring scenarios in mind. Here you can :

- Send and receive text messages
- Send photos (from file or `SKImage`)
- Send Inline and Reply keyboards
- React to InlineKeyboards queries

## Usage

- You'll first need to generate a token by talking to @BotFather on Telegram. Simply follow his instructions.
- When you have your key ready, you can jump to the help patches in the node browser.

## Credits

- Big thanks to motzi for his [beta plugin](https://github.com/mhusinsky/vvvv-Telegram) that was quite helpful to get the inner workings of the lib