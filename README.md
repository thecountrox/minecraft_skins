# Minecraft skin server
MINECRAFT skin server is where you host a png file of people's skin and use a plugin to change the default skin server to point to this....
Although this is a hacky way this works flawlessly.
To setup your own skin server abd to use it on an offline server you need a forge server and the ssskins plugin.
Also need an unbanned github account.
Step 1 : Make a new repo on github with any name (further refered as <repo_name>).
Step 2 : Upload your friends skin with their minecraft/cracked username as the name of the files (eg. If your name is Aluvinium then your skin file should be Aluvinium.png))
Step 3 : Load the server with the plugin/Lmod and stop it , this generates a config file where you need to enter the skin server url in the following format
         https://raw.githubusercontent.com/<github username>/<repo_name>/main/
Step 4 : Load up the server and see if it works.

For Spigot/Bungee/Sponge servers please see SkinRestorer plugin.
