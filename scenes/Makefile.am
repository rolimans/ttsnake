##   Automake.am - Automake script
##
##   Copyright (c) 2021 - Monaco F. J. <monaco@usp.br>
##
##   This file is part of TexTronSnake
##
##   TexTronSnake is free software: you can redistribute it and/or modify
##   it under the terms of the GNU General Public License as published by
##   the Free Software Foundation, either version 3 of the License, or
##   (at your option) any later version.
##
##   This program is distributed in the hope that it will be useful,
##   but WITHOUT ANY WARRANTY; without even the implied warranty of
##   MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
##   GNU General Public License for more details.
##
##   You should have received a copy of the GNU General Public License
##   along with this program.  If not, see <http://www.gnu.org/licenses/>.


# Where scene files are installed
#   $(datadir) is autotools defined and defaults to $(prefix)/share
#   @alt_short_name@ was manually defined in autoconf.ac

distdir=$(datadir)/@alt_short_name@

# Introduction animation's scene files are listed in $(scrdir)/intro.am.
# This file is generated by a helper script in order to save us typing.

include $(srcdir)/intro.am

# Data files are installed in $(distdir)/

nobase_dist_DATA = $(intro_scenes) game/scene-0000001.txt game/scene-0000002.txt 

EXTRA_DIST = $(intro_scenes) game/scene-0000001.txt game/scene-0000002.txt
