EVERYTHING = hello fahr_while fahr_for define

all: $(EVERYTHING)

clean:
	$(RM) $(EVERYTHING) *.o
.PHONY: clean

hello.o: lib.o
hello: hello.o lib.o

fahr_for: fahr_for.o

fahr_while: fahr_while.o

define: define.o

# %: %.o
# 	$(CC) -o $@ $^

# hello: hello.o
# 	$(CC) -o $@ $<

# fahr_while: fahr_while.o
# 	$(CC) -o $@ $<
