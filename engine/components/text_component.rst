TextComponent
=============

This component add text to game object.

.. warning:: This component use the TransformComponent and it can't work without it.

Editor
------

In the editor, you can change text and informations from font (name, size, bold, italic, underline, color, antialias).

Script
------

Variables
^^^^^^^^^

- game_object: Object which own this component (GameObject)
- engine: Utility class to control the game (Engine)
- text: Text will be displayed (string)
- font_name: Name of font used (string)
- font_size: Size of font used (integer)
- font_bold: True if text is in bold (boolean)
- font_italic: True if text is in italic (boolean)
- font_underline: True if text is underline (boolean)
- font_color: Color of font used (list of four integers -> [Red, Green, Blue, Alpha])
- font_antialias: True if antialias is active (boolean)
- transformed_font: Final font 
- render: Final render. 

.. warning:: You mustn't change transformed_font directly but use update_font function.

.. warning:: You mustn't change render directly but use update_render function.

Functions
^^^^^^^^^

- rendered_size(text): Return size of text which be rendered with the font of component (text -> string)
- update_font(): Update font of component
- update_render(): Update render of component