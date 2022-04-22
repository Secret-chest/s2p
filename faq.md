---
layout: default
title: FAQ
permalink: /faq/
---

> ## Table of contents
> * Table of contents
> {:toc}


## Where can I get the converted code?

You can't. Scratch2Python is an interpreter, not a transpiler. It does not output any Python files. It just runs the Scratch project on the fly.

## Will there be an API for programming Scratch projects in Python?

It's planned.

## What operating systems does Scratch2Python support?

Go to [the download page]({{ site.baseurl }}/download).

## Why are there only source releases?

Scratch2Python is not stable yet. It's not even close to being done. Packaging at this stage would be a waste of time. You also can run Python code pretty easily.

## Which license does this use?

GPLv3. The GPLv3 is a free software license. [Go here to see the license, plus the permissions it offers you.](https://github.com/Secret-chest/scratch2python/blob/main/LICENSE.md)

## Will there be a GUI?

Yes, but only after everything else is finished. It will have social features and will use GTK+. GTK+ is a GNOME toolkit, but it also works on:
* Other GTK-based desktops (Cinnamon, <abbr title="They do like their name capitalized but it's not an acronym">MATE</abbr>, Xfce, <abbr title="Lightweight X Desktop Envrionment">LXDE</abbr>, <abbr title="Pi Improved Xwindow Environment, Lightweight">PIXEL</abbr>, etc.)
* Qt-based desktops (KDE Plasma, LXQt)
* Other X and Wayland window managers with GTK+ support (WindowMaker, Openbox, Fluxbox, Mutter)
* Windows, if we ship GTK+ and a suitable theme
* MacOS

## Where is the source code for this website?

[Here.](https://github.com/Secret-chest/s2p)

## This is going to be so confused with [Scratch2Py](https://github.com/The-Cloud-Dev/scratch2py)! Can I suggest a new name?

Yes, you can do so [here](https://github.com/Secret-chest/scratch2python/discussions/23). However,

>  It'd be better if it didn't contain "Scratch", "Python", "py", or anything similar, because if I were to change the name, I would consider Scratch2Python a temporary one and wait for a more interesting one.

If I like your name, it will be the official name for the official release.
