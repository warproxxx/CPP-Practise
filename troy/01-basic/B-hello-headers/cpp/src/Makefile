CC=g++
CFLAGS =-c -Wall -I ../include

all: helloheaders

helloheaders: main.o Hello.o
	$(CC) main.o Hello.o -o helloheaders

main.o: main.cpp
	$(CC) $(CFLAGS) main.cpp

Hello.o: Hello.cpp
	$(CC) $(CFLAGS) Hello.cpp