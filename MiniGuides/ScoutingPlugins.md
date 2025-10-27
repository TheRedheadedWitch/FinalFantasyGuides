# Scouting Plugins

You will need 3 plugins for easy scouting.

1. Scout Helper
2. Lifestream
3. VNavMesh

[!Note]
You can get away with just using the first plugin as it is the only one in the regular Dalamud repository, but you will be manually doing a lot of work.

To set up the first one easily. The second one will require one of two options. You can add the mega repository which has both at<br>
> `https://raw.githubusercontent.com/WilliamW1979/FFXIV/main/repository.json`<br>

or you could get them directly from their source repos at<br>

> `https://github.com/NightmareXIV/MyDalamudPlugins/raw/main/pluginmaster.json`<br>
> `https://puni.sh/api/repository/veyn`<br>

[!Note]
I recommend the Mega Repository because it combines all the repositories into one easy thing to add. The person who create the Mega Repository wrote a script that will create a json file that contains all the different jsons into one and then checks them every 5 minutes for updates. The limitation is that you have to wait up to 5 minutes for an update but you never have to worry about adding a ton of repositories to your game. It also grows so as more are created or discovered and reported, they are added to the list.

## VNavMesh
VNavMesh by itself isn't much, it is a plugin that maps a zone and allows your character to move through the zone either by flight or by walking. It has basic commands, 3 of them I suggest setting up as macros
`/vnav flyflag` => Flies you to your flag location
`/vnav moveflag` => Walks you to your flag location
`/vnav stop` => Stops any vnav movement.
The true strength in VNavMesh is that other plugins can use it. Lifestream is one of them.

## Lifestream
I really love this plugin. The creator did a great job writing it and keeps it up to date. They even take suggestions on how to upgrade their plugin and make it better. I have personally made suggestions to it that are being implemented. With that said, I will just mention some of the basic uses for Lifestream that makes it worth wild.
`/lifesteam` => Opens up the main settings window
`/li [Command]` => Runs a command that is either built in or one that you custom create. This is the heart of Lifestream that makes it so great.
[^1] fc => Once set up, will teleport you straight to your FC.
[^2] gc => Teleports you and walks you to your GC (even in Limsa, will use the teleporters)
[^3] fcgc => Teleports you to your FC's GC which can be different then your personal one
[^4] home => Teleports you to your home
[^5] SERVER (Faerie) => Teleports you to that server, even if it is on another Data Center (EXTREMELY FAST)

These are some examples, you can find more built in commands in Lifestream but for what we want, we will be using the `/lifestream` settings window to access the third tab called **Custom Alias**. This tab allows you to create custom commands in lifestream so that you can do your own thing. I am not going to sit here and explain how to set up your own commands, instead I will share my own commands that I made myself that you can ulitize.<br>
[Lifestream Custom Aliases](https://github.com/TheRedheadedWitch/FinalFantasyGuides/blob/main/LifestreamCustomAlias.md)

Using that link, you want to copy the ones in the **Scouting** section. You technically only need the ones for the patch you want to scout, but I recommend importing them all. Instructions on how to import them are at the botton of the page.

Once you have all the plugins install and all the custom aliases imported that you need, you are ready.
