Color
=====

This class represents a Color.

Variables
---------

- r: Red component of Color (integer)
- g: Green component of Color (integer)
- b: Blue component of Color (integer)
- a: Alpha component of Color (integer)
  
.. note:: These components must be between 0 and 255

Functions
---------

- darker(force=1): Return a darker color. (force -> integer)
- lighter(force=1): Return a lighter color. (force -> integer)
- rgb(): Return a list with R, G, B values
- rgba(): Return a list with R, G, B, A values
- html(): Return html value
- from_rgb(r, g, b): Return a color with R, G, B value (r -> integer, g -> integer, b -> integer)
- from_rgba(r, g, b, a): Return a color with R, G, B, A value (r -> integer, g -> integer, b -> integer, a -> integer)
- from_color(color): Return a color from a color (copy) (color -> Color)
- from_html(html): Return a color from html value (html -> string)
- from_name(name): Return a color from its name (name -> string)

.. note:: List of defined names : "WHITE", "BLACK", "GRAY", "RED", "GREEN", "BLUE", "FUCHSIA", "YELLOW", "CYAN", "LIME", "BROWN", "NAVY_BLUE", "OLIVE", "PURPLE", "TEAL", "SILVER", "ORANGE"

.. warning:: All functions started by "from_xxx" are classmethods. To use it, you must write Color.<method> and not use a instance. 
