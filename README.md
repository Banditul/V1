# PPC Trucking V1

This is a modified version of the popular Trucking Gamemode by [PowerPC603](http://forum.sa-mp.com/member.php?u=109984) for Grand Theft [San Andreas Multiplayer](http://www.sa-mp.com) (SA:MP). You can find the original post on SA:MP forums here: http://forum.sa-mp.com/showthread.php?t=196493.

## Included
*	Gamemode as .pwn file
*	Ready to go server.cfg file (You only have to change few things)
*	All required files for PAWNO so you can modify the Gamemode as you like and re-compile it

## Installation
*	First go to the SA-MP website and [download the newest version](http://sa-mp.com/download.php) (both: server and client)
*	Follow [these instructions](http://forum.sa-mp.com/showthread.php?t=106958) to set up your server
*	Then [get the latest release](https://github.com/PPC-Trucking/V1/releases/latest) of this repository
*	Unpack the archive into the directory where you have set up your server. Follow the structure of the folders. For example: Place files from the "gamemodes" folder **only** into the "gamemodes" folder. __Do not mix it up and pay attention to this part, since it is *very important!*__
*	([__*__](#licensing)) Download the following plugins and place them into the "plugins" folder. If the folder does not exists in the root directory (where your "gamemodes" folder is in), create it. **And only there!**
	*	[sscanf](http://forum.sa-mp.com/showthread.php?t=570927)
	*   [streamer](http://forum.sa-mp.com/showthread.php?t=102865)
*   ([__*__](#licensing)) Get these files as well and put them into the ~/pawno/include folder.
	*   [sscanf2.inc](http://forum.sa-mp.com/showthread.php?t=570927)
	*   [streamer.inc](http://forum.sa-mp.com/showthread.php?t=102865)
	*   [zcmd.inc](http://forum.sa-mp.com/showthread.php?t=91354)
	*   [dutils.inc](http://dracoblue.net/downloads/dutils/)
*	Now open _~/pawno/pawno.exe_ and load the Gamemode to re-compile it
	* If everything worked, you should get a line saying ``Pawn compiler 3.2.3664 		Copyright (c) 1997-2006, ITB CompuPhase``
		* In this case, you can continue with the next point
		* If it did not work for you, please use Google first to solve the problem by yourself
			* If you could solve the problem, continue with the next point
			* If you could __not find__ a solution for your problem, post the output in the [forum post](http://forum.sa-mp.com/showthread.php?t=196493)
*	If everything worked for you, the last thing you have to do is this:
	*	As a Windows user, you have only to open the server.cfg file and to set your desired rcon_password
	*	If you are running your server more professional on a Linux machine, change ``plugins sscanf streamer`` to ``plugins sscanf.so streamer.so`` and make sure that you have placed these plugins into the folder. You also have to set your desired rcon_password.

__Hint:__ You can use the [Server.cfg Generator](http://www.gta-freak.cloudns.org/server_cfg) by [malaka](http://forum.sa-mp.com/member.php?u=112277) to manage your Server.cfg file online!

## Credits
*	[PowerPC603](http://forum.sa-mp.com/member.php?u=109984) - awesome Gamemode
*	[Y_Less](http://forum.sa-mp.com/member.php?u=29176) - very handy way to handle parameters (sscanf)
	*	Emmet_ - Thank you for re-posting the great work of Y_Less
*	[Incognito](http://forum.sa-mp.com/member.php?u=925) - abbility to use more objects than usually possible (streamer)
*	Zeex - quick and nice solution to create commands (zcmd)
*	[DracoBlue](http://forum.sa-mp.com/member.php?u=389) - easy way saving and loading information (dutils)
	
### Thanks for reading!
*	By the way, if you already have experience with [Notepad++](http://notepad-plus-plus.org), have an eye at Slice's tutorial [how to use Notepad++ with PAWN](http://forum.sa-mp.com/showthread.php?t=174046).

### Licensing
__*__ Due to copyright terms it is not allowed to ship those files with this Gamemode. So you have to download and put them into the right folder yourself.

**If you have any questions or if you ran into problems, feel free to [open an issue](https://github.com/PPC-Trucking/V1/issues) and to ask your question here. You can also [post](http://forum.sa-mp.com/showthread.php?t=196493) in the SA:MP forum.**
