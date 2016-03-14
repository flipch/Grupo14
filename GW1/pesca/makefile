BASE_DIR = pesca
SRC_DIR = pesca/src
INC_DIR = pesca/include
OBJ_DIR = pesca/obj
TEST_DIR = pesca/testes
BIN_DIR = pesca/bin
OBJECTOS = barco.o capitao.o cardume.o fifo.o main.o mundo.o posicao.o semaphore.o shared.o util.o
CC = gcc

.PHONY: all clean

$(BIN_DIR): $(OBJ_DIR)/$(OBJECTOS)
		$(CC) $(OBJ_DIR)/main.o -o $(BASE_DIR)/bin

main.o: 

all:

clean:
	rm -f *~
