Vec2
====

This class represents a Vector 2D.

Variables
---------

- x: X coords (integer)
- y: Y coords (integer)

Functions
---------

- coords(): Return list with X and Y coords
- set_coords(x, y): Set x and y coords (x -> integer, y -> integer)
- normalized(): Return normalized Vec2
- zero: Return Vec2(0, 0)

.. warning:: Function zero is a classmethod. To use it, you must write Vec2.zero().