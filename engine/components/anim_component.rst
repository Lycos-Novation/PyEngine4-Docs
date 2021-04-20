AnimComponent
=============

This component add animations to game object.

.. warning:: This component use the TransformComponent and it can't work without it.

Editor
------

In the editor, you can add, remove and manage animations but also change frames per seconds and the current playing animation.

Script
------

Variables
^^^^^^^^^

- game_object: Object which own this component (GameObject)
- engine: Utility class to control the game (Engine)
- fps: Number of frames per seconds (int)
- playing: Name of current animation (string)
- anims: Dictionnary of animations (dict<string, AnimSprite/AnimSpriteSheet>)
- current_sprite: Index of current displayed sprite (int)

Functions
^^^^^^^^^

No public function in this component.
