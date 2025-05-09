# <img src="https://raw.githubusercontent.com/expressobits/steam-multiplayer-peer/main/icon.png" alt= “icon” width="32" height="32"> Welcome to Expresso Steam Multiplayer Peer 👋
![Version](https://img.shields.io/badge/version-0.2.3-blue.svg?cacheSeconds=2592000)
[![Documentation](https://img.shields.io/badge/documentation-no-red.svg)](todo-doc)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](MIT)

Godot Asset Lib: https://godotengine.org/asset-library/asset/2258

## Branchs Map

🪹[main](https://github.com/expressobits/steam-multiplayer-peer/tree/main): Contains C++ Plugin

🪹[demo](https://github.com/expressobits/steam-multiplayer-peer/tree/demo): Same example as godot bomberman ([This](https://github.com/godotengine/godot-demo-projects/tree/master/networking/multiplayer_bomber)) But modified EnetPeer with SteamMultiplayerPeer

🪹[addon](https://github.com/expressobits/steam-multiplayer-peer/tree/addon): Compiled version of the libs that are in the godot asset lib store.

🪹[module](https://github.com/expressobits/steam-multiplayer-peer/tree/module): Same compiled version but just the addon folder, to be added as a git submodule

## Tutorial and Learnings (How to use)

See post of Michael Macha
https://michaelmacha.wordpress.com/2024/04/08/godotsteam-and-steammultiplayerpeer/

See too on youtube videos
https://www.youtube.com/playlist?list=PLg_8mgEWE2p8ZA-AqUUJ3CYEtrRVFhl_v

Thank you Michael!

## Features

✔️ Change easy Enet peer to Steam Peer

✔️ Use Steam Sockets (Low level like enet).

✔️ GDExtension (Easy to add your project)
 
✔️ No dependency with GodotSteam, but demo use GodotSteam to handle connections with lobbies (See lobbies tutorial in Godot Steam [here](https://godotsteam.com/tutorials/lobbies/)).


## GodotSteam SteamMultiplayerPeer Differences

| Differences | This SteamMultiplayerPeer | GodotSteam SteamMultiplayerPeer |
|---|---|---|
| Lib Type | GDExtension, add on your project libs to use easy. | C++ module, you need to use the precompiled <br>from godotsteam or compile it yourself |
| Steam Connection | Steam Sockets [Steam Docs](https://partner.steamgames.com/doc/api/ISteamNetworkingSockets)<br>Steam's lowest connection level,<br>manages a connection <br>(It's very close to Enet, <br>that's why I chose this approach for the plugin) | Steam Messages [Steam Docs](https://partner.steamgames.com/doc/api/ISteamNetworkingMessages)<br>Without a connection idea,<br>the connection is managed by the lobby,<br>Need Steam lobbies. |
| TODO  |  |  |

## Known issues

⚠️ No channel support currently
It's been concluded that it's a limitation of the socket system, I'll take it out of the plan for now. See issue (https://github.com/expressobits/steam-multiplayer-peer/issues/2)

## In Progress

🔨 Bugs fixes

## Planneds

📅 No planned features.

<!-- ## Install
See in [Wiki](https://github.com/ExpressoBits/inventory-system/wiki) -->

## Authors

👤 **Rafael Correa**
* Twitter: [@ScriptsEngineer](https://twitter.com/ScriptsEngineer)
* Github: [@scriptsengineer](https://github.com/scriptsengineer)

👤 **Zennyth**
* Github: [@Zennyth](https://github.com/Zennyth)

👤 **greenfox1505**
* Github: [@greenfox1505](https://github.com/greenfox1505)

👤 **MichaelMacha**
* Github: [@MichaelMacha](https://github.com/MichaelMacha)


## 🤝 Contributing

Contributions, issues and feature requests are welcome!

Feel free to check [issues page](https://github.com/ExpressoBits/steam-multiplayer-peer/issues).

To suggest or discuss some project structure, feel free here [discussions page](https://github.com/expressobits/steam-multiplayer-peer/discussions)


## Show your support

Give a ⭐️ if this project helped you!


## 📝 License

This project is [MIT](MIT) licensed.
