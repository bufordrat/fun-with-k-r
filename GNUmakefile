PROGZ = hello fahr_while fahr_for define

$(PROGZ): $(foreach p,$(PROGZ),$p.o)

# these are builtin of course in more sophisticated fashion
%.o: %.c
	$(CC) -c $<

%: %.o
	$(CC) -o $@ $<

clean:
	$(RM) *.o
	$(RM) $(PROGZ)
