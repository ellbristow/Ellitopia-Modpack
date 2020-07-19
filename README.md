# Ellitopia Modpack
The Ellitopia Minecraft Modpack is a collection of mods and relevant config files used by MultiMC to create the Ellitopia minecraft server.
This modpack works perfectly in single player mode, but is best enjoyed on the Ellitopia Server.
Anyone who wants to play on the server will have to have the latest version of the mods to sign in.

## Prerequisites
This modpack requires:
* [Java 8](https://www.java.com/en/download/manual.jsp)
* [MultiMC](https://multimc.org/#Download)

## Installation
1. Download the [latest release](https://github.com/ellbristow/Ellitopia-Modpack/releases/latest)
1. In MultiMC, Select "Add Instance"
1. Choose "Import form Zip"
1. Locate the downloaded modpack and let MultiMC import it
1. Launch the instance
1. Hit Multiplayer
1. Click "Add Server"
1. Enter **mc.ellitopia.com** as the "Server Address" and name the server whatever you like
1. Enjoy!

[You can see server status here](https://status.ellitopia.com)

If you spot an issue, please check the [Issues](https://github.com/ellbristow/Ellitopia-Modpack/issues) to see if it has already been reported, and if not, create a new report providing as much detail as possible, including the release version, and error or crash logs etc.

Please check, and feel free to contribute to the [Wiki](https://github.com/ellbristow/Ellitopia-Modpack/wiki) (WIP) for details of what each mod does and how it is used.


## Important 
If you wan't to use the included discord rich presence. Thn you need to:
1. navigate into the config folder (you can find it in .minecraft)
1. find the config called "craftpresence.properties" and open it
1. find line 32 where it says "Client_ID="
1. open discord and right click on you name
1. you should be able to "copy ID"
1. then paste you ID into the "craftpresence.properties" file at line 32 after the = sign
