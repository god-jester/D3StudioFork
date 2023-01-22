<h1>D3Studio{Fork}</h1>
<p>Save editor for Diablo 3 Reaper of Souls and Eternal Collection, made for PS4 & Nintendo Switch. Mod your character/account items, gold, materials, gear, and stats</p>
<hr>
</div>
<h2 align="center">
  D3StudioFork v4 by jester
</h2>
<br>
<h3>
  Next generation Diablo 3 save editor (Reaper of Souls &amp; Eternal Collection)
</h3>
<p>
  This modding tool is for editing your items, gold, materials, gear, and stats for your Diablo 3 characters (heroes) and profile (account). Developed <ins>primarily for PS4 and Nintendo Switch for modding seasonal saves.</ins> Based on <a href="https://github.com/Tonic-Box/D3Studio-Source">D3Studio</a> by TonicBox.
</p>
<h3>
  Downloads and release notes can be found on the <a href="https://github.com/god-jester/D3StudioFork/releases">Releases</a> page
</h3>
<p>
  This is <ins>the most popular editor</ins> for creating and sharing D3 modded PS4 saves to download and resign, usually for people who bought Save Wizard. If you don't have Save Wizard or a jailbroken PS4 and would like YOUR PS4/PS5 save to be modded (and keep your heroes!), <ins>you may purchase on my Discord</ins> - or join just to chat! Click below:
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
  <img src="https://diablo.jester.dev/D3StudioFork/assets/images/D3SF-About.png" alt="Main Screenshot"> 
</p>
<br>
<h3 id="exclusive-features">Exclusive features found only in this editor:</h3>
<ul>
  <li><strong>Every single GBID (7,206), Affix (7,479), and Rare Name string (60,679) in the game</strong></li>
  <li>Incredible performance: launches and loads saves in a fraction of the time of all other editors, with massively reduced RAM usage</li>
  <li>Instant responsiveness: tasks and threading implemented by GoobyCorp
    <ul>
      <li>When testing the database of 60k strings, another editor took 41 minutes to launch… but v4.2 launches instantly!</li>
    </ul>
  </li>
  <li>Support for editing the <strong><ins>Sanctified</ins></strong> item flag, <strong>which only works during Seasonal play</strong>
    <ul>
      <li>Note that you can only have one Sanctified item equipped at a time</li>
    </ul>
  </li>
  <li>Sanctified items are marked with a plus (+)</li>
  <li>Primal Ancient items are marked with an asterisk (*)</li>
  <li>Support for toggling every possible item flag in the game</li>
  <li>Able to duplicate 1x, 10x, or 50x in one click instead of spamming the old button</li>
  <li>Able to paste Tier Quality to selected items, exactly like pasting a Rare Name to selected items</li>
  <li>You can edit <code class="language-plaintext highlighter-rouge">\db\CurrentSeason.txt</code> if there’s a new season before a new editor release</li>
  <li>Developed for editing Switch/PS4 seasonal saves instead of Xbox 360/PS3 saves like other editors
    <ul>
      <li>This allows for my modern approach to truly unlock every transmog, legendary power, frame, pet, and wing set… including ALL SEASONAL PETS, and the Wanderer’s Set + Ethereal transmogs with <strong>one click</strong></li>
      <li>Old-gen importing cannot affect seasons, so please use <a href="https://github.com/god-jester/D3StudioFast/releases/latest">D3StudioFast</a> for 360/PS3 legacy methods</li>
    </ul>
  </li>
  <li>Single executable file, with a total of 2 folders and about 16 files in the ZIP, for a total size of ~4.5MB - NOT cluttered with useless HUGE files like other editors</li>
  <li>All stashes forcibly increment the item position from 0-910 (max) for each item, this avoids situations where duping too many items in the editor wouldn’t show up in the in-game stash. I ran into this issue with only 148 items in my stash!</li>
  <li>The Stash tab used to have items stuck in different slots when importing from the Locker or a Hero File, but now it will correctly force everything into your Stash</li>
  <li>Still the only editor to handle all the new data in S25 Soul Shards (which, along with Ethereals, can still be used in all seasonal play)
    <ul>
      <li>If inserting/modifying legit items or opening a save with S25 Soul Shards, you can actually copy/paste/duplicate them without the constant errors from every other editor, and they will behave properly when leveled up in-game</li>
      <li>With D3Studio Fork, Soul Shards have always leveled up properly and unlocked new Hell Powers (affixes) when upgraded, just like the legit items</li>
    </ul>
  </li>
  <li>Full support for displaying and editing the 8 missing follower item slots, every single item slot in the game is properly handled: 32 total new slots including generic follower slots and Scoundrel/Templar/Enchantress</li>
  <li>Changed “Max All Materials” to “99999999 Materials” so you can still pick up materials in-game</li>
  <li><strong>Everything is inside one EXE now</strong></li>
  <li>Added “Seasonal” checkbox next to the “Set 21 Dots/Max Stats” button that will instantly convert your character to and from current season</li>
  <li>Removed the (Seasonal) text from the Sex/HeroCore dropdown; each season seems to rotate the IDs, so it was unreliable</li>
  <li>Made all stashes forcibly and recursively change the item slot from 0-910 (max) for each item, this avoids situations where editing and duping too many items in the editor wouldn’t show up in-game: I ran into this issue with only 148 items in my stash, now <strong>fixed!</strong></li>
  <li>Fixed type conversion for item IDs to what the game expects: <code class="language-plaintext highlighter-rouge">unsigned long</code> - this fixes some rare arithmetic errors</li>
  <li>Fixed Blacksmith being set to level 56, correctly goes to 12 now</li>
  <li>Error messages are now more descriptive if there is an issue when launching, previously it would ALWAYS say “Fatal Error: Missing libraries”</li>
  <li>Added a “Max Positive Stats” button on Hero page next to “Set 21 Dots/Max Stats” for Paragon modding, with updated math to be as potent as possible</li>
  <li>Changed cosmetic images and icons, and they no longer stretch/distort. The new size of primary executable is ~4MB</li>
  <li>Changed colors and layout all around the whole tool, and if an item’s prefix is “Jester’s” it has a custom color!</li>
  <li>Lots and lots of improvements to the UI (e.g. layout improvements, fixed typos) and quality-of-life features (easier duplication, pasting rare names, etc.)</li>
</ul>
<h3 align="center">
  <b><ins>PLEASE</ins> read the <a href="https://github.com/god-jester/D3StudioFork/releases/tag/v4.0.0">extensive v4.0 notes</a></b> for full changes compared to D3Studio 3.5
</h3>
<hr>
<p align="center">
  <img src="https://diablo.jester.dev/D3StudioFork/assets/images/D3SF-Item-Flags.png?v=4.3"> 
</p>
<p align="center">
  This fork of D3Studio is the fastest and best D3 save/hero editing tool for <b>PS4 (Playstation 4), Nintendo Switch (including Yuzu), and PS5 (Playstation 5)</b> in 2023. This application was made for <b>Diablo III: Reaper of Souls (RoS) and Eternal Collection.</b> It will work with <b>Diablo 3 Vanilla for PS3 (Playstation 3) and Xbox 360,</b> but it is not ideal. 
</p>
<p align="center"> 
  D3StudioFork is also known as D3Studio Fork and D3 Studio Fork: a save modding tool based on D3Studio. It supercedes D3RoSEdit and DIIIROS.SaveEdit (DIII Save Editor) with more and better features. It will not work with Xbox One/Series X|S until a method is discovered to decrypt and edit game saves. Not compatible with the PC version of Diablo 3!
</p>
