## wiiugamerj's game updater system

This repository is used for the auto update system in my different Godot games and apps.
There's nothing to do here since this repository is kind of being used as a server.

### How does it work
When the videogame/app starts, it downloads the latest .txt file available at the moment. This .txt file will have the number of the latest version of the game.
Then, the game will proceed to check if it's a new version, and if it is, it will download the .pck file, that will also be available in the latest release.
After downloading the .pck file, which is like a [dlc for Godot games](https://docs.godotengine.org/es/4.x/tutorials/export/exporting_pcks.html), the game will restart and the changes will be applied.

### How are games and files organized
Since I am making multiple Godot projects, I decided to use this repo for all of them, so each one has a release with its tag (If the game is JustDanceFusion, the tag's name will be the same), each one with the app's latest version written in a text file.
