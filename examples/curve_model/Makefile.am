# Copyright (C) 2010-2011 Free Software Foundation, Inc
# 
# This program is free software: you can redistribute it and/or modify
# it under the terms of the GNU General Public License as published by
# the Free Software Foundation; either version 3 of the License, or
# (at your option) any later version.
# 
# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
# GNU General Public License for more details.
# 
# You should have received a copy of the GNU General Public License
# along with this program.  If not, see <http://www.gnu.org/licenses/>.

noinst_PROGRAMS = usercurve

usercurve_SOURCES = usercurve.cc
usercurve_LDADD = $(top_builddir)/goptical_core/src/libgoptical.la \
                  $(top_builddir)/goptical_design/src/libgoptical_design.la
usercurve_CPPFLAGS = -I$(top_srcdir)/goptical_core/src \
                   -I$(top_srcdir)/goptical_design/src
