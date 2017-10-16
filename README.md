# cwl-mode.el

This library helps you to write [Common Workflow Language](http://www.commonwl.org) in Emacs.

Requirements:
  * Emacs 24.4 or later
  * yaml-mode.el
  * flycheck.el (optional)

To use this package, add the following line to your `.emacs` file:
```emacs
    (require 'cwl-mode)
```
cwl-mode highlights some keywords for usability.
Also, it enables on-the-fly YAML checker if flycheck is installed.
