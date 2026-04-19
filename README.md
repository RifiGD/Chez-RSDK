# Beat The Shit Out Of Chez

Game created during April Fools by [Samuel772](https://github.com/SAMUEL0772)

Original Game can be found [here](https://github.com/SAMUEL0772/Beat-The-Chez)

RSDKv4 Port created by [RifiGD](https://github.com/RifiGD)

# Special Thanks
* [Skyward](https://github.com/CDSkyward)
    * Helped with a few RSDK related questions
* [Kotas](https://github.com/Eggbanana123)
    * Helped fix the issue where you could spam with the mouse to hit Chez

# Context
No

# Installing
1. Download the repository using using the "Code" then "Download ZIP" button
2. Download the latest RSDKv4 executable from [here](https://github.com/RSDKModding/RSDKv4-Decompilation/releases), and put the executable in the same folder of this repository that you just downloaded
3. Open the game to create the `settings.ini` file, and then close the game and edit it as follows:
```
[Game]
; Sets the game language (0 = EN, 1 = FR, 2 = IT, 3 = DE, 4 = ES, 5 = JP, 6 = PT, 7 = RU, 8 = KO, 9 = ZH, 10 = ZS)
Language=0
; Determines game type in scripts (0 = Standalone/Original releases, 1 = Origins release)
GameType=0
; If set to true, disables the start menu
SkipStartMenu=true
; Handles pausing behaviour when focus is lost
; 0 = Game focus enabled, engine focus enabled
; 1 = Game focus disabled, engine focus enabled
; 2 = Game focus enabled, engine focus disabled
; 3 = Game focus disabled, engine focus disabled
DisableFocusPause=3
```
4. Enjoy!
