CC = g++
CFLAGS = -Wall -std=c++11
LDFLAGS = -lstdc++

TARGET = server

$(TARGET): server.cpp
	$(CC) $(CFLAGS) $< -o $@ $(LDFLAGS)

.PHONY: clean

clean:
	rm -f $(TARGET)
