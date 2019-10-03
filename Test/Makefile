p: main.o test.o
	gcc -o p main.o test.o

main.o: main.c test.h
	gcc -o main.o main.c -c -std=c99 -Wall

test.o: test.c test.h
	gcc -o test.o test.c -c -std=c99 -Wall

