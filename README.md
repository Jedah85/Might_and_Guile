<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html xmlns="http://www.w3.org/1999/xhtml" lang="en" xml:lang="en">
<head>
<title>Might & Guile</title>
<meta http-equiv="Content-Type" content="text/html; charset=iso-8859-1" />
<link rel="stylesheet" href="style/g3readme_cam.css" type="text/css" />
<link href="style/g3icon.ico" rel="icon" type="image/bmp" />
</head>
<body>
<h1>Might and Guile - a tweak mod and kit pack focusing on warriors and rogues</h1>
<div class="section">
  <p><strong>Author: <a href="http://forums.gibberlings3.net/index.php?showuser=6306">Duns Scotus, the SubtleDoctor</a><br />
    On the web: <a href="http://www.gibberlings3.net">Home page</a></strong> and <strong><a href="http://forums.gibberlings3.net/index.php?showtopic=26838">discussion forum</a></strong></p>
  <p><strong> Version 2.6 </strong><br />
    <strong> Languages:</strong> English<br />
    <strong>Platforms: </strong>Windows, Mac OS X</p>
</div>
<h2>Overview</h2>
<div class="section">
  <p>This mod is all about improving gameplay. While I love mods that bring the game closer to PnP, like Rogue Rebalancing and aTweaks, BG is a single-player computer game. If tweaking a rule makes this specific game more fun, then it's a good tweak, PnP be damned. Consider this mod as a collection of 'house rules' specific to the BG campaign. Every choice has been made with an eye to the particular gameplay mechanics of BG2 and the EEs.</p>
  <p>I call this a "post-hac tweak mod" because it is designed to be installed on top of - not instead of - all the other great mods out there.  I began with a BGT game with over 75 mods; they made the game great, but a few things still irked me, like druid shapechanges and the the archer's called shots and awkwardly fourth-wall-breaking weapon names. (<i>Holy sword +6? Really? That's a punchline, not a game feature.</i>) I made a bunch of little tweaks, then I learned Weidu for easy re-installation, and then I learned more.  Before I knew it I had 30 components altering many different aspects of the game.</p>
  <p><strong><u>Everything is completely optional.  You can use as many or as few of the mod components as you want.  None of them rely on each other, there is no 'core' component. Use what you like, ignore what you don't.</u></strong> </p>
</div>
<h2>Installation</h2>
<div class="section">
  <p><strong>Windows:</strong><br />
    The mod archive should be extracted into your game folder from the archive (or just unzipped and then copied there). If properly extracted, you should have a "might_and_guile" folder and "setup-might_and_guile.exe" in your game folder. To install, simply double-click "setup-might_and_guile.exe" and follow the instructions on screen.</p>
  <p>Run setup-might_and_guile.exe in your game folder to reinstall, uninstall or otherwise change components.</p>
  <p><strong>Mac OS X:</strong><br />
    This mod is packaged and installed with WeiDU. To install, simply extract the contents of the mod into your game folder. If properly extracted, you should have a folder called "might_and_guile," a file called "weidu," and the "Mac WeiDU Launcher" in your game directory. To install, simply double-click the WeiDU Launcher, choose "Might and Guile" from the list, and follow the instructions on screen.</p>
</div>
<h2>Compatibility</h2>
<div class="section">
  <p>Might and Guile is designed to work with any Infinity Engine game on a variant of the BG2 engine that someone might purchase and play today, in 2015. At the moment, that includes TOB, TuTu, BGT, BG:EE, BG2:EE, and IWD:EE.</p>
  <p>Might and Guile aims to be compatible with almost all other popular mods. There are however a few compatibility issues of note:<br />
  <ul>
  	<li>I have not tested compatibility with Kit Revisions. These two mods cover some of the same ground. Eventually (after KR is released, anyway) I will try to see if I can make them work well together. But for now, you should probably choose one or the other. (You may try to skip the M&G overhauls/tweaks and only install new kits... it should work, but there might be balance issues compared to the KR kits.)</li><br />
  	<li>Some of the components of <u>Rogue Rebalancing</u> modify the same resources as M&G; be aware that you might see some different behavior depending on which one is installed last.</li><br />
  </ul></p>
  <p>If you install lots of kit mods, keep in mind that without TobEx, the kit selection screen can only show 10 kits per class - the main class plus nine kits. If you install a lot of kits, some of the Might and Guile kits may not be visible. The vanilla game has 4 kits in each class, so you can install six kits without worries. Plan ahead, or else use the 'Mod Kit Remover' mod to clear space in the Character Generation screens before installing M&G.</p>
  <p>See the component descriptions below for more specific information about compatibility.</p>
  <p><strong>Load Order:</strong><br />
    Might and Guile should be installed <strong>after</strong> all other mods that add or change items or kits. It should be installed <strong>after</strong> the "WSPATCK for All" component of <u>tb#Tweaks</u>. It should be installed <strong>before</strong> <u>Refinements</u> and <u>Sword Coast Stratagems</u>.</p>
  <p>My load order looks something like this:
  <ul>
    <li> [item mods]</li>
    <li> [quest mods]</li>
    <li> [NPC mods]</li>
    <li> [spell mods]</li>
    <li> [kit mods]</li>
    <li> [tweak mods]</li>
    <li> BG2Tweaks</li>
    <li> Might and Guile</li>
    <li> Refinements HLAs</li>
    <li> SCS</li>
    <li> aTweaks</li>
  </ul>
