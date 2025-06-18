all: hello.out fahr_while.out fahr_for.out define.out file_copying.out character_count_while.out character_count_for.out

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

file_copying.out: file_copying.c
	$(CC) -o $@ $(basename $@).c

character_count_while.out: character_count_while.c
	$(CC) -o $@ $(basename $@).c

character_count_for.out: character_count_for.c
	$(CC) -o $@ $(basename $@).c

