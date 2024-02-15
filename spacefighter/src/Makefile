COMPILER = gcc
OUT_PATH = ../build/
OUT_NAME = galaxy
COMPILER_LIB_FLAG = -lncurses -lm

all: galaxy.o
	$(COMPILER) main.o -o $(OUT_PATH)$(OUT_NAME) $(COMPILER_LIB_FLAG) 

clean:
	rm -rf *.o

galaxy.o: main.c
	$(COMPILER) -c main.c $(COMPILER_LIB_FLAG)