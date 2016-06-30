all: hello.o main.o
	g++ -o hello hello.o main.o

hello.o: hello.cpp
	g++ -c hello.cpp

main.o: main.cpp
	g++ -c main.cpp

clean: 
	rm *.o hello
