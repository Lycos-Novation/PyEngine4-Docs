GameObject
==========

Class which represents an object of the game.

Variables
---------

- childs: List of childs game objects of current object (list of GameObject)
- components: List of components of current object (list of Components)
- id\_: Id of object (integer)

.. warning:: Most of these variables mustn't be manipulated. Only id\_ is safe.

Functions
---------

- add_component(comp): Add a component to object (comp -> Component)
- get_component(name): Return a component by his name or None if any component is found (name -> string)

