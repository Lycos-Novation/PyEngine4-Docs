SoundComponent
==============

This component add sounds to game object.

Editor
------

In the editor, you can change sound by selecting or drag and drop and volume.

Script
------

Variables
^^^^^^^^^

- game_object: Object which own this component (GameObject)
- engine: Utility class to control the game (Engine)
- sound: Current sound (string)
- volume: Current volume from 0 to 100 (integer)

Functions
^^^^^^^^^

- play(): Play the current sound
