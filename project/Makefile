CC = gcc
CFLAGS = -Wall -g

OBJ = main.o helper.o
TARGET = app

all: $(TARGET)

$(TARGET): $(OBJ)
	$(CC) $(OBJ) -o $(TARGET)

main.o: main.c helper.h
	$(CC) $(CFLAGS) -c main.c

helper.o: helper.c helper.h
	$(CC) $(CFLAGS) -c helper.c

clean:
	rm -f *.o $(TARGET)
