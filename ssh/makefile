SYS_LINK=-L/usr/lib
SYS_LINK=-L/usr/lib
SYS_LINK=-L/usr/lib
SYS_LINK=-L/usr/lib
INCS = -I../include
OBJS = ../obj
FLAGS = -O
cc = gcc

all : prun pcheck sng_prun move 

prun : prun.c
	$(cc) $(EXTRA) $(INCS) $(FLAGS) -o prun prun.c -L$(OBJS) -lsng
pcheck : pcheck.c
	$(cc) $(EXTRA) $(INCS) $(FLAGS) -o pcheck pcheck.c -L$(OBJS) -lsng
sng_prun : sng_prun.c
	$(cc) $(EXTRA) $(INCS) $(FLAGS) -o sng_prun sng_prun.c -L$(OBJS) -lsng

move :
	mv prun ../bin
	mv pcheck ../bin
	mv sng_prun ../bin
