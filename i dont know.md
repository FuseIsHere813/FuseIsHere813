![](https://pbs.twimg.com/media/GUgvjl2XoAA7nyC?format=jpg&name=small)
# Friday Night Funkin' OS Engine - NEW 0.6.3 UPDATE!
![](https://img.shields.io/github/issues/notweuz/FNF-OSEngine) ![](https://img.shields.io/github/forks/notweuz/FNF-OSEngine) ![](https://img.shields.io/github/stars/notweuz/FNF-OSEngine) ![](https://img.shields.io/github/license/notweuz/FNF-OSEngine) ![GitHub all releases](https://img.shields.io/github/downloads/notweuz/FNF-OSEngine/total) ![GitHub repo size](https://img.shields.io/github/repo-size/notweuz/FNF-OSEngine) ![](https://img.shields.io/github/contributors/notweuz/FNF-OSEngine) ![GitHub release (latest by date)](https://img.shields.io/github/downloads/notweuz/FNF-OSEngine/latest/total)

## Installation:
As from when I bulit the game (since the 0.5 update), you must use [Haxe 4.2.4 or greater.](https://haxe.org/download) (Greater versions after that weren't tested).

After installing Haxe, enter these lines in the Command Prompt to install/set these libararies.

Refer to the [Building Instructions.](github.com/FuseIsHere813/FNF-OSEngine-New/wiki/Library%20Installion)

If you don't want your mod to be able to run .lua scripts, delete the "LUA_ALLOWED" line on Project.xml

If you get an error about StatePointer when using Lua, run `haxelib remove linc_luajit` into Command Prompt/PowerShell, then re-install linc_luajit.

## OS Engine Credits:
* [weuz_](https://github.com/notweuz) - Coding
* [nelifs](https://github.com/nelifs) - Coding and Design
* [Cooljer](https://github.com/cooljer) - Arts

### OS Engine Special Thanks
* [Fuse](https://github.com/FuseIsHere813) - 0.6.3 PORT HEH!
* [ExpungedGaming6969](youtube.com/@ExpungedGaming6969) - New Ideas for Engine.
* [jonnycat](https://github.com/McJonnycat) - Fixing bugs in Engine <3.
* [Kade Engine](https://gamebanana.com/mods/44291) - Circle Note Skin.

## Psych Engine Credits:
* Shadow Mario - Programmer
* Riveren - Artist

### Psych Engine Special Thanks
* bbpanzu - Ex-Programmer
* SqirraRNG - Crash Handler and Base code for Chart Editor's Waveform
* KadeDev - Fixed some cool stuff on Chart Editor and other PRs
* iFlicky - Composer of Psync and Tea Time, also made the Dialogue Sounds
* PolybiusProxy - .MP4 Video Loader Library (hxCodec)
* Keoiki - Note Splash Animations
* Smokey - Sprite Atlas Support
* Nebula the Zorua - LUA JIT Fork and some Lua reworks & VCR Shader code
_____________________________________

## OS Engine Features

OS Engine is a fork of [Psych Engine](https://github.com/shadowmario/psychengine/tag/0.6.2), which means it supports mods, like the original.

Not only that, we bring new features for this modfication, making mods more user-friendly, and of course, more VDAB friendly too.

More features will be added later (For contribution, make a pull request with your desired change. (Will be reviewed.))

### Note Skins
OS Engine adds the circle noteskin only, right? well, now there is NEW 3D NOTES!
Select your desired in the Options Menu.

### Showcase Mode
This feature hides HUD and enables botplay. Useful for showcasing, and for youtube.

### Perfect!! Judgement
Adds Perfect!! Judgement. It's better than sick. Btw you can disable it in settings if you want.

![](https://media.discordapp.net/attachments/969211146412363828/969213039230455838/unknown.png)
![](https://media.discordapp.net/attachments/969211146412363828/969212313410351134/unknown.png?width=1440&height=190)

### Lane Underlay
You can set lane underlay transparency under arrows by using that functions.

![](https://media.discordapp.net/attachments/969211146412363828/969212761605296198/unknown.png?width=465&height=676)
![](https://media.discordapp.net/attachments/969211146412363828/969212421887635546/unknown.png?width=1440&height=326)

### Custom Settings in Chart Editor.
There's multiple new functions in chart editor. Like player/opponent trail, camera move and etc.

![](https://media.discordapp.net/attachments/969211146412363828/969213936924774430/unknown.png)

### Literally Useless Exit Game State
Now you can press ESC at title state. And game will ask you do you want to close game or no

![](https://media.discordapp.net/attachments/969211146412363828/969214715702177812/unknown.png?width=1202&height=676)

### Bit Changed Main Menu State

![](https://media.discordapp.net/attachments/969211146412363828/969214974369099807/unknown.png)

### Winning icons 
Instead of 2 icons, there'll be three icons (losing, normal, winning). And yes, you can use double icons (without winning).

![](https://github.com/weuz-github/FNF-OSEngine/blob/main/assets/preload/images/icons/icon-bf.png?raw=true)

*thanks Cooljer for remaking original fnf icons*

### Shaders
Returned shaders from old psych engine versions. Now you can make your bambi mods.

### Custom Title State
Bit changed Title State. Now it looks way more better.

![](https://media.discordapp.net/attachments/969211146412363828/969215626126196797/unknown.png?width=1202&height=676)

### Striped Health Bar
Cassette Girl vibes?

![](https://media.discordapp.net/attachments/969211146412363828/969218236950397038/unknown.png)
