# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: mmeyn <marvin@42.fr>                       +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2023/03/11 10:50:51 by mmeyn             #+#    #+#              #
#    Updated: 2023/04/30 12:06:49 by mmeyn            ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

NAME = libft.a

COMP = gcc -Wall -Werror -Wextra

SRC =    ft_strlen.c    \
        ft_isdigit.c \
        ft_atoi.c \
        ft_bzero.c \
        ft_calloc.c \
        ft_isalnum.c \
        ft_isalpha.c \
        ft_isascii.c \
        ft_isprint.c \
        ft_memchr.c \
        ft_memcmp.c \
        ft_memcpy.c \
        ft_memmove.c \
        ft_memset.c \
        ft_strchr.c \
        ft_strdup.c \
        ft_strlcat.c \
        ft_strlcpy.c \
        ft_strlen.c \
        ft_strncmp.c \
        ft_strnstr.c \
        ft_strrchr.c \
        ft_tolower.c \
        ft_toupper.c \
        ft_substr.c \
        ft_strjoin.c \
		ft_strtrim.c \
		ft_itoa.c \
		ft_split.c \
		ft_strmapi.c \
		ft_striteri.c \
		ft_putchar_fd.c \
		ft_putstr_fd.c	\
		ft_putendl_fd.c \
		ft_putnbr_fd.c \

OBJ = $(SRC:.c=.o)

all: $(NAME)

%.o: %.c
	$(COMP) -c -o $@ $<

$(NAME): $(OBJ)
	ar rc $(NAME) $(OBJ)

clean:
	rm -f $(OBJ)

fclean: clean
	rm -f $(NAME)

re: fclean all
