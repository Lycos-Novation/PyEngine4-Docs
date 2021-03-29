AutoComponent
=============

This component create automatic movement and rotation to game object.

.. warning:: This component use the TransformComponent and it can't work without it.

Editor
------

In the editor, you can change the movement and the rotation with differents spins.
There is also a checkbox to activate/desactivate the component.

Script
------

Variables
^^^^^^^^^

- game_object: Object which own this component (GameObject)
- engine: Utility class to control the game (Engine)
- move: Movement of component (list of two integers)
- rotation: Rotation of component in degrees (integers)
- active: True if component is active

Functions
^^^^^^^^^

No public function in this component.
