LDFLAGS=-lX11 -lXtst -ljack -llua5.2
CFLAGS=-Wall -std=c++11

midi2input: midi2input.c options.h
	g++ $(CFLAGS) $^ -o $@ $(LDFLAGS)
clean: 
	rm -f midi2input
