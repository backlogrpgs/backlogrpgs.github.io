---
layout: post
title: "Eye of the Beholder - Let's play Mazes and Monsters"
date: 2022-03-07 03:02:00
categories: PC
tags: 1991 CRPG dungeon-crawler real-time fantasy dungeons-&-dragons MS-DOS
---

<a target="_blank" href="https://res.cloudinary.com/backlogrpgs/image/upload/v1646461753/eob1/png/eob1banner.png" title="Eye of the Beholder">
	<picture>
    <source srcset="https://res.cloudinary.com/backlogrpgs/image/upload/v1646461541/eob1/eob1banner.webp">
    <img src="" alt="https://res.cloudinary.com/backlogrpgs/image/upload/v1646461784/eob1/jpg/eob1banner.jpg"  style="width:100%;border:4px solid #7b7d7d;">
</picture></a>

Eye of the Beholder is a first-person dungeon crawler released in 1991 for MS-DOS. It was ported to the Amiga, the Sega CD and the SNES. The game uses the rules of Advanced Dungeons & Dragons 2nd Edition and was developed by Westwood Studios and published by TSR, the creators of the D&D before being acquired by Wizards of the Coast. As for Westwood Studios, besides creating many titles with the AD&D license, they are also the developers of Dune II and the creators of the Command and Conquer series. 

Part of a trilogy, Eye of the Beholder was followed by Eye of the Beholder II: The Legend of Darkmoon and Eye of the Beholder III: Assault on Myth Drannor (which wasn’t developed by Westwood Studios).
I played the GOG edition of the game. It comes with the Manual and a Clue Book, the former with 44 pages and the latter with 75. I miss the times when manuals had complementary content and good artwork, but I’m also glad that companion books aren’t required anymore because games became less cryptic.

<!--more-->

