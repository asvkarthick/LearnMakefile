CC=gcc
CFLAGS=-I.
DEPS=hellomake.h
OBJ=hellomake.o hellofunc.o

%.o: %.c $(DEPS)
	$(CC) -c -o $@ $< $(CFLAGS)
hello: $(OBJ)
	$(CC) $^ -o $@ $(CFLAGS)
clean:
	rm hello *.o
run:
	./hello
