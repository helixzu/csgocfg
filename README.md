# XZU.cfg Documentation

An advanced Counter-Strike: Global Offensive config.
Easy to modify to suit your play style. And no, this will not get you VAC banned...

**Features:**
* Viewmodel changer
* Knife Changer (for local sever use)
* Console shortcuts

**coming soon:**
* Quick rebind
* Easy install "Installing has never been easier, simply run the "winInstall.bat" and it will place all the neccercery files in the correct place.
Once in CS:GO, in console, type `exec /xzu/xzu.cfg`"

# Installation
1. Download the files
2. Extract the "xzu" folder to `C:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive\csgo\cfg`
3. Either set `exec xzu/xzu.cfg` in your CS:GOs launch options or `exec xzu/xzu.cfg` in console once CS:GO is loaded.
4. Profit?!?!?

# Usage

Most of the config is controlled via the console.
If the "sv_cheats" value is set to "1" it means the command will only work on servers that have it enabled, otherwise you may use the command anywhere. Alot of the commands will automatically set the value to "1" if you have permission to do so (Server admin / Host)

command | explanation | sv_cheats
--------|-------------|------------
`hands` | Quickly change your viewmodel on the go, instructions are displayed in console once the command is executed | 0
`a`     | Reload the config / Reset to default | 0
`kz`    | Launch a local server with KZ settings | 0
`m9`    | Give yourself an M9 Bayonet | 1
