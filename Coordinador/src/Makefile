CFLAGS = -lcommons -pthread

%: %.o
	cc -o $(*F) -g $(*F).o $(CFLAGS)

Coordinador: Coordinador.o

Coordinador.o: Coordinador.h