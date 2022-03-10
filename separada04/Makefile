GCC = gcc
FLAGS = -ansi -pedantic -Wall -std=c99
C_FLAGS = -lm
PROGRAMAS = matricesApp

matricesApp:
	$(GCC) $(FLAGS) funcionesmatrices.c -c
	$(GCC) $(FLAGS) ctime.c -c
	$(GCC) $(FLAGS) $@.c -c
	$(GCC) $(FLAGS) -o $@ $@.o funcionesmatrices.o ctime.o

clean:
	$(RM) $(PROGRAMAS) *.o

