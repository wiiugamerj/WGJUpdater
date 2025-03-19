## Just Dance Fusion auto update repository

This repository is used for the auto update system in my fangame; Just Dance Fusion.
There's nothing to do here since this repository is kind of being used as a server.


### How does it work
When the videogame starts, it downloads the latest .txt file available at the moment. This .txt file will have the number of the latest version of the game.
Then, the game will proceed to check if it's a new version, and if it is, it will download the .pck file, that will also be available in the latest release.
After downloading the .pck file, which is like a [dlc for Godot games](https://docs.godotengine.org/es/4.x/tutorials/export/exporting_pcks.html), the game will restart and the changes will be applied.
