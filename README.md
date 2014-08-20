KVFilesBuilder
==============

**Small script that allows to split the Dota 2 KV files into smaller files to make them easier to read / manage**
It generates the KV files by combining together smaller txt files

Example:
--------
In my npc_abilities_custom.txt I have different kind of spells. Instead of having all of them in one big file
I can have "001_damage_spells.txt", "002_utility_spells.txt" and "003_misc_spells.txt".
The script will combine all the files into npc_abilities_custom.txt

How to use:
--------------
- Drop make_kv.py in your "dota_ugc/game/dota_addons/<your_addon>/scripts/npc/" folder
- Create a folder for each kv file you want to split (abilities, items or units)
- Add the subfiles in the folders. (Note: They will added in the final final in alphabetical order)
- Run "python build_kv.py <abilities/items/units/all>"

**Contaxt: tischeldota@gmail.com**
