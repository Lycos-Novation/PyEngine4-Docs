GameObject
==========

Class which represents an object of the game.

Variables
---------

- parent: Parent of current object or None (GameObject)
- childs: List of childs game objects of current object (list of GameObject)
- components: List of components of current object (list of Components)
- id\_: Id of object (integer)
- tag : Tag of object (string)

.. warning:: Most of these variables mustn't be manipulated. Only id\_ and parents are safe on reading and tag is safe reading and writing.

Functions
---------

- add_child(child): Add a child to object (child -> GameObject)
- add_component(comp): Add a component to object (comp -> Component)
- get_component(name): Return a component by his name or None if any component is found (name -> string)

