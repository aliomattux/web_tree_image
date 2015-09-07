Display images and icons in tree view
=====================================


Attention. This module forked from OCA branch.


This module defines a tree image widget, to be used with either binary fields
or (function) fields of type character. Use widget='image' in your view
definition. This module is a base for https://github.com/aliomattux/sale_line_images.
With this module you can specify style="max-height: ''; max-width: ''"
By default there is 64px which will preserve aspect ration. In this module we also add to form widget as this was not covered in the OCA branch

If you use the widget with a character field, the content of the field can be
any of the following:

* The absolute or relative location of an image. For example,
  "/<module>/static/src/img/youricon.png"

* A standard icon from the web distribution, without path or extension, For
  example, 'gtk-open'

* A dynamic image in a data url base 64 format. Prefix with
  'data:image/png;base64,'
