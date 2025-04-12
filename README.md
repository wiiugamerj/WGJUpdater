# wiiugamerj's game updater system

This repository is used for the auto update system in my different Godot games and apps.
There's nothing to do here since this repository is kind of being used as a server.

### How does it work?
1. When the videogame/app starts, it downloads the latest .txt file available at the moment. This .txt file will have the number of the latest version of the game.
2. The game checks if it's a new version, and if it is, it will download the .pck file, that will also be available in the latest release.
3. After downloading the .pck file (update file), the game will restart and the changes will be applied.

### How are games and files organized?
Since I am making multiple Godot projects, I decided to use this repo for all of them. Each one has a release with its tag (The tag's name will be its game's name), with the app's latest version written in a text file.
