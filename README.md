# XZU.cfg Documentation

An advanced Counter-Strike: Global Offensive config.
Easy to modify to suit your play style. And no, this will not get you VAC banned...

**Features:**
* Viewmodel changer
* Knife Changer (for local sever use)
* Console shortcuts
* KZ style checkpoints (for local sever use)

**coming soon:**
* Quick rebind
* Easy install.bat

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
`a`        | Reload the config / Reset to default | 0
`features` |
`hands`    | Quickly change your viewmodel on the go, instructions are displayed in console once the command is executed | 0
`kz`       | Launch a local server with KZ settings | 0
`vkz`      | Launch a local server with VKZ settings | 0
`cp`       | Load KZ style checkpoints. By default bound as: `p` to set checkpoint and `l` to load checkpoint | 1
`$`        | Give max money | 1
`m9`       | Give yourself an M9 Bayonet | 1
`bay`      | Give yourself a Bayonet | 1
`kara`     | Give yourself a Karambit | 1
`flip`     | Give yourself a Flip Knife | 1
`gut`      | Give yourself a Gut Knife | 1
`hunt`     | Give yourself a Huntsman Knife | 1
`but`      | Give yourself a Butterfly Knife | 1
`falc`     | Give yourself a Falcion Knife | 1
`shad`     | Give yourself Shadow Daggers | 1
`bow`      | Give yourself a Bowie Knife | 1
`stil`     | Give yourself a Stiletto Knife | 1
`tal`      | Give yourself a Talon Knife | 1
`surv`     | Give yourself a Survival Knife | 1
`para`     | Give yourself a Paracord Knife | 1
`skel`     | Give yourself a Skeleton Knife | 1
`nomad`    | Give yourself a Nomad Knife | 1
