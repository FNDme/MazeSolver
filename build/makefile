IDIR =../include
CC=g++
CFLAGS=-I$(IDIR) -std=c++11 -g

ODIR=../src
LDIR =../lib

LIBS=-lm

_OBJ = maze_t.o main_maze_t.o
OBJ = $(patsubst %,$(ODIR)/%,$(_OBJ))

all: Maze

$(ODIR)/main_maze_t.o: $(ODIR)/main_maze_t.cpp
	$(CC) -c -o $@ $< $(CFLAGS)

$(ODIR)/maze_t.o: $(ODIR)/maze_t.cpp
	$(CC) -c -o $@ $< $(CFLAGS)

Maze: $(OBJ)
	$(CC) -o $@ $^ $(CFLAGS) $(LIBS)

.PHONY: clean

clean:
	rm -f $(ODIR)/*.o *~ $(INCDIR)/*~