#Makefile
OBJ = realpath.o

%.o: %.c
	  $(CC) -c -o $@ $< $(CFLAGS)

realpath: $(OBJ)
	  gcc -o $@ $^ $(CFLAGS)

clean:
	rm -f $(OBJ)


