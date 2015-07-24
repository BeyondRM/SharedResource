  This module is for storing a sample "Open RPG Maker" project's XML files, for examination and analysis.

  The data paths in an ORM project are:

    %root%/
        attributes/
        battleanimations/
        characters/
        charactersprites/
        classes/
        commonevents/
        conditions/
        fonts/
        globalanimations/
        images/
            animations/
            backgrounds/
            battlecharacters/
            faces/
            fonts/
            icons/
            monsters/
            sprites/
            system/
            tiles/
        items/
        layouts/
        maps/
        monsteranimations/
        monstergroups/
        monsters/
        music/
        skills/
        sounds/
            ambient/
            battle/
            misc/
        terrain/
        tilesets/
        vehicles/

  Two paths have sub-folders (images, sounds) that are for the binary resources; they are for what they say. The others
are for the XML files which define the respective game content. It seems the ORM model is based off of "keep the images
and sound separate from XML", which makes the folder structure a little more complex than necessary.

  A few aspects of ORM are not completed, so their XML files are not represented yet; the database tabs "Common Events"
and "Monster Groups" will remain empty until he [Justin "tuxinator" Davis] actually creates them.