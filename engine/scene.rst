Scene
=====

Class which represents a world for the game.

Variables
---------

- bg_color: Color of background (list of four integers : [Red, Green, Blue, Alpha])
- game_objects: List of Game Objects own by the scene (List of GameObject)

.. warning:: game_objects mustn't be manipulated, use functions.

Functions
---------

- add_game_objects(game_objects): Adding Game Objects to the scene (game_objects -> List of GameObjects)
- add_game_object(game_object): Add a Game Object to the scene (game_object -> GameObject)
- get_game_object(id): Getting Game Object by id or None if any Game Object is found (id -> integer)
