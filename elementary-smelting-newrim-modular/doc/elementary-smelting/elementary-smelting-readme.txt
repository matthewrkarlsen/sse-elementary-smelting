Mod Name:
    Elementary Smelting

Version:
    0.9.3
    
Important Upgrade Note:
    Please ensure that any of the ESPs below that you cannot use or do not wish to
    use are unchecked.

Author:
    Matthew R. Karlsen (mattrk)

Nexus Mods files page:
    https://www.nexusmods.com/skyrim/users/3546091?tab=user+files

Mod Description:
    Provides reverse recipes for craftable metal items (i.e. enables you to smelt the 
    item back in to ingots). Provides the correct quantity of the most valuable ingot
    type (based on quantity x value). The mod depends upon PRUFEI (Protection for 
    Recipes Using Favorite and Equipped Items) in order to prevent smelting of favorite
    and equipped items.

Important version for end users:
    If you are using version 0.9.2 or earlier you do not need to upgrade and should not
    do so. The main reason for the 0.9.3 upgrade is to remove the dependency on the
    Unofficial Skyrim patches.

Dependencies:
    PRUFEI (if NOT using the all-in-one version)
    The Skyrim Script Extender (SKSE)
    
Installation:
    Install SKSE from https://skse.silverlock.org/ using Vortex or another mod manager
    Install PRUFEI (if NOT using the all-in-one version) using Vortex or another mod manager
    Install Elementary Smelting using Vortex or another mod manager

Optional ESP files (included in the all-in-one version):
    elementary-smelting-scale-recovery.esp    Allows breakdown of dragon scale-based armors
                                              (~50% scale recovery).

    elementary-smelting-dawnguard.esp         Allows breakdown of Dawnguard craftable items.
                                              Requires Dawnguard and the Unofficial Dawnguard Patch.

    elementary-smelting-dragonborn.esp        Allows breakdown of Dragonborn craftable items. Requires
                                              Dragonborn and the Unofficial Dragonborn Patch.

    elementary-smelting-hearthfire.esp        Allows breakdown of Hearthfire craftable items. Requires
                                              Dragonborn and the Unofficial Hearthfire Patch.

    elementary-smelting-leather-recovery.esp  Allows breakdown of leather armors. This recovers 50% of
                                              the total leather (leather and strips) in the form of
                                              leather strips.

    elementary-smelting-clutter-smelting.esp  Allows the breakdown of metal Skyrim clutter items (the
                                              number of ingots provided is based on the item weight).

    elementary-smelting-extended.esp          This modification extends Elementary Smelting to include
                                              items that are, by default, non-craftable (such as the 
                                              Imperial Bow).

Changes:
    0.5.1 -- Initial public release
    0.6.1 -- Added optional support for dragon scale-based armors, leather armor, Dawnguard 
               craftable equipement, Dragonborn craftable equipment, and Hearthfire smeltable items
               (the ESPs for these extensions need to be downloaded separately).
    0.7.1 -- Added support for the breakdown of Skyrim metal clutter items.
    0.7.2 -- Fixed Clothes Iron breakdown recipe.
    0.8.1 -- Added recipes for non-craftable items via the "Elementary Smelting Extended" ESP.
    0.9.1 -- Tweaked to prevent users being presented with an incomplete smelting menu whilst
               the favorite update script is running.
    0.9.2 -- Fixed a bug that prevented the last item of any type from being smelted.
    0.9.3 -- Steel Bolts now smelt to a steel ingot (not a dwarven metal ingot)
          -- Crossbows now smelt to 3 steel ingots (not 3 dwarven metal ingots)
          -- A Fur Boots breakdown recipe has been added
          -- A Fur Armor breakdown recipe has been added
          -- A Fur Helmet brekdown recipe has been added
          -- A Fur Bracers breakdown recipe has been added
          -- A Steel Nordic Gauntlets breakdown recipe has been added
          -- A Steel Imperial Gauntlets breakdown recipe has been added
          -- The Tanning Rack now blocks use while favorites are being updated

Credits:
    Created by Matthew R. Karlsen (mattrk)
    This mod would have been impossible without major assistance from 'mrpwn' and 
    'IsharaMeradin' on the PRUFEI mod. These mod authors are not responsible for
    any bugs that may remain). Thanks to InfamousNate for spotting the bug fixed
    in version 0.9.2.
        
Thanks:
    Bethesda, for creating the game and making it moddable.
    You, for downloading and trying this mod.

License:
    The .esp file contains data that belongs to the game's creators and is supplied under their
    particular license.
    The changes specific to this mod, made by the mod authors, are released under the license in 
    the license file.