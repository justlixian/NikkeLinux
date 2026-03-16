# NikkeLinux

This repo is made specifically for me, in case I needed a reinstall, but based on the job of KoleckOLP. I feel because of his usage of AI, some parts are outdated, lack explanations, or are just unnecessary. The lottery thing isn't needed anymore. I used Bazzite and did not touch the terminal at all.

---

## Requirements
1. **Steam:** Needed to enable Proton, a compatibility layer to run Windows files. You can install via Flathub on your distro.
2. **ProtonPlus:** Needed to install different types of Proton forks. You can install via Flathub on your distro.
3. **Miniloader:** Needed for the whole game.

---

## Installation

1.  **Install Steam and ProtonPlus:** See **Requirements** for explanations. 
2.  **Download MiniLoader:** Get `NikkeMiniloader0.0.6.143.exe` from this repo, the [Official website](https://nikke-en.com/NikkeMiniloader0.0.6.143.exe), or [Archive.org](https://web.archive.org/web/20230215142046/https://nikke-en.com/NikkeMiniloader0.0.6.143.exe).
3.  **ProtonPlus Setup:** With **ProtonPlus** installed, download both `Proton-GE Latest` and `DW-Proton Latest`. It's normal if it takes a while. Restart Steam; we'll need them for step 4.
4.  **Move the miniloader:** After you have downloaded the file, move it to your desired location. It can be anywhere, but if you want to move it later on, you will have to update it manually on Steam.
5.  **Add miniloader to Steam:** Add `NikkeMiniloader0.0.6.143.exe` as a **Non-Steam Game**. Click on `Properties` > `Compatibility` and enable it. Select `DW-Proton Latest`. Click OK.
6.  **Initial Install:** Launch the game through Steam and install the game launcher. Best to use the default download location of `C:\NIKKE`. Wait for the game to fully finish downloading, and click `X` once finished. Clicking `Launch` now will have no effect, but you will have to manually close it on Steam.
7.  **Locate the files:** Go to `~/.steam/steam/steamapps/compatdata/`, sort by date, and open the most recent folder (e.g., `3788235738`).
8.  **Copy the Launcher's file path:** If you set everything to default, your path should look something like this: `pfx/drive_c/NIKKE/Launcher/nikke_launcher.exe`. Once you find the `.exe`, right-click and copy its path.
9.  **Add the launcher:** Just like before, add the `nikke_launcher.exe` as a **Non-Steam Game**. Click on `Properties` > `Compatibility` and enable it. But this time, we'll use `Proton-GE Latest` instead. 
10. **Run the launcher:** Now that's done, you can now simply play the game. Based on my testing, the first launch took a while. Sometimes you have to hit `Play` and `Cancel` a few times. After that, it shouldn't have the issue anymore.
11. **Enjoy the game!:** Once the launcher finally opens, select **"Other Logins"** and sign in as you would on Windows. You can install the game normally.

---

## Quality-of-Life stuff
1. **Hide the miniloader:** Do note that you CANNOT remove the miniloader from Steam. It is required to load the launcher, which is required to load the game. Hiding it is the best way.
2. **SteamGridDB integration:** To make it look native to the Steam client, you can rename it to `NIKKE: Goddess of Victory` and set a custom logo, grid, background, icon, and wide cover from SteamGridDB. I have included what I personally use in this repo.
3. **Add to Desktop:** Using Steam, you can simply add the app to the Desktop.
4. **Decky PlayTime:** To track your game time (and other non-Steam games), you can simply use Decky Playtime. You can search how to install `Decky` on your distro.

---

## Quirks
As this is more of a workaround than anything else, there will be some quirks.
1. **Double overlay:** Because of this game's nature of having both the game and the launcher, the launcher will have an overlay of its shape under the game. You can simply close it; it will not affect the game.
2. **You will be logged out:** Every time you launch the game, you will have to login back to the launcher. I haven't found a workaround for this yet.
3. **The game will remain running:** Due to the anti-cheat's nature, the game will constantly be running in the background unless you manually press `Exit` on your system tray or `Quit` on Steam.

---

**Credits:** Made by JustLixian, based on the work of Koleck.