</div>
<h2>Contents</h2>
  <h4 class="subheader">Component 400 (BETA - and only for EE 2.0+): </h4>
  <div class="section">
    <p><strong><em>Rogue Feats and HLAs</em></strong></p>
      <p> To reflect their cleverness and resourcefulness, thieves will be given the chance to learn feats as they progress in levels. They will begin the game with three feats (determined by kit) and then choose a new one every other level. <b>Note: this makes fundamental changes to all thief kits.</b> Most kit abilities (traps, poison, combat bonuses) are <b>removed</b> and turned into optional feats. The idea is, you will be able to choose feats to build something like the vanilla kits... but you can also build a character with different capabilities. It's up to you. (But on the other hand, there are still kits, and their choice of feats is somewhat restricted by what it appropriate for that kit.) Also note: every kit now begins the game with 30 skill points and gains 20 skill points per level.</p>
      <p><b>Also note:</b> when you use the "choose a feat" innate ability, do not take any other action (moving, fighting, spellcasting) until you have chosen a feat. If the list of feats disappears from the screen, you cannot get them back and will have to wait until you gain two more levels to choose another one.</p>
      <p><b>Also note:</b> technically, choosing a feat counts as casting a wizard spell. If you do it outdoors in Athkatla, the Cowled Wizards will teleport in and confront you. Unfortunately there is no workaround for this.</p>
      <p>This component includes a new kit: the Alchemist. This rogue is able to use knowledge of herbs and chemistry to brew powerful potions and create other psuedo-magical effects.</p>
      <p>The Rogue Feats include:
	  <ul>
	    <li> <b>Stealth Bonus:</b> this ability increase the rogue's Hide in Shadows and Move Silently skills by 10% each.</li>
	    <li> <b>Thieving Bonus:</b> this ability increase the rogue's Pick Pockets and Open Locks skills by 10% each.</li>
	    <li> <b>Detection Bonus:</b> this ability increase the rogue's Find Traps and Detect Illusions skills by 10% each.</li>
	    <li> <b>Dart Trap:</b> this ability sets a wide-area trap that does missile damage to anyone within 15 feet when it is triggered. Damage is 2d6, plus an additional 2d6 for each 6 levels of the trap-setter.</li>
	    <li> <b>Fire Trap:</b> this ability sets a trap that causes a fiery explosion when triggered. Damage is 2d8, plus an additional 2d8 for each 6 levels of the trap-setter. Victims may save vs Breath to take half damage and avoid being knocked back by the blast. (Hunter only - requires Dart Trap)</li>
	    <li> <b>Web Trap:</b> this ability sets a trap that, when triggered, covers an area with a 15 foot radius with sticky, gooey webbing. Victims must make a saving throw to avoid being held fast each round they stay in the area of effect. (Hunter only - requires Dart Trap)</li>
	    <li> <b>Basic Alchemy:</b> using foraged ingredients, this ability allows the rogue to craft one of the following potions once per day: Elixir of Health; Potion of Strength; Potion of Perception; Potion of Fire Resistance; Potion of Cold Resistance; or two Flaming Oils.</li>
	    <li> <b>Advanced Alchemy:</b> using foraged ingredients, this ability allows the rogue to craft one of the following potions once per day: toPion of Regeneration; Oil of Speed; Potion of Clarity; Potion of Mind Focusing; Potion of Invisibility; or Potion of Fiery Burning. (Alchemist only - requires taking Basic Alchemy twice)</li>
	    <li> <b>Hulking Transformation:</b> The Alchemist causes a permanent change in his or her physiology, becoming able to trigger a transformation into a powerful brute once per day. This ability comes at a cost, however, resulting in a permanent -1 penalty to the Alchemist's Strength and Constitution. (Alchemist only - requires taking Basic Alchemy twice)</li>
	    <li> <b>Flaming Weapon:</b> this ability allows the rogue to coat a weapon in a viscous and highly flammable oil. For 5 rounds, the weapon will do 1d4 fire damage in addition to normal damage. (Requires Brew Potions)</li>
	    <li> <b>Poison Weapon (Toxin):</b> this ability allows the Assassin to coat a weapon in a potent toxin. When it enters the bloodstream of a victim, they take immediate damage from the poison, and must save vs. Death to avoid taking more damage over the next several rounds. As the Assassin reached higher level, the amount and duration of the damage increase. The poison retains its potency for 5 rounds, and victims may only be affected once per round. (Assassin only)</li>
	    <li> <b>Poison Weapon (Paralytic):</b> this ability allows the Hunter to coat a weapon in a contact poison that causes both paralysis/shock and unconsciousness in victims. after being applied, its potency lasts for 5 rounds. (Hunter only)</li>
	    <li> <b>Armor Class Bonus:</b> this ability confers a permanent -1 bonus to Armor Class upon the rogue. (Swashbucklers may repeat this feat up to 4 times)</li>
	    <li> <b>Saving Throws Bonus:</b> this ability confers a permanent -1 bonus to all saving throws. (Requires AC Bonus)</li>
	    <li> <b>Contingency (Escape):</b> the rogue will be affected by the spell Remove Paralysis whenever Held, Webbed, or otherwise helpless. (Swashbuckler only - requires AC Bonus)</li>
	    <li> <b>To-Hit Bonus:</b> this ability confers a permanent +1 bonus to all attack rolls upon the rogue. (Swashbucklers may repeat this feat up to 4 times)</li>
	    <li> Backstab Bonus:</b> this ability increases the rogue's backstab multiplier by 1. (Assassins only may repeat this feat up to 2 times - requires To-Hit Bonus)</li></li>
	    <li> <b>Melee Trick (Trip):</b> upon using ability, which lasts two rounds and may be used once per combat encounter, successful melee attacks will knock the target to the ground upon a failed save vs. Breath. (Requires To-Hit Bonus)</li>
	    <li> Melee Trick (Disarm):</b> upon this ability, which lasts two rounds and may be used once per combat encounter, successful melee attacks will disarm to target and cause a -4 penalty to THAC0 upon a failed save vs. Breath. (Requires To-Hit Bonus)</li>
	    <li> <b>Melee Trick (Blind):</b> upon this ability, which lasts two rounds and may be used once per combat encounter, successful melee attacks interfere with the target's vision, causing a very brief period of Blindness upon a failed save vs. Rod/Staff. (Requires To-Hit Bonus)</li>
	    <li> <b>Melee Trick (Disrupt):</b> upon this ability, which lasts two rounds and may be used once per combat encounter, successful melee attacks interfere with the target's inner ear, resulting in Deafness and a 50% chance of spell failure for 2 rounds upon a failed save vs. Spells. (Requires To-Hit Bonus)</li>
	    <li> <b>Smoke Bomb + Grease Jar:</b> once per day, the rogue may attack enemies with a Grease Jar (which mimics the effects of the wizard spell Grease) and a Smoke Bomb (which mimics the effects of the wizard spell Stinking Cloud).</li>
	    <li> <b>Use Wands:</b> this ability allows the rogue to use wands normally restricted to wizards. (Requires Smoke Bomb/Grease Jar and Intelligence 15 or higher)</li>
	    <li> <b>Use Scrolls:</b> this ability allows the rogue to cast spells from scrolls, as if a wizard. (Requires Use Wands and Intelligence 17 or higher)</li>
	    <li> <b>Shadow Pool:</b> this allows the Shadowdancer to use one of the following five abilities: Sanctuary, Blur, Blindness, Shadow Door, or Shadowstep. (Shadowdancer only)</li>
	    <li> <b>Luck Bonus:</b> this ability confers a permanent +1 bonus to the rogue's Luck. (Trueclass or Swashbuckler only)</li>
	  </ul>
      <p> A note about backstabbing: the base tables are simplified: x2 at level 1, x3 at level 9, and x4 at level 18. Shadowdancers' multiplier is 1 lower than other thieves. And Swashbuckers' multiplier is always x1. BUT, any thief can take the 'Backstab Bonus' feat once to improve the multiplier (to x5 for most thieves, x4 for Shadowdancers, and x2 for Swashbucklers). And Assassins may take that feat up to three times, thus reaching a x7 multiplier.</p>
      <p> Additionally, this component will alter the rogue HLA tables. Since the Spike Trap and Fire Trap HLAs have been repurposed (and rebalanced) as low/mid-level feats, the rogue HLA tables will be quite shortened. To make up for this, the following changes will be made to Rogue HLA tables:
	  <ul>
	    <li> Time Trap becomes Maze Trap.</li>
	    <li> The Swashbuckler feat 'Contingency: Escape' wil be available to all thieves as an HLA.</li>
	    <li> The Shadowdancer feat 'Shadow Pool' will be available to all thieves as an HLA.</li>
	    <li> Instead of traps, Trueclass bards can choose Extra level 6 Spell, Contingency: Escape, and Power Attack.</li>
	    <li> Blades can choose Extra Level 6 Spell, Contingency: Escape, and Whirlwind.</li>
	    <li> Jesters can choose Extra Level 6 Spell, Contingency: Escape, and Shadow Pool.</li>
	    <li> Skalds can choose Power Attack, War Cry, and Hardiness.</li>
	  </ul>
      <p><b>Compatibility:</b> this component treads some of the same ground as Rogue Rebalancing component #2: "Thief Kit Revisions." Best not to use them together; choose whichever you prefer. Also, you should not use the Item Revisions component "Thieves Can Use Wands" - with this component, thieves using wands is a feat! (This will override the IR component if you do install both.) Please note that this component will only grant feats to the base five thief kits: thief, assassin, hunter, swashbuckler, and shadowdancer. Thief kits from other mods may be used alongside this component, but they will only get their normal kit abilities.</p>
  </div>
  <h4 class="subheader">Component 220: </h4>
  <div class="section">
    <p><strong><em>Revised Movement Bonuses ("Quickstride")</em></strong></p>
      <p> Barbarians' and Monks' movement bonus is changed from a permanent characteristic to an at-will innate ability called Quickstride. Now if they want to walk more slowly to keep the group together, they can do so.</p>
      <p> Rangers and Scouts (if installed, see component 420 below) get the Quickstride ability at 10th level.</p>
  </div>
  <h4 class="subheader">Component 225: </h4>
  <div class="section">
    <p><strong><em>Revised Stalkers</em></strong></p>
      <p> The Stalker loses its special wizard spells (install the Mage Hunter kit instead, see component 350 below), and can cast fewer spells per day than normal rangers. However they can set traps like a thief, and can attain greater proficiency than other rangers with daggers and short swords.</p>
      <p> ALL rangers can now backstab for x2 damage from stealth; Stalkers' backstab multiplier increases at higher levels.</p>
      <p><b>Compatibility:</b> warning, the changes to spell tables wrought by this component will not interact well with other mods that change rangers' spell tables (like Tweaks Anthology's "IWD Spell Tables for Rangers"). The exception to this is Faiths & Powers: the F&P ranger spell tables will be recognized by M&G. If you want rangers to have more and earlier spellcasting, we suggest installing F&P.</p>
  </div>
  <h4 class="subheader">Component 230: </h4>
  <div class="section">
    <p><strong><em>Revised Archers</em></strong></p>
    <p> Archers are switched to the Marksman schedule of bonuses and Called Shots.</p> 
    <div class="kit_description">
      <p>Advantages:<br />
        &ndash; +1 to hit and damage rolls with ranged weapon at levels 3, 6, 10, 15, and 21.<br />
        &ndash; Can achieve Grand Mastery (+++++) with bows and crossbows.<br />
        &ndash; May learn to use a Called Shot at levels 2, 4, 6, 9, 13, 17, and 21. Called Shots may be used at will, and the effects work for one round. The Archer has a +2 bonus to thac0 and damage while performing Called Shots, but must remain stationary during that time. The Archer may chose from among the following Called Shots:

