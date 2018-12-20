CFLAGS = -lcommons -lparsi

%: %.o
	$(CC) -o $(*F) -g $(*F).o $(CFLAGS)

ESI: ESI.o

ESI.o: ESI.h