# Copyright 2009 The Go Authors.  All rights reserved.
# Use of this source code is governed by a BSD-style
# license that can be found in the LICENSE file.

include $(GOROOT)/src/Make.inc

TARG=⚛sdl/ttf

GOFILES:=constants.go
CGOFILES:=ttf.go
CGO_LDFLAGS:=-lSDL_ttf

CLEANFILES+=ttf

include $(GOROOT)/src/Make.pkg