CALLED SHOTS <br />
        &ndash; Trip Shot: aimed at the legs, this shot causes the target to fall down for one round upon a failed save vs. Breath.<br />
        &ndash; Pinning Shot: this shot pins the target's person or clothes to the ground; the target must remain stationary for two rounds upon a failed save vs. paralyzation.<br />
        &ndash; Tangling Shot: this shot causes the target to lose their footing and slowly recover, becoming Slowed for two rounds upon a failed save vs. Breath.<br />
        &ndash; Fumbling Shot: this shot knocks loose the targets grasp on a weapon, resulting in a -4 penalty to thac0 and reduced APR for one round, upon a failed save vs. Breath.<br />
        &ndash; Blinding Shot: aimed at the eyes, this shot causes the target to flinch and momentarily lose their vision, being Blinded for one round upon a failed save vs. Breath.<br />
        &ndash; Stunning Shot: aimed at the head, this shot causes the target to become dazed for 3 seconds upon a failed save vs. paralyzation.<br />
        &ndash; Hammer Shot: this shot strikes with unusual force, adding 2d3 crushing damage to the normal missile damage unless the target makes a successful save vs. Breath.</p>
      <p>Disadvantages:<br />
        &ndash; May only become proficient (+) with melee weapons.<br />
        &ndash; May only wear leather or similar armors.<br />.</p>
    </div>
    <p><b>Compatibility:</b> this component will conflict with other mods that alter the Archer kit, like the "Improved Archer" mod.</p>
  </div>
  <h4 class="subheader">Component 235: </h4>
  <div class="section">
    <p><strong><em>Revised Beastmasters</em></strong></p>
      <p> Beastmasters gain the ability to wield daggers, axes, and spears in addition to the normal group of weapons available to them.</p>
      <p> Beastmasters may also shapechange into wolf and werewolf forms, and may summon a Spirit Wolf to aid them in combat once per day.</p>
  </div>
  <h4 class="subheader">Component 250: </h4>
  <div class="section">
    <p><strong><em>Revised Berserker and Rage</em></strong></p>
      <p> Berserkers and Wizard Slayers are limited to Mastery (+++) in weapons. Berserkers are further limited to basic proficiency (+) in fighting styles. Berserk Rage and Barbarian Rage are merged, because 1) I don't know why there are two different kinds of Rage, and 2) vanilla Berserk Rage is more like a Mind Shield spell than an actual Rage. Rage now lasts for 30 seconds, provides a bonus 0.5 APR, increases STR and CON by 3, provides immunity to Charm/Hold/Stun/Confusion (but NOT level drain or Maze/Imprisonment), and penalizes AC by 2.</p>
  </div>
  <h4 class="subheader">Component 260: </h4>
  <div class="section">
    <p><strong><em>Revised Kensai</em></strong></p>
      <p>At character creation, Kensai will begin with an innate spell ability that will let them choose a weapon. Upon casting, they are changed to a sub-kit which can reach Grand Mastery (+++++) in that weapon, and can only be proficient (+) in others. After gaining enough levels to master their weapon of focus and a fighting style or two, the kensai will be able to choose a second weapon of focus. Thereafter, they will be able to choose a new weapon of focus after reaching Grand Mastery in their current one.</p>
      <p>Kensai thac0/damage bonuses become just damage bonuses, because they have great thac0 anyway. Their AC bonuses get better over time like a Swashbuckler's. Finally, kensai get a 0.5 bonus to APR right from 1st level, drastically increasing their offensive capabilities. The trade-off for this is having to truly devote themselves completely and permanently to their chosen weapon: kensai <b>cannot dual-class at all.</b> If you're into playing a kensage or a kenthief, this component is not for you. But I think it allows kensai to truly shine as a kit on its own.</p>
      <p>Finally, upon choosing a weapon focus, the Kensai will receive a weapon from the Candlekeep armory. In some instances (weaker weapons like staff, spear, dagger) it will be a +1 magical weapon.</p>
  </div>
  <h4 class="subheader">Component 265: </h4>
  <div class="section">
    <p><strong><em>Revised Monk Fists</em></strong></p>
      <p>Monk fists are are rebalanced to do less damage, but have higher APR.  The fists also become toggleable, able to switch at will between doing fatigue damage as a normal unenchanted fist, and crushing and magical damage as an enchanted fist.</p>
  </div>
  <h4 class="subheader">Component 270: </h4>
  <div class="section">
    <p><strong><em>Revised Bard Kits</em></strong></p>
      <p>This component replaces the Blade's Offensive Spin ability with a special Weapon Display "bard song" called the Blade Dance. This impressive and complicated set of weapon maneuvers causes opponents to hesitate when attacking. The Blade receives a 2-point AC bonus and nearby enemies suffer from -2 thac0 and -1 damage penalties. At levels 13 and 20 these effects increase, and opponents must save vs. spells or become Panicked.</p>
      <p>This component also improves the Skald's combat abilities, at the expense of reduced spellcasting.</p>
    <div class="kit_description">
      <p>SKALD: This nordic Bard is also a warrior of great strength, skill, and virtue; <PRO_HISHER> songs are inspiring sagas of battle and valor, and the Skald devotes <PRO_HISHER> life to those pursuits.</p>
      <p>Advantages:<br />
        &ndash; +1 bonus to hit at 1st level, and each 6 levels thereafter.<br />
        &ndash; - The Skald's Song is different from the typical Bard's and varies with level:<br />
 1st level: Grants allies a +2 bonus to hit and damage rolls, and a +2 bonus to AC.<br />
 15th level: Grants allies a +4 bonus to hit and damage rolls, a +4 bonus to AC, and immunity to fear.<br />
 20th level: Grants allies a +4 bonus to hit and damage rolls, a +4 bonus to AC, and immunity to fear, stun, and confusion. <br />
