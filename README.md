ZTK - Project Z Toolkit
=======================

General information
-------------------

ZTK is a fork from GTK 3.24 that aims to keep the structure of GTK+ 3 alive, to update and improve it and to change and tweak the code, so it works optimal for users. To learn more about the toolkit, see the resources from [GTK](https://gtk.org/).

Future goals
------------

- [ ] Reimplement type-ahead into the file chooser
- [ ] Reimplement the color wheel as a color-chooser (as found in older versions of GTK)
- [ ] Make compatible with GTK 4 applications
- [ ] Make compatible with libhandy-1.0
- [ ] Make compatible with libadwaita
- [ ] Implement a proper theming engine

The last few goals represent tasks to make one toolkit library that can be used as a fully functional replacement for GTK 3, GTK 4, libhandy and libadwaita. This is to simplfy the use of interface libraries for applications, give users and distribution makers the freedom to make their desktop work and look as they want it and as a response to the ["Please don't theme my app"](https://stopthemingmy.app/) movement.

Status
------

This project is still heavily under construction, so things may not be in the right place.

Licensing terms
---------------

ZTK is released under the terms of the GNU Lesser General Public License, version 2.1 or, at your option, any later version, as published by the Free Software Foundation.

Please, see the [`COPYING`](./COPYING) file for further information.

ZTK includes a small number of source files under the Apache license:
- A fork of the roaring bitmaps implementation in [gtk/roaring](./gtk/roaring)
- An adaptation of timsort from python in [gtk/timsort](./gtk/timsort)

