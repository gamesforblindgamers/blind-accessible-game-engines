# Make Blind-Accessible Games Faster

Are you interested in making games that blind and visually impared gamers can play, too? Me, too. Here's a list of resources, reading, and game engines that are useful in quickly putting together a game that works well for blind and visually impaired players.


| Name | Repository | Description | Can output to screen readers? | Uses Text-to-Speech? | Exported Game Runs on (OSes) |
| --- | --- | --- | --- | --- | --- |
| Bevy | https://bevyengine.org/ | A refreshingly simple data-driven game engine built in Rust. Free and Open Source Forever! It has an API to integrate with AccessKit. | Yes | No | Windows, Linux, Mac, Web |
| Blind-Accessible HTML + Javascript Game Template | https://github.com/nightblade9/themis-games-template | A combination of HTML and Javascript for making web games that work across multiple devices (web, phone) and allow you to easily navigate your game elements and announce to the player. | Yes | No | Web |
| C/C++, C#, Java, Lua, Python, Ruby, etc.  | Various | Many programming languages allow you to create console (text) games, which integrate well with existing screen readers (NVDA, Orca, etc.) | Yes | No | Windows, Linux, Mac |
| Godot  | https://godotengine.org/ | A feature-rich, general-purpose 2D and 3D game engine with built-in UI. Includes text-to-speech, and AccessKit integration is in the works. [Search the assetlib](https://godotengine.org/asset-library/asset?filter=nvda&category=&godot_version=&cost=&sort=updated). | No | Yes | Windows, Linux, Mac, Web, Mobile |
| syngen  | https://github.com/nicross/syngen | A spatial sound and synthesis library for audio game development and experience design. A light wrapper around the Web Audio API for building synths and positioning them as props on a three-dimensional binaural soundstage. See [this template](https://github.com/nicross/syngen-template). | No | No | Windows, Linux, Mac (same as OS you build on) |
| Unseen RPG Engine | https://ericbomb.itch.io/the-unseen-rpg-engine | A console application that allows creation of blind accessible RPG's. It edits text files that then gets read by a central EXE and builds the game at run time. As a console application the hope is it is as accessible as possible.  Meaning changes can also be done easily by editing these text files. | Yes | No | Windows |
| Twine | https://learn.microsoft.com/en-us/dotnet/core/get-started | Twine is an open-source tool for telling interactive, nonlinear stories, without writing any code. You can extend your stories with variables, conditional logic, images, CSS, and JavaScript if you wish. | Yes | No | Web |
