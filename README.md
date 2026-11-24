# Ahad of the Curve (AOTC)

<img width="1970" height="1996" alt="AOTC-0 18 0-collage" src="https://github.com/user-attachments/assets/8a712b00-d708-457d-a40d-db95e6db5921" />

AOTC never edits the game's own archives, and everything it does can be undone.

## What it restores

**Characters**
- **Filia:** original knockdown sprites, the afro pick in her burst, original panties colour, story cutscenes
- **Cerebella:** original spin and knockdown sprites
- **Fukua:** original knockdown sprites
- **Valentine:** red crosses on her hat, chest, knee pads and shuriken (sprites, palettes, character select, HUD portraits), story intro and ending, and all of her talking heads
- **Parasoul:** Black Egrets, original armbands, original face-down wakeup, story cutscenes, the soldier talking head
- **Beowulf:** the original wall intro (Mariel's Lab Zero logo, and Mike Z, Alex Ahad and Peter Bartholow back on her board), story cutscenes
- **Big Band**, **Double**, **Eliza**, **Painwheel** and **Ileum:** story art and cutscenes

**Voice and text**
- Cut voice lines: Peacock's "I've seen enough doujin to know where this is going.", Big Band's "You little in the middle, but you got much back." and Parasoul's "Take the shot, Juju."
- Original combo callouts ("BARELY LEGAL" is back)
- Mike Z's Soviet announcer *(optional)*

**Art**
- Art Gallery: 27 pictures and 26 thumbnails back to their originals
- Digital Art Compendium: 56 original images *(only if you have the free Compendium DLC)*

See [CHANGELOG.md](CHANGELOG.md) for when each restoration was added.

## Download
Get the latest version from **[Releases](../../releases/latest)** and pick **one**:

| Download | What it is |
|---|---|
| `AOTC-<version>-Standalone.zip` | The installer with the Ahad of the Curve logo |
| `AOTC-<version>-Standalone-nologo.zip` | The same installer without ASCII art of Filia's fat ASC. For use in polite company or running on tourney machines. |

## Install
1. Close Skullgirls.
2. Extract the ZIP anywhere (your Desktop is fine).
3. Double-click `AOTC.cmd` and choose **[1] Restore**.
4. Answer `Restore Mike-Z's Soviet Voice? Y/N`. Everything else is always restored.
5. Launch Skullgirls through Steam. The first launch takes longer while SkullLoader builds its cache.

**Undo:** run `AOTC.cmd` again and choose **[2] Re-censor**.

**Upgrading from an older AOTC:** close Skullgirls, run the **new** `AOTC.cmd`, choose **[2] Re-censor**, then **[1] Restore**. The status line tells you when an older version is installed.

**Coming from a Skullgirls Mod Manager version of AOTC (0.15 or older):** untick the AOTC mods and apply, or use **Restore originals**, in Skullgirls Mod Manager before installing. AOTC checks for this and stops if it finds leftovers.

## Requirements
- The Steam version of Skullgirls 2nd Encore, **3.7.20** (the November 11, 2026 patch), on Windows.
- The Digital Art Compendium DLC is optional. Without it, AOTC skips the Compendium images and restores everything else. If you add the DLC later, choose **[2] Re-censor** and then **[1] Restore**.

## Good to know
- AOTC loads through **SkullLoader** and adds only `mods\AOTC.lua`, `mods\AOTC\`, `CoreMessaging.dll` and some Compendium images. It records what it changed in `Restoration Backups\AOTC-Standalone`, so Re-censor undoes exactly that.
- SkullLoader is built for one Skullgirls version at a time. If Skullgirls updates, AOTC refuses to install rather than guess, and the status line tells you. Until AOTC is updated, run **[2] Re-censor** to get back to a working game.
- Run Re-censor before using Steam's **Verify integrity of game files**.
- If Re-censor says a file is in use, close Skullgirls (check Task Manager). If it still says so, restart your PC and run Re-censor again.
- The SkullLoader build AOTC ships also stops the game reaching its online news server, so the in-game news feed may stay empty while AOTC is installed.

## Credits
Shoutout to Skullgirls Community's Cut for SkullLoader and the archive verification bypass code I shamelessly stole from it <3. AOTC ships their official SkullLoader build.

Thanks to Anonnie04 for [Skullgirls Mod Manager](https://github.com/Anonnie04/skullgirls-mod-manager), which earlier AOTC versions supported.
