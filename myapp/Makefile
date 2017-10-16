.PHONY = clean
INCLUDE = /home/oripon/week4/include
LIB = /home/oripon/week4/lib

CC = gcc
CFLAGS = -g -c -I
OUTPUT = main
OBJFILES = main.o

$(OUTPUT) : $(OBJFILES)
	$(CC) -o $(OUTPUT) -L $(LIB) $(OBJFILES) -lfuncs
%.o : %.c
	$(CC) $(CFLAGS)$(INCLUDE) -c $< -o $@
clean:
	rm *.o main
