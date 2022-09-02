# D3StudioFork v4.2 by jester
## A heavily improved Diablo 3 (RoS/Eternal) editor based on the recently open-sourced [D3Studio](https://github.com/Tonic-Box/D3Studio) by TonicBox

## Downloads can be found under [Releases](https://github.com/god-jester/D3StudioFork/releases) 

## Exclusive Features

- **Every single GBID (7,206), Affix (7,479), and Rare Name string (60,661) in the game**
- Incredible performance: launches and loads saves in a fraction of the time of all other editors, with massively reduced RAM usage
- Instant responsiveness: tasks and threading implemented by @GoobyCorp
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
 	- With D3StudioFork, Soul Shards have always leveled up properly and unlocked new Hell Powers (affixes) when upgraded, just like the legit items
- Full support for displaying and editing the 8 missing follower item slots, every single item slot in the game is properly handled: 32 total new slots including generic follower slots and Scoundrel/Templar/Enchantress
- Changed "Max All Materials" to "99999999 Materials" so you can still pick up materials in-game
- Lots and lots of UI and quality-of-life improvements exclusive to this fork
### **<ins>PLEASE</ins> read the [extensive changelog in v4.0](https://github.com/god-jester/D3StudioFork/releases/tag/v4.0.0)** for full changes compared to D3Studio 3.5

<hr>

![image](https://i.imgur.com/jZ7cr4q.png)

![image](https://i.imgur.com/aWaxHNL.png)

<details>
  <summary>More screenshots</summary>
  
  ![image](https://i.imgur.com/LHBHCJX.png)

  ![image](https://i.imgur.com/kh3aRXu.png)

  ![image](https://i.imgur.com/s3xNnnp.png)
  
  https://user-images.githubusercontent.com/90997402/149216231-26232c89-eb1e-4837-a62c-bb3995de7af5.mp4
  
</details>
