CFLAGS = -lcommons -lpthread

%: %.o
	$(CC) -o $(*F) -g $(*F).o $(CFLAGS)

Instancia: Instancia.o

Instancia.o: Instancia.h
