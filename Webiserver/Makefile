NAME = form

CC = c++

FLAGS	= -Wall -Wextra -Werror

RM = rm -rf

SRC = ServerData.cpp main.cpp

all : $(NAME)

$(NAME) : $(SRC)
	$(CC) $(FLAGS) $(SRC) -o $(NAME)

clean :
	$(RM) $(NAME)

fclean :
	$(RM) $(NAME)

re : clean all