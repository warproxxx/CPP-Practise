CC=g++
CFLAGS=-c -Wall -I ../include

all: shared_library

shared_library: main.o library.so
	$(CC) main.o -o shared_library -rdynamic library.so -Wl,-rpath,/home/warproxxx/Desktop/Practise/troy/01-basic/D-shared-library/cpp

Hello.o: src/Hello.cpp
	$(CC) $(CFLAGS) src/Hello.cpp

main.o: src/main.cpp
	$(CC) $(CFLAGS) src/main.cpp

library.so: Hello.o
	ld -r Hello.o -o library.so

clean: 
	-rm *.o *.so shared_library