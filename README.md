# oh-foundry

FoundryVTT system for the Outer Heaven ttrpg system

# Currently implemented

A single actor type which is able to :

-   Allow for the edition of base actor data. (Such as health, power, speed, saves and number of actions...)
-   Contain items types (which they can add, edit and remove from the sheet)
-   Show an item summary in chat
-   Show a summary of the unit's defenses in chat
-   Use weapon items and have their attack roll and damage roll displayed in chat. Apply damage to units or target specific units to have their range penalties automatically calculated.
-   Damage takes into account armor properly.
-   Tally up a total point cost from all the items of the actor
-   Settings for compendiums and critical damage behavior
-   Use effects for buffs and such. (Pretty barebones)
-   All items types can have embeded effects that apply to the actor.
-   Side/Team initative instead of individual token initiative
-   Weapons should have an option to be reloaded to full, which would display a chat template.

A number of item types :

-   Equipment, Ability and Skill types, which are quite simple.
-   Weapons, which have the ability to be used to shoot from the actor sheet.
-   Armors, which may provide a number of defenses then displayed on the actor sheet.

# Features I would like to implement

-   Items other than weapons can be 'used' (charges and power consumption)
-   Checkmark on tokens when they are set to "Done" in the initiative tracker + button on their right click menu to set them as "Done".
-   Sheet buttons (such as Show Defenses / Fire Weapon) can be dragged to the macro bar and make a macro.
-   A few measurement Templates
-   Add a heat generation stat to items which, when used, would increase the actor's Heat value.
-   Add an actor heat dissipation stat which would reduce the actor's current heat value on the start of his turn.
-   Damage over Time effects that trigger on turn start.
-   Token-Action-HUD module integration (https://github.com/LDMonay/token-action-hud-oh)
-   An actor or item type used to handle the newly made campaign system (Mostly a simple record sheet, with a few functionalities allowing for passing a week and calculating expenses.)
-   Vehicle actors that can contain other actors...
