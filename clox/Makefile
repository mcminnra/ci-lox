CC = clang
CFLAGS = -Wall -Wextra -std=c99
SRC = $(wildcard *.c)
HDR = $(wildcard *.h)

.DEFAULT_GOAL := run
.PHONY: run

clox: $(SRC) $(HDR)
	$(CC) $(CFLAGS) -o $@ $(SRC)

run: clox
	./clox
