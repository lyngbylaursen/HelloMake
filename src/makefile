CC=gcc
CFLAGS=-c -Wall
LDFLAGS=
SOURCES=hellomake.c hellofunc.c
OBJECTS=$(SOURCES:.c=.o)
EXECUTABLE=hellomake

all: $(SOURCES) $(EXECUTABLE)
    
$(EXECUTABLE): $(OBJECTS) 
	$(CC) $(LDFLAGS) $(OBJECTS) -o $@

.cpp.o:
	$(CC) $(CFLAGS) $< -o $@
