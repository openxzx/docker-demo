CC := gcc

CFLAGS := -Wall -Werror
SRC = src/hello.c

all:
	$(CC) --static -o hello $(CFLAGS) $(SRC)

clean:
	@rm -f hello