</p>
      <p>Disadvantages:<br />
        &ndash; May cast one fewer spell per level compared to most bards.<br />.</p>
    </div>
    <p><b>Compatibility:</b> this component will conflict with some of the changes in the 4th component of Rogue Rebalancing, "Bard Kit Revisions." If you install both, some of the RR stuff may be overridden by this mod. I think it should be okay to do so, however, which would give you M&G Blades and Skalds, and RR Jesters.</p>
  </div>
  <h4 class="subheader">Component 275: </h4>
  <div class="section">
    <p><strong><em>Revised Shadowdancer</em></strong></p>
      <p>This component removes Shadowdancers' "Hide in Plain Sight" ability. It also turns their "Shadowstep" ability into something called "Shadow Pool" which allows the Shadowdancer to cast any one of the following spells:<br />
        &ndash; Sanctuary<br />
        &ndash; Blur<br />
        &ndash; Blindness<br />
        &ndash; Shadow Door<br />
        &ndash; Shadowstep</p>
  </div>
  <h4 class="subheader">Component 310: </h4>
  <div class="section">
    <p><strong><em>Add the CORSAIR fighter kit</em></strong></p>
    <div class="kit_description">
      <p>CORSAIR: Part warrior, part rogue, part charming sailor, the Corsair is a dashing swordsman who survives by sharp wits and a sharper blade.</p>
      <p>Advantages:<br />
        &ndash; Can achieve Grand Mastery (5 stars) with light bladed weapons.<br />
        &ndash; Gains a bonus to Armor Class for every six levels gained.<br />
        &ndash; Can use use the skill Swashbuckling once per day for each five levels. While Swashbuckling, the character wheels and spins and parries, gaining an Armor Class of -1 per two levels, up to a maximum of -10.</p>
      <p>Disadvantages:<br />
        &ndash; Cannot become proficient with heavy weapons.<br />
        &ndash; May only achieve Mastery (+++) with ranged weapons.<br />
        &ndash; May not wear heavier armor than studded leather.<br />.</p>
    </div>
  </div>
  <h4 class="subheader">Component 320: </h4>
  <div class="section">
    <p><strong><em>Add the MARKSMAN fighter kit</em></strong></p>
    <div class="kit_description">
      <p>MARKSMAN: This soldier is the epitome of skill with ranged weapons. He can make almost any shot, no matter how difficult. To become so skilled, the Marksman has had to sacrifice some proficiency with melee weapons and armor.</p>
      <p>Advantages:<br />
        &ndash; +1 to hit and damage rolls with ranged weapon at levels 3, 6, 10, 15, and 21.<br />
        &ndash; Can achieve Grand Mastery (+++++) with bows and crossbows.<br />
        &ndash; May learn to use a Called Shot at levels 2, 4, 6, 9, 13, 17, and 21. Called Shots may be used at will, and the effects work for one round. The Marksman has a +2 bonus to thac0 and damage while performing Called Shots, but must remain stationary during that time. The Marksman may chose from among the following Called Shots:

CALLED SHOTS <br />
        &ndash; Trip Shot: aimed at the legs, this shot causes the target to fall down for one round upon a failed save vs. Breath.<br />
        &ndash; Pinning Shot: this shot pins the target's person or clothes to the ground; the target must remain stationary for two rounds upon a failed save vs. paralyzation.<br />
        &ndash; Tangling Shot: this shot causes the target to lose their footing and slowly recover, becoming Slowed for two rounds upon a failed save vs. Breath.<br />
        &ndash; Fumbling Shot: this shot knocks loose the targets grasp on a weapon, resulting in a -4 penalty to thac0 and reduced APR for one round, upon a failed save vs. Breath.<br />
        &ndash; Blinding Shot: aimed at the eyes, this shot causes the target to flinch and momentarily lose their vision, being Blinded for one round upon a failed save vs. Breath.<br />
        &ndash; Stunning Shot: aimed at the head, this shot causes the target to become dazed for 3 seconds upon a failed save vs. paralyzation.<br />
        &ndash; Hammer Shot: this shot strikes with unusual force, adding 2d3 crushing damage to the normal missile damage unless the target makes a successful save vs. Breath.</p>
      <p>Disadvantages:<br />
        &ndash; May only specialize (++) with melee weapons.<br />
        &ndash; May not wear heavier armor than splint mail.<br />.</p>
    </div>
  </div>
  <h4 class="subheader">Component 322: </h4>
  <div class="section">
    <p><strong><em>Add the ELVEN ARCHER ranger kit</em></strong></p>
    <div class="kit_description">
      <p>ELVEN ARCHER: The Elven Archer is the epitome of skill with the bow - the result of elves natural aptitude with bows as well as their single-minded dedication to training with the weapon. To become so skilled with the bow, the Archer has had to sacrifice some proficiency with melee weapons and armor.</p>
      <p>Advantages:<br />
        &ndash; +1 to hit and damage rolls with ranged weapon at levels 3, 6, 10, 15, and 21.<br />
        &ndash; Can achieve Grand Mastery (+++++) with bows.<br />
        &ndash; May learn to use a Called Shot at levels 1, 2, 4, 6, 9, 13, 17, and 21. Called Shots may be used at will, and the effects work for one round. The Marksman has a +2 bonus to thac0 and damage while performing Called Shots, but must remain stationary during that time. The Marksman may chose from among the following Called Shots:

CALLED SHOTS <br />
        &ndash; Pinning Shot: this shot pins the target's person or clothes to the ground; the target must remain stationary for two rounds upon a failed save vs. paralyzation.<br />
        &ndash; Fumbling Shot: this shot knocks loose the targets grasp on a weapon, resulting in a -4 penalty to thac0 and reduced APR for one round, upon a failed save vs. Breath.<br />
        &ndash; Blinding Shot: aimed at the eyes, this shot causes the target to flinch and momentarily lose their vision, being Blinded for one round upon a failed save vs. Breath.<br />
        &ndash; Stunning Shot: aimed at the head, this shot causes the target to become dazed for 3 seconds upon a failed save vs. paralyzation.<br />
        &ndash; Hammer Shot: this shot strikes with unusual force, adding 2d3 crushing damage to the normal missile damage unless the target makes a successful save vs. Breath.<br />
        &ndash; Entangling Shot: this shot Entangles the target (per the druid spell) for 12 seconds, and thorns will cause 1d4 piercing damage, unless the target makes a successful saving throw vs. paralyzation.<br />
        &ndash; Sleep Shot: this shot puts the target into a sluggish sleep for 12 seconds unless the target makes a successful saving throw vs. spells.<br />
        &ndash; Faerie Fire: this shot lights up the target with a white glow for 24 seconds, preventing invisibility and causing a -3 penalty to AC, unless the target makes a successful saving throw vs. spells.</p>
      <p>Disadvantages:<br />
        &ndash; May not wear any metal armor.<br />
        &ndash; May only become Proficient (+) with melee weapons.<br />.</p>
    </div>
  </div>
  <h4 class="subheader">Component 324: </h4>
  <div class="section">
    <p><strong><em>Add the HALFLING SLINGER kit</em></strong></p>
    <div class="kit_description">
      <p>HALFLING SLINGER: The Slinger is the epitome of skill with the sling - the result of halflings' natural aptitude with bows as well as their single-minded dedication to training with the weapon. To become so skilled with the sling, the Slinger has had to sacrifice some proficiency with melee weapons and armor.</p>
      <p>Advantages:<br />
        &ndash; +1 to hit and damage rolls with ranged weapon at levels 3, 6, 10, 15, and 21.<br />
        &ndash; Can achieve Grand Mastery (+++++) with slings.<br />
        &ndash; May learn to use a Called Shot at levels 2, 4, 6, 9, 13, 17, and 21. Called Shots may be used at will, and the effects work for one round. The Slinger has a +2 bonus to thac0 and damage while performing Called Shots, but must remain stationary during that time. The Slinger may chose from among the following Called Shots:

