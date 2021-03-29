BasicPhysicComponent
====================

This component add gravity to game object.

.. warning:: This component use the TransformComponent and it can't work without it.

Editor
------

In the editor, you can change gravity with a spin.

Script
------

Variables
^^^^^^^^^

- game_object: Object which own this component (GameObject)
- engine: Utility class to control the game (Engine)
- gravity: Current gravity of component (integer)
- max_gravity: Maximum gravity of component (integer)
- grounded: True if object can't be move by gravity (boolean)
- time: Time must be elipsed beform apply gravity (float)

.. note:: You may not change grounded and time.

.. warning:: grounded only work with the CollisionComponent

Functions
^^^^^^^^^

No public function in this component.
