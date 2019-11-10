# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: lminta <lminta@student.42.fr>              +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2019/04/02 20:58:32 by lminta            #+#    #+#              #
#    Updated: 2019/04/17 20:53:57 by lminta           ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

NAME = libft.a

SRC = ./

INC = ./

FLAGS = -Wall -Werror -Wextra -c -I $(INC)

FILES = $(SRC)/ft_abs.c $(SRC)/ft_atoi.c $(SRC)/ft_bzero.c $(SRC)/ft_cut.c $(SRC)/ft_isalnum.c \
ft_isalpha.c $(SRC)/ft_isascii.c $(SRC)/ft_isdigit.c $(SRC)/ft_islower.c $(SRC)/ft_isprint.c \
ft_isspace.c $(SRC)/ft_isupper.c $(SRC)/ft_itoa.c $(SRC)/ft_letter_counter.c $(SRC)/ft_lstadd.c \
ft_lstdel.c $(SRC)/ft_lstdelone.c $(SRC)/ft_lstiter.c $(SRC)/ft_lstmap.c $(SRC)/ft_lstnew.c \
ft_memalloc.c $(SRC)/ft_memccpy.c $(SRC)/ft_memchr.c $(SRC)/ft_memcmp.c $(SRC)/ft_memcpy.c \
ft_memdel.c $(SRC)/ft_memmove.c $(SRC)/ft_memset.c $(SRC)/ft_pow.c $(SRC)/ft_putchar.c \
ft_putchar_fd.c $(SRC)/ft_putendl.c $(SRC)/ft_putendl_fd.c $(SRC)/ft_putnbr.c $(SRC)/ft_putnbr_fd.c \
ft_putstr.c $(SRC)/ft_putstr_fd.c $(SRC)/ft_strcat.c $(SRC)/ft_strchr.c $(SRC)/ft_strclr.c \
ft_strcmp.c $(SRC)/ft_strcpy.c $(SRC)/ft_strdel.c $(SRC)/ft_strdup.c $(SRC)/ft_strequ.c $(SRC)/ft_striter.c \
ft_striteri.c $(SRC)/ft_strjoin.c $(SRC)/ft_strlcat.c $(SRC)/ft_strlen.c $(SRC)/ft_strmap.c \
ft_strmapi.c $(SRC)/ft_strncat.c $(SRC)/ft_strncmp.c $(SRC)/ft_strncpy.c $(SRC)/ft_strnequ.c \
ft_strnew.c $(SRC)/ft_strnstr.c $(SRC)/ft_strrchr.c $(SRC)/ft_strsplit.c $(SRC)/ft_strstr.c \
ft_strsub.c $(SRC)/ft_strtrim.c $(SRC)/ft_tolower.c $(SRC)/ft_toupper.c $(SRC)/ft_word_counter.c \
$(SRC)/ft_recharlloc.c

OBJ = ft_abs.o ft_atoi.o ft_bzero.o ft_cut.o ft_isalnum.o \
ft_isalpha.o ft_isascii.o ft_isdigit.o ft_islower.o ft_isprint.o \
ft_isspace.o ft_isupper.o ft_itoa.o ft_letter_counter.o ft_lstadd.o \
ft_lstdel.o ft_lstdelone.o ft_lstiter.o ft_lstmap.o ft_lstnew.o \
ft_memalloc.o ft_memccpy.o ft_memchr.o ft_memcmp.o ft_memcpy.o \
ft_memdel.o ft_memmove.o ft_memset.o ft_pow.o ft_putchar.o \
ft_putchar_fd.o ft_putendl.o ft_putendl_fd.o ft_putnbr.o ft_putnbr_fd.o \
ft_putstr.o ft_putstr_fd.o ft_strcat.o ft_strchr.o ft_strclr.o \
ft_strcmp.o ft_strcpy.o ft_strdel.o ft_strdup.o ft_strequ.o ft_striter.o \
ft_striteri.o ft_strjoin.o ft_strlcat.o ft_strlen.o ft_strmap.o \
ft_strmapi.o ft_strncat.o ft_strncmp.o ft_strncpy.o ft_strnequ.o \
ft_strnew.o ft_strnstr.o ft_strrchr.o ft_strsplit.o ft_strstr.o \
ft_strsub.o ft_strtrim.o ft_tolower.o ft_toupper.o ft_word_counter.o \
ft_recharlloc.o

all: $(NAME)

$(NAME):
	gcc $(FLAGS) $(FILES)
	ar rc $(NAME) $(OBJ)

clean:
	/bin/rm -f $(OBJ)

fclean: clean
	/bin/rm -f $(NAME)

re: fclean all
