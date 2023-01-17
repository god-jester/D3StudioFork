<h1 align="center">
	D3StudioFork v4 by jester
</h1>

<h2 align="center">
	Next generation Diablo 3 save editor (Reaper of Souls & Eternal Collection)
</h2>

<p align="center">
	This modding tool is for editing your items, gold, materials, gear, and stats for your Diablo 3 characters (heroes) and profile (account). Developed <ins>primarily for PS4 and Nintendo Switch for modding seasonal saves.</ins> Based on <a href="https://github.com/Tonic-Box/D3Studio-Source">D3Studio</a> by TonicBox. </p>

<h2 align="center">
	Downloads can be found on the <a href="https://github.com/god-jester/D3StudioFork/releases">Releases</a> page
</h2>

<p align="center">
	This is <ins>the most popular editor</ins> for creating and sharing D3 modded PS4 saves to download and resign, usually for people who bought Save Wizard. If you don't have Save Wizard or a jailbroken PS4 and would like YOUR PS4/PS5 save to be modded (keep your heroes), <ins>you may purchase on my Discord</ins> - or join just to chat! - by clicking below:
</p>

<p align="center">
	<a href="https://jester.dev/discord">
		<img src="https://discordapp.com/api/guilds/879421301054386186/widget.png?style=banner3" alt="Discord Banner">
	</a>
</p>

<h4 align="center">
	Currently updated for Season 27, with Season 28 planned when it releases soon in 2023!
</h4>

<hr>

<p align="center">
	<img src="https://user-images.githubusercontent.com/90997402/212484729-d9221506-84f0-4c6f-9853-af4f5e9d3867.png" alt="Main Screenshot"> 
</p>

<br>

## Exclusive features found only in this editor:
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

<p align="center">
	<img src="https://user-images.githubusercontent.com/90997402/212484629-e22ae8af-002c-420f-ad59-2fad40959bf9.png" alt="2023 Screenshot PS4"> 
</p>

<p align="center">
	<img src="https://user-images.githubusercontent.com/90997402/212484693-3e253b21-3cdf-41e3-93b0-127415c81700.png" alt="PS4 Screenshot 2023"> 
</p>

<p align="center">
	<img src="https://user-images.githubusercontent.com/90997402/212484700-56ef3242-e690-4df3-bac6-22b68cae73da.png" alt="D3Studio Screenshot D3StudioFork"> 
</p>

<p align="center">
	<img src="https://user-images.githubusercontent.com/90997402/212484711-13ba67fa-9682-47e3-bc47-30acbaedaa5c.png" alt="Character Screenshot Hero D3Studio"> 
</p>
	
<p align="center">
	This fork of D3Studio is the fastest and best D3 save/hero editing tool for <b>PS4 (Playstation 4), Nintendo Switch (including Yuzu), and PS5 (Playstation 5)</b> in 2023. This application was made for <b>Diablo III: Reaper of Souls (RoS) and Eternal Collection.</b> It will work with <b>Diablo 3 Vanilla for PS3 (Playstation 3) and Xbox 360,</b> but it is not ideal. 
</p>

<p align="center"> 
	D3StudioFork is also known as D3Studio Fork and D3 Studio Fork: a save modding tool based on D3Studio. It supercedes D3RoSEdit and DIIIROS.SaveEdit (DIII Save Editor) with more and better features. It will not work with Xbox One/Series X|S until a method is discovered to decrypt and edit game saves. Not compatible with the PC version of Diablo 3!
</p>
