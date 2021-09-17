CC=gcc
CFLAGS=-ansi
EJS=agenda
####################
OBJECTS=main.o
####################
all: clear $(EJS)

clear: 
	rm -f $(EJS) $(OBJECTS)

agenda: main.o
	$(CC) -o agenda $(OBJECTS)

main.o: main.c
	$(CC) $(CFLAGS) -c main.c

