SpriteSheetComponent
====================

This component add spritesheet to game object.

.. warning:: This component use the TransformComponent and it can't work without it.

Editor
------

In the editor, you can change spritesheet by selecting json file but also the numbers of sprite and the current index of sprite.

Script
------

Variables
^^^^^^^^^

- game_object: Object which own this component (GameObject)
- engine: Utility class to control the game (Engine)
- sprite: Resource file. Will search in resources folder. (string)
- sprite_number: Number of sprite in width and height. (list of two integers)
- current_sprite: Index of current displayed sprite (integer)
- render: Final render. 

.. note:: Current_sprite start at 0.

.. warning:: You mustn't change render directly but use update_render function.

Functions
^^^^^^^^^

- update_render(): Update render of component