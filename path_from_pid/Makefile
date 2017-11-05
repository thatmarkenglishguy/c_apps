OBJ = path_from_pid.o

%.o: %.c
	  $(CC) -c -o $@ $< $(CFLAGS)

pathfrompid: $(OBJ)
	  gcc -o $@ $^ $(CFLAGS)
