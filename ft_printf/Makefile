NAME=libftprintf.a
FILES=*.c
OBJECTS=*.o
all: $(NAME)

$(NAME):
	@gcc -c $(FILES) -Wall -Wextra -Werror
	@ar rc $(NAME) $(OBJECTS)
	@ranlib $(NAME)
clean:
	@rm -f $(OBJECTS)
fclean: clean
	@rm -f $(NAME)
re: fclean all