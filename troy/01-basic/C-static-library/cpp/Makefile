CC=g++
CFLAGS=-c -Wall -I ../include

all: static_library

static_library: main.o library.a
	$(CC) main.o library.a -o static_library

main.o: src/main.cpp
	$(CC) $(CFLAGS) src/main.cpp

Hello.o: src/Hello.cpp
	$(CC) $(CFLAGS) src/Hello.cpp

library.a: Hello.o
	ar rvs library.a Hello.o