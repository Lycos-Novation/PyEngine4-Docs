CollisionComponent
==================

This component add collision and collision callback to game object.

.. warning:: This component use the TransformComponent and a component with a render and it can't work without them.

Editor
------

In the editor, you can change if object is solid with a checkbox and specify a callback by giving the name of component and the function will be called.

Script
------

Variables
^^^^^^^^^

- game_object: Object which own this component (GameObject)
- engine: Utility class to control the game (Engine)
- solid: True if object is solid (boolean)
- callback: Component and its function which will be call on collide (string)

.. note:: callback use a specific format : "NameComponent - NameFunction".
    For example: "myScript - collide" is a valid callback.

.. note:: A function which will be used as a callback must accept two arguments : the object which collide with and the cause of collision.

Functions
^^^^^^^^^

- can_go(position, cause="UNKNOWN"): Return if object can go to a position. (position -> Vec2, cause -> string)
