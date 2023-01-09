<h1 align="center" style="margin-top: 0px;">
	D3StudioFork v4 by jester
</h1>

<h2 align="center" style="margin-top: 0px;">
  A modern Diablo 3 save editor (Reaper of Souls/Eternal Collection), based on <a href="https://github.com/Tonic-Box/D3Studio">D3Studio</a> by TonicBox
</h2>

<h3 align="center" style="margin-top: 0px;">
	Downloads can be found on the <a href="https://github.com/god-jester/D3StudioFork/releases">Releases</a> page
</h3>

<p align="center" style="margin-bottom: 20px;">
  <a href="https://jester.dev/discord">
    <img src="https://discordapp.com/api/guilds/879421301054386186/widget.png?style=banner3" alt="Discord Banner" align="center">
  </a>
</p>

<h3 align="center">
  This is a tool for editing your items, gear, and stats on your account and characters (heroes). Developed primarily for PS4 and Nintendo Switch for seasonal save modding!
</h3>

<hr>

<p align="center" width="100%">
	<img src="https://i.imgur.com/jZ7cr4q.png" alt="Main Screenshot"> 
</p>

<br>

## Exclusive features in this release
- **Every single GBID (7,206), Affix (7,479), and Rare Name string (60,661) in the game**
- Incredible performance: launches and loads saves in a fraction of the time of all other editors, with massively reduced RAM usage
- Instant responsiveness: tasks and threading implemented by GoobyCorp
	- When testing the database of 60k strings, another editor took 41 minutes to launch... but v4.2 launches instantly!
- Support for editing the **<ins>Sanctified</ins>** item flag, **which only works during Seasonal play**
	- Note that you can only have one Sanctified item equipped at a time
- Sanctified items are marked with a plus (+)
- Primal Ancient items are marked with an asterisk (*)
- Support for toggling every possible item flag in the game 
- Able to duplicate 1x, 10x, or 50x in one click instead of spamming the old button
- Able to paste Tier Quality to selected items, exactly like pasting a Rare Name to selected items
- You can edit `\db\CurrentSeason.txt` if there's a new season before a new editor release
- Developed for editing Switch/PS4 seasonal saves instead of Xbox 360/PS3 saves like other editors
	- This allows for my modern approach to truly unlock every transmog, legendary power, frame, pet, and wing set... including ALL SEASONAL PETS, and the Wanderer's Set + Ethereal transmogs with **one click**
	- Old-gen importing cannot affect seasons, so please use [D3StudioFast](https://github.com/god-jester/D3StudioFast/releases/latest) for 360/PS3 legacy methods
- Single executable file, with a total of 2 folders and about 16 files in the ZIP, for a total size of ~4.5MB - NOT cluttered with useless HUGE files like other editors
- All stashes forcibly increment the item position from 0-910 (max) for each item, this avoids situations where duping too many items in the editor wouldn't show up in the in-game stash. I ran into this issue with only 148 items in my stash!
- The Stash tab used to have items stuck in different slots when importing from the Locker or a Hero File, but now it will correctly force everything into your Stash
- Still the only editor to handle all the new data in S25 Soul Shards (which, along with Ethereals, can still be used in all seasonal play)
 	- If inserting/modifying legit items or opening a save with S25 Soul Shards, you can actually copy/paste/duplicate them without the constant errors from every other editor, and they will behave properly when leveled up in-game
 	- With D3Studio Fork, Soul Shards have always leveled up properly and unlocked new Hell Powers (affixes) when upgraded, just like the legit items
- Full support for displaying and editing the 8 missing follower item slots, every single item slot in the game is properly handled: 32 total new slots including generic follower slots and Scoundrel/Templar/Enchantress
- Changed "Max All Materials" to "99999999 Materials" so you can still pick up materials in-game
- **Everything is inside one EXE now**
- Added "Seasonal" checkbox next to the "Set 21 Dots/Max Stats" button that will instantly convert your character to and from current season
- Removed the (Seasonal) text from the Sex/HeroCore dropdown; each season seems to rotate the IDs, so it was unreliable
- Made all stashes forcibly and recursively change the item slot from 0-910 (max) for each item, this avoids situations where editing and duping too many items in the editor wouldn't show up in-game: I ran into this issue with only 148 items in my stash, now **fixed!**
- Fixed type conversion for item IDs to what the game expects: `unsigned long` - this fixes some rare arithmetic errors
- Fixed Blacksmith being set to level 56, correctly goes to 12 now
- Error messages are now more descriptive if there is an issue when launching, previously it would ALWAYS say "Fatal Error: Missing libraries"
- Added a "Max Positive Stats" button on Hero page next to "Set 21 Dots/Max Stats" for Paragon modding, with updated math to be as potent as possible
- Changed cosmetic images and icons, and they no longer stretch/distort. The new size of primary executable is ~4MB
- Changed colors and layout all around the whole tool, and if an item's prefix is "Jester's" it has a custom color!
- Lots and lots of improvements to the UI (e.g. layout improvements, fixed typos) and quality-of-life features (easier duplication, pasting rare names, etc.)


### **<ins>PLEASE</ins> read the [extensive changelog in v4.0](https://github.com/god-jester/D3StudioFork/releases/tag/v4.0.0)** for full changes compared to D3Studio 3.5

<hr>

<p align="center" width="100%">
	<img src="https://i.imgur.com/aWaxHNL.png"> 
</p>

<p align="center" width="100%">
	<img src="https://i.imgur.com/LHBHCJX.png"> 
</p>

<p align="center" width="100%">
	<img src="https://i.imgur.com/kh3aRXu.png"> 
</p>

<p align="center" width="100%">
	<img src="https://i.imgur.com/s3xNnnp.png"> 
</p>
