SpriteComponent
===============

This component add sprite to game object.

.. warning:: This component use the TransformComponent and it can't work without it.

Editor
------

In the editor, you can change sprite by selecting json file.

Script
------

Variables
^^^^^^^^^

- game_object: Object which own this component (GameObject)
- engine: Utility class to control the game (Engine)
- sprite: Resource file. Will search in resources folder. (string)
- render: Final render. 

.. warning:: You mustn't change render directly but use update_render function.

Functions
^^^^^^^^^

- update_render(): Update render of component