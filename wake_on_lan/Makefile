# COMPILER VARS
CC = gcc
CC_FLAGS = -Wall -Wextra -Werror

# SOURCE VARS
SRC =	src/wake_on_lan.c \
		src/args/check_args.c \
		src/socket/manage_socket.c

# INCLUDE VARS
INCLUDE_PATH = include/

# BINARY VARS
NAME = Wake_on_lan
BIN_PATH = bin/

all:
	mkdir $(BIN_PATH)
	$(CC) $(CC_FLAGS) -o $(BIN_PATH)$(NAME) -I$(INCLUDE_PATH) $(SRC)

clean:
	rm -f $(BIN_PATH)$(NAME)

re: clean all