CALLED SHOTS <br />
        &ndash; Trip Shot: aimed at the legs, this shot causes the target to fall down for one round upon a failed save vs. Breath.<br />
        &ndash; Pinning Shot: this shot pins the target's person or clothes to the ground; the target must remain stationary for two rounds upon a failed save vs. paralyzation.<br />
        &ndash; Tangling Shot: this shot causes the target to lose their footing and slowly recover, becoming Slowed for two rounds upon a failed save vs. Breath.<br />
        &ndash; Fumbling Shot: this shot knocks loose the targets grasp on a weapon, resulting in a -4 penalty to thac0 and reduced APR for one round, upon a failed save vs. Breath.<br />
        &ndash; Blinding Shot: aimed at the eyes, this shot causes the target to flinch and momentarily lose their vision, being Blinded for one round upon a failed save vs. Breath.<br />
        &ndash; Stunning Shot: aimed at the head, this shot causes the target to become dazed for 3 seconds upon a failed save vs. paralyzation.<br />
        &ndash; Hammer Shot: this shot strikes with unusual force, adding 2d3 crushing damage to the normal missile damage unless the target makes a successful save vs. Breath.</p>
      <p>Disadvantages:<br />
        &ndash; May not wear any metal armor.<br />
        &ndash; May only become Proficient (+) with melee weapons.<br />
        &ndash; May not cast druid spells.<br />.</p>
    </div>
  </div>
  <h4 class="subheader">Component 350: </h4>
  <div class="section">
    <p><strong><em>Add the MAGE HUNTER ranger kit</em></strong></p>
    <div class="kit_description">
      <p>MAGE HUNTER: These rangers participate in demanding rituals with Avenger druids in order to gain access to magic abilities which help them in their campaign against any wizards who use their skills to defile nature.</p>
      <p>Advantages:<br />
        &ndash; Mage Hunters have a +1 bonus to all saving throws. This bonus increases by one for each five levels gained.<br />
        &ndash; Each successful melee hit bestows a 40% chance of spell failure on the target for one round.<br />
        &ndash; May use a special vocalization that can deafen anyone nearby and impose a 40% chance of spell failure on them if they fail a saving throw vs. Petrification.</p>
        &ndash; Can cast the following as 1st-level spells: Shocking Touch, Deafness.<br />
        &ndash; Can cast the following as 2nd-level spells: Remove Magic, Minor Spell Deflection.<br />
        &ndash; Can cast the following as 3rd-level spells: Breach, Non-Detection, Spell Thrust.</p>
      <p>Disadvantages:<br />
        &ndash; Suffers a -1 penalty to Strength and Constitution.<br />
        &ndash; May not use Charm Animal ability.<br />.</p>
    </div>
  </div>
  <h4 class="subheader">Component 360: </h4>
  <div class="section">
    <p><strong><em>Add the BARBARIAN RANGER kit</em></strong></p>
    <div class="kit_description">
      <p>BARBARIAN RANGER: Among barbarian tribes there are hunters of great skill. Spending many days alone in the wild, stalking their prey, they are closer to nature than most men. They are not quite as hardy as their more aggressive brethren, and tend to be loners. Yet they bring uncommon skills to bear both in providing for, and in defending, their tribe.</p>
      <p>Advantages:<br />
        &ndash; Can move 2 points faster than other characters.<br />
        &ndash; May enter an enraged state, enhancing combat abilities, once per day per six levels.<br />
        &ndash; May Charm animals once per day per five levels.<br />
        &ndash; Gains 5% physical damage resistance at 11th level, and again at 15th and 19th levels.</p>
      <p>Disadvantages:<br />
        &ndash; Cannot cast druid spells.<br />
        &ndash; -2 penalty to Charisma.<br />
        &ndash; May not wear armor heavier than studded leather or hide armor.<br />
        &ndash; May not dual-class.<br />.</p>
    </div>
  </div>
  <h4 class="subheader">Component 390 (BETA): </h4>
  <div class="section">
    <p><strong><em>Warrior Feats</em></strong></p>
      <p> To reflect their study of martial disciplines and techniques, single-class unkitted fighters and rangers will be able to choose from among 10 melee feats.  They include:
	  <ul>
	    <li> Parry: for the next 2 rounds, the warrior wil have a 4-point AC bonus, and APR will be 0.5. At 7th level and higher, the AC bonus will be 6 points and APR will be 1.</li>
	    <li> Flurry: for the next 2 rounds, the warrior will have a +1 APR bonus, but will suffer a 2-point penalty to THAC0 and AC.</li>
	    <li> Heroic Resistance: for the next 2 rounds, the warrior's physical resistances will be set to 50%, but will suffer a 50% penalty to movement rate.</li>
	    <li> Heroic Resolve: the warrior will be affected by the spell Remove Paralysis whenever Held, Webbed, or otherwise helpless. (Available to fighters at 10th level, and to rangers at 12th level.)</li>
	    <li> Heroic Willpower: for the next 3 rounds, the warrior has a +3 bonus to saves vs. Spells.</li>
	    <li> Knockdown: for the next 2 rounds, each successful melee attack will cause the target to save vs. Breath or be knocked to the ground for 3 seconds.</li>
	    <li> Knockback: for the next 2 rounds, each successful melee attack will cause the target ti save vs. Breath or be knocked 10 feet away from the warrior.</li>
	    <li> Cutting Blow: for the next 2 rounds, each successful melee attack will cause the target to save vs. Death or suffer a bleeding wound that does 1 point of slashing damage every 3 seconds, for 15 seconds.</li>
	    <li> Tempo: for the next 3 rounds, each successful melee attack will cause the target to suffer a 1-point AC penalty for 5 rounds.</li>
	    <li> Disrupt: for the next 2 rounds, each successful hit will cause a ringing in the ears of the target, similar to deafness and causing spellcasters to suffer a non-cumulative 50% chance of casting failure if they fail a save vs. Spells.</li>
	    <li> Tactics: the warrior develops the permanent ability to confer combat bonuses upon allies within earshot (20 feet). The warrior can switch back and forth between a +1 AC bonus and a +1 thac0 bonus, but cannot use both tactics at the same time, and the warrior himself does not benefit from the bonus.</li>	  </ul>
      <p> Fighters may choose a feat at 2nd, 4th, 7th, 10th, 13th, 16th, and 19th levels.  Rangers may choose a feat at 3rd, 6th, 12th, and 18th levels.</p>
      <p><b>Also note:</b> technically, choosing a feat counts as casting a wizard spell. If you do it outdoors in Athkatla, the Cowled Wizards will teleport in and confront you. Unfortunately there is no workaround for this.</p>
  </div>
  <h4 class="subheader">Component 410: </h4>
  <div class="section">
    <p><strong><em>Add the SNIPER thief kit</em></strong></p>
    <div class="kit_description">
      <p>SNIPER: Whether you need to hit a target with a poisoned arrow or shoot a rope to the windowsill of a noble's mansion for a burglary, the Sniper is a highly trained stealthy marskman who can get the job done.</p>
      <p>Advantages:<br />
        &ndash; +1 to hit and damage rolls with missiles weapon at levels 1, 3, 6, 10, 15, and 21.<br />
        &ndash; Can achieve Mastery (3 Points) with bows and crossbows<br />
        &ndash; May learn to use a Called Shot at levels 2, 4, 6, 9, 13, 17, and 21. Called Shots may be used at will, and the effects work for one round. The Sniper has a +2 bonus to thac0 and damage while performing Called Shots, but must remain stationary during that time. The Sniper may chose from among the following Called Shots:

