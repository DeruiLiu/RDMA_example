CC = gcc
LDFLAGS = -libverbs

uc_pingpong: uc_pingpong.c pingpong.c
	$(CC) uc_pingpong.c pingpong.c -o uc_pingpong $(LDFLAGS)

clean:
	rm uc_pingpong
