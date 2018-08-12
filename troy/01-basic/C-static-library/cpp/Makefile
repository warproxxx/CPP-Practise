CC=g++
CFLAGS=-c -Wall -I ../include

all: static_library

static_library: main.o Hello.o
	$(CC) main.o Hello.o -o static_library

main.o: src/main.cpp
	$(CC) $(CFLAGS) src/main.cpp

Hello.o: src/Hello.cpp
	$(CC) $(CFLAGS) src/Hello.cpp