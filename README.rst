================
Nvim Black Block
================

Nvim Black Block executes `Black <https://github.com/psf/black>`__ on a
selection and replaces (in-place) the original text with the Black-formatted
one.

Alternatives to this plugin exists, see for example `Black
<https://vimawesome.com/plugin/black>`__. That plugin does executes on the
entire file - which might be nice if you've written the Python file from
scratch. However, in a versioned controlled environment, it's not always best
practice to reformat an entire file (``git blame`` becomes distorted, can cause
merge conflicts with colleagues, etc.). This plugin covers that gap by only
executing on a selection of the file.

**This is a work in progress.**
