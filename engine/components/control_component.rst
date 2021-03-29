TransformComponent
==================

This component allow controlling game object.

Editor
------

In the editor, you can change keys, control type and speed.

.. note:: Keys with pygame's names.

.. note:: List of Control type :
    - FOURDIRECTION : Object can move in four directions (Up, Down, Left, Right)
    - DOWNUP : Object can move in two directions (Up, Down)
    - LEFTRIGHT : Object can move in two directions (Left, Right)
    - CLASSICJUMP : Basic platformer controler. Move in X axis and can make a jump. (Use BasicPhysicComponent)

Script
------

Variables
^^^^^^^^^

- game_object: Object which own this component (GameObject)
- engine: Utility class to control the game (Engine)
- keys: Dictionnary of keys used. Use UPJUMP, DOWN, RIGHT, LEFT as keys. (dictionnary)
- control_type: Type of control (string)
- speed: Speed of object (integer)

Functions
^^^^^^^^^

No public function in this component.
