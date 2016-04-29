# Auto-Build Minecraft Server

This docker image provides a quick launch of craftbukkit server that the version is 1.7.9, it's original and with no mods.

To simply run this server, type:

    $ docker pull tonypai/docker-craftbukkit
    $ docker run -d -p 25565:25565 --name cb tonypai/docker-craftbukkit