Besides these two books, the game should have come with a Data Sheet, since it’s the only place where you can find the keyboard commands. It seems the people at GOG thought players would only use their mouses. Fortunately, some kind users on the GOG forums [scanned it](https://www.gog.com/forum/forgotten_realms_collection/eye_of_the_beholder_data_card_and_sewer_maps)
 for our benefit.
<hr>

<h2>The Narrative</h2>

Taking place in the Forgotten Realms world, the game starts with a cool introduction that shows a group of adventures being recruited by Piergeiron, chief lord of the city of Waterdeep, to descend into the sewers beneath the city and destroy the source of evil that resides there, the beholder Xanathar.


After entering the dungeon, I thought there wouldn’t have any more plot development, but the game surprised me. There is a subplot about a group of dwarfs who wanted to reclaim the catacombs under the sewers, but after being ambushed by drows they need assistance to save their king and their prince. Nothing complex or that will cause important changes on the game. On the contrary, you can ignore the quest entirely or kill the prince.

Like many RPGs of the time, the plot isn’t the game’s strongest aspect. It’s more like a story hook than a full narrative, but it serves its purpose of catching the players’ attention and imagination.






<div class="video-responsive">
<iframe style="width:560; height=315; border: 4px solid #7b7d7d;" src="https://www.youtube-nocookie.com/embed/-6c8-rz-SkM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

<hr>

<h2>Presentation</h2>



The game looks very good, with colorful and well-made sprites and backgrounds. Enemies look great and are taken directly from the Monster Manual (I think it was called Monstrous Manual at the time). Unfortunately, they suffer from a severe lack of animation, with a few frames to depict idle and attack positions.

By the way, I love that party members have such silly faces that never fail to make me chuckle when I look at them.

 


As for music, besides at the opening scene, there is none in the game. That could create an unnerving sensation while exploring unknown corridors of a subterranean maze, but you would need more ambient sounds to evoke this feeling.

<h3>DOSBox</h3>

There is a large discussion about how DOS games should look like, the difficulties raised by playing in LCD screens, the size of pixels, resolution and many more elements that would need a write-up from a person with better technical understanding of the situation. While you may think the subject isn’t worth your time, you certainly can’t play games that look like this: 


<div class="row">
  <div class="column">
  <figure>
    <a target="_blank" href="https://res.cloudinary.com/backlogrpgs/image/upload/v1646584455/eob1/png/eob1gdb1.png" title="It’s horrendous and all out of proportions.">
	<picture>
    <source srcset="https://res.cloudinary.com/backlogrpgs/image/upload/v1646584832/eob1/eob1gdb1.webp">
    <img src="https://res.cloudinary.com/backlogrpgs/image/upload/v1646584618/eob1/jpg/eob1gdb1.jpg" alt="Shows the first screen of the game (a pile of rocks) with wrong proportions and aspect ratio." style="width:100%; border: 4px solid #7b7d7d;">
	</picture></a>
	<figcaption>GOG's untampered installation</figcaption>
	</figure>
	</div>
  <div class="column">
  <figure>
  <a target="_blank" href="https://res.cloudinary.com/backlogrpgs/image/upload/v1646584455/eob1/png/eob1gdb2.png" title="It still is horrendous and all out of proportions.">
  <picture>
    <source srcset="https://res.cloudinary.com/backlogrpgs/image/upload/v1646584832/eob1/eob1gdb2.webp">
    <img src="https://res.cloudinary.com/backlogrpgs/image/upload/v1646584617/eob1/jpg/eob1gdb2.jpg" alt="Shows a scene of the game (a fight against many kobolds) with wrong proportions and aspect ratio." style="width:100%; border: 4px solid #7b7d7d;">
	</picture></a>
	<figcaption>GOG's untampered installation</figcaption>
	</figure>
	</div>
</div>

This is how everything looks like after installing the game with GOG GALAXY. Nowadays their distributions come with a GUI to configure the resolution and aspect ratio, so you can use that. Or you could do better and use a more up-to-date official instance of DOSBox, or try one of its forks. I used DOSBox-X during part of my play through and I was very happy with the results. I choose it because it has the “pixel-perfect” output. I also turned on the option to “Fit to aspect ratio”. It produced infinitely better results. Because a specific problem I will explain later, I played most of the game with the [DOSBox-pixel-perfect](https://github.com/bladeSk/DOSBox-pixel-perfect) distribution. Aside the pixel-perfect output, there isn't anything special about this distribution, but it worked well enough.

<hr>
<h2>Mechanics</h2>

As an official AD&D product, Eye of the Beholder has the same rules of the pen and paper game. The manual does a good job explaining the mechanics, but they are only useful when creating a character, since the software does all the mathematics for you.

<h3>Character Creation</h3>

At the beginning you must create four characters. You choose their gender, race, class, then roll their attributes, and finally pick a portrait and a name. Interestingly, you can freely change the value of your stats without restrictions. It’s possible to maximize your party, start with random attributes, or even copy the character sheets from your RPG group. The last option would make more sense in 1991 than nowadays, but who knows.

<div class="adiv">
 <figure>
	<a target="_blank" href="https://res.cloudinary.com/backlogrpgs/image/upload/v1646514500/eob1/png/eob1ccs.png" title="Time to spend three hours thinking on a name">
    <picture>
    <source srcset="https://res.cloudinary.com/backlogrpgs/image/upload/v1646514619/eob1/eob1ccs.webp">
	<img src="https://res.cloudinary.com/backlogrpgs/image/upload/v1646514579/eob1/jpg/eob1ccs.jpg" alt="descrição alternativa" style="border: 4px solid #7b7d7d;">
	</picture></a>
	<figcaption>Roll the dices!</figcaption>
</figure>
</div>

Your party can have up to six members. Some will offer join you, others must be resurrected first (remember to pick up the skeletons you find along the way). Interestingly, you can ditch your original party in favor of the later recruits. I would advise against it, since none of them are better than your original characters.

After creating a party, you can finally start to explore the sewers of Waterdeep.

<h3>Exploration</h3>

Eye of the Beholder is a first-person dungeon crawler; therefore the gameplay consists of exploring the subterranean maze, killing enemies and acquiring new equipment and items. Initially I thought the game would become dull quickly, but the Waterdeep dungeon proved far more interesting than my early assumptions. It's composed of twelve floors, and except for a few, they have unique designs and foes. The maps are big, especially if you consider the game doesn’t have an automap function.

On the subterranean maze  you will find illusory walls, concealed switches, hidden passages, portals that don’t need special items to work, portals that need special items to work, and lots of closed doors. Something that’s a highlight and you don’t see that often on these old games is the possibility to open doors by forcing or by lock picking them. Your party will also face traps like pits, traps that throw darts, and traps that cast spells. Finally, if exploring and discovering secrets is your thing, each level has a hidden quest to be completed. 

Many walls have runes with messages to the player, some useful, some cryptic, and I bet that a few are useless. An interesting detail is that some of them can only be read if you have specific races on your party. 

<div class="row">
  <div class="column">
  <figure>
    <a target="_blank" href="https://res.cloudinary.com/backlogrpgs/image/upload/v1646522684/eob1/png/eob1ssc3.png" title="Level 4">
	<picture>
    <source srcset="https://res.cloudinary.com/backlogrpgs/image/upload/v1646522355/eob1/eob1ssc3.webp">
    <img src="https://res.cloudinary.com/backlogrpgs/image/upload/v1646522579/eob1/jpg/eob1ssc3.jpg" alt="The picture shows the dungeons's fourth level." style="width:100%; border: 4px solid #7b7d7d;">
	</picture></a>
	<figcaption>Level 4</figcaption>
	</figure>
	</div>
 
  <div class="column">
  <figure>  
	<a target="_blank" href="https://res.cloudinary.com/backlogrpgs/image/upload/v1646522683/eob1/png/eob1ssc1.png" title="Level 7">
	<picture>
    <source srcset="https://res.cloudinary.com/backlogrpgs/image/upload/v1646522354/eob1/eob1ssc1.webp">
    <img src="https://res.cloudinary.com/backlogrpgs/image/upload/v1646522579/eob1/jpg/eob1ssc1.jpg" alt="The picture shows the dungeons's seventh level." style="width:100%; border: 4px solid #7b7d7d;">
	</picture></a>
	<figcaption>Level 7</figcaption>
	</figure>
	</div>
</div>


<div class="row">
  <div class="column">
  <figure>
  <a target="_blank" href="https://res.cloudinary.com/backlogrpgs/image/upload/v1646522684/eob1/png/eob1ssc2.png" title="Level 9">
  <picture>
    <source srcset="https://res.cloudinary.com/backlogrpgs/image/upload/v1646522355/eob1/eob1ssc2.webp">
    <img src="https://res.cloudinary.com/backlogrpgs/image/upload/v1646522579/eob1/jpg/eob1ssc2.jpg" alt="The picture shows the dungeons's ninth level." style="width:100%; border: 4px solid #7b7d7d;">
	</picture></a>
	<figcaption>Level 9</figcaption>
	</figure>
	</div>
  	
  <div class="column">
  <figure>
  <a target="_blank" href="https://res.cloudinary.com/backlogrpgs/image/upload/v1646522684/eob1/png/eob1ssc4.png" title="Level 11">
  <picture>
    <source srcset="https://res.cloudinary.com/backlogrpgs/image/upload/v1646522355/eob1/eob1ssc4.webp">
    <img src="https://res.cloudinary.com/backlogrpgs/image/upload/v1646522579/eob1/jpg/eob1ssc4.jpg" alt="The picture shows the dungeons's eleventh level." style="width:100%; border: 4px solid #7b7d7d;">
	</picture></a>
	<figcaption>Level 11</figcaption>
	</figure>
	</div>
</div>


Lastly, while exploring your party will become hungry and their food bar will start to deplete. When it finally reaches zero, characters will lose 1 HP every 24 hours. They also won’t be able to memorize or pray for spells, so check this status regularly.

<h3>Automap</h3>

The game lacks an automap, so you will need to make your own maps like it’s 1980 or have the Clue book, which has the maps of all floors, the location of all items, secret quests and a few more tips. Or you could use the program “[The All-Seeing Eye](http://ase.zorbus.net)” (ASE), which is a great companion software. It will automap while you explore, showing items, enemies, secret walls, traps and tips for all floors. It also has a few other useful functions, like show you all the entire map, edit the party members, and more.

 <figure>
    <a target="_blank" href="https://res.cloudinary.com/backlogrpgs/image/upload/v1646462115/eob1/png/eob1ase.png" title="Best software ever!">
	<picture>
    <source srcset="https://res.cloudinary.com/backlogrpgs/image/upload/v1646462146/eob1/eob1ase.webp">
    <img src="https://res.cloudinary.com/backlogrpgs/image/upload/v1646462072/eob1/jpg/eob1ase.jpg" alt="Shows the game's main screen with the All-seeing eye software screen at its right." style="border: 4px solid #7b7d7d;">
	</picture></a>
	<figcaption>The All-Seeing Eye</figcaption>
</figure>


It’s a great program but I couldn’t make it work with DOSBox-X. I tried different configurations, I tried to replace the GOG DOSBox, all to no avail. So, I changed to DOSBox-pixel-perfect distribution and it worked flawlessly. I still prefer DOSBox-X tough.

<h3>Battle System</h3>

Battles happen in real time, so be prepared to strike any enemies as you see them and to be attacked at any moment. As your characters are positioned in rows, each containing two party members, their placement will limit their offensive options. Only the ones on the front row can attack with melee weapons, while those on the back rows can only attack with ranged weapons and spells.

<figure style="float:right;margin-left:10px;">
<a target="_blank" href="https://res.cloudinary.com/backlogrpgs/image/upload/v1646500477/eob1/eo1golem.gif" title="Golem punch!">
<img src="https://res.cloudinary.com/backlogrpgs/image/upload/v1646500477/eob1/eo1golem.gif" alt="GIF of an enemy golem punching." style="border: 4px solid #7b7d7d;"></a>
<figcaption>Golem punch!</figcaption></figure>

For each character, the game displays their name, portrait and current HP. It will also show their primary and secondary hands. There you can equip weapons, shields, potions, a spellbook or a holy symbol. You can also see their position on the party's formation. It’s possible to freely change that while exploring or fighting. It’s a useful feature when a front character gets paralyzed, is too damaged or dies.

Interestingly, the game doesn’t reset enemies after they disappear, neither they have a way to heal themselves. So, it’s possible to exchange a few blows against a monster, run away to recover, then come back to continue the fight without any negative repercussion. You can also keep your distance by attacking with spells or throwing weapons while stepping to the sides or back. Another nice strategy is to hit enemies from the side or from behind before they can react for some sneak damage. 

<figure style="float:right;margin-left:10px;">
    <a target="_blank" href="https://res.cloudinary.com/backlogrpgs/image/upload/v1646514015/eob1/png/eob1sc1.png" title="Damn trash bear!">
	<picture>
    <source srcset="https://res.cloudinary.com/backlogrpgs/image/upload/v1646513939/eob1/eob1sc1.webp">
    <img src="https://res.cloudinary.com/backlogrpgs/image/upload/v1646513971/eob1/jpg/eob1sc1.jpg" alt="The party is attacked by a kobold" style="border: 4px solid #7b7d7d;">
	</picture></a>
	<figcaption>A kobold attacks!</figcaption>
</figure>

Like on the pen and paper RPG, clerics must pray for spells and wizards need to memorize theirs. During my play through, I didn’t feel that I needed a mage in my party. They can be very useful, but it's not a class that you will miss out. But I was glad I had a cleric. Even if spells that recover HP aren’t essential to most battles, clerics can cure poisoning and paralysis. They can also create food, making rations unnecessary.

To attack you must right-click on the hand that you wish the character to use. If it has a weapon, the character will use it. If it has a spellbook or a holy symbol, a menu will open up so you can choose a spell. It seems fine early on, but as battles become longer, its repetitiveness will start to weigh on you.

Excluding enemies that cause negative statuses or that can one hit a character, most fights consists of you and your enemy hitting each other back and forth. There’s no strategy involved, what makes killing monsters a lot less satisfying. Another problem is that you must manage the actions of six characters in real time, without the option to automate a few of them, fighting enemies quickly becomes tiresome and boring. It’s possible to use the keyboard instead of the mouse, but I didn’t feel it was an improvement. 
Battles end up hectic when facing strong opponents, but not in a fun and rewarding manner. Everything becomes worse when enemies flank your party or hit you from behind without any warning.
<hr>

<h2>Final Thoughts</h2>

I found Eye of the Beholder more enjoyable than I initially thought it would be. I liked the exploration, the hidden secrets, and the uneasy feeling when your party descends into an unknown lower level. Having said that, the combat detracts from the experience, due to a cumbersome interface and awful flow. As that is an important aspect in a dungeon crawler, it’s hard to recommend this game. 

It’s an overall fun adventure, marred by its fights. Probably at the time it was a fun way to spend time between weekly D&D sessions. It’s also relatively short if you don’t make your own maps. So if you don’t mind the annoying combat and has a passion for dungeon crawlers, go get it. It’s available on GOG on their “Forgotten Realms: The Archives—Collection One” pack, alongside the other two Eye of the Beholder games.

**Final opinion:** Not recommend thanks to its combat. If you don’t find it too annoying, it’s a good game.