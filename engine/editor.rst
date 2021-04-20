Editor
======

One of principal components of PyEngine is the Editor.
He's composed of four other components.

Viewport
--------

In the center of the screen, there is the viewport.

You can see the current selected scene here.

.. warning:: The viewport haven't got any logic or game loop.

ProjectExplorer
---------------

At the bottom, there is the project explorer.

You can choose if you want see scripts, prefabs, textures or scenes.
If you right click on the right part, you can create new assets or delete an old one.

Scripts
^^^^^^^

A Script in PyEngine4 is a python file where you create a logic for an object.

On creation, PyEngine4 ask a name for the script.
If you double click on it, you will open the script.

Prefabs
^^^^^^^

*Coming Soon*

Textures
^^^^^^^^

A texture is a .PNG or .JPG file which can be used for a sprite.

On creation, PyEngine4 ask a name and a path to the file.
If you double click on it, you will be able to change the path.

Sounds
^^^^^^

A sounds is a .WAV, .OGG or .MP3 which can be used in AudioComponent or MusicComponent.

On create, PyEngine4 ask a name and a path to the file.
If you double click on it, you will be able to change the path.

Scenes
^^^^^^

A scene is a 2D world where you can put objects. You must have a scene for any game.

On creation, PyEngine4 ask a name for the scene.

SceneTree
---------

On the left, you can see the Scene Tree.

It shows the objects which are in the current selected scene.

You can create a new game object with selected an already existed game object and make a right click.
You will choose a name and the new game object will be the child of the existed.

You can also delete a game object with a right click.

Inspector
---------

On the right, there is the inspector.

This panel will show the properties and components of the selected game object (or asset in the case of texture).

You can add a new component in a normal game object with the button on the bottom or with right click.
You can also delete a component of a normal game object with right click.