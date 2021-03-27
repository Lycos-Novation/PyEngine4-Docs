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
If you rightclick on the right part, you can create new assets or delete an old one.

Scripts
^^^^^^^

A Script in PyEngine4 is a python file where you create a logic for an object.

On creation, PyEngine4 ask a name for the script.
If you doubleclick on it, you will open the script.

Prefabs
^^^^^^^

*Coming Soon*

Textures
^^^^^^^^

A texture is a .PNG or .JPG file with can be use for a sprite.

On creation, PyEngine4 ask a name and a path to the file.
If you doubleclick on it, you will be able to change the path.

Scenes
^^^^^^

A scene is a 2D world where you can put objects. You must have a scene for any game.

On creation, PyEngine4 ask a name for the scene.

SceneTree
---------

On the left, you can see the Scene Tree.

It show the objects which is in the current selected scene.

You can create a new game object with selected an already existed game object and make a rightclick.
You will choose a name and the new game object will be the child of the existed.

You can also delete game object with a rightclick.

Inspector
---------

On the right, there is the inspector.

This panel will show the properties and components from the selected game object (or asset in the case of texture).

You can add a new component in a normal game object with the button on the bottom or with rightclick.
You can also delete component of a normal game object with rightclick.