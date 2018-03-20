CC=gcc
CXX=g++
RM=rm -f
LDFLAGS=
LDLIBS=
CPPFLAGS=-g

SRCS=main.cpp
OBJS=$(subst .cpp,.o,$(SRCS))

all: example

example: $(OBJS)
	    $(CXX) $(LDFLAGS) -o example $(OBJS) $(LDLIBS)

clean:
	    $(RM) $(OBJS)

distclean: clean
