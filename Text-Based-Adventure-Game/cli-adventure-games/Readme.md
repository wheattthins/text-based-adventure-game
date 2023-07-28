Text Based Adventure Games built with Node.js

> "_It runs on the world's most powerful graphic chip - Imagination_" - Sheldon Cooper


The game engine is still in active development and supports only basic features. 

_Pull requests and Game Scripts welcome!_

## Installation
Run 
```bash
$ [sudo] npm install -g cli-adventure-games
```

To play, execute
```bash
$ cli-adventure-games
```

You will be shown help instructions before you start the game. At any point, you can type `help` to get help.


## For developers
There is a Game Script, that is fed into the Game Engine. The script file is a JSON, that consists of how the game should work. The game engine describes the scenarios listed in the JSON to the player, takes his input and acts accordingly.

You can either contribute to the Game Script, by building one of your own games or you can contribute to the engine as well. 

To create your own game script, please refer to the `Maya.json` in the `Games` folder.
