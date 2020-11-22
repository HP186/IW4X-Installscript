# IW4X-Linux-Server-Installscript

This is a reworked script originally provided by [@linkuso](https://github.com/linkuso/iw4x-linux-server-installscript). 
This script contains multiple fixes and should give you an immaculate experience.

Run install.sh as root and follow the instructions. 
Afterwards you'll have to upload your Modern Warfare 2 basegame to the newly created "MW2" folder.

If you want to save some time with the configuration of the freshly installed server, you can download prebuilt dedicated server configs [here](https://cdn.discordapp.com/attachments/269972437393735682/656242057114943489/IW4x_Prebuild_dedi_configs.zip).

Just be sure to include

**set sv_lanonly "1"**

in your server.cfg, or you'll have to deal with crashes. 
This variable is broken, it won't affect the public visibility of your server, players will still see the server in the serverbrowser.
