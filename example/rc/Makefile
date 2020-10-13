CC = gcc
LDFLAGS = -libverbs

rc_pingpong: rc_pingpong.c pingpong.c
	$(CC) rc_pingpong.c pingpong.c -o rc_pingpong $(LDFLAGS)

clean:
	rm rc_pingpong
