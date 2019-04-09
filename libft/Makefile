# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: asansyzb <marvin@42.fr>                    +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2018/10/25 18:01:53 by asansyzb          #+#    #+#              #
#    Updated: 2018/11/04 15:09:37 by asansyzb         ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

NAME = libft.a
CFLAGS = -Wall -Werror -Wextra
SRC_DIR = srcs/.*c
OBJ_DIR = obj/

OBJECT = *.o
HEADER = /includes/libft.h

all: $(NAME)

$(NAME):
	@gcc $(CFLAGS) -c $(SRC) -I $(HEADER)
	@ar rc $(NAME) ft_*.o
	@ranlib $(NAME)
clean:
	@/bin/rm -f $(OBJECT)
fclean: clean
	@/bin/rm -f $(NAME)
re:	fclean all
