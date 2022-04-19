# ContentLib-Recipes
Repo for Custom Recipes for ContentLib

The main config is for base game modding. You'll still need to follow the correct folder structure as outlined in the ContentLib wiki, with recipes/schematics/etc put in their respective subfolders.

The [ModName]\ContentLib\... is a modding setup necessary to change recipes of modded items (with the recipe change for the mod that adds said recipe)
in the example I have, it changes the Modular Load Balancer mod, which adds 3 different types of buildings (regular, filtered, and overflow).
For some reason I had issues with the filtered version, hence the redundant recipe (as well as using both folder structures)
You wouldn't need multiple recipes, nor multiple folders, to get things to work, it's there as a redundancy and I haven't taken the time to remove the redundnat/pointless extra recipes :P

As far as finding building/item names, there is an extensive repo for vanilla recipes. You can use ContentInspector for modded items, or just open up the mod's .pak file in UModel, where you can drill down to the recipes subfolder "open" the recipe, and it will give you the full name for the item
