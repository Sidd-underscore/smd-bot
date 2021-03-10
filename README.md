# SMD's Bot

A (hopefully) feature-rich Discord bot for ![SMD's server](https://discord.gg/6D7YCrrHUz).


## Self-Hosting

This self-hosting guide requires you to have some basic knowledge about running windows PowerShell, JavaScript, Node.js and Discord bots. We do not provide any support for self-hosting, unless you DM `SMD || BLM!!! ||#4553` on Discord.

### Prerequisites

In order to run ModMail, you will need to install the following software. Please also note that SMD Bot can only be hosted on Windows.

- [Node.js](https://nodejs.org/en/)
- [Windows PowerShell (comes with a windows computer)](https://docs.microsoft.com/en-us/windows-server/administration/windows-commands/powershell)
- [Preferably Visual Studio Code, but you can use anything else (for coding the bot)](https://code.visualstudio.com/)

### Getting the Sources

Please download this code (if you have not already) by clicking that green button that says `[down arrow] Code` Next, install Node.js and open the folder in which you have downloaded this code. Click file (in file explorer), Open Windows PowerShell, Open Windows PowerShell. Run the code `node -v` and you should see something like `v12`. After that, run the code `npm install discord.js`. This installs the discord.js language which we use in this bot.

### Configuration

Configuration is done through a `config.py` file. You should make a copy of `config.example.py` and rename it to `config.py`. All fields must be filled in, except for bot list tokens and the Sentry URL only if you have `testing` set to `False`.

### Installing Modules

ModMail utilises [discord.py](https://github.com/Rapptz/discord.py) and several other modules to function properly. The list of modules can be found in `requirements.txt` and you can install them with the following command.

```sh
pip3 install -r requirements.txt
```

### Running the Bot

Congratulations! You have set up everything and you can finally have the bot up and running. Use the following command to run.

```sh
python3 launcher.py
```

## Code of Conduct

This project is governed by [Contributor Covenant Code of Conduct](https://github.com/chamburr/modmail/blob/master/CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code.

## License

This project is licensed under [GNU Affero General Public License v3.0](https://github.com/chamburr/modmail/blob/master/LICENSE).
