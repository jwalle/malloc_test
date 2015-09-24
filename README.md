# malloc_test


test: re
	gcc $(CFLAGS) -o test ./tests/test.c $(LINK) $(NAME) $(INC) -g
