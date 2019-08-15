CC = gcc
OBJ = pong.o

all : $(OBJ)
	$(CC) -o pong *.o -lSDL -lSDL_image -lSDL_ttf
	rm -rf $(OBJ)
.o:
	$(CC) -c $^

clean:
	rm -rf $(OBJ)
	rm -rf pong

