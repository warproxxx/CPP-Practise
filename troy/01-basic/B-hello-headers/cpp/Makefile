CC=g++
CFLAGS =-c -Wall -I ../include

all: helloheaders

helloheaders: main.o Hello.o
	$(CC) main.o Hello.o -o helloheaders

main.o: src/main.cpp
	$(CC) $(CFLAGS) src/main.cpp

Hello.o: src/Hello.cpp
	$(CC) $(CFLAGS) src/Hello.cpp