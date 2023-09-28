![](Thumbnail.png "application-thumbnail")

# Sanitarium

> ❝ Spiralling upwards out of the vacuum, you open your eyes and struggle to comprehend your environment. Underneath you, the springs of an institutional cot sink almost to the floor. The mattress is roughly the thickness of a paper towel and reeks of affliction. Vague memories assault you, a hurried phone call, a message of utmost importance, and a car losing control. As you wake up with a throbbing head, you hear people screaming, sobbing, laughing manically in the background. Is it a nightmare? Are you insane? Is it a reality? Maybe this is death. ❞
>
> ❝ This game **is not abandonware 🚫** and is still for sale on [GOG 💰](https://gog.com/en/game/sanitarium) and [Steam 💰](https://store.steampowered.com/app/284050/Sanitarium/). ❞
>

📌 ┃ **Year** ‣ 1998 ┃ **Genre** ‣ Adventure ┃ **Platform** ‣ Windows 98SE ┃ **License** ‣ Proprietary ┃ **Category** ‣ Diagonal-down • Graphic adventure • Puzzle elements • Horror ┃ **Media** ‣ CD-ROM 

📦 ┃ **[DOSBox](https://www.dosbox.com/) ⬜ (untested)** ┃ **[DOSBox Staging](https://dosbox-staging.github.io/) ⬜ (untested)** ┃ **[DOSBox-X](https://dosbox-x.com/) 🟩** 

📎 ┃ **[Wikipedia](https://en.wikipedia.org/wiki/Sanitarium_(video_game))** ┃ **[MobyGames](https://www.mobygames.com/game/572/sanitarium/)** ┃ **[AbandonwareDOS](https://www.abandonwaredos.com/abandonware-game.php?abandonware=Sanitarium&gid=2289)** ┃ **[MyAbandonware](https://www.myabandonware.com/game/sanitarium-cs8)** ┃ **[GOG 💰](https://gog.com/en/game/sanitarium)** ┃ **[Steam 💰](https://store.steampowered.com/app/284050/Sanitarium/)** 

## Host Requirements
- Download the patched executable file manually from [MyAbandonware](https://www.myabandonware.com/game/sanitarium-cs8), search for *"English version 292 KB (Windows)"*, place it in the `Assets` directory, and rename it to `sntrm.exe`.
- Download the Level 2 patch file manually from [MyAbandonware](https://www.myabandonware.com/game/sanitarium-cs8), search for *"Level 2 Fix English version 57 KB (Windows)"*, place it in the `Assets` directory, and rename it to `plevel2.zip`.
- Download the Labyrinth patch file manually from [MyAbandonware](https://www.myabandonware.com/game/sanitarium-cs8), search for *"Labyrinth Fix English version 20 KB (Windows)"*, place it in the `Assets` directory, and rename it to `plab.zip`.

## Installation Notes
- Open *My Computer* and double-click on the `E:` CD-ROM drive to start the installation.
- Important points:
  - Use the default **drive** and **directory** for the installation location.
  - **DO NOT** install *DirectX* or *Direct Media* when prompted.
  - Always pick the largest installation size when prompted.
- Applying patches:
  - A patched executable file is available on `C:\PATCH\SNTRM.EXE`. Copy this file to `C:\Program Files\ASC Games\Sanitarium`, replacing existing `SNTRM.EXE`.
  - A patch is available on `C:\PATCH\PLEVEL2.ZIP`. Extract the compressed file and copy `SCN.006` to `C:\Program Files\ASC Games\Sanitarium\Data`.
  - A patch is available on `C:\PATCH\PLAB.ZIP`. Extract the compressed file and copy `SCN.016` to `C:\Program Files\ASC Games\Sanitarium\Data`.

## Additional Notes
- The CPU *core* directive is currently set as `dynamic_x86` to [boost performance](https://dosbox-x.com/wiki/Guide%3AInstalling-Windows-98#_dynamic_vs_normal_core). It may impact Windows shut-down and restart processes. Switch it back to `normal` if you find an issue.
- Mounted CD-ROM images at launch:
  1. Sanitarium Disc #1
  2. Sanitarium Disc #2
  3. Sanitarium Disc #3
- Swapping CD-ROM disc when multiple images are mounted: From DOSBox-X menu **DOS > Swap CD drive**.

![](Montage.png "Sanitarium")

