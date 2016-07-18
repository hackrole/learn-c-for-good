# the compiler to use
CC = gcc
# compile flags
# -g adds debugging information
# -Wall turn all warnings
CFLAGS = -g -Wall

# the name to use for both target and output
tg = hello

all: $(tg).out

$(tg).out: $(tg).c
	$(CC) $(CFLAGS) -o $(tg).out $(tg).c
	./$(tg).out
rm:
	find . -name "*.out" -exec rm {} \;
