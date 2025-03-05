

``` mermaid
graph LR
Fighter --> Melee --> Swordsman
Swordsman --> Blademaster
Swordsman --> Samurai
Swordsman --> Knight
Swordsman --> Fencer --> Duelist 
Swordsman --> Swashbuckler --> Gladiator
Swordsman --> Ronin
Swordsman --> Legionnaire
Swordsman --> Valkyrie
Knight --> Noble --> Lord --> Heritage
Knight --> RylKnt(Royal Knight)
Knight --> GtrKnt(Gutter Knight)
Melee --> Defender --> Guardian --> Ironclad
Guardian --> RylGrd(Royal Guard) --> RylKnt(Royal Knight)
Guardian --> GrdSp(Guardian Spirit)
Melee --> Stealth
Stealth --> Ninja
Melee --> Pugilist --> MA(Martial Artist) --> Monk 
Monk --> DivP(Divine Palm)
Monk --> Drmk(Drunken Monk)
Monk --> MntSt(Mantis Style)
Monk --> TgrsSt(Tiger Style)
Monk --> MnkSt(Monkey Style)
Monk --> DrgSt(Dragon Style)
Monk --> CrnSt(Crane Style)
Monk --> IrnSt(Iron Stomach)
Pugilist --> Boxer
Melee --> Grappler
Melee --> HvyWpn(Heavy Weapon) --> Berserker 
HvyWpn(Heavy Weapon) --> Crusher
HvyWpn(Heavy Weapon) --> Shieldbreaker
HvyWpn(Heavy Weapon) --> Halberdier
Melee --> Mounted --> Cavalier --> Lancer --> Dragoon
Mounted --> MntAr(Mounted Archer)
Fighter --> Ranged
Ranged --> Archer
Archer --> MntAr(Mounted Archer)
Ranged --> Marksman
Ranged --> Gunner --> Gunslinger --> Cowboy
Gunner --> Cannoneer --> Artillerist
Fighter --> Soldier 
Soldier --> Deserter --> Mercernary
Soldier --> GrW(Gritty Warrior) --> Dauntless
Soldier --> Tactician --> SgSp(Siege Specialist)
Fighter --> Commander
Commander --> Tactician --> Warfare
Commander --> Captain 
Captain --> Admiral
Captain --> General
Fighter --> Hero --> Champion
Crafting --> Fletcher
Crafting --> Perfumer 
Crafting --> Brewer --> Alchemist
Brewer --> DM(Drunken Monk)
Brewer --> Beerbarian
Crafting --> Butcher --> Chef --> FF(Food Fighter) 
Healer --> Doctor
Doctor --> Surgeon
Doctor --> Plaguist
Doctor --> Apothecary --> Chemist
Worker --> Farmer
Farmer --> Herbalist 
Farmer --> Florist
Herbalist --> Apothecary
Herbalist --> Poisoner 
Worker --> Miner
Worker --> Fisherman
Worker --> Carpenter
Carpenter --> Builder 
Builder --> Architect
Worker --> Blacksmith
Blacksmith --> Armourer
Blacksmith --> Jeweller
Blacksmith --> Weaponsmith
Blacksmith --> Mechanic --> Artificer
Tinker --> Mechanic --> Inventor
Pedlar --> Salesperson --> Merchant --> Financier
Apprentice --> Accountant --> Financier 
Apprentice --> Cartographer
Apprentice --> Scribe --> Novelist
Scribe --> Archivist
Scholar --> Philosopher	
Scholar --> Archeologist
Scholar --> Mastermnd --> Genius
Scholar --> Advisor --> Mentor 
Envoy --> Colonist
Envoy --> Diplomat
Diplomat -->  Emissary
Diplomat --> Politician
Socialite --> Politician
Socialite --> Courtier
Socialite --> Dandy --> Debonaire
Jack-of-all-Trades --> Adept --> Pilot --> Aviator
Scribe --> Secretary 
Secretary --> CS(Civil Servant)
Service --> Secretary 
Service --> Maid
Service --> Butler
Service --> Househusband/Wife
Service --> Counsellor --> Advisor
Counsellor --> Courtesan
Counsellor --> Negotiator 
Service --> Connoisseur
Service --> Barber
Law --> Lawyer --> Magister --> Justicar --> Judge --> Marshal
Law --> Investigator --> Inquisitor
Investigator --> Detective
Law --> Watchman --> Bodyguard --> BP(Border Patrol)
Watchman --> Bailiff
Law --> Vigilane --> Enforcer
Slayer --> Avenger
Slayer --> GS(Giant Slayer)
Slayer --> DS(Dragon Slayer)
Slayer --> Executioner --> Hitman --> Assassin
Slayer --> IS(Insect Slayer) --> BS(Beast Slayer)
Slayer --> Undead
Slayer --> Plant
Slayer --> GodS(God Slayer)
Occultist --> FT(Fortune Teller)
Occultist --> Maou --> CB(Cursed Blade)
Maou --> Witchblade --> Veil-piercer
Maou --> Asura
BO(Blighted One) --> SlmO(Solemn One)
DE(Daemon Eater) --> Daemonhost --> Parasite
Nightmare --> Nightblade
Occultist --> Medium --> Exorcist
Art --> Dancer --> Skindancer	
Dancer --> Skydancer
Dancer --> Dervish
Dancer --> StrtP(Street Performer)
Art --> Acrobat --> Daredevil
Art --> Actor
Actor --> Jester
Art --> Musician
Art --> Painter
Art --> Poet
Musician --> Bard
Musician --> Diva
Musician --> Idol
Rogue --> MR(Mystic Rogue)
Rogue --> Spy --> Agent
Spy --> Infiltrator
Propagandist --> Agitator
Faithful --> Precant --> Zealot --> Apocalyptist
Faithful --> Ardent --> HW(Holy Warrior) --> WP(War Priest)
Oathkeeper --> HW(Holy Warrior) --> Templar --> Paladin
Faithful --> Acolyte --> Anointed --> Angel --> Archangel --> Ascendant
Ardent --> Preacher --> Bishop --> Cleric --> Saint
Preacher --> Priest --> Bishop --> Saint --> Oracle --> Prophet --> Sin-Eater
Faithful --> Demigod --> Godling --> Seraphim
Dawnstrider --> Enlightened
Pacifist --> Peacekeeper
Arcanist --> Necromancer
Necromancer --> BA(Blood Aspirant) --> Vampire
Necromancer --> SU(Specter User) --> Spiritcaller --> Soulbound
Arcanist --> Astrologer --> Astromancer --> StarChild --> Starlancer
Arcanist --> Chronomancer
Arcanist --> Sigilmancer --> Talismancer 
Arcanist --> Transformation --> Shapeshifter
Transformation --> Mimic
Transformation --> Shifter
Arcanist --> WF(Wand Fighter) --> MG(Magical Girl) 
Arcanist --> RM(Rune Master) --> RK(Rune Knight)
RM(Rune Master) -->  RunMd(Rune Maiden)
RM(Rune Master) --> RunSe(Rune Seer)
RM(Rune Master) --> RunSm(Rune Smith)
RunSm(Rune Smith) --> RunWr(Rune Wright)
Arcanist --> Psionics
Psionics --> Telekinetic --> Telepath
Telekinetic --> MdBrk(Mindbreaker)
Arcanist --> Puppeteer
Arcanist --> Elemental 
Elemental --> BlzMg(Blizzard Mage)
Elemental --> Aeromancer
Elemental --> Cryomancer
Elemental --> Electrokinetic
Elemental --> Firebrand
Elemental --> Geomancer
Elemental --> Hydromancer
Elemental --> Stormbringer
Elemental --> Pyroclast
Elemental --> Pyrokinetic
Elemental --> Pyromancer
Arcanist--> Dragon
Arcanist--> Abjurer
Arcanist--> Allomancer
Arcanist--> Mage --> Battlemage
Conjurer --> Invoker
Conjurer --> Summoner 
Summoner --> Puppetmaster
Summoner --> Homunculator
Enchanter --> Illusionist 
Scryer --> Seer --> Diviner
Ritualist --> Spellweaver
Spellweaver --> SpBnd(Spell Binder)
Spellweaver --> SpBrk(Spell Breaker)
Spellweaver --> SpSng(Spell Singer)
Spellweaver --> Hexer
Arcanist --> Shaman 
Sorcerer --> Shadowmancer --> Blackmage
Ruiner -->  Silencer
Sage --> Mystic
Druid
Outlander
Hermit
Beastmaster --> BugTamer
Nature --> Wanderer --> Courier --> Explorer
Wanderer --> Nomad 
Wanderer --> Hunter --> Scout
Nature --> Survivor --> Trapper
Nature --> Botanist
Survivor --> Ranger --> Tracker
Wanderer --> Adventurer
Underground --> Gambler
Underground --> Fugitive
Underground --> Criminal --> Thief
Criminal --> Counterfeiter
Thief --> PH(Phantom Thief)
Thief --> Outlaw
Underground --> Begger
Outlaw --> Bandit
Outlaw --> Highwayman
Thief --> Pirate
Pirate --> Corsair --> Marauder --> Reaver
Underground --> GR(Gutter Rat) --> CR(City Rat) --> StreetTough
GR(Gutter Rat) --> Scavenger
Thief --> Burglar
Scoundrel --> Trickster --> Beguiler
Scoundrel --> Vagabond
Corsair --> Smuggler
Saboteur --> Devastator
Sailor --> Boatman
Boatman --> Mariner
Mariner --> Drifter
Mariner --> SeaCa(Sea Captain)
Mariner --> DRWO(Drowned One)
Sailor --> ShpG(Ship's Gunner)
HrsR(Horse Rider) --> Coachman
Clockwork
Hero --> PsC(People's Champion) --> Liberator --> Frdfg(FreedomFighter)
 ```
 