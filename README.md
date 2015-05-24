name: Pyromancer
frequency: 5000
default: false
healthperlevel: 0.5

manaBonus: 12
manaPerSecond: 1
manaPerLevel: 0.1
statmods:
  str: 1
  dex: 1
  int: 2
  wis: 1
  con: 1
  chr: 0

allowedRaces:
  - Chunel
  - Meroei
allowedGroups:
  - ANY

allowedArmour:
  - chainarmor
  - ironarmor
allowedWeapons:
  - STONE_SWORD
  - IRON_SWORD
allowedTools:
  - irontools
  - stonetools

skillPoints: 10
skillPointsPerLevel: 0.1

skills:
     weaponmaster:
        vars:
            skillname: StaffMaster
            chance: 90.5
            damag: 5
            weapons: "STICK"
 permskills:
    fireball:
        level: 5
        cost: 5
        cooldown: 30000
        command: /fireball
        perm: essentials.fireball
    
    
