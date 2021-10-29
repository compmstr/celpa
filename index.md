---
title: My local emacs package archive
---

# About

This is just a repo for the local emacs code I write, as opposed to
the previous setup of a folder in Dropbox.

This setup is based off of a blog post about [delpa](https://blog.davep.org/delpa/).

# Using it

Basically I'll set it up using:
```elisp
(require 'package)
(add-to-list 'package-archives '("celpa" . "https://compmstr.github.io/celpa"))
```
