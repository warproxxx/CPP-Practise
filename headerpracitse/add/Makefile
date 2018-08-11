CC=g++
CFLAGS=-c -Wall

all: add

add: main.o add.o
	$(CC) main.o add.o -o add

main.o: main.cpp
	$(CC) $(CFLAGS) main.cpp

add.o: add.cpp
	$(CC) $(CFLAGS) add.cpp