CALLED SHOTS <br />
        &ndash; Trip Shot: aimed at the legs, this shot causes the target to fall down for one round upon a failed save vs. Breath.<br />
        &ndash; Pinning Shot: this shot pins the target's person or clothes to the ground; the target must remain stationary for two rounds upon a failed save vs. paralyzation.<br />
        &ndash; Tangling Shot: this shot causes the target to lose their footing and slowly recover, becoming Slowed for two rounds upon a failed save vs. Breath.<br />
        &ndash; Fumbling Shot: this shot knocks loose the targets grasp on a weapon, resulting in a -4 penalty to thac0 and reduced APR for one round, upon a failed save vs. Breath.<br />
        &ndash; Blinding Shot: aimed at the eyes, this shot causes the target to flinch and momentarily lose their vision, being Blinded for one round upon a failed save vs. Breath.<br />
        &ndash; Stunning Shot: aimed at the head, this shot causes the target to become dazed for 3 seconds upon a failed save vs. paralyzation.<br />
        &ndash; Hammer Shot: this shot strikes with unusual force, adding 2d3 crushing damage to the normal missile damage unless the target makes a successful save vs. Breath.</p>
      <p>Disadvantages:<br />
        &ndash; May only distribute 20 skill points per level among thieving skills.<br />
        &ndash; Reduced backstab multiplier.<br />.</p>
    </div>
  </div>
  <h4 class="subheader">Component 420: </h4>
  <div class="section">
    <p><strong><em>Add the SCOUT thief kit, and revise the Swashbuckler</em></strong></p>
      <p>This component splits the Swashbuckler in two: the Scout is good at combat and gets traps but no backstab (like the old swashbuckler), and the new Swashbuckler is good at combat and can backstab (somewhat) but cannot set traps.</p>
    <div class="kit_description">
      <p>SCOUT: While technically a member of the thief class, a scout does not burgle or murder. Scouts employ the dexterity and ingenuity of thieves for military purposes. They have skill in combat and with traps, but do not employ backstabs against enemies.</p>
      <p>Advantages:<br />
        &ndash; +1 bonus to Armor Class and thac0 at 1st level, plus an additional +1 bonus every 6 levels.<br />
        &ndash; May specialize (2 slots) in weapons.<br />
        &ndash; May specialize in Single-Weapon Style</p>
      <p>Disadvantages:<br />
        &ndash; May not backstab.<br />.</p>
    </div><br />
    <div class="kit_description">
      <p>SWASHBUCKLER: This rogue is part acrobat, part swordsman, and part wit: the epitome of charm and grace. Swashbucklers are seen by many as fops, and they generally make poor thieves. But their skill with blades is not to be underestimated; it usually gets them out of trouble when charm fails.</p>
      <p>Advantages:<br />
        &ndash; +1 bonus to Armor Class and thac0 at 1st level, plus an additional +1 bonus every 6 levels.<br />
        &ndash; May achieve Mastery (three slots) in light bladed weapons (long sword, scimitar, short sword, dagger, darts).<br />
        &ndash; Begins with one proficiency point in Single-Weapon Style, and may add one more.<br />
        &ndash; Begins with one proficiency point in Two-Weapon Style, and may add two more.<br />
        &ndash; Can use use the skill Swashbuckling once per day at level 1, 3, 6, 10, 15, and 21. While Swashbuckling, the character wheels and spins and parries, gaining an Armor Class of -1 per two levels, up to a maximum of -10. The character's movement rate is halved while swashbuckling.</p>
      <p>Disadvantages:<br />
        &ndash; May not use traps.<br />
        &ndash; May only distribute 15 skill points per level among thieving skills.<br />
        &ndash; The swashbuckler can backstab, but with a reduced multiplier.<br />
        &ndash; May not dual-class to fighter.<br />.</p>
    </div>
  </div>
  <h4 class="subheader">Component 450: </h4>
  <div class="section">
    <p><strong><em>Add the JONGLEUR bard kit</em></strong></p>
    <div class="kit_description">
      <p>JONGLEUR: These agile bards are master acrobats and jugglers. Their skill in flipping, vaulting and balancing is matched only by their accuracy with hurled knives and other implements.</p>
      <p>Advantages:<br />
        &ndash; +1 bonus to Armor Class at 1st level, plus an additional +1 bonus every 6 levels.<br />
        &ndash; May achieve Mastery (three slots) with daggers, darts, and two-weapon fighting.<br />
        &ndash; Begins with one proficiency point in Single-Weapon Style, and may add one more.<br />
        &ndash; Begins with one proficiency point in Two-Weapon Style, and may add two more.<br />
        &ndash; Instead of a traditional bard song, may perform the 'Dance of Illusion.' This complex dance spins a web of illusion around the Jongleur's allies. At 1st level, they are Blurred (+1 AC, +2 AC vs. missile weapons). At 13th level the AC bonuses double to -2/-4, and the Jongleur's allies are also protected by Reflected Images. At 20th level the AC bonuses triple to -3/-6 and the Jongleur's allies are protected by Mirror Images.
