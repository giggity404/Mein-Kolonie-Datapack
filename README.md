### Mein-Kolonie-Datapack
A datapack integrating several mods from the [Mein-Kolonie Modpack](https://www.curseforge.com/minecraft/modpacks/mein-kolonie) with minecolonies

#### New Research:
  -Cutting board: adds cooking related Farmers Delight recipes they wouldn't otherwise be able to learn  
  -Cooking pot: adds many cooking pot recipes from Farmers Delight to lvl4 cook   
  -Neptune's Blessing: adds the Neptune's Bounty loot table from  aquaculture to the level 5 fisherman bonus loot table, costs a diamond fishing rod  
  -Swifty: allows enchanter to produce swift sneak enchantment, which is limited on the restricted map size [not yet implemented but [will be soon](https://github.com/ldtteam/minecolonies/pull/8929)]  
    
#### New custom Recipes   *(recipes that get taught automatically)* 
  -Most cooking board and cooking pot recipe, not all ingredient combinations are possible as the request system is confused by products with many different recipes. It will request the first version of the recipe in their list of crafting recipes. Their order can be changed with the arrows in the restaurant GUI. Check which versions are available from the JustEnoughItems interface  
  -Forester stripped log/wood recipes now produce tree bark  
    
#### New item tags   *( allow/prevents recipes being taught manually)* 
  -Adds rotten flesh to prepared leather recipe for fletcher, prepared leather-to-leather to smelter  
  -Adds smallships recipes to sawmill  
  -Adds tree bark & straw as ingredients to sawmill  
  -Adds organic compost recipes to farmer  
  -Adds iron based DecoraviteBlocks mod items to blacksmith  
  -Adds several Farmers Delight items to compostables list  
  -Prevents mostly fletcher & dyer from making recipes other workers already take care of  

#### New Loot tables
-Adds aquaculture neptunium loot table to bonus5 fisherman loot table, with Neptunes Bounty Research as a condition  
-Changes the enchanter loot table to the enchanting table mechanics, to easily include all modded enchantments, the enchanting level is adjusted for each enchanter level. A mending buff is added as it would be very rare without it. They are converted to single enchantments to overriding all enchantments after position [0] with an empty string. This may be changed to manually listing all enchantment and its weight at a later date.  

#### New Advancments
-Added hidden advancements for poor colony management, eg hitting your citizens  
-Added guard armor achievements, triggered by interacting with them when wearing it (full gold, full diamond, full netherite, full plate with netherite sword & shield, full neptunium)  
-Added raid loot advancement for scimitar, spear and spectre  
-Added location advancement for walking through a naturally gen abandoned colony
