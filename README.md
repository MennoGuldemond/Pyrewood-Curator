[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

# Pyrewood Curator

A discord bot that manages wow raid schedules and crafters information, stored in Google sheets.

## Getting started

1. run 'npm install'
1. open https://developers.google.com/sheets/api/quickstart/nodejs and click the button 'Enable the Google Sheets API'
1. Follow the steps to generate a credentials.json file and replace it with the one in the project (or add it to the root if there is none).
1. run 'node generate-token.js' and follow the steps to create a token.json file.
1. Add a config.json file to the root with the following properties:
   - BotToken: "token of the bot"
   - clientId: "bot client id"
   - guildId: "id of your discord server"
   - raidSpreadsheetId: "Google sheets spreadsheet id"
   - hordeCrafterSpreadsheetId: "Google sheets spreadsheet id"
   - allianceCrafterSpreadsheetId: "Google sheets spreadsheet id"
   - searchChannelId: "id of the channel"
   - hordeTradeChannelId: "id of the channel"
   - allianceTradeChannelId: "id of the channel"
1. run 'node bot.js' to start the bot.
