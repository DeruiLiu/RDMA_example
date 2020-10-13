CC = gcc
LDFLAGS = -libverbs

srq_pingpong: srq_pingpong.c pingpong.c
	$(CC) srq_pingpong.c pingpong.c -o srq_pingpong $(LDFLAGS)

clean:
	rm srq_pingpong
