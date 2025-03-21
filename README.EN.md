<h1 align="center">
  <img src="https://user-images.githubusercontent.com/93424739/194055848-84830c09-dd8a-4017-b691-5198130bd3f0.jpg">
</h1>

<h1 align="center">
  <p>Bot auto play League of Legends<p>
  <img src="https://readme-typing-svg.herokuapp.com?color=%2336BCF7&center=true&vCenter=true&width=380&lines=Bot+AI+League+of+Legends">
</h1>

<p align="center">
  Display language:
  <a href="https://github.com/kgemas/League-AI/blob/main/README.md">[Vietnamese]</a>
  -
  <a href="https://github.com/kgemas/League-AI/blob/main/README.EN.md">[English]</a>
</p

What is this?
===
- This is a self-playing bot of league of legends.
- Released to test new technologies, it uses only publicly available apis and does not interfere with the game at all.
- The way this bot works is to emulate a keyboard and mouse like a player.
<details open>
  <summary>Expand / Shrink</summary>
  <p align="center">
    <img src="https://github.com/kgemas/League-AI/raw/main/Assets/example.gif">
  </p>
</details>


Download
===
- Latest version, please download the file [LeagueAI.zip] (https://github.com/kgemas/League-AI/releases/latest).
- Once the download is done, you can compare it with the md5 hash to ensure that the file you download is safe.


Environmental requirements
===========
For the software to work, operating environment packages are required.
- Install .NET Framework 4.7.2 Runtime [Download Here](https://go.microsoft.com/fwlink/?LinkId=863262).


30 seconds install.
===
- **Step 1**: Open the extracted folder (or install), find the configuration file ```config.json```. Please modify the path to your game folder and save the settings again.

For riot server, point to **Riot Games** directory.
```
"DefaultLeaguePath": "C:/Riot Games"
```
For garena server, point to **32787** directory.
```
"DefaultLeaguePath": "E:/GamePC/Garena/Games/32787"
```

- **Step 2**: Open the game app. The screen will have several menus like this.
<p align="center">
  <img src="https://github.com/kgemas/League-AI/raw/main/Assets/dashboard.PNG">
</p>

- **Step 3**: Run the program ```LeagueAI.exe``` and enter the Key (if any).
- Done 🎉 Keep the screen unlocked and go play 💃

Advanced File Customization ```config.json```
===
```
// server
"hostActive": "https://leaguebot.khaivu.dev"

// the number of games the bot will play on its own
"maxGame": 8,

// 1 = automatic shutdown, 0 = no shutdown
"autoShutdown": 1,

// skill upgrade order
"upgrandSkillMap": {
  "1": "Q",
  "2": "W",
  "3": "E",
  "4": "Q",
  "5": "W",
  "6": "R",
  "7": "Q",
  "8": "W",
}
```

Advanced customization for unsupported servers
===========
In some game distributions, you may encounter a case where the file path does not have a default value like in the settings file ```appsettings.json```. The workaround is to point each file to its correct address. There are 6 files that need to be configured manually as shown below.

<p align="center">
  <img src="https://github.com/kgemas/League-AI/raw/main/Assets/adventureConfig.PNG">
</p>

The ```DefaultLeaguePath``` option is the game's root path. All remaining 5 options will have Path = DefaultLeaguePath + "remaining value".

More specifically, for example ```LeagueGameconfigPath``` as shown in the picture will have the actual path as ```G:\\Game\\LOL\\LOL_Game\\32787\\Game\\Config\\game.cfg```.

Find the correct file and shorten the path to match string addition. Until the publisher fixes the bug, this configuration will remain active. Because the software needs to use these profiles to get permission to read the API.

Updates and patches
===========
- For stable operation, update to the new version when possible, the latest versions usually include bug fixes and new features.
- Starting from the following updates, the ```UpdateBotAI.exe``` tool will be attached to the file ```LeagueAI.zip``` at [release](https://github.com/kgemas/League-AI/releases/latest). Run the file ```UpdateBotAI.exe``` and it will replace the old versions by itself.

Support telegram group.
===
[LeagueAI - Github Kgemas (Vietnam)](https://t.me/+HBclRDdmP4pjYjNl)

Behavior rules:
1. For newbie: read the answer using the search function on github + telegram group before asking a question.
2. With members: be polite and help newcomers when possible.

I created a telegram group to help fix bugs faster, simply because I'm more active here.

The software itself is experimental software for new technologies.

I'm the only developer so it would be great if people help each other and I just need to take care of new unexplored issues.


Can't run the software?
===
- As one master said
<p align="center">
  <img src="https://user-images.githubusercontent.com/93424739/212647023-0b3e30a5-bfd2-4bb0-966a-8f32cbb2c587.png">
</p>

- You can track **resolved** issues [here](https://github.com/kgemas/League-AI/issues?q=is%3Aissue+is%3Aclosed).

- Or view issues **in progress** [here](https://github.com/kgemas/League-AI/issues?q=is%3Aopen+is%3Aissue).

- If you have some new unresolved errors, please [create a new issue](https://github.com/kgemas/League-AI/issues/new/choose), it may take 1-2 days for me to process, but please be patient 😂


Project support?
===
- If you find this project interesting, become one of the server maintainers using the QR on the left.
- If you want to thank the developer, on the right is his QR 🐳.

<p align="center">
  <img src="https://user-images.githubusercontent.com/93424739/212659961-08520136-8fd4-492c-9e2c-73a501fd6426.png" width="600">
</p>

Good luck 🐱‍👤🎶
