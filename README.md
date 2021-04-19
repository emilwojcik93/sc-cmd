# sc-cmd
Collection of parameters available for latest LIVE (ver. 3.12.1) and latest PTU (ver. 3.13.0) of Star Citizen.

[Example USER.cfg](https://github.com/emilwojcik93/sc-cmd/blob/main/LOWEST_USER.cfg)

[Raw parameters list and description](https://github.com/emilwojcik93/sc-cmd/blob/main/parameters.txt)

## Shortcuts
%CONSOLE% = in game console open with `~` key

%LOG% = `"C:\Program Files\Roberts Space Industries\StarCitizen\LIVE\Game.log"`

%ROOT% = `"C:\Program Files\Roberts Space Industries\StarCitizen\LIVE"`

%USER% = `"C:\Program Files\Roberts Space Industries\StarCitizen\LIVE\USER.cfg"`

## Introduction
I was looking for description of parameters for latest LIVE version of Star Citizen but I don’t find any, so in this repo I would like to collect all available (working) parameters for this game. All informations will be placed in wiki of this repo. Those parameters and their descriptions was capture through %CONSOLE% and %LOG% file.

First of all there is [Official RSI Technical Support Page](https://support.robertsspaceindustries.com/hc/en-us/categories/202530337-Technical-Support), I recommended to check exactly those articles:
* [Game Information and Installs](https://support.robertsspaceindustries.com/hc/en-us/sections/360000132827-Game-Information-and-Installs)
* [Graphic Updates and Issues](https://support.robertsspaceindustries.com/hc/en-us/sections/360000502253-Graphic-Updates-and-Issues)

There are few general steps which should you check on your device which are present in this [video tutorial](https://youtu.be/xD9irwzIfso) until 7:52

Additional:
* [CCleaner installation & usage](https://youtu.be/6EyCnqtaNss)
* [Network Reset](https://www.digitalcitizen.life/how-reset-all-your-windows-10-network-adapters-just-6-clicks/)
* [Network Optimization](https://youtu.be/xoOLBAmlVhg)
   * `HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\LanmanServer\Parameters`
      * IRPStackSize = 32
      * SizReqBuf = 17424
   * `HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\Tcpip\Parameters`
      * DefaultTTL = 64
      * TCP1323Opts = 1
      * MaxFreeTcbs = 65536
      * MaxUserPort = 65534
      * GlobalMaxTcpWindowSize = 65535
   * `HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\Tcpip\Parameters\Interfaces\{key-value-of-your-nic}\DhcpIPAddress = <IP-ADDR>`
      * MTU = 1470
      * TcpAckFrequency = 1
      * TcpNoDelay = 1
* [Disable background apps](https://www.windowscentral.com/how-prevent-apps-running-background-windows-10)
* [Disable pagefiles](https://tunecomp.net/win10-page-file-disable/)

Every parameters on the [list](https://github.com/emilwojcik93/sc-cmd/wiki/Parameters-list) has assigned default value.

## Usage
Parameter `Con_Restricted = 0` is require to unlock %USER% file in game.

Semicolon `;` is used to comment out something from %USER% file eg. description of parameter or unused parameter.

%CONSOLE% support Copy [CTRL+C] and Paste [CRTL+V] keyboard shortcut also like it's mention in Introduction all logs are stored in %LOG% file. Parameters can be modified through %USER% file.

   - `TAB` is autocomplete button which mean that you can automatically fills in partially typed commands

   ![TAB autocompletion](https://github.com/emilwojcik93/sc-cmd/blob/main/TAB_autocompletion.gif)

   - to list all used parameters with set values just type in %CONSOLE% `\` then press `TAB` button

   ![List parameters](https://github.com/emilwojcik93/sc-cmd/blob/main/list_parameters.gif)

   - to get description of parameter in %CONSOLE% write at the end of target command add help sign ` ?` eg. `quit ?`

   ![Help sign](https://github.com/emilwojcik93/sc-cmd/blob/main/help_example.gif)
   
## [My PC Config](https://www.passmark.com/baselines/V10/display.php?id=139586361841)

[![PC spec](https://www.passmark.com/baselines/V10/images/139586361841.png)](https://www.passmark.com/baselines/V10/display.php?id=139586361841)

Resolution: 3840x1080 30FPS

<a href="https://imgur.com/gallery/W5FZBXL"><img src="https://i.imgur.com/77I4bl5.jpeg"  width="400" /></a>

[Philips 499P9H 32:9 SuperWide curved LCD display](https://www.usa.philips.com/c-p/499P9H_27/brilliance-329-superwide-curved-lcd-display)

<a href="https://imgur.com/gallery/zkA81Vk"><img src="https://i.imgur.com/DRXwldF.jpg"  width="400" /></a>

Network: Central Europe, 500/30 Mbps

<a href="https://www.speedtest.net/result/11281207985"><img src="https://www.speedtest.net/result/11281207985.png" width="400" /></a>

[Star Citizen Telemetry Dashboard](https://robertsspaceindustries.com/telemetry)

[Dashboard explanation](https://support.robertsspaceindustries.com/hc/en-us/articles/360011767373-Star-Citizen-Telemetry-Dashboard)

<a href="https://imgur.com/gallery/1DGVPpC"><img src="https://i.imgur.com/8whaG2M.png"  width="400" /></a>

[My RSI Account](https://robertsspaceindustries.com/citizens/emilwojcik93)
