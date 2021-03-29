Game
====

Class which represents the core of the game.

Variables
---------

- engine: Utility class to control the game (Engine)
- name: Title of the Game (string)
- width: Width of Window (integer)
- height: Height of Window (integer)
- scenes: List of scenes (list of Scene)
- current_scene: Index of current displayed scene (integer)
- clock: Pygame's clock to control time of Game (Clock)
- screen: Window of Game (Surface)
- is_running: True if game is currently running (boolean)

.. note:: Changing name, width and height will have any effect.

.. warning:: Most of these variables mustn't be manipulated. Only current_scene, is_running and getting engine is safe.

Functions
---------

- stop(): Stop Game
- get_fps(): Return current FPS
