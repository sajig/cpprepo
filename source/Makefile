TARGET_DIR=../target

all: ${TARGET_DIR}/hello.o ${TARGET_DIR}/main.o
	g++ -o ${TARGET_DIR}/hello ${TARGET_DIR}/hello.o ${TARGET_DIR}/main.o

${TARGET_DIR}/hello.o: hello.cpp
	g++ -c hello.cpp -o ${TARGET_DIR}/hello.o 

${TARGET_DIR}/main.o: main.cpp
	g++ -c main.cpp -o ${TARGET_DIR}/main.o

clean: 
	rm ${TARGET_DIR}/*.o ${TARGET_DIR}/hello
