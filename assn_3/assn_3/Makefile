# CSC 541 Assignment 3
# Mitchell Neville

# Compile parameters
CC = g++ 
CFLAGS = -c -Wall

EXEC = assn_3

all: Main

Main: Main.o
	$(CC) -o $(EXEC) Main.o

Main.o: Main.cpp
	$(CC) $(CFLAGS) Main.cpp