NAME			= libftprintf.a
CC				= gcc
CFLAGS			= -Wall -Wextra -Werror
RM				= rm -f
SRCS			=	ft_printf.c \
								ft_printf_char_utils.c \
								ft_printf_int_utils.c

OBJS			= $(SRCS:.c=.o)

$(NAME):		$(OBJS)
				ar -rcs $(NAME) $(OBJS)

all:			$(NAME)

clean:
				$(RM) $(OBJS)

fclean:			clean
				$(RM) $(NAME)

re:				fclean all

.PHONY:			all clean fclean re