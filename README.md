![](Thumbnail.png 'application-thumbnail')

# Personal Library of Nostalgic Games

「**PLoNG**」

> ❝ PLoNG is an attempt to preserve the memory of my gaming youth. ❞
>

📌 ┃ Type: **SDC Library** ┃ Name: **PLoNG** ┃ SDC Version: **1.0.23.5e** 

📦 ┃ **[DOSBox](https://www.dosbox.com/) 🟩** ┃ **[DOSBox Staging](https://dosbox-staging.github.io/) 🟩** ┃ **[DOSBox-X](https://dosbox-x.com/) 🟩** 

📎 ┃ **[Simple DOSBox Client](https://github.com/rarioj/sdc)** ┃ Cover Arts: **[MobyGames](https://www.mobygames.com/)** ┃ Program Assets: **[Archive.org](https://archive.org/)** 

## Getting Started
It is not necessary to clone or download the whole repository. This library uses [Simple DOSBox Client](https://github.com/rarioj/sdc) to process the `Library.txt` configuration file. Refer to SDC's [Host Requirements](https://github.com/rarioj/sdc#host-requirements) section for all the required and recommended tools. A [`Setup`](https://raw.githubusercontent.com/rarioj/sdc/main/Setup) script from SDC and a [`Library.txt`](https://raw.githubusercontent.com/rarioj/plong/main/Library.txt) configuration file from this repository are all you need. Steps to follow:

1. Create an empty library directory.
2. Download the latest `Library.txt` configuration file and the latest `Setup` script.
3. Make the `Setup` script executable.
4. Run the `Setup` script.

```shell
mkdir plong
cd plong
curl "https://raw.githubusercontent.com/rarioj/plong/main/Library.txt" -o Library.txt
curl "https://raw.githubusercontent.com/rarioj/sdc/main/Setup" -o Setup
chmod a+x Setup
./Setup
```

5. Once the library is ready, go to the desired game directory.
6. Run the `Launch` script and enjoy the game.

```shell
cd "Games/By Genre/Adventure/Beneath a Steel Sky"
./Launch
```

## Is this legal?
The purpose of this repository is to share a plain-text library configuration file. None of the program assets, such as floppy disks, CD-ROM images, zipped archives, and game manuals, are hosted here. I do not take any responsibility if downloading and running old programs (applications, tools, operating systems, and games) is considered illegal in certain countries. I do not condone the act of software piracy or copyright infringement.

Some of the old programs listed here are **Freeware** (free to use and distribute), **Abandonware** (no longer being distributed or supported by the developer or copyright holder), **Discontinued** (end-of-life software), and some are **Proprietary** (software is still available for purchase). Please try to buy the program first from [GOG](https://www.gog.com/), [Steam](https://store.steampowered.com/), or other online stores. Each program in the library, especially those tagged as *Proprietary*, will include external links to buy online.

All program assets are available from the [Internet Archive](https://archive.org/). It is possible, however, that some assets are no longer downloadable. Please submit an issue if that is the case. I asked [ChatGPT](https://chat.openai.com/) about the legality of playing old DOS games downloaded from the Internet Archive.

> ❝ The legality of playing old DOS games downloaded from Archive.org depends on the specific circumstances and the copyright status of the particular game in question.
>
> In general, it is illegal to download and play copyrighted material without the permission of the copyright owner. However, some older games, especially those made for MS-DOS, are now considered abandonware, which means that the copyright owner may no longer exist or may not be enforcing their rights to the game. In such cases, it may be legal to download and play the game.
>
> It's important to note that the legality of abandonware is a grey area, and there is no clear consensus on whether it is legal or not. If you're concerned about the legality of playing a specific game, you may want to consult a lawyer or do some research to determine the copyright status of the game.
>
> In general, it is a good idea to respect the rights of copyright owners and to only play games that you have legally obtained. ❞ — ChatGPT

![](Montage.png 'Personal Library of Nostalgic Games')

> <table><tr><td width="50%">
>
> ### 🗄️ 10 Categories
> - 🗂️ [All Programs ‣ Games (30)](./All%20Programs/Games/README.md)
> - 🗂️ [Games ‣ By Genre ‣ Action (14)](./Games/By%20Genre/Action/README.md)
> - 🗂️ [Games ‣ By Genre ‣ Adventure (4)](./Games/By%20Genre/Adventure/README.md)
> - 🗂️ [Games ‣ By Genre ‣ Puzzle (4)](./Games/By%20Genre/Puzzle/README.md)
> - 🗂️ [Games ‣ By Genre ‣ Racing (2)](./Games/By%20Genre/Racing/README.md)
> - 🗂️ [Games ‣ By Genre ‣ Role-playing (2)](./Games/By%20Genre/Role-playing/README.md)
> - 🗂️ [Games ‣ By Genre ‣ Strategy (5)](./Games/By%20Genre/Strategy/README.md)
> - 🗂️ [Games ‣ By License ‣ Abandonware (10)](./Games/By%20License/Abandonware/README.md)
> - 🗂️ [Games ‣ By License ‣ Freeware (20)](./Games/By%20License/Freeware/README.md)
> - 🗂️ [Games ‣ By Platform ‣ DOS (30)](./Games/By%20Platform/DOS/README.md)
>
> </td><td width="50%">
>
> ### 📓 30 Programs
> 🔎 ┃ [Abuse](./All%20Programs/Games/Abuse/README.md) ┃ [Alien Carnage](./All%20Programs/Games/Alien%20Carnage/README.md) ┃ [Ascendancy](./All%20Programs/Games/Ascendancy/README.md) ┃ [Beneath a Steel Sky](./All%20Programs/Games/Beneath%20a%20Steel%20Sky/README.md) ┃ [Bio Menace](./All%20Programs/Games/Bio%20Menace/README.md) ┃ [Blackthorne](./All%20Programs/Games/Blackthorne/README.md) ┃ [Blood & Magic](./All%20Programs/Games/Blood%20%26%20Magic/README.md) ┃ [Cadaver](./All%20Programs/Games/Cadaver/README.md) ┃ [Civilization](./All%20Programs/Games/Civilization/README.md) ┃ [Command & Conquer](./All%20Programs/Games/Command%20%26%20Conquer/README.md) ┃ [Command & Conquer: Red Alert](./All%20Programs/Games/Command%20%26%20Conquer%20-%20Red%20Alert/README.md) ┃ [D/Generation](./All%20Programs/Games/D-Generation/README.md) ┃ [Electroman](./All%20Programs/Games/Electroman/README.md) ┃ [Flight of the Amazon Queen](./All%20Programs/Games/Flight%20of%20the%20Amazon%20Queen/README.md) ┃ [God of Thunder](./All%20Programs/Games/God%20of%20Thunder/README.md) ┃ [Hi-Octane](./All%20Programs/Games/Hi-Octane/README.md) ┃ [Jetpack](./All%20Programs/Games/Jetpack/README.md) ┃ [Lure of the Temptress](./All%20Programs/Games/Lure%20of%20the%20Temptress/README.md) ┃ [One Must Fall 2097](./All%20Programs/Games/One%20Must%20Fall%202097/README.md) ┃ [Prince of Persia CD Collection](./All%20Programs/Games/Prince%20of%20Persia%20Collection/README.md) ┃ [Stargunner](./All%20Programs/Games/Stargunner/README.md) ┃ [Supaplex](./All%20Programs/Games/Supaplex/README.md) ┃ [Teen Agent](./All%20Programs/Games/Teen%20Agent/README.md) ┃ [The Elder Scrolls: Arena](./All%20Programs/Games/The%20Elder%20Scrolls%20-%20Arena/README.md) ┃ [The Elder Scrolls II: Daggerfall](./All%20Programs/Games/The%20Elder%20Scrolls%202%20-%20Daggerfall/README.md) ┃ [The Incredible Machine](./All%20Programs/Games/The%20Incredible%20Machine/README.md) ┃ [The Incredible Machine 2](./All%20Programs/Games/The%20Incredible%20Machine%202/README.md) ┃ [The Lost Vikings](./All%20Programs/Games/The%20Lost%20Vikings/README.md) ┃ [The Need for Speed: Special Edition](./All%20Programs/Games/The%20Need%20for%20Speed/README.md) ┃ [Xargon](./All%20Programs/Games/Xargon/README.md) 
> </td></tr></table>

&nbsp;

