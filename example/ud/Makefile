CC = gcc
LDFLAGS = -libverbs

ud_pingpong: ud_pingpong.c pingpong.c
	$(CC) ud_pingpong.c pingpong.c -o ud_pingpong $(LDFLAGS)

clean:
	rm ud_pingpong
