# cataclysmWuxia
Add Wuxia elements to the Cataclysm

# How it works
Some categories have branches depending on if you choose Orthodox, Unorthodox, or Demonic. Other are universal
Weapon categories require you to be wielding an appropriate weapon to cast
Some spells can transform into new spells after reaching certain thresholds/conditons
After achieving mastery, you reach an optional end game condition.

# Orthodox
## Sword
Huashan Themed (Plum Blossom)
	Upgrade condition:
		Meditate with sword next to a plum tree
	Counter stance for a single attack
		Can't move or manually attack, but can counterattack
	Multi cut technique
		Lower damage, causes bleeding
	Dash to opponent and do aoe damage
	Hit all enemies in front of you
## Staff
Beggar Themed
	Upgrade condition:
		Meditate with staff
	Line with aoe attack
	Hit everyone around you with aoe (chance of down)
	Pull an enemy close
	Multi hit single target
## Palm
Shaolin Themed
	Upgrade condition:
		Meditate unarmed
	Counter stance for x amount of time
		Can't move or manually attack, but can counterattack
	Push enemy
	Down an opponent -> Paralyze an opponent
## Medicinal Arts
Divine Doctor
	Upgrade condition:
		Meditate while injured
	Recipies to restore qi, temporary positive effects
	Abilities to stop negative effects
## Formations
Formation Master
	Upgrade condition:
		TODO: Figure this out!
	Put traps on ground

# Unorthodox
## Sword
Assassination Themed
	Upgrade condition:
		Meditate with sword at night
## Axe
Includes hooked weapons
Forest/Mountain bandit Themed
	Upgrade condition:
		Meditate with axe next to tree, OR chopping a tree down with an axe
## Fist
Drunken Fist Themed
	Upgrade condition:
		Meditate unarmed while drunk
## Poison Arts
Abilities to spread aoe poison
	Upgrade condition:
		Meditate while poisoned
Recipies to give permanent bonuses
	But includes a small drawback
		Ex: Immune to poison, weaker in the cold
## Hidden Weapons
Gives recipes to create powerful weapons, probably based off of charges
	Bombs, hidden needles, bolas etc
	Upgrade condition:
		TODO: Figure this out

# Demonic
Focuses 
## Sword
Blood Swordsman
	Upgrade condition:
		Meditate with sword next to blood
	Uses player's blood as an additional resource, can be avoided if near blood
	Create a sword out of blood
	Can shoot blades of blood
	Can shoot knives of blood
## Spear
Includes polearms
Fallen monk
	Upgrade condition:
		Meditate with spear next to blood
Uses player's blood as an additional resource, can be avoided if near blood
	Line with no aoe
	Hit everyone in front of you
	Single target hit
	Push an enemy a short distance away
## Finger
Stab with finger
	Upgrade condition:
		Meditate while unarmed next to blood
Shoot blood beam
## Gu Arts
Abilities for single target debuffs
	Upgrade condition:
		TODO: Figure this out, holding insect eggs?
Recipies to give permanent bonuses
	But includes a large drawback
## Jiangshi
Gives recipies to create a jiangshi from a corpse
	Upgrade condition:
		Meditate next to fresh human corpse
Gives recipies to upgrade a jiangshi
Gives spells to manipulate the jiangshi
	Healing, stat bonuses, pulling towards player character, etc

# Universal
## Body Tempering
Gives recipies that make you damage yourself, with small chance of getting a permenant bonus
Once you get a bonus, you lose that recipe, and unlock the recipe for the next tier
Recipies become more and more complex as time goes on
## Qinggong
Only one qinggong effect can be applied at a time
The effect is lost when
	The player ends the effect (casting the spell again)
	The player casts a spell that gives a different qinggong effect (as you can only have one qinggong effect at a time)
	The player crouches/goes prone/gets knocked down/is winded/ etc
	The player runs out of qi (the effects have a continous qi drain)
Have a super fast one tile dash
	Have its cost increase each time it is cast in a row
		Look into u_spellcasting_adjustment, and creating an effect with increasing intensity to tie into this

# Meditate
Meditating restores qi over time
Meditating has a chance to restore a small amount of health to a random body part. The body part must not be broken.
Most unlocking is done through the meditate recipe.
If you are wielding a corresponding weapon you have a chance of unlocking skills related to that weapon
	Ex: While holding a staff, with Orthodox staff unlocked, and meditating you have a small chance of unlocking a new staff skill. 
Other categories may have different or additional conditions, like being near blood, cutting trees, etc