</p>
      <p>Disadvantages:<br />
        &ndash; May not become proficient in heavy weapons or in sword-and-shield style.<br />
        &ndash; Limited to light armors.<br />.</p>
    </div><br />
    </div>
   </div>
  <h4 class="subheader">Component 470: </h4>
  <div class="section">
    <p><strong><em>Add the GALLANT bard kit</em></strong></p>
    <div class="kit_description">
      <p>GALLANT: Part charming aesthete, part dashing warrior, gallants travel the land in search of beauty, love, and adventure. They steal the hearts of the young, and lift the spirits of the elderly. Their code, similar to a paladin's, requires that they defend the innocent and members of the opposite sex, and aid the needy in times of trouble and danger.</p>
      <p>Advantages:<br />
        &ndash; Gain a permanent +1 bonus to Luck.<br />
        &ndash; +1 bonus to thac0 every 6 levels.<br />
        &ndash; Essence of Purity: the Gallant clings to life with more ferocity than most, receiving +1 hit point per level for 12 levels, and receiving a +1 bonus to saves vs. death.  This saving throw bonus increases at levels 3, 6, 10, 15, and 21.<br />
        &ndash; From 7th level, may cast the priest spell Death Ward as an innate ability once per day.<br />
        &ndash; May use the innate ability "Heart of Valor" once per day, which functions like the priest spell Aid. From 9th level, this ability also Protects from Evil.</p>
      <p>Disadvantages:<br />
        &ndash; May cast one fewer spell per level compared to most bards.<br />
        &ndash; Bard song does not improve over time.<br />
        &ndash; No pickpocketing ability.<br />.</p>
    </div>
   </div>
  <h4 class="subheader">Component 460: </h4>
  <div class="section">
   <p><strong><em>Add the LOREMASTER bard kit</em></strong></p>
    <div class="kit_description">
      <p>LOREMASTER: Loremasters are romantically entranced by the past. There is a fine line between Loremaster and sage - so fine that many Lore masters call themselves sages and are rarely questioned about it. However, true sages are knowledge specialists who concentrate their efforts into mastering a specific field such as mushrooms, elven swords, and so on. Loremasters are fond of any aspect of history that makes a good story. Further, Loremasters are likely to go adventuring and exploring, playing the part of an archaeologist or anthropologist, to learn about the world first-hand instead of from dusty tomes.</p>
      <p>Advantages:<br />
        &ndash; Through their devoted study of the past, gain a fundamental understanding of many strange magical items not normally usable by the bard class. Thus, they can use any magical item.<br />
        &ndash; Loremasters' studies enhance their understanding of magic, such much that they cast spells as if they were one level higher.<br />
        &ndash; Loremasters may cast the Find Traps priest spell as an innate ability.</p>
      <p>Disadvantages:<br />
        &ndash; Bard song does not improve over time.<br />.</p>
    </div>
  </div>
  <h4 class="subheader">Component 480: </h4>
  <div class="section">
    <p><strong><em>Add the MEISTERSINGER bard kit</em></strong></p>
    <div class="kit_description">
      <p>MEISTERSINGER: These bards wander the woodlands, charming animals with their melodies and helping druids and rangers to protect nature. They are the enemies of ruthless hunters and trappers, striving against such activities with their animal allies, beguiling music, and nature-based magic.</p>
      <p>Advantages:<br />
        &ndash; May use the ranger's Animal Empathy ability.<br />
        &ndash; May use the 'Summon Rabbit' innate ability.<br />
        &ndash; Once per day, may summon a swarm of rodents to <PRO_HISHER> aid (3 a 1st level, and 3 more for every third level after that).<br />
        &ndash; May cast the following druid spells: Cure Light Wounds, Entangle, Sanctuary, Shillelagh, Barkskin, Charm Person/Mammal, Resist Fire/Cold, Slow Poison, Remove Paralysis, Cure Disease, Zone of Sweet Air, Summon Insects, Cure Serious Wounds, Call Woodland Being, Leser Restoration, Mass Cure, Chaotic Commands, Insect Plague, Animal Summoning III, and False Dawn.</p>
      <p>Disadvantages:<br />
        &ndash; May only gain proficiency in weapons appropriate for use by druids.<br />.</p>
    </div>
  </div>
  <h4 class="subheader">Component 490: </h4>
  <div class="section">
    <p><strong><em>Add the LORESINGER OF MILIL divine bard kit</em></strong></p>
    <div class="kit_description">
      <p>LORESINGER OF MILIL: Loresingers venerate Milil, god of poetry, song, and storytelling. More bard than priest, they volunteer their talents as cantors for churches. Loresingers may use a mix of divine and arcane magic, but may not turn undead like most priests.</p>
      <p>Advantages:<br />
        &ndash; May cast the following priest spells: Cure Light Wounds, Sanctuary, Find Traps, Silence 15' Radius, Spiritual Hammer, Cure Medium Wounds, Holy Smite, Death Ward, Holy Power, Greater Command, Cure Critical Wounds, and False Dawn.<br />
        &ndash; The Loresinger's song gives allies the effects of the Chant spell. From 5th level it has a chance to Slow any nearby undead. From 9th level, it also grants allies Protection from Evil. And from 13th level, the song has a chance to Hold nearby undead.</p>
      <p>Disadvantages:<br />
        &ndash; Reduced pickpocketing ability.<br />.</p>
    </div>
  </div>
  <h4 class="subheader">Component 500: </h4>
  <div class="section">
    <p><strong><em>Multiclass Kits</em></strong></p>
      <p>This component liberalizes the multiclassing rules in targeted ways:</p>
      <ul>
        <li> Enables humans to multiclass.</li>
        <li> Enables elves to be bards, fighter/clerics, cleric/thieves, cleric/rangers, and cleric/mages.</li>
        <li> Enables half-elves to be cleric/thieves.</li>
        <li> Enables dwarves to be cleric/thieves.</li>
        <li> Enables halflings to be fighter/clerics and cleric/thieves.</li>
      </ul>
      <p>This component also makes rangers unable to dual-class to cleric, unless they first find a special totem of the goddess Mielikki and use it to change their kit to a Woodscout of Mielikki.  Multiclass ranger/clerics will automatically begin as Woodscouts, except elves who begin as Forestwalkers of Solonor Thelandira. (Note, in IWDEE and BG2EE, these ranger/cleric changes will only take effect if baldur.ini is set such that cleric/rangers receive all druid spells.)</p>
      <p>Finally, this component introduces several multiclass kits to the game. If your game version is EE v2.0 or higher, these are available at character generation; in earlier versions of the games, you must use a totem or item to adopt the kit. The multiclass kits are:</p>
      <ul>
        <li> Elven Bladesinger - for elven fighter/mages.</li>
        <li> Spellfilcher - for mage/thieves.</li>
        <li> Ranger/mage - from mage/thieves.</li>
        <li> Spellbender - for cleric/mages.</li>
      </ul>
      <div class="kit_description">
        <p>ELVEN BLADESINGER: Among the Elven nations there is an order of warriors who wield power matched by few.  Combining martial skill with magical prowess, Bladesingers have the resources to face nearly any threat.  They master the use of long blades wielded in one hand, keeping the other free for spellcasting.</p>
        <p>Abilities:<br />
          &ndash; Bladesingers begin at level 1 with proficiency in Single-Weapon Style.  At level 7, this automatically increases to specialization.  They may reach grandmastery with long swords, scimitars, and katanas.<br />
          &ndash; Once per day per 6 levels, a bladesinger may perform the Bladesong, a dance in which <PRO_HESHE> whirls a blade faster than the eye can follow, blocking incoming attacks and devastating enemies.  Upon beginning the Bladesong, for 24 seconds, the bladesinger has a +1 bonus to thac0 per 5 levels, a -2 bonus to AC vs. melee attacks per five levels, one extra attack per round, faster movement rate, and all successful attacks do maximum damage.<br />
        <p>Restrictions:<br />
          &ndash; Bladesingers may only reach basic proficiency with other one-handed weapons and missile weapons.  They may not become proficient with two-handed weapons or in any other fighting style.<br />.</p>
      </div>
      <div class="kit_description">
        <p>SPELLFILCHER: The Spellfilchers are hidden society of very specialized thieves.  They hone their abilities toward a dangerous goal: stealing magic from wizards.  To that end, Spellfilchers have a few special tricks they can employ when confronted by angry mages.</p>
        <p>Abilities:<br />
          &ndash; Any target struck by a Spellfilcher in melee combat must save vs. rods/wands or suffer a 33% chance of miscast magic for 3 rounds.<br />
          &ndash; Spellfilchers may cast the priest spell "Silence 15' Radius" to prevent an enemy from casting spells.<br />
          &ndash; At 5th level, Spellfilchers may cast a special variant of "Spell Turning" which lasts for 12 hours.  It will only turn back a single spell.<br />
          &ndash; At 9th level Spellfilchers become innately and permanently protected by the effect of the spell "Non-detection."</p>
        <p>Restrictions:<br />
          &ndash; None<br />.</p>
      </div>
      <div class="kit_description">
        <p>RANGER/MAGE:  Yeah - ranger/mage.  (Hint, you have to start out as a thief/mage.  This component is EE-only!)</p>
        <p>Abilities:<br />
          &ndash; Bonuses to hit points and thac0 compared to thief/mages.<br />
          &ndash; Limited access to thief abilities: may only use Hide in Shadows, Move Silently, Find Traps, and Detect Illusions.<br />
          &ndash; May cast Goodberry innately, and has 3 druid spells each of levels 1-3 automatically added to the wizard spellbook.</p>
        <p>Restrictions:<br />
          &ndash; Limited to Good alignments.<br />.</p>
      </div>
      <div class="kit_description">
        <p>SPELLBENDER: Spellbenders make a science of mapping the ways to bypass Mystra's restrictions. Practicing as generalist clerics and studying arcane magery, they learn to manipulate the intersection of those two areas of magic. They may sacrifice a memorized wizard spell to instead create one of numerous divine effects; and they may sacrifice a memorized cleric spell to create an arcane effect. Some energy is lost in the translation - the improvisational effects must be spells of lower level than the one sacrificed. (It is unknown what happens to the lost energy - some believe this practice has contributed to the recent rise of wild magic and sorcerers. Spellbenders must be wary, as they are apt to be persecuted by Mystra's Monitors.)</p>
        <p>Abilities:<br />
          &ndash; Spellbenders receive the "Arcane Weaving" priest spells of levels 2-7, which allow them to cast wizard spells of one level lower.<br />
          &ndash; Spellbenders receive the "Divine Weaving" wizard spells of levels 2-7, which allow them to cast wizard spells of one level lower.<br />.</p>
      </div>
  </div>
