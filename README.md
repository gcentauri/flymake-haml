flymake-haml.el
===============

An Emacs flymake handler for syntax-checking HAML source code.

Installation
=============

If you choose not to use one of the convenient packages in
[Melpa][melpa] and [Marmalade][marmalade], you'll need to add the
directory containing `flymake-haml.el` to your `load-path`, and then
`(require 'flymake-haml)`. You'll also need to install
[flymake-easy](https://github.com/purcell/flymake-easy).

Usage
=====

Add the following to your emacs init file:

    (require 'flymake-haml)
    (add-hook 'haml-mode-hook 'flymake-haml-load)

[marmalade]: http://marmalade-repo.org
[melpa]: http://melpa.org

<hr>

[![](http://api.coderwall.com/purcell/endorsecount.png)](http://coderwall.com/purcell)

[![](http://www.linkedin.com/img/webpromo/btn_liprofile_blue_80x15.png)](http://uk.linkedin.com/in/stevepurcell)

[Steve Purcell's blog](http://www.sanityinc.com/) // [@sanityinc on Twitter](https://twitter.com/sanityinc)
