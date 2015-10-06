CC=gcc
CFLAGS=-I.
DEPS=hellomake.h

%.o: %.c $(DEPS)
	$(CC) -c -o $@ $< $(CFLAGS)
hello: hellomake.o hellofunc.o
	$(CC) hellomake.o hellofunc.o -o hello $(CFLAGS)
clean:
	rm hello *.o
run:
	./hello
