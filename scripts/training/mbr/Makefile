CC=g++
OBJS=mbr.o 
CXXFLAGS=-O3
LDFLAGS=
LDLIBS= 

all: mbr

clean: 
	rm -f *.o

mert: $(OBJS)
	gcc $(OBJS) $(LDLIBS) -o $@

mert_p: $(OBJS)
	gcc $(LDFLAGS) $(OBJS) $(LDLIBS) -o $@
