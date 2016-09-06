all:
	g++ -Wall -c -o libmosq.o libmosq.c
	g++ -Wall -c -o simpleclient.o simpleclient.cpp
	g++ -Wall -o simpleclient simpleclient.o libmosq.o -lmosquitto
