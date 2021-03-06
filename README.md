# sc-cmd
Collection of parameters available for latest LIVE (ver. 3.12.0) of Star Citizen.

[Example USER.cfg](https://github.com/emilwojcik93/sc-cmd/blob/main/LOWEST_USER.cfg)

[Raw parameters list and description](https://github.com/emilwojcik93/sc-cmd/blob/main/parameters.txt)

# [Wiki](https://github.com/emilwojcik93/sc-cmd/wiki)
Full list of parameters and their description

## Shortcuts
%CONSOLE% = in game console open with `~` key

%LOG% = `"C:\Program Files\Roberts Space Industries\StarCitizen\LIVE\Game.log"`

%ROOT% = `"C:\Program Files\Roberts Space Industries\StarCitizen\LIVE"`

%USER% = `"C:\Program Files\Roberts Space Industries\StarCitizen\LIVE\USER.cfg"`

## Introduction
I was looking for description of parameters for latest LIVE version of Star Citizen but I don’t find any, so in this repo I would like to collect all available (working) parameters for this game. All informations will be placed in wiki of this repo. Those parameters and their descriptions was capture through %CONSOLE% and %LOG% file.

Every parameters on the [list](https://github.com/emilwojcik93/sc-cmd/wiki/Parameters-list) has assigned default value.

## Usage
Parameter `Con_Restricted = 0` is require to unlock %USER% file in game.

Semicolon `;` is used to comment out something from %USER% file eg. description of parameter or unwanted parameter.

%CONSOLE% support Copy [CTRL+C] and Paste [CRTL+V] keyboard shortcut also like it's mention in Introduction all logs are stored in %LOG% file. Parameters can be modified through %USER% file.

   - `TAB` is autocomplete button which mean that you can automatically fills in partially typed commands

   ![TAB autocompletion](https://github.com/emilwojcik93/sc-cmd/blob/main/TAB_autocompletion.gif)

   - to list all used parameters with set values just type in %CONSOLE% `\` then press `TAB` button

   ![List parameters](https://github.com/emilwojcik93/sc-cmd/blob/main/list_parameters.gif)

   - to get description of parameter in %CONSOLE% write at the end of target command add help sign ` ?` eg. `quit ?`

   ![Help sign](https://github.com/emilwojcik93/sc-cmd/blob/main/help_example.gif)
