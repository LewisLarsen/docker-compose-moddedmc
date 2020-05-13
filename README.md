# docker-compose-moddedmc
A simple docker-compose repository to get a Modded (Forge) Minecraft Server up and running effortlessly. 

## Usage

To get started, make sure you have [Docker installed](https://docs.docker.com/docker-for-mac/install/) on your system, and then clone this repository.

## How to use this
A short tutorial on how to use this docker-compose file.

Clone the repository into a folder
```
git clone https://github.com/LewisLarsen/docker-compose-moddedmc.git .
```
Once that has done, the only thing left is to build the container so the server will start.
```
docker-compose up --d --build
```

Open Minecraft and connect,  it should work! 

**Please**  note that it may take a while, since it has to download and install Forge then the server files. This depends on the quality of your internet connection and may vary for different people.

To get the modpack server URL, visit https://curseforge.com and download the pack you wish, CTRL+J (Google Chrome) and copy the url shown. It will be something such as `https://media.forgecdn.net/files/2929/251/SERVERZIP.zip` Copying and pasting the server pack download URL from curseforge will ****NOT** work. 

## Credits & Additional Information
Thank you to [iztg](https://github.com/itzg/docker-minecraft-server) for his image and helpful documentation. For additional reference and advice please see his repository. This is the bare minimum in order to get a Spigot Server working. 