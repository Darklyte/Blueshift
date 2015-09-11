
### TODO: 
* Fitness -> Immunity: grants immunity to impairment effects. This should mean slowing effects, lifting, etc.  not impairment penalty. 
* On 0 outcome, let the character chose "no progress" or "success at a cost"
* Create Archetypes
* Write descriptions for each species
* "You always have enough thermal clips unless you are in a dire situation
* Persistent damage does not take advantage of vulnerabilities unless the persistent damage type, itself, takes advantage of that vulnerability.


### Testing
* Melee Attacks: 1H weapons deal 1 damage with melee attacks.  2H weapons deal 2 damage. Melee-specific weapons have their own damage. A melee attack is a Melee/HalfSTR vs Fortitude. 
* Change name of Charisma to Willpower?

#################################
# Blue Shift v0.1.2015.09.....


#################################
# Blue Shift v0.1.2015.09.11

## Races
* Removed defense boosts from all races. It made a single defense too high when specialized and never compensated for anything.
* All potency bonuses changed to favor bonuses.

### Asari
* Removed passive biotic amp.  Added +2 force with biotic talents. 

### Human
* Training Focus: Changed from +1 potency to +1 outcome.

### Quarian

* Quarantine Suit: changed from 3 Shield resilience to +10 shields and +10 resilience.

## Talents
### Physical
* Overkill: Now reduces cost of first ranged weapon attack by 2 AP.
### Social
* Warp: Changed from 2 round duration to 1 round per outcome.
* Warp: Range reduced from 10 to 7
## Goods and Services
* Burden: Burden increases every 10 over capacity instead of 5.
* Impact Force: No longer deals damage and only pushes based on force-mass formula. Talents that use impact force will be given a damage type

### Armor
* Tech Armor: Changed to +20 shields. Can now be detonated to deal damage, stagger, and push opponents
* Barrer: Changed to +20 Barriers (This has the side effect of converting your shields into barriers). Can now be detonated to deal damage, push and lift enemies.

### Weapons
* Grenade: Damage, Area, and Range increased to 5. Cost increased to 500c
* Grenade: Grenades are now electromagnetically charged allowing them to adhere to surfaces shortly after thrown. This prevents them from just being thrown back.
* M-4 Shuriken: Given Sidearm property.
* Sidearm: Property defined. Weapons with the sidearm property can be drawn, holstered, or reloaded for 2 AP

## Combat
* Overwatch now explicitly states that you cannot take cover while it is active.
* Lots of status effects defined
* Reload changed from 6 AP to 4 AP
* Aim: Does not benefit against enemies within 3 spaces.
* M-23 Katana: Range reduced from 5 to 3.
* Take Cover: Reduced from 4 AP to 2 AP.

## Other stuff
* Default Mass reduced from 3 to 2.
** Tiny:   Mass 0

** Small:  Mass 1

** Medium: Mass 2

** Large:  Mass 3

** Huge:   Mass 4

** Omg:    Mass 5+

#################################
# Blue Shift v0.1.2015.08.14

## Races
### Human
#### Characeristics
* Adaptation: Humans now have emphasis when they use adaptation.
### Quarian
##### Characteristics
* Tech Specialist: Changed Omni-tools to Combat Tech.

## Talents

### Combat
#### Fitness
* Immunity: Immunity effectiveness decreased significantly.

#### Shotgun
* Inferno Grenade: Reduced cost from 6 AP to 4 AP.

###Mental
#### Electronics
* Sabotage: Changed from Effect to Hit.
* Sabotage: Duration changed from 2 rounds to 1 round per outcome.

#### Grenades
* Proximity Mine: Reduced cost from 6 AP to 4 AP.
* Proximity Mine: Changed triggering text.
* Arc Grenade: Reduced cost from 6 AP to 4 AP.

#### Security
* Defense Drone: Increased from 15 to 20 EP
#### Sniper Rifles
* Operative: 5 XP upgrade now specifies sniper rifle actions only.

### Social
#### Melee
* Heavy Strike: Target defense changed from Reflex to Fortitude


## Equipment
* Starting currency increased to 25,000 credits.
### Weapons
* M-3 Predator: Damage increased from 2 piercing to 4 piercing.
* Weapon Properties: Added Deadly Strike. Weapons with this property grant +3 outcome on critical strikes instead of +2 outcome.
* Weight reduction ratio, which determines the WCFDA conversion from "Weight units" to kilograms", increased from 6 to 10. This should decrease the weight of all weapons by about 33%.

* HP 					= 25 + 5*CON
* Energy 				= 25 + 5*INS 
* Energy Regen	= 5 ( + STR technically)