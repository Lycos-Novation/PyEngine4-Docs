ButtonComponent
===============

This component add button to game object.

.. warning:: This component use the TransformComponent and it can't work without it.

Editor
------

In the editor, you can change callback, backgroud color, size, text and informations from font (name, size, bold, italic, underline, color, antialias).

Script
------

Variables
^^^^^^^^^

- game_object: Object which own this component (GameObject)
- engine: Utility class to control the game (Engine)
- bg: Background color (Color)
- callback: Component and its function which will be call on click (string)
- size: Size of component (Vec2)
- text: Text will be displayed (string)
- font_name: Name of font used (string)
- font_size: Size of font used (integer)
- font_bold: True if text is in bold (boolean)
- font_italic: True if text is in italic (boolean)
- font_underline: True if text is underline (boolean)
- font_color: Color of font used (Color)
- font_antialias: True if antialias is active (boolean)
- transformed_font: Final font 
- render: Final render. 

.. note:: callback use a specific format : "NameComponent - NameFunction".
    For example: "myScript - click" is a valid callback.

.. warning:: You mustn't change transformed_font directly but use update_font function.

.. warning:: You mustn't change render directly but use update_render function.

Functions
^^^^^^^^^

- update_font(): Update font of component
- update_render(): Update render of component