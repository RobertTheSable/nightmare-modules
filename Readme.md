# Nightmare Modules

Nightmare modules for Fire Emblem Monshou no Nazo (FE3) and Thracia 776 (FE5).

## FE3 Modules

Located in the fe3 subdirectory. These should be used with a headered ROM and have been tested with revision 1.0 roms.

### Chapter Sprite Editor

Changes what sprites are loaded into the temporary sprite slots in each chapter.

### Promotion Editor

Edits which classes promote into which other classes.

Merric's promotion to "Sage" is not affected by this.

### Item Locks

Edit which items/items groups can be used by different classes.

This just edits which items are enabled it the item menu - things like animations are not affected.

### Promotion Items

Various editors for checks related to promotion items.

#### Promotion Item Lock

Edits which classes can use which promotion items.

#### Dragon Whip/Knight Crest checks

Because Pegasus Knights and Cavaliers can dismount, the game needs to check a character's stored mounted class to determine if they can use a given promotion item.
These editors let you change which classes are checked for each and what behavior is used.
It's changing the operands of several CMP and BEQ instructions, which is why the offsets are weird.

### Shop Editors

Edit the contents of shops.

## FE5 Modules

Located in the fe5 subdirectory. These are meant to be used with an unheadered ROM. They have not been tested extensively so I am not sure which revisions they are compatible with.

### Animations.

Various modules that edit what battle sprites/animations are used for what classes. There is also an editor for battle sprite shields.

### Quotes Editors

Editors for associations for boss, death, and escape quotes.

### Weapon Triangle

Modules that let you adjust the properties of the weapon triangle. The Editor lets you edit what weapons have advantages over others, and the bonus editor changes the hit bonus.
