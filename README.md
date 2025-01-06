# Minecraft 1.8 server example

Original fork by @EcoliEater87.
Guide was not proofread. No beta; we die like Eagler 1.5.2.

Removed the client.
If you're looking for the original repo, google it. It's pretty easy to find because there are a million forks out there.

#### If you want to add Bedrock support, go install GeyserMC and Floodgate.

#### This guide assumes you agree to the End User License Agreement for Minecraft servers. eula=true is set already; but you must agree to it to continue.

SUPPORT WILL NOT BE PROVIDED FOR YOUR SERVER. THIS IS MEANT AS A TEMPORARY SOLUTION TO HOSTING, AS GITHUB WILL MOST LIKELY DOWN YOUR CODESPACE LATER ON.
------------
### Instructions:
#### Open a codespace or clone this repository to a folder if you're self-hosting.
You need to start Bungeecord and the Minecraft server using Java.
To do this, you will need **TWO** terminal tabs: One for the legitimate Minecraft server, and one for the Bungee instance. These processes must be running simultaneously, otherwise your server will not be joinable.
If you're having issues, try using tmux. It usually works.
Once your server is started, forward ports 25565 (Minecraft) and 8081 (TCP).
Your server can be accessed on Java Edition by simply connecting to the forwarded port 25565; if you're trying to join on Eagler then simply prepend "wss://" to the beginning of the forwarded port.
An example would be changing "examplegithubcodespacename-25565.app.github.dev" to "wss://examplegithubcodespacename-25565.app.github.dev"

### Choosing different server eggs

#### If you don't want a normal Vanilla Java server (or you want to add plugins designed for different server eggs), you can procure your own server.jar file. Place it in /server/ after deleting the original. Installing ViaVersion/Backwards/Rewind/RewindLegacySupport is recommended for best compatibility. You can find these on Spigot, which is why Paper is usually the best option. Make sure you install versions designed specifically for your server version, otherwise shit will hit the fan.
----------

#### The only goal of this repo is to give users an example of a Minecraft server, or something similar. I'm not providing support for this repo, and the repository will **not** be updated.

#### The DMCA-infringing client which was present in the original repo has been removed to prevent it from disappearing off the face of the earth. If you're really hard-pressed to play Minecraft without paying, womp womp. Go buy it. At the time of writing it is only around $30.
----------

## VERY IMPORTANT
### Updating EaglerxBungee:

#### If you're adding Eaglercraft support, then you will need to update EaglercraftXBungee, which is in /bungee/plugins/. You can usually find a version of this file in any Eaglercraft client, in the Multiplayer menu in the top-right as of u40.
----------

Repository modified by xthecube.