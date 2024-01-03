# General

### ResourceMultiplier=1

This setting will multiply the output of every resource. For example if this is set to 10 and Ammonite Bile amount is set to 2, each time Ammonite Bile is generated it will create 20. Useful for server events.


### CostMultiplier=1

This setting will multiply the cost of every resource generator and bait. While this can be used in conjunction with the individual cost multipliers it is not recommended.


### NetEnabled=true

Set to false to disable the Fish Net


### MineEnabled=true

Set to false to disable the Geode Mine


### PumpEnabled=true

Set to false to disable the Oil Pump


### CompyTrapEnabled=true

Set to false to disable the Compy Trap


### OvusTrapEnabled=true
Set to false to disable the Ovus Trap

### NetRequireBait=true
Set to false to allow the Fish Net to work without bait. 

### CompyTrapRequireBait=true
Set to false to allow the Compy Trap to work without bait. 

### OvusTrapRequireBait=true
Set to false to allow the Ovus Trap to work without bait. 

### MineRequirePower=true
Set to false to allow the Geode Miner to work without power. 

### PumpRequirePower=true
Set to false to allow the Oil Pump to work without power.


# Fish Net

### NetTickTimeSeconds=30
The amount of time, in seconds, between resource generation for the Fish Net.

### NetBaitConsumptionChance=0.75
The chance that resource generation will consume bait. A value of 1 will always consume bait, whereas 0 will never consume bait. Setting to 0 with the require bait setting as true will require bait to be present, but wont consume it.

### NetCanProduceAll=true
Does the Fish Net have a chance to gather all resources with each tick (true) or only 1 type of resource (false)? If set to false, it will always generate clams, but can only generate either Ammonite Bile OR Leech Blood. By default, there is a chance for you to only get clams. 

### AmmoniteBileChance=0.2
The chance that resource generation will produce Ammonite Bile. 0-1

### AmmoniteBileAmount=2
How much bile will be generated per tick.

### LeechBloodChance=0.2
The chance that resource generation will produce Leech Blood. 0-1

### LeechBloodAmount=2
How much leech blood is generated per tick. 

### ClamChance=1
The chance that resource generation will produce clams. 0-1

### ClamAmount=1
How many clams are generated per tick. 

### NetCraftCostMultiplier=1
Control the amount of materials the Fish Net takes to craft. 


# Clams
The total chance for each item in this section should equal less than 1. Any remainder will automatically be applied to regular Fish Meat.

### RawFishAmount=30
How much Raw Fish can be in a clam.

### RawPrimeFishChance=0.2
The chance you will get Raw Prime Fish from a clam.

### RawPrimeFishAmount=15
How much Raw Prime Fish can be in a clam.

### PearlChance=0.2
The chance you will get Pearls from a clam.

### PearlAmount=20
How many Pearls that can be in a clam.

### BlackPearlChance=0.05
The chance you will get Black Pearls from a clam.

### BlackPearlAmount=5
How many Black Pearls that can be in a clam.


# Geode Miner
### MineTickTimeSeconds=30
The amount of time, in seconds, between resource generation for the Geode Miner.

### GeodeChance=1
The chance of getting a Geode each tick. 

### GeodeAmount=1
The number of Geodes generated each tick.

### MineCraftCostMultiplier=1
Control the amount of materials the Geode Miner takes to craft. 


# Geodes
The total chance for each item in this section should equal less than 1. Any remainder will automatically be applied to Stone.

### StoneAmount=100
How much Stone can be in a geode. 

### FlintChance=0.2
The chance you will get Flint from a geode. 

### FlintAmount=50
How much Flint can be in a geode.

### MetalChance=0.1
The chance you will get Metal from a geode.

### MetalAmount=20
How much Metal can be in a geode.

### CrystalChance=0.1
The chance you will get Crystal from a geode.

### CrystalAmount=10
How much Crystal can be in a geode.

### ObsidianChance=0.1
The chance you will get Obsidian from a geode.

### ObsidianAmount=10
How much Obsidian can be in a geode.


# Oil Pump
### PumpTickTimeSeconds=30
The amount of time, in seconds, between resource generation for the Oil Pump.

### OilAmount=5
How much Oil is generated per tick. 

### PumpCraftCostMultiplier=1
Control the amount of materials the Oil Pump takes to craft.


# Compy Trap
The total chance for each item in this section should equal less than 1. Any remainder will automatically be applied to regular Meat.

### CompyTrapTickTimeSeconds=30
The amount of time, in seconds, between resource generation for the Compy Trap.

### CompyBaitConsumptionChance=0.75
The chance that resource generation will consume bait. A value of 1 will always consume bait, whereas 0 will never consume bait. Setting to 0 with the require bait setting as true will require bait to be present, but wont consume it.

### CompyCanProduceAll=true
Does the Compy Trap have a chance to gather all resources with each tick (true) or only 1 type of resource (false)? If set to false, it will only generate 1 of the 3 resources possible per tick.

### RawMeatAmount=30
How much Raw Meat can be generated per tick.

### PrimeChance=0.3
The chance that Prime Meat will be generated. 

### PrimeAmount=10
How much Prime Meat can be generated per tick.

### HideChance=0.5
The chance that Hide will be generated.

### HideAmount=15
How much Hide can be generated per tick.

### CompyTrapCraftCostMultiplier=1
Control the amount of materials the Compy Trap takes to craft.


# Ovus Trap
### OvusTrapTickTimeSeconds=30
The amount of time, in seconds, between resource generation for the Ovus Trap.

### OvusBaitConsumptionChance=0.80
The chance that resource generation will consume bait. A value of 1 will always consume bait, whereas 0 will never consume bait. Setting to 0 with the require bait setting as true will require bait to be present, but wont consume it.

### OvusCanProduceAll=true
Does the Ovus Trap have a chance to gather all resources with each tick (true) or only 1 type of resource (false)? If set to false, it will only generate 1 of the 3 resources possible per tick.

### MuttonChance=0.8
The chance that Mutton will be generated.

### MuttonAmount=10
How much Mutton can be generated per tick.

### PeltChance=0.2
The chance that Pelt will be generated.

### Pelt Amount=20
How much Pelt can be generated per tick.

### Wool Chance=1
The chance that Wool will be generated.

### Wool Amount=10
How much Wool can be generated per tick.

### PeltAndWool=false
Can the Ovus Trap generate both Pelt and Wool? If false, only wool will be generated. 

### OvusTrapCraftCostMultiplier=1
Control the amount of materials the Ovus Trap takes to craft.


# Bait
### CompyBaitCraftAmount=25
How much Compy Bait you get from 1 craft.

### OvusBaitCraftAmount=25
How much Ovus Bait you get from 1 craft.

### FishBaitCraftAmount=15
How much Fish Bait you get from 1 craft.
