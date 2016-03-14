# Project Name
TARGET = pesca

# Libraries
LIBS = -lm

# Compiler
CC = gcc

# Compiler Flags
CFLAGS = -Wall –I$(INC_DIR) 

# Linker
LINKER = gcc -o

# Linker Flags
LFLAGS = -Wall -I$(INC_DIR) -lm

# Folders
BASE_DIR = pesca
SRC_DIR  = pesca/src
INC_DIR  = pesca/include
OBJ_DIR  = pesca/obj
TEST_DIR = pesca/testes
BIN_DIR  = pesca/bin

SOURCES  := $(wildcard $(SRC_DIR)/*.c)
OBJECTS := $(wildcard $(OBJ_DIR)/*.o )
INCLUDES := $(wildcard $(INC_DIR)/*.h)


# Link Objects
$(BIN_DIR)/$(TARGET): $(OBJECTS)
		
# Tests
tester:

.PHONY: clean

# Clean
clean:
	@echo " Cleaning...";
	rm -f *~



