# What is this?
IMSCARED is, as it's advertised, a "pixelated nightmare". It's a critically-acclaimed pixel horror game made by Ivan Zanotti, in English and Italian.

This repo contains a patch made specifically for the [YoYo Loader](https://github.com/Rinnegatamante/yoyoloader_vita) by [Rinnegatamante](https://github.com/Rinnegatamante).

# Some things I should know?
Yes. First off, the game will try to deceive you and will create files in the assets folder of the game (`ux0:data/gms/<IMSCARED HERE>/assets`).

Be sure to check it often with a file management app like VitaShell. 

Another thing, **always quit the game with Select**. The game will ask you to quit the game with Select, and therefore, if you try to quit by closing the app, it won't work as the game won't progress at times.

## CONTROLS
- Move - L-Stick/D-Pad
- Look Around - R-Stick
- Interact - Cross
- Crouch - L
- Run - R
- Select - Pause/Quit
- Misc. things - Circle/Triangle

# How to Install
1. Download the patch file and buy IMSCARED on Steam.
2. Patch the `data.win` file at the game's directory using xDelta, save it as `game.droid` and put it in the assets folder of the `.APK` file also found in the Downloads.
3. Grab every single file from the game folder (except for the `.exe` file) and put it in the assets folder of the `.APK`.
4. Grab the finished APK, open up VitaShell on your PS Vita, and drag the file to `ux0:data/gms/<Whatever name you want>`. Make sure to rename the file to `game.apk`.
5. In the assets folder in VitaShell, create three folders: `imscared`, `Enter a great place` and `Entra in un posto meraviglioso`. These are act as folders the game will look for.
6. Enjoy the game.

# Issues
Some issues are present.

For one, the frame rate will drop heavily when on some certain areas. They are still playable but will provide a less enjoying experience.

Another thing is that some textures in the game are not edited to suit for the PS Vita (keyboard controls may be present for some of those).

Some text files might not be generated because of the external filesysten the game used. While I made sure that all of them were replaced, one or two might not come up.

I will look into fixing these issues as soon as I can. Meanwhile, if you find any other issues, please report so in the Issues page.

# Credits
- [Rinnegatamante](https://github.com/Rinnegatamante) for making the YoYo Loader
- [Ivan Zanotti](https://twitter.com/mymadnessworks?lang=en) for making the original game
