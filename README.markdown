Some yas snippets for oomph-lib development
===============

Setup
----

* Get yasnippet and set up as normal.

* Add `(add-to-list 'yas-snippet-dirs "~/path/to/this/dir")` to your emacs
  init file.
  
* Consider removing some of the default c++ snippets. In particular `pt` is
  a snippet for `protected:`, which does not play nicely with the oomph-lib
  convention of using "_pt" for pointers (pressing tab after a pointer name
  will convert it to "protected:\n"). To do this simply delete the
  corresponding snippet file.
