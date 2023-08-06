<div align="center">
  <a href="https://github.com/Xyio24/HideScoreboardNumber">
    <img src="pack.png" alt="Logo" width="32" height="32">
  </a>

<h3 align="center">Hide Scoreboard Number</h3>

  <p align="center">
    Do you annoyed with the ugly red number in your scoreboard? Then, you can use this resourcepack to get rid of that red number.
    <br />
    <br />
    <a href="https://github.com/Xyio24/HideScoreboardNumber">View Documentation</a>
    ·
    <a href="https://github.com/Xyio24/HideScoreboardNumber/issues">Report a Bug</a>
  </p>
</div>

<p align="center">
  <img alt="GitHub last commit" src="https://img.shields.io/badge/Last_Commit-August_6_2023-red">
  <img alt="GitHub Release Date" src="https://img.shields.io/badge/Release_Date-August_6_2023-red">
</p>

---
How to install it to your Minecraft
---
1. Go to "Options".
2. Click "Resource Pack".
3. Click "Open Pack Folder"
4. Copy & Paste the downloaded file to your minecraft resourcepack folder.
5. Click "Done"
6. Done.

---
How to install it to your Server
---
1. First you will need to upload your resourcepack to Dropbox and copy the URL.
2. In the `server.properties` file you will need to copy that link to the following setting:
```
https://www.dropbox.com/scl/fi/1lc1a66puik8u2mhb9qur/Hide-Scoreboard-Number-1.19.4.zip?rlkey=vxtnukmw9i38i0j4hlh4yvzrq&dl=0
```
```properties
...
resource-pack-prompt= https://www.dropbox.com/scl/fi/1lc1a66puik8u2mhb9qur/Hide-Scoreboard-Number-1.19.4.zip?rlkey=vxtnukmw9i38i0j4hlh4yvzrq&dl=0
...
```
3. Then, restart your server. Now it will be loaded when player joins the server.

---
How to install it to your Oraxen or ItemsAdder
---
Oraxen and ItemsAdder have their own hide scoreboard system. But if you have problems with that you can use this.

Oraxen:
1. Simply just extract my premade texture.
2. Then upload or copy the `assets` folder to the `/plugins/Oraxen/pack` . Leaving the `pack.mcmeta` as it not required by Oraxen.
3. Run `/o rl all` in your server.
4. Now it will be reloaded and applied to players.

ItemsAdder:
1. Same as before, but the location is different.
2. Make new folder like this `/plugins/ItemsAdder/contents/HideScoreboardNumber/resourcepack`.
3. Copy `assets` folder to the following path.
4. Run `/iareload` then `/iazip` and follow the ItemsAdder tutorial for uploading pack.
   
