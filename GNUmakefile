all: hello.out fahr_while.out fahr_for.out define.out

clean:
	$(RM) *.out

hello.out: hello.c
	$(CC) -o $@ $(basename $@).c

fahr_while.out: fahr_while.c
	$(CC) -o $@ $(basename $@).c

fahr_for.out: fahr_for.c
	$(CC) -o $@ $(basename $@).c

define.out: define.c
	$(CC) -o $@ $(basename $@).c
