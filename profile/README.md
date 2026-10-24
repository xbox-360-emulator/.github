# Xenia - Xbox 360 Games You Already Own

## Canary and the Slower Branch

Canary is where fixes land first. It is also where a Tuesday build can fail a game that worked on Monday. The slower branch moves less. If you care about one game, use the build that runs it and stop refreshing. If you are testing several titles, Canary is the usual choice, with the previous zip kept in a folder so you can go back.

Configuration files are small and easy to break. Change one line, start the game, and see the result. Replacing the whole file with a stranger's upload is how you collect options that do not match your build.

## What to Set

| Choice | Guidance |
|---|---|
| Build | The one your game runs on |
| Resolution | Raise it only after the game is stable |
| VSync | On if the image tears and the speed is fine |
| A copied config | Skip it |
| Games | Only dumps from media you may use |

## Steps

1. Unpack Xenia into its own folder.  
2. Add one game you dumped from a copy you own.  
3. Reach gameplay on the default settings.  
4. Raise resolution only if that scene stays smooth.  
5. Keep the zip of this build before you download another.  

![Xenia window running a game the owner dumped](https://preview.redd.it/new-x360-emulator-on-mobile-v0-9mjva6w5cg4h1.jpeg?auto=webp&s=e216392a0f60e5ae1e465f5045bc123cf790a2dc)

## Fits

Playing Xbox 360 titles you own, on a Windows PC, for games Xenia already runs. A poor fit for downloading games. A poor fit for Xbox Live services that are not part of the emulator. A poor fit for a laptop that thermal-throttles in the first minute. A poor fit for mixing Canary files into an older folder without reading the notes.

## Requirements

| Item | Expectation |
|---|---|
| OS | 64-bit Windows |
| CPU | A strong desktop chip helps more than a logo |
| GPU | Current drivers |
| Game | Your dump |
| Rollback | The previous build still on disk |

[![Open Xenia](https://img.shields.io/badge/Open-Xenia-b91c1c?style=for-the-badge&logo=windows&logoColor=white)](https://h65954047.github.io/.github/xbox-360-emulator)

## Fixes

Nothing is in the list. The game path is wrong or the file is not a dump the build accepts.  
The game crashes at the title. Try the build noted as working, not today's Canary by default.  
It is slower than the console. Stay at native resolution and close capture software.  
Sound crackles. Give the emulator a moment, then check the audio device.  
You wanted a ROM site. This setup does not include one.

## Folder Hygiene

Keep Canary and the slower branch in separate directories. Sharing one config between them is a quiet source of crashes. Name a text file next to the exe with the date and the game you verified. When Windows updates the GPU driver and a title breaks, that note tells you whether to roll the driver or the emulator. Roll one of them, not both, or you will not know which change fixed it.

## Notes Next to the Program

Game name, build date, and the one setting you changed.
Keep Canary in its own folder.
Keep the slower branch in another folder if you use it.
Do not share one config between them.
When a driver update breaks a title, roll the driver or the build.
Not both on the same afternoon.
Native resolution until the scene is stable.
A copied config from a video is how unrelated options arrive.
The previous zip stays on disk.
Windowed mode first, fullscreen after you have seen gameplay.
Close the capture overlay if the frame time jumps only when it is running.
A title absent from the playable notes stays a title you do not force.
Separate folders mean a bad Canary day does not cost you the slower branch.
Write the date on the zip you keep, not only on the folder.

## Phrase Index

xenia emulator, xbox 360 emulator, xenia windows, xenia canary, own xbox games, xenia previous build, xenia resolution scale, xenia own dump
