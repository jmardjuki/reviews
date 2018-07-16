# Makefike
# by Janet Mardjuki
TARGET=helloWorld

SOURCES = \
	helloWorld.c

OBJECT = $(SOURCES: .c=.o)

OUTDIR = $(HOME)/project/reviews/operatingSystems/bfraserDouga/helloWorld
CC_CPP = g++
CC_C = gcc

CFLAGS = -Wall -g -std=c99 -D _POSIX_C_SOURCE=200809L -Werror

all: $(OBJECT)
	$(CC_C) $(CFLAGS) $(SOURCES) -o $(OUTDIR)/$(TARGET) -lpthread

clean:
	rm -f $(OUTDIR)/$(TARGET)