</div>
<h2>Contact Information</h2>
<div class="section">
  <p>This mod was created by SubtleDoctor. You can visit <a href="http://forums.gibberlings3.net/index.php">The
    Gibberlings Three</a> for information on this and many other fine mods.</p>
</div>
<h2>Thanks and Acknowledgements</h2>
<div class="section">
  <p>Huge thanks in particular to Smeagolheart, Crevsdaak, kjeron, Camdawg, Mike1072, kreso, Grammarsalad and The Imp for advice and help with the code. And to everyone participating in the Dev thread at forum.baldursgate.com, for helping to sort through my good and bad ideas and helping me get the best ones implemented. </p>
  <p>Special thanks to Galactygon, Demivrgvs, and Pecca for directly contributing mod resources (the Beastheart of Malar's Beast Claw ability, the Nightrunner of Mask's Summon Shadow ability, and the various Magic Bolt cantrip projectiles, respectively). </p>
  <p>Special thanks to DreamSlaveOne at G3 for contributing .BAM files for the mage's Cantrip ability, druids' Shapeshift: Lion ability, the innate Spell Sequencers, and the Spellbender's special abilities.</p>
  <p>Thanks to the still active and vibrant Infinity Engine modding community. </p>
  <p><strong>Tools Used in Creation</strong><br />
    <a href="http://www.weidu.org/"><acronym title="Weimer Dialogue Utility">WeiDU</acronym></a> by
    Wes Weimer, and then the bigg and then Wisp<br />
    <a href="http://www.idi.ntnu.no/~joh/ni/">Near Infinity</a> by Jon Olav Hauglid, and then Argent77 and Astrobryguy<br />
    <a href="http://iesdp.gibberlings3.net/"><acronym title="Infinity Engine Structures Description Project">IESDP</acronym></a> maintained by igi</p>
</div>
<h2>Credits and Copyright Information</h2>
<div class="section">
  <p>Copyright 2015-2016. If you want to use or adapt any part of this mod in another mod or similar endeavor, please try to contact me at forums.gibberlings3.net or forums.beamdog.com to discuss it. As a general rule, I have no problem with that as long as you credit the source of the work. If you cannot get in touch with me, assume that you have my permission to use any of this code for any project that is non-commercial, offered for free, and intended for the greater enjoyment of players of Infinity Engine games. You may NOT use this code for any profit-making or commercial venture, without express permission from me.</p>
</div>
<h2>Version History</h2>
<div class="section">
  <p><strong>Version 2.6 - June 2016</strong></p>
  <ul>
    <li>added tactician stances to warrior feats</li>
    <li>added the Alchemist kit (installs with the Rogue Feats)</li>
    <li>new icons for all feats</li>
    <li>some bug fixes (as always)</li>
  </ul>
  <p><strong>Version 2.5 - May 2016</strong></p>
  <ul>
    <li>changed Called Shots over to a feat system</li>
    <li>added Rogue Feats & HLAs!!</li>
  </ul>
  <p><strong>Version 2.4 - April 2016</strong></p>
  <ul>
    <li>SoD compatibility</li>
    <li>improved Bladesinger</li>
  </ul>
  <p><strong>Version 2.3.2 - April 2016</strong></p>
  <ul>
    <li>warrior feats!!</li>
  </ul>
  <p><strong>Version 2.3.1 - April 2016</strong></p>
  <ul>
    <li>beastmaster fixes, ranger/mage fixes, readme fixes</li>
  </ul>
  <p><strong>Version 2.3 - April 2016</strong></p>
  <ul>
    <li>Ranger/mage!!!</li>
  </ul>
  <p><strong>Version 2.1 to 2.2 - ???</strong></p>
  <ul>
    <li>I need to be better about updating this...</li>
    <li>I think this was basically, EET compatibility and EE 2.0 compatibility</li>
  </ul>
  <p><strong>Version 2.0 - December 2015</strong></p>
  <ul>
    <li>major re-write</li>
    <li>the overhauls and basic game/rule tweaks are moved back to Scales of Balance v5</li>
    <li>revised rangers expanded and split up into modular components</li>
  </ul>
  <p><strong>Version 1.6 - December 2015</strong></p>
  <ul>
    <li>IWO IWD stuff</li>
    <li>fix for the Beastmaster spirit summon on the pre-EE engine</li>
  </ul>
  <p><strong>Version 1.5 - November 2015</strong></p>
  <ul>
    <li>at-will called shots</li>
    <li>increased light/heavy weapon differences in IWO</li>
    <li>beastmaster spirit summons</li>
    <li>altered hit dice revisions</li>
  </ul>
  <p><strong>Version 1.4 - November 2015</strong></p>
  <ul>
    <li>fixed marksman and barb ranger usability</li>
    <li>added light/heavy weapons to IWO</li>
    <li>archer/slinger proficiency changes</li>
    <li>added support for F&P kits and sphere system</li>
  </ul>
  <p><strong>Version 1.3 - October 2015</strong></p>
  <ul>
    <li>fixed corsair and marksman installation</li>
    <li>fixed elven archer proficiencies</li>
    <li>fixed monitor's casting level bonuses</li>
    <li>added "revised shadowdancer" component</li>
  </ul>
  <p><strong>Version 1.2 - October 2015</strong></p>
  <ul>
    <li>werewolf shapeshifting for beastmasters</li>
  </ul>
  <p><strong>Version 1.1 - September 2015</strong></p>
  <ul>
    <li>fixed proficiency limits for mod clerics and rogues in the WPO</li>
  </ul>
  <p><strong>Version 1.0 - September 2015</strong></p>
  <ul>
    <li>first version, from the ashes of Scales of Balance</li>
  </ul>
</div>
</body>
</html>
