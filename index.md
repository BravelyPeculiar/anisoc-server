Welcome to the Anisoc Minecraft Server, a server for the UoB Anime & Manga Society! This page will tell you how to get set up and connected.

To start with, make sure you have a valid Minecraft Java Edition account, and have the Minecraft launcher installed. Then, follow these instructions to install the mod loader and the modpack that the server requires.

## Installing the Fabric mod loader

1. Download the latest [Fabric installer](https://fabricmc.net/use/installer/)
2. Run the downloaded installer, using these settings:
    - Use the `Client` tab
    - Minecraft Version: `1.18.1`
    - Loader Version: `0.12.12`
    - Leave the default install location unchanged
    - Untick the `Create profile` option

## Installing the Anisoc modpack

1. Download [anisoc_modpack.zip](https://github.com/BravelyPeculiar/anisoc-server/releases), and extract it to a safe location on your computer
2. Open the Minecraft launcher, and select the **Installations** tab
3. Press **New installation**, and enter these settings:
    - Name: `Anisoc`
    - Version: `release fabric-loader-0.12.12-1.18.1`
    - Game Directory: Enter the path to the `anisoc_profile` folder that you extracted from the downloaded zip file
4. Press **Create**!

## Connecting to the server

1. Go to the main **Play** tab of the Minecraft launcher
2. To the left of the big green Play button, click on the dropdown menu, and select `Anisoc`
3. Press **Play**! The Anisoc server should already be on the game's multiplayer server list

To play unmodded Minecraft again later, go back to the dropdown menu in the launcher and select the Minecraft version number you want to play.

## Optional bonus! Setting up improved spatial audio (for Windows)

This setup will make Minecraft's audio more realistic if you're wearing headphones; the position that sounds are coming from will be more clearly audible.

1. Download and run the [OpenAL 1.1 Windows Installer](https://www.openal.org/downloads/)
2. Go to the folder `%AppData%` (by typing it into the start menu search)
3. In that folder, open the file `alsoft.ini` in a text editor (if the file is not there, create it)
4. Type `hrtf = true` into the file, save and close it

You're finished! Sound positioning in Minecraft should now be more realistic.

Depending on the specific shape of your head (yes really!) this effect may not work as well on some people, and in some cases may be distracting or cause mild headaches. If you want to disable the effect later, simply go back to the `alsoft.ini` file and edit it to say ``hrtf = false`.